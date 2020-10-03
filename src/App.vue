<template>
  <div id="app">
    <br />
    <HelloWorld id="text" msg="MY MUSIC" />
    <music />
  </div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
import music from "./components/music.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    music,
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
  background-size: cover;
  background-image: url();
}
#text {
  color: rgb(0, 0, 0);
}
</style>
