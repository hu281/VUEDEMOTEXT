<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from './views/home.vue';

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
body {
  background-color: #000;
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

#app {
  min-height: 100vh;
}
</style>