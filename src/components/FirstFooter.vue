<template>
    <div class="menu-footer">
       <div class="menu-list">
          <div class="content-list">
              <h3>DC COMICS</h3>
              <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Comics</a></li>
                  <li><a href="#">Movies</a></li>
                  <li><a href="#">TV</a></li>
                  <li><a href="#">Videos</a></li>
                  <li><a href="#">News</a></li>
                  
              </ul>
              <h3>SHOP</h3>
              <ul>
                  <li><a href="#">Shop DC</a></li>
                  <li><a href="#">Shop DC Collectibles</a></li>
                  
              </ul>
          </div>
          <div class="content-list">
              <h3>DC</h3>
              <ul>
                  <li><a href="#">Terms Of Use</a></li>
                  <li><a href="#">Privacy policy (New)</a></li>
                  <li><a href="#">Ad Choices</a></li>
                  <li><a href="#">Advertising</a></li>
                  <li><a href="#">Jobs</a></li>
                  <li><a href="#">Talent Workshops</a></li>
                  <li><a href="#">CPSC Certificates</a></li>
                  <li><a href="#">Ratings</a></li>
                  <li><a href="#">Shop Help</a></li>
                  <li><a href="#">Contact Us</a></li>
              </ul>
          </div>
          <div class="content-list">
              <h3>SITES</h3>
              <ul>
                  <li><a href="#">DC</a></li>
                  <li><a href="#">MAD Magazine</a></li>
                  <li><a href="#">DC Kids</a></li>
                  <li><a href="#">DC Universe</a></li>
                  <li><a href="#">DC Power Visa</a></li>
                  
              </ul>
          </div>
       </div>
       <div class="logo-footer">
          <img src="../assets/img/dc-logo-bg.png" alt="logo-bg">
       </div>
    </div>
  </template>
  
  <script>
  export default {
  name : 'FirstFooter',
  }
  </script>
  
  <style lang="scss" scoped>
  .menu-footer{
      background-image: url(../assets/img/footer-bg.jpg);
      display: flex;
      color: white;
      overflow: hidden;
      justify-content: space-around;
    }
    .logo-footer img {
      width: 100%;
      margin: -50px 0;
    }
    .menu-list{
      display: flex;
      li {
          list-style-type: none;
          padding: 2px 0;
          a{
              color: rgb(201, 192, 192);
              text-decoration: none;
              font-size:12px;
          }
          a:hover{
              text-decoration:underline;
          }
          };
      .content-list{
          padding: 20px 30px;
          h3{
              padding: 15px 0;
          }
      }    
    }
   
  </style>