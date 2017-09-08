<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
    <detailComponent></detailComponent>
    <listComponent></listComponent>
  </div>
</template>

<script>
import listComponent from "./components/list-component.vue"
import detailComponent from "./components/detail-component.vue"
export default {
  name: 'app',
  components:{listComponent,detailComponent}
}
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
