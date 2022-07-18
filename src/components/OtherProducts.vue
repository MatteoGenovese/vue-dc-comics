<template>

  <div class="product-container">
    <div class="wrapper container" >
      <div class="product" v-for="(product,index) in products" :key="index">
        <div class="image-container">
          <img :src="require(`../assets/images/${product.url}`)" :alt="product.title">
        </div>
        <h4>{{ product.title }}</h4>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'OtherProducts',
  data: function() {
    return {
      products: [
        {
          title: "DIGITAL COMICS",
          url: "buy-comics-digital-comics.png"
        }, 
        {
          title: "DC MERCHANDISE",
          url: "buy-comics-merchandise.png",
        }, 
        {
          title: "SUBSCRIPTION",
          url: "buy-comics-subscriptions.png",
        }, 
        {
          title: "COMIC SHOP LOCATOR",
          url: "buy-comics-shop-locator.png",
        }, 
        {
          title: "DC POWER VISA",
          url: "buy-dc-power-visa.svg",
        }
        ]
    }
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.product-container {
  height: 150px;
  background-color: #3880F1;
  color: #fff;

  .container{
    display: flex;

  }
  .wrapper{
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;

    div.product{
      margin-right: 2rem;
    }
    div.product{
      display: flex;
      align-items: center;
    }
    h4{
      font-size: 1rem;
    }
  }
  img {
    height: 50px;
    width: 50px;
  }

}
</style>
