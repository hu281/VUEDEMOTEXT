<template>
  <div class="tiaojianxuanran">
    <h3>条件渲染</h3>
    
    <!-- v-if 指令 -->
    <p v-if="isVisible">这个段落会根据 isVisible 显示/隐藏</p>
    
    <!-- v-else 指令 -->
    <p v-if="score >= 60">及格</p>
    <p v-else>不及格</p>
    
    <!-- v-else-if 指令 -->
    <p v-if="score >= 90">优秀</p>
    <p v-else-if="score >= 80">良好</p>
    <p v-else-if="score >= 70">中等</p>
    <p v-else-if="score >= 60">及格</p>
    <p v-else>不及格</p>
    
    <!-- v-show 指令 -->
    <p v-show="isShow">这个段落会根据 isShow 显示/隐藏（通过 CSS）</p>
    
    <!-- 多个元素的条件渲染 -->
    <template v-if="isLoggedIn">
      <p>欢迎回来！</p>
      <button>退出登录</button>
    </template>
    <template v-else>
      <p>请先登录</p>
      <button>登录</button>
    </template>
  </div>
</template>

<script>
export default {
  name: "Tiaojianxuanran",
  data() {
    return {
      isVisible: true,
      isShow: true,
      isLoggedIn: false,
      score: 85
    }
  }
}
</script>

<style scoped>
.tiaojianxuanran {
  color: lightgreen;
  border: 1px solid lightgreen;
  padding: 10px;
  margin: 10px 0;
}
</style>