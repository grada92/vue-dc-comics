<template>
  <div  class="box-black">
    <div class="jumbotron"></div> <!---add jumbotron--->
    
    <div class="section-card">
        <div class="title-current"><h3>CURRENT SERIES</h3></div>
        <div class="multi-cards" v-for="card in dates" :key="card.series">
            <img :src="card.thumb" alt="thumb"/> 
            <p>{{card.series}}</p>

        </div>

        <div class="button-load">
        <button> <h3>LOAD MORE</h3> </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'SectionContent',
props:{
    dates: Array,
}
}
</script>

<style lang="scss" scoped >
.box-black {
    background-color: black;
    padding-bottom:30px
}
.section-card {
    max-width: 1200px;
    margin: 0 auto; 
    display: flex;
    flex-wrap: wrap;
    padding-top: 50px;
    position: relative;
       
}
p {
    color:white;
    font-size: 14px;
    text-transform: uppercase;
    
}

.title-current{
    position: absolute;
    left: 0;
    top: 0;
    transform: translate(0 , -50%);
    h3 {
        background-color: hsl(209deg 100% 49%);
        color: white;
        padding: 8px;
      }
  }

.jumbotron{
    background-image: url(@/assets/img/jumbotron.jpg);
    height: 350px;
    background-size: cover;
}
.multi-cards {
    width: calc(100% / 6 - 20px);
    margin: 10px;
    img{
    height: 210px;
    object-fit: initial;
    width: 100%;
    }
}

.multi-cards:hover {
    cursor:pointer;
    opacity: 0.8;
    transform: scale(1.1);
}

.button-load {
    text-align: center;
    width: 100%;
      button {
          background-color: hsl(209deg 100% 49%);
          text-align: center;
          color: white;
          padding: 10px 45px;
          border: none;
          cursor: pointer;
        }
  }

</style>