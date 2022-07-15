<template>
  <footer>
    <div class="d-flex justify-content-between container">
      <div id="footer-left-container">


      </div>


      <div id="footer-right-container">
        <img src="../assets/images/dc-logo-bg.png" alt="">
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
  footer{
    background-image: url(../assets/images/footer-bg.jpg);
    width: 100%;
    height: 15rem;

    div#footer-right-container{
      height: 15rem;
      overflow: hidden;
      text-align: center;
              position: relative;

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
        }
</style>
