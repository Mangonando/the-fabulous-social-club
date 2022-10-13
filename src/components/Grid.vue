<template>
  <div class='fab-grid-container'>
    <div class='fab-grid'>
      <img
        class='box'
        src='../assets/fabulous-4.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-2.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-3.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-1.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-5.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-7.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-7.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-2.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-2.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-2.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-2.png'
        alt='The Fabulous Social Club'
      />
      <img
        class='box'
        src='../assets/fabulous-2.png'
        alt='The Fabulous Social Club'
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
