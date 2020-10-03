<template>
  <div id="app">
    <Navigation />
  </div>
</template>

<script>
import Navigation from "./components/Navigation";

export default {
  name: 'App',
  components: {
      Navigation
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Open Sans";
  }
</style>
