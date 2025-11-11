<template>
  <div class="home-container">
    <h1>VUE3教学</h1>
    <hr>
    <Mobanyufa></Mobanyufa>
    <Shuxingbangding></Shuxingbangding>
    <Tiaojianxuanran></Tiaojianxuanran> 
    <liebiaoxuanran></liebiaoxuanran>
    <shijianchuancan></shijianchuancan>
    <shijianxiushifu></shijianxiushifu>
    <keyguanlizhuangtai></keyguanlizhuangtai>
    <Shijianchuli></Shijianchuli>
    <Shuzubianhuazhence></Shuzubianhuazhence>
    <jisuanshuxing></jisuanshuxing>
    <Classbangding></Classbangding>
    <stylebangding></stylebangding>
    <Biaodanshujubangding></Biaodanshujubangding>
    <Mobanyinyong></Mobanyinyong>
    <Zujianzucheng></Zujianzucheng>
    <Zujianqiantao></Zujianqiantao>
    <Zujianchuanzhiprops></Zujianchuanzhiprops>
    <PropsjiaoyanA></PropsjiaoyanA>
    <Zujianshijian></Zujianshijian>
    <ZujianshijianVmodel></ZujianshijianVmodel>
    <chacaoslots></chacaoslots>
    <shengmingzhouqi></shengmingzhouqi>
    <shengmingzhouqiyingyong></shengmingzhouqiyingyong>


  </div>
</template>

<script>
import keyguanlizhuangtai from '../components/kkeyguanlizhuangtai.vue';
import Mobanyufa from '../components/mobanyufa.vue';
import Shijianchuli from '../components/shijianchuli.vue';
import Shuxingbangding from '../components/shuxingbangding.vue';
import Tiaojianxuanran from '../components/tiaojianxuanran.vue';
import liebiaoxuanran from '../components/liebiaoxuanran.vue';
import Shijianchuancan from '../components/shijianchuancan.vue';
import Shijianxiushifu from '../components/shijianxiushifu.vue';
import Shuzubianhuazhence from '../components/shuzubianhuazhence.vue';
import jisuanshuxing from '../components/jisuanshuxing.vue';
import Classbangding from '../components/classbangding.vue';
import Stylebangding from '../components/stylebangding.vue';
import Biaodanshujubangding from '../components/biaodanshujubangding.vue';
import Mobanyinyong from '../components/mobanyinyong.vue';
import Zujianzucheng from '../components/zujianzucheng.vue';
import Zujianqiantao from '../components/zujianqiantao.vue';
import Zujianchuanzhiprops from '../components/zujianchuanzhiprops.vue';
import PropsjiaoyanA from '../components/propsjiaoyanA.vue';
import Zujianshijian from '../components/zujianshijian.vue';
import ZujianshijianVmodel from '../components/zujianshijianVmodel.vue';
import chacaoslots from '../components/chachaoslots.vue';
import shengmingzhouqi from '../components/shengmingzhouqi.vue';
import shengmingzhouqiyingyong from '../components/shengmingzhouqiyingyong.vue';



export default {
  name: 'home',
  components: {
    Mobanyufa,
    Shuxingbangding,
    Tiaojianxuanran,
    liebiaoxuanran,
    keyguanlizhuangtai,
    Shijianchuli,
    Shijianchuancan,
    Shijianxiushifu,
    Shuzubianhuazhence,
    jisuanshuxing,
    Classbangding,
    Stylebangding,
    Biaodanshujubangding,
    Mobanyinyong,
    Zujianzucheng,
    Zujianqiantao,
    Zujianchuanzhiprops,
    PropsjiaoyanA,
    Zujianshijian,
    ZujianshijianVmodel,
    chacaoslots,
    shengmingzhouqi,
    shengmingzhouqiyingyong
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
