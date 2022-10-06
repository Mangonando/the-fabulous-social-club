<template>
    <div class="fab-grid">
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
    </div>
</template>

<script>
export default {
  name: 'FabulousGrid',
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.fab-grid {
  @apply grid grid-cols-3 gap-4;
}

.box {
  @apply w-32 h-32 bg-pink-500;
}
</style>
