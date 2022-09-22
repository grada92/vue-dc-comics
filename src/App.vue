<template>
  <div id="app">
    <HeaderComics/>
    <SectionContent/>
    
  </div>
</template>

<script>
import HeaderComics from "./components/HeaderComics.vue";
import SectionContent from "./components/SectionContent.vue";

export default {
  name: 'App',
  components: {
    HeaderComics,
    SectionContent,
}
}


</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}
</style>
