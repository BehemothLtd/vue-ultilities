<template>
  <div class="loading">
    <img :src="imagePath" />
  </div>
</template>

<script>
export default {
  props: {
    imagePath: {
      type: String,
      required: true
    }
  }
};
</script>

<style lang="scss" scoped>
.loading {
  display: flex;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 99999999;
  background: #00000099;
  align-items: center;
  justify-content: center;
}
</style>