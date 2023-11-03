<template>
  <HeaderBlue />
  <HeaderBlack />
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <FooterBlue />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import HeaderBlue from "./components/HeaderBlue.vue";
import HeaderBlack from "./components/HeaderBlack.vue";
import FooterBlue from "./components/FooterBlue.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    HeaderBlue,
    HeaderBlack,
    FooterBlue,
  },
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
