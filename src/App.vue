<template>
  <div id="app">
    <BackgroundEffect></BackgroundEffect>
    <router-view></router-view>
  </div>
</template>

<script>
// import Home from './views/home.vue';
import BackgroundEffect from './components/BackgroundEffect.vue';

export default {
  name: 'App',
  components: {
    // Home
    BackgroundEffect,
  },
};
</script>

<style>
body {
  background-color: #000;
  color : #fff;
  font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.app-container {
  position: relative;
  min-height: 100vh;
  width: 100%;
  overflow-x: hidden;
  background-color: #000;
}
</style> 