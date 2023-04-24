<template>
  <div id="app">
    <MainCard/>
  </div>
</template>

<script>
import MainCard from './components/MainCard.vue';
export default {
  name: 'App',
  components: {
        MainCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  background-image: url('../src/assets/1and0.webp');
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-color: rgba(255, 255, 255, 0.8); /** change the opacity value (0.0 to 1.0) to your liking*/
}
</style>
