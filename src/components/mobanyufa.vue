<template>
<div class="mobanyufa">
  <h3>模板语法</h3>
  
  <div>{{ ok ? "oki" : "ok2" }}</div>
  
  <div>{{ rawHtml }}</div>
  <div v-html="rawHtml"></div>
</div>
</template>

<script>
export default {
  name: "mobanyufa",
  data() {
    return {
      msg: "adadadadad",
      number: 1,
      ok: true,
      rawHtml: "<a href='https://www.baidu.com'>百度</a>"
    }
  },
}
</script>

<style scoped>
.mobanyufa {
  color: yellow;
}
</style>