<template>
  <footer>
    <div class="footer-top">
      <div class="container d-flex justify-content-between">
        <div id="footer-left-container" class="d-flex">
          <div class="links">
            <h2>DC Comics</h2>
            <ul>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>
            <h2>SHOP</h2>
            <ul>
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>
          </div>
          <div class="links">
            <h2>DC</h2>
            <ul>
              <li>Terms Of Use</li>
              <li>Privacy policy (New)</li>
              <li>Ad Choices</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscriptions</li>
              <li>Talent Workshops</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contact Us</li>
            </ul>
          </div>
          <div class="links">
            <h2>SITES</h2>
            <ul>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>
            </ul>
          </div>

        </div>


        <div id="footer-right-container">
          <img src="../assets/images/dc-logo-bg.png" alt="">
        </div>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="container d-flex justify-content-between align-items-center">

        <div id="footer-left-container" class="d-flex">
          <a href="#">SIGN-UP NOW!</a>
        </div>

        <div id="footer-right-container">
          <span>FOLLOW US</span>
          <img src="../assets/images/footer-facebook.png" alt="">
          <img src="../assets/images/footer-periscope.png" alt="">
          <img src="../assets/images/footer-pinterest.png" alt="">
          <img src="../assets/images/footer-twitter.png" alt="">
          <img src="../assets/images/footer-youtube.png" alt="">
        </div>
      </div>

    </div>
  </footer>

</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import "~bootstrap/scss/bootstrap.scss";
  .footer-top{
    background-image: url(../assets/images/footer-bg.jpg);
    width: 100%;
    height: 17rem;

    div#footer-right-container{
      height: 17rem;
      overflow: hidden;
      text-align: center;


      img{
        height: 400px;
        object-fit: cover;
        vertical-align: middle;
        position: relative;
        top:50%;
        -ms-transform: translateY(-50%);
        transform: translateY(-50%);
      }

    }

    div#footer-left-container{
      height: 100%;
      font-size: 0.7rem;
      color: white;

      h2{
        font-size: 1.2rem;
      }
      .links{
        margin-right: 30px;
      }
      ul{
        text-decoration: none;
        list-style: none;
        padding-left: 0;
      li{
        color: #88847A;

        &:hover{
          text-decoration: underline;
          cursor: pointer;
        }

        }
      }

    }
        }
    .footer-bottom {
      height: 7rem;
      background-color: #303030;

      .container{
        height: 100%;
      }

      a{
        padding: 1rem;
        background-color: #303030;
        border: 4px solid #008DFF;
        color: white;
        text-decoration: none;
      }
      span, img{
        color: #008DFF;
        margin-right: 1rem;
      }

      .footer-right-container,
      .footer-left-container{
        height: 100%;
      }


    }
</style>
