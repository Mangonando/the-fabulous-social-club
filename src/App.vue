<template>
  <NavBar />
  <Hero />
  <Grid />
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
</style>
