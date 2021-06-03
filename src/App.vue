<template>
  <div id="app">
    <HelloWiredElements />
  </div>
</template>

<script>
import HelloWiredElements from "./components/HelloWiredElements";

export default {
  name: "App",
  components: {
    HelloWiredElements,
  },
};
</script>

<style>
#app {
  font-family: "Gloria Hallelujah", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  margin: 0;
  font-size: 16px;
  line-height: 1.8;
}
</style>
