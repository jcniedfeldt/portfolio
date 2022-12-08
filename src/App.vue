<template>
  <div id="app">
    <MainSection msg="Welcome to Your Vue.js App" />
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  </div>
</template>

<script>
import MainSection from "./components/MainSection.vue";

export default {
  name: "app",
  components: {
    MainSection
  }
};
</script>

<style>
/* #app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
