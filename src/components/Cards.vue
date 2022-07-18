<template>

  <div id="cards">

    <img src="thumbPassed" alt="Default">
    <p>pricePassed</p>
    

  </div>
</template>

<script>
import { stringify } from 'querystring';

export default {
  name: 'Cards',
  props : {
    thumbPassed : String,
    pricePassed : String,
    seriesPassed : String,
    typePassed : String,
  },
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
