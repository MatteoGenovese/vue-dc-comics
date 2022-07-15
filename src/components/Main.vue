<template>
  <main >
    <div class="main-content">
      <div class="container">Content goes here</div>
    </div>

    <div class="product-content d-flex align-items-center justify-content-between">
      <div class="container d-flex align-items-center justify-content-between">
        <div class="d-flex align-items-center">
          <img src="../assets/images/buy-comics-digital-comics.png" alt="digital">
          Digital Comics
        </div>
        <div class="d-flex align-items-center">
          <img src="../assets/images/buy-comics-digital-comics.png" alt="digital">
          Digital Comics
        </div>
        <div class="d-flex align-items-center">
          <img src="../assets/images/buy-comics-digital-comics.png" alt="digital">
          Digital Comics
        </div>
        <div class="d-flex align-items-center">
          <img src="../assets/images/buy-comics-digital-comics.png" alt="digital">
          Digital Comics
        </div>
        <div class="d-flex align-items-center">
          <img src="../assets/images/buy-comics-digital-comics.png" alt="digital">
          Digital Comics
        </div>
      </div>
    </div>

    
  </main>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  main{

    .main-content{
    height: 150px;
    background-color: #000;
    color: #fff;
    }
    .product-content{
      height: 150px;
      background-color: #3880F1;
      color: #fff;
      img{
        height: 50px;
      }
    }

  }

</style>
