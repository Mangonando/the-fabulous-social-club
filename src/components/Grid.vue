<template>
<div><h1 class="heading">Welcome to this extravaganza fashionista</h1>
  <div class="fab-grid-container">
    <div class="fab-grid">
      <img
        class="box hover:shadow-[#74B2CF] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-4.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#468F1A] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-2.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#E65E30] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-3.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#F56CAE] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-1.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#FFFC00] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-9.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#468F1A] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-7.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#F56CAE] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-5.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#CC3314] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-8.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box hover:shadow-[#FFFC00] hover:shadow-[0px_0px_100px_50px]"
        src="../assets/fabulous-10.png"
        alt="The Fabulous Social Club"
      />
      <!-- <img
        class="box"
        src="../assets/fabulous-2.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box"
        src="../assets/fabulous-2.png"
        alt="The Fabulous Social Club"
      />
      <img
        class="box"
        src="../assets/fabulous-2.png"
        alt="The Fabulous Social Club"
      /> -->
    </div>
  </div></div>
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
.heading {
  @apply font-bold text-2xl md:text-3xl lg:text-4xl
    my-4 md:my-8
}
.fab-grid-container {
  @apply flex justify-center items-center;
}

.fab-grid {
  @apply grid grid-cols-3 gap-4
    sm:max-w-screen-sm md:max-w-screen-md
    lg:max-w-screen-lg xl:max-w-screen-xl 2xl:max-w-screen-2xl;
}

.box {
  @apply w-full h-auto
    scale-100 transition ease-in duration-700
    hover:scale-125 hover:z-10;
}
</style>
