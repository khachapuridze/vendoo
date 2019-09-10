<template>
  <div id="app">
    <app-imageContainer></app-imageContainer>
    <app-infoContainer></app-infoContainer>
    <app-categories></app-categories>
    <app-footer/>
  </div>
</template>

<script>
import Footer from './components/footer.vue'
import infoContainer from './components/infoContainer.vue'
import categories from './components/categories.vue'
import imageContainer from './components/imageContainer.vue'

export default {
  name: 'app',
  components: {
    'app-footer':Footer,
    'app-infoContainer':infoContainer,
    'app-categories': categories,
    'app-imageContainer': imageContainer
  
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
