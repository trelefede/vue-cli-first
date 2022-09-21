<template>
  <div id="app">
    <AppTitle msg="La mia prima app con Vue CLI!" />
  </div>
</template>

<script>
import AppTitle from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    AppTitle,

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
