<template>
  <main>
    <div class="main-content">
      <div class="container">


      </div>
    </div>
  </main>
</template>

<script>
import OtherProducts from './OtherProducts.vue'

export default {
  name: 'Main',
  components: {
    OtherProducts,
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
main {

  .main-content {
    height: 150px;
    background-color: #000;
    color: #fff;
  }



}
</style>
