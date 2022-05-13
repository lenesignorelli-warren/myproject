<template>
  <div id="app">
    <MenuProject />
    <BannerProject />
    <DestaquesProject />
    <Investir-Project />
    <RodapeProject />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MenuProject from "./components/MenuProject.vue";
import BannerProject from "./components/BannerProject.vue";
import DestaquesProject from "./components/DestaquesProject.vue";
import InvestirProject from "./components/InvestirProject.vue";
import RodapeProject from "./components/RodapeProject.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    MenuProject,
    BannerProject,
    DestaquesProject,
    InvestirProject,
    RodapeProject,
  },
};
</script>

<style>
* {
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
}
</style>
