<template>
  <div id="app">
    <MenuProject />
    <BannerProject />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MenuProject from './components/MenuProject.vue'
import BannerProject from './components/BannerProject.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    MenuProject,
    BannerProject
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
