<template>
  <div class="hero">
    <img class="" src="../assets/influencer-hero.jpg" alt="The Fabulous Social Club Logo" />
  </div>
</template>

<script>
export default {
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
