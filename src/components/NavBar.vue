<template>
    <div class="navbar">
      <img
        class="logo"
        src="../assets/logo-the-fabulous-social-club.png"
        alt="The Fabulous Social Club Logo">
    </div>
</template>

<script>
export default {
  name: 'FabulousNavBar',
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.navbar {
  @apply bg-white my-2
    flex justify-center items-center;
}

.logo {
  @apply w-24 h-auto;
}
</style>
