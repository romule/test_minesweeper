<template>
  <div class="hello"></div>
  <MineCell />
</template>

<script>
import MineCell from "./MineCell.vue";

export default {
  name: "MineSweeper",

  components: {
    MineCell,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  display: grid;
  /* grid-template-columns: repeat(10, 1fr);
  grid-template-rows: repeat(10, 25px);
  max-width: 250px;
  margin: 20px auto; */
}
</style>
