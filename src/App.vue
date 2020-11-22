<template>
  <div id="app">
    <questao-3 />
    <questao-4 />
  </div>
</template>

<script>
import questao3 from "./components/Questao3.vue";
import questao4 from "./components/Questao4.vue";

export default {
  name: "App",
  components: {
    questao3,
    questao4,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}
</style>
