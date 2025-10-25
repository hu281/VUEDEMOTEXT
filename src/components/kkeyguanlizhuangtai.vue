<template>
  <div class="keyguanlizhuangtai">
    <h3>key属性添加到v-for中</h3>
    <!-- 推荐我们在任何时间段写v-for的时候，要为其加一个key 属性，key绑定的值期望是一个基础的类型的值，
    例如字符串或者number -->
    <!-- 最好不要使用index作为key值，我们要确保每一条数据的唯一索引不会发生变化
    因为这会基于数组的顺序来决定元素，如果数组的顺序发生变化，这些key值就变成了无效的，会导致重置出错 -->
    <div v-for="(name, index) in names" :key="index">{{ name }} --- {{ index }}</div>
    
    <div v-for="value in results" :key="value.gkey">
      <p>{{ value.name }}</p>
      <img :src="value.img" :alt="value.title">
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      names: ['张三零', '小王', '小李'],
      results: [
        {
          "gkey": "102094960",
          "qcmsintl": "0",
          "w64": -1,
          "gtype": "3",
          "title": "双人游戏大全",
          "url": "http://360game.360.cn/flash/102094960.html",
          "ggata": "(\"type\":\"flashgame\",\"appid\":\"102094960\")",
          "name": "双人游戏大全",
          "img": "/p0.qhimg.com/d/appstorage/74fcbblda492f34b5ba49499549afba0.png"
        },
        {
          "gkey": "102144745",
          "qcmsintl": "0",
          "w64": -1,
          "gtype": "3",
          "title": "餐厅游戏大全",
          "url": "http://360game.360.cn/flash/102144745.html",
          "ggata": "(\"type\":\"flashgame\",\"appid\":\"102144745\")",
          "name": "餐厅游戏大全",
          "img": "/p2.qhimg.com/t01c4a2f17a198def57.png"
        },
        {
          "gkey": "102144642",
          "qcmsintl": "0",
          "w64": -1,
          "gtype": "3",
          "title": "火柴人游戏合集",
          "url": "http://360game.360.cn/flash/102144642.html",
          "ggata": "(\"type\":\"flashgame\",\"appid\":\"102144642\")",
          "name": "火柴人游戏合集",
          "img": "/p1.qhimg.com/t0147f6ec029fefe8d7.png"
        }
      ],
      myObject: {
        title: '游戏列表',
        author: 'ADAD',
        Date: '2021-09-01'
      }
    }
  }
}
</script>

<style scoped>
.keyguanlizhuangtai {
  color: green;
}
</style>