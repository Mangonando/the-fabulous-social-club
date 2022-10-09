<template>
  <div class="hero">
    <img class="" src="../assets/influencer-hero.jpg" alt="The Fabulous Social Club Logo" />
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line quotes
  name: "FabulousHero",
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.hero {
  @apply bg-green-500 flex justify-center items-center;
}
</style>
