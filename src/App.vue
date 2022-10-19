<template>
  <div class="logo-header">
    <img width="100" height="100" alt="Vue logo" src="./assets/war-zone.png" />
    <h1>MineSweeper</h1>
  </div>
  <MineSweeper msg="Welcome to Your Vue.js App" />
</template>

<script>
import MineSweeper from "./components/MineSweeper.vue";

export default {
  name: "App",
  components: {
    MineSweeper,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.logo-header {
  display: flex;
  justify-content: center;
  align-items: flex-end;
}
</style>
