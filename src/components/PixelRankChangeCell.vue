<template>
  <span class="box green-box" v-if="this.params.value > 0">{{this.params.value}}%</span>
  <span class="box red-box" v-else-if="this.params.value < 0">{{this.params.value}}%</span>
  <span class="box" v-else>{{this.params.value}}</span>
</template>

<script>
import Vue from "vue";
export default Vue.extend({
  name: "PixelRankChangeCell"
});
</script>

<style lang="scss" scoped>
@import "../styles/rank-change-cell.scss";
</style>