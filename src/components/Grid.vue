<template>
    <h1 class="grid">The fabulous social club</h1>
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
.grid {
  @apply bg-pink-500;
}
</style>
