<template>
  <div class="shuxingbangding">
    <h3>属性绑定</h3>
    
    <!-- 基本属性绑定 -->
    <div :id="dynamicId">动态ID绑定</div>
    
    <!-- 布尔值属性绑定 -->
    <button :disabled="isDisabled">禁用按钮</button>
    
    <!-- 绑定多个属性 -->
    <div v-bind="objectOfAttrs">绑定多个属性</div>
    
    <!-- class 绑定 -->
    <div :class="{ active: isActive, 'text-danger': hasError }">class绑定</div>
    
    <!-- style 绑定 -->
    <div :style="{ color: activeColor, fontSize: fontSize + 'px' }">style绑定</div>
    
    <!-- 数组语法 -->
    <div :class="[activeClass, errorClass]">数组class绑定</div>
    
    <!-- 绑定HTML属性 -->
    <div :data-custom="customData">自定义数据属性</div>
  </div>
</template>

<script>
export default {
  name: "Shuxingbangding",
  data() {
    return {
      dynamicId: 'my-dynamic-id',
      isDisabled: true,
      isActive: true,
      hasError: false,
      activeColor: 'red',
      fontSize: 20,
      activeClass: 'active',
      errorClass: 'text-danger',
      customData: 'custom-value',
      objectOfAttrs: {
        id: 'container',
        class: 'wrapper',
        title: '这是一个标题'
      }
    }
  }
}
</script>

<style scoped>
.shuxingbangding {
  color: lightblue;
  border: 1px solid lightblue;
  padding: 10px;
  margin: 10px 0;
}

.active {
  font-weight: bold;
  color: green;
}

.text-danger {
  color: red;
}

.wrapper {
  border: 2px dashed #ccc;
  padding: 10px;
  margin: 10px 0;
}
</style>