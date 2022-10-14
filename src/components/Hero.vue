<template>
  <div class="hero">
    <img class="" src="../assets/fab-hero.png" alt="The Fabulous Social Club Hero" />
  </div>
</template>

<script>
export default {
  name: 'FabulousHero',
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.hero {
  @apply flex justify-center items-center;
}
</style>
