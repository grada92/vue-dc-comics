<template>
  <div  class="box-black">
    
    <div class="section-text">
        <div class="multi-cards" v-for="card in dates" :key="card.series">
            <img :src="card.thumb" alt="thumb"/> 
            <p>{{card.series}}</p>

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
}
.section-text {
    max-width: 1200px;
    margin: 0 auto; 
    display: flex;
    flex-wrap: wrap;
    padding-top: 50px;
       
}
p {
    color:white;
    font-size: 14px;
    text-transform: uppercase;
    
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

</style>