<template>
  <div id="app">
    <HeaderComics/>
    <SectionContent :dates='cards'/>
    <SecondSection/>
    <FirstFooter />
    <SecondFooter/>
    
  </div>
</template>

<script>
import HeaderComics from "./components/HeaderComics.vue";
import SectionContent from "./components/SectionContent.vue";
import SecondSection from "./components/SecondSection.vue";
import FirstFooter from "./components/FirstFooter.vue";
import SecondFooter from "./components/SecondFooter.vue";
import {cards} from './data.js/data.js'

export default {
  name: 'App',
  data(){
    return {cards}
  },
  components: {
    HeaderComics,
    SectionContent,
    SecondSection,
    FirstFooter,
    SecondFooter,
}
}


</script>

<style lang="scss">
 @import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: 'Poppins', sans-serif;
    -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
 
  
}
</style>
