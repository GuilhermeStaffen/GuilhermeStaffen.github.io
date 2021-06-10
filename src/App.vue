<template>
  <div id="app">
    <Header/>

  </div>
</template>

<script>
import Header from './components/includes/header.vue';

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
#app {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif ;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #eeeaea;
  background-color: #181818;
}
</style>
