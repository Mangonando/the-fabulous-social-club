<template>
  <div class='fab-grid-container'>
    <div class='fab-grid'>
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
      <img
        class='box'
        src='../assets/logo-the-fabulous-social-club.png'
        alt='The Fabulous Social Club Logo'
      />
    </div>
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
.fab-grid-container {
  @apply flex justify-center items-center;
}

.fab-grid {
  @apply grid grid-cols-3 gap-4
    sm:max-w-screen-sm md:max-w-screen-md
    lg:max-w-screen-lg xl:max-w-screen-xl 2xl:max-w-screen-2xl;
}

.box {
  @apply w-full h-auto bg-pink-500;
}
</style>
