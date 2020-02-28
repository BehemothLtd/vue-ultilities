<template>
  <div>
    <div>
      <h1>Loading</h1>
      <Loading ref="Loading" imagePath="https://cdn.onlinewebfonts.com/svg/img_235526.png" />
    </div>
  </div>
</template>

<script>
import Loading from "./components/Loading.vue";

export default {
  components: {
    Loading
  },
  mounted: function() {
    this.$refs.Loading.show();
  }
};
</script>

<style>
</style>