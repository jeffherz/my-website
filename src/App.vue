<template>
  <home-screen />
</template>

<script>
import HomeScreen from './components/HomeScreen.vue'

export default {
  name: 'App',
  components: {
    HomeScreen
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #b0dee6;
  margin-top: 60px;
}
</style>
