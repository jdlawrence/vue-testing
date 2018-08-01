<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <JamilBase></JamilBase>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import JamilBase from './components/JamilBase.vue';

export default {
  name: 'app',
  components: {
    // HelloWorld,
    JamilBase,
  },
};
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
