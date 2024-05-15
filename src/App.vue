<template>
  <div id="app">
    <HelloWorld msg="Hello Vue 2 + Vite" />
    <Carrousel></Carrousel>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Carrousel from "./components/Carrousel.vue";
export default {
  components: {
    HelloWorld,
    Carrousel
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 90%;

}
</style>