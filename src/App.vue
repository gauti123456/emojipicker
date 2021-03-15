<template>
  <div id="app">
    <h1>v-emoji-picker</h1>
    <h3>Install: npm install v-emoji-picker</h3>
    <Demo/>
  </div>
</template>

<script>
import Demo from "./components/Demo";

export default {
  name: "App",
  components: {
    Demo
  }
};
</script>

<style style="scss">
#app {
  font-family: Noto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
