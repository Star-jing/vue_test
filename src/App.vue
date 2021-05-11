<template>
  <div id="app">
    <Box />
    <Tab />
    <Nav />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Img />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Box from "./components/Box.vue";
import Img from "./components/Img.vue";
import Tab from "./components/Tab.vue";
import Nav from "./components/Nav.vue";
export default {
  name: "App",
  components: {
    HelloWorld,
    Box,
    Img,
    Tab,
    Nav,
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
}
</style>
