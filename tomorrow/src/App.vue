<template>
  <div id="app">
    <Panel context="Welcome111123 to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Panel from './components/Panel.vue';

export default {
  name: 'App',
  components: {
    Panel
  },
};
</script>

<style>
#app {
  width: 100%;height: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
