<template>
  <div id="app">
    <img width="25%" src="https://tools-tips.com/wp-content/uploads/2017/06/animation.gif">
  </div>
</template>

<script>
import Meme from "./components/Meme";

export default {
  name: "App",
  components: {
    Meme
  }
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
