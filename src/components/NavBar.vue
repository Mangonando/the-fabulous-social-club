<template>
    <div class="navbar">
      <div class="logo-container">
        <img
          class="logo"
          src="../assets/logo-the-fabulous-social-club.png"
          alt="The Fabulous Social Club Logo">
      </div>
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
  @apply sticky top-0 z-50 bg-white;
}

.logo-container {
  @apply py-2 flex justify-center items-center;
}

.logo {
  @apply w-24 md:w-28 lg:w-32 xl:w-48 h-auto;
}
</style>
