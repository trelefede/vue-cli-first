<template>
  <div id="app">
    <AppTitle msg="La mia prima app con Vue CLI!" />
    <JumboTron />
  </div>
</template>

<script>
import AppTitle from './components/HelloWorld.vue'
import JumboTron from './components/JumboTron.vue';

export default {
  name: 'App',
  components: {
    AppTitle,
    JumboTron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
