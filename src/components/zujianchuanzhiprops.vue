<template>
  <div class="zujianchuanzhiprops">
    <hr>
    <h3>父组件向子组件传值</h3>
    <Child :message="message" :age="age" :names="names" :userInfo="userInfo"></Child>
    
  </div>
</template>

<script>
import Child from '../pages/child.vue';
export default {
    name: 'Zujianchuanzhiprops',
    data() {
        return {
           message:"父组件向子组件传值",
           age:18,
           names:["张三","李四","王五"],
           userInfo:{
               title: "789789789889",
               id: 4545
           }
        }
    },
    components: {
        Child
    }
};
</script>

<style scoped>
.zujianchuanzhiprops {
    color: yellow;
}
</style>