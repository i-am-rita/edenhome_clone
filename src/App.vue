<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Nav />
  <Navbar />
  <Home />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Home from "./components/Home.vue";
import Nav from "./components/Nav.vue";

export default {
  name: "App",
  components: {
    Nav,
    Navbar,
    Home,
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
  background-color: #fff9f5;
  /* padding: 0;
  margin: -0; */
  /* margin: -1% 0 0 0; */
}
</style>
