<template>
  <div id='app'>
    <!-- <img src="./assets/logo.png"> -->
    <h1>Hello World!</h1>
    <Kev />
  </div>
</template>

<script>
import Kev from './components/Kev.vue';
export default {
  name: 'App',
  components: {
    Kev
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
