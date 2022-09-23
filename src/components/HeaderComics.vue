<template>
  <div class="content">
    <div>
        <img src="../assets/img/dc-logo.png" alt="logo-header">
    </div>
    <div>
        <ul class="list">
            <li> <a href="">CHARACTERS</a></li>
            <li><a href="">COMICS</a></li>
            <li><a href="">MOVIE</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">GAMES</a></li>
            <li><a href="">COLLECTIBLES</a></li>
            <li><a href="">VIDEO</a></li>
            <li><a href="">FANS</a></li>
            <li><a href="">NEWS</a></li>
            <li><a href="">SHOP</a></li>
        </ul>
    </div>

  </div>
</template>

<script>
export default {
name: 'HeaderComics',
}
</script>

<style lang="scss" scoped>

.content {
    max-width: 1200px;
    margin: 0 auto;
    display:flex;
    justify-content: space-between;
    align-items: center;
     .list {
        display: flex;
        list-style-type: none;
        
        li {
            padding: 0px 10px; 
             
        }
        a {
            text-decoration: none;
            color: black;
            padding: 28px 0px;
            
            
        }
    }
}

img {
    width: 60px;
    margin: 10px 0;
}

a:hover {
    border-bottom: 4px solid #0282f9;
}
</style>