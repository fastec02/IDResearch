<template>
  <div id="app">
    <a href="/">
      <img width="25%" src="./assets/logo.png">
    </a>
    <router-view/>
  </div>
</template>

<script>
import Home from "./components/Home";

export default {
  name: "app",
  components: {
    Home
  },
  mounted() {}
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
