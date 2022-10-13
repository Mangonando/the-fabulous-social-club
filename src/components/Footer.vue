<template>
  <div class="footer">
    <img
      class="logo"
      src="../assets/logo-the-fabulous-social-club.png"
      alt="The Fabulous Social Club Logo"
    />
    <img class="logo" src="../assets/github-logo.svg" alt="Github logo" />
    <img class="logo" src="../assets/linkedin-logo.svg" alt="Linkedin logo" />
  </div>
</template>

<script>
export default {
  name: "FabulousFooter",
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.footer {
  @apply bg-yellow-400 flex justify-center items-center;
}

.logo {
  @apply w-24 md:w-28 lg:w-32 xl:w-48 h-auto;
}
</style>
