<template>
  <div>{{params.value}}</div>
</template>
<script>
import Vue from "vue";

export default Vue.extend({
  name: "PixelRankCell"
});
</script>

<style lang="scss" scoped>
div {
  width: 100px;
  text-align: center;
}
</style>