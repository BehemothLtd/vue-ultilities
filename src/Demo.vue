<template>
  <div>
    <div>
      <h1>Loading</h1>
      <!-- <Loading ref="Loading" imagePath="https://cdn.onlinewebfonts.com/svg/img_235526.png" /> -->
      <Loading ref="Loading" :template="1" />
      <Loading ref="Loading" :template="2" />
      <Loading ref="Loading" :template="3" />
      <Loading ref="Loading" :template="4" />
      <Loading ref="Loading" :template="5" />
      <Loading ref="Loading" :template="6" />
      <Loading ref="Loading" :template="7" />
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