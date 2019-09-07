<template>
  <div id="app">
    <Footer/>
  </div>
</template>

<script>
import Footer from './components/footer.vue'

export default {
  name: 'app',
  components: {
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  box-sizing: border-box;


  ul {
    padding: 0;
  }
}
</style>
