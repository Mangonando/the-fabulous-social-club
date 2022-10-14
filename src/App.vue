<template>
  <NavBar />
  <Hero class="space-down" />
  <Grid class="space-down"/>
  <Footer />
</template>

<script>
import NavBar from './components/NavBar.vue';
import Hero from './components/Hero.vue';
import Grid from './components/Grid.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    Hero,
    Grid,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

.space-down {
  @apply mb-8 lg:mb-16;
}
</style>
