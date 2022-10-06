<template>
  <NavBar />
  <Hero />
  <Grid />
</template>

<script>
import NavBar from './components/NavBar.vue';
import Hero from './components/Hero.vue';
import Grid from './components/Grid.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    Hero,
    Grid,
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
