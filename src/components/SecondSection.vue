<template>
  <div class="logo-box" >
    <div class="img-container">
        <div class="card">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMICS</span>
        </div>

        <div class="card">
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <span>DC MERCHANDISE</span>
        </div>

        <div class="card">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>SUBSCRIPTION</span>
        </div>

        <div class="card">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <span>COMIC SHOP LOCATOR</span>
        </div>

        <div class="card alternative">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span>DC POWER VISA</span>
        </div>
        
        

    </div>
  </div>
</template>

<script>
export default {
name: 'SecondSection',

}
</script>

<style lang="scss" scoped>
.logo-box {
    background-color: #0282f9;
    padding: 25px 0px;
}
.img-container {
    display: flex;
    max-width: 1200px;
    margin: 0 auto;
    justify-content: space-around;

} .card {
    display: flex;
    align-items: center;
    column-gap: 15px;
    color:white;

} img {
    height: 40px;
}



</style>