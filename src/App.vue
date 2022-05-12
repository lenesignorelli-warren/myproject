<template>
  <div id="app">
    <MenuProject />
    <BannerProject />
    <DestaquesProject />
    <Investir-Project />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MenuProject from './components/MenuProject.vue'
import BannerProject from './components/BannerProject.vue'
import DestaquesProject from './components/DestaquesProject.vue'
import InvestirProject from './components/InvestirProject.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    MenuProject,
    BannerProject,
    DestaquesProject,
    InvestirProject
  },
}
</script>

<style>

</style>
