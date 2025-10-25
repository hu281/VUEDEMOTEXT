<template>
  <div class="home-container">
    <h1>VUE3教学</h1>
    <hr>
    <Mobanyufa></Mobanyufa>
    <Shuxingbangding></Shuxingbangding>
    <Tiaojianxuanran></Tiaojianxuanran> 
    <liebiaoxuanran></liebiaoxuanran>
    <Kkeyguanlizhuangtai></Kkeyguanlizhuangtai>
    <Shijianchuli></Shijianchuli>
    <Shuzubianhuazhence></Shuzubianhuazhence>
  </div>
</template>

<script>
import keyguanlizhuangtai from '../components/kkeyguanlizhuangtai.vue';
import Mobanyufa from '../components/mobanyufa.vue';
import Shijianchuli from '../components/shijianchuli.vue';
import Shuxingbangding from '../components/shuxingbangding.vue';
import Tiaojianxuanran from '../components/tiaojianxuanran.vue';
import liebiaoxuanran from '../components/liebiaoxuanran.vue';
import shijianchuancan from '../components/shijianchuancan.vue';
import shijianxiushifu from '../components/shijianxiushifu.vue';
import Shuzubianhuazhence from '../components/shuzubianhuazhence.vue';
import shuzubianhuazhence from '../components/shuzubianhuazhence.vue';

export default {
  name: 'home',
  components: {
    Mobanyufa,
    Shuxingbangding,
    Tiaojianxuanran,
    liebiaoxuanran,
    keyguanlizhuangtai,
    Shijianchuli,
    shijianchuancan,
    shijianxiushifu,
    shuzubianhuazhence
  },
}
</script>

<style scoped>
.home-container{
  position: relative;
  z-index: 10;
}

h1 {
  z-index: 11;
  color: aqua;
}
</style>
