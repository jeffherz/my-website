<template>
  <navigation />
  <home-screen />
</template>

<script>
import HomeScreen from './components/HomeScreen.vue'
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    HomeScreen,
    Navigation
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
