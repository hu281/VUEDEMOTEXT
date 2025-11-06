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
    <jisuanshuxing></jisuanshuxing>
    <classbangding></classbangding>
    <stylebangding></stylebangding>
    <Zujianzucheng></Zujianzucheng>
    <Zujianqiantao></Zujianqiantao>
    <Zujianchuanzhiprops></Zujianchuanzhiprops>
    <PropsjiaoyanA></PropsjiaoyanA>
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
import jisuanshuxing from '../components/jisuanshuxing.vue';
import classbangding from '../components/classbangding.vue';
import stylebangding from '../components/stylebangding.vue';
import biaodanshujubangding from '../components/biaodanshujubangding.vue';
import mobanyinyong from '../components/mobanyinyong.vue';
import Zujianzucheng from '../components/zujianzucheng.vue';
import Zujianqiantao from '../components/zujianqiantao.vue';
import Zujianchuanzhiprops from '../components/zujianchuanzhiprops.vue';
import PropsjiaoyanA from '../components/propsjiaoyanA.vue';

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
    shuzubianhuazhence,
    jisuanshuxing,
    classbangding,
    stylebangding,
    biaodanshujubangding,
    mobanyinyong,
    Zujianzucheng,
    Zujianqiantao,
    Zujianchuanzhiprops,
    PropsjiaoyanA,
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
