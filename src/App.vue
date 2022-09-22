<template>
  <div id="app">
    <HeaderComics/>
    
  </div>
</template>

<script>
import HeaderComics from "./components/HeaderComics.vue";

export default {
  name: 'App',
  components: {
    HeaderComics,
}
}


</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 1200px;
  margin: 0 auto;
}
</style>
