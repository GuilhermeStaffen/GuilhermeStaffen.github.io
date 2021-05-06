<template>
  <div id="app">
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<script>
import Footer from './components/includes/footer.vue'

export default {
  name: 'App',
  components: {
    Footer

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
  background-color: #314149;
}
</style>
