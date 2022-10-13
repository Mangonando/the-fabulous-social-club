<template>
  <div class="footer">
    <div class="icons-container">
      <a href="https://github.com/Mangonando/the-fabulous-social-club"
        ><img class="icon" src="../assets/github-logo.svg" alt="Github icon"
      /></a>
      <a href="https://www.linkedin.com/in/juan-f-ramirez/"
        ><img class="icon" src="../assets/linkedin-logo.svg" alt="Linkedin icon"
      /></a>
    </div>
    <div class="logo-container">
      <img
        class="logo"
        src="../assets/logo-the-fabulous-social-club.png"
        alt="The Fabulous Social Club Logo"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'FabulousFooter',
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.footer {
  @apply flex justify-center items-center flex-col;
}

.icons-container {
  @apply flex flex-row
    md:space-x-2 lg:space-x-4;
}

.icon{
  @apply w-8 md:w-9 lg:w-12 xl:w-14 h-auto
    fill-lime-400;
}

.logo {
  @apply w-20 md:w-36 lg:w-44 xl:w-48 h-auto;
}
</style>
