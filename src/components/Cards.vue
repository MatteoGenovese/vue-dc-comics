<template>

  <div class="pz_card">
    <div class="img-container">
      <img :src="thumbPassed" alt="Default">
    </div>
    <!-- <div>{{ pricePassed }}</div> -->
    <div>{{ seriesPassed }}</div>
    <!-- <div>{{ typePassed }}</div> -->
  </div>

</template>

<script>

export default {
  name: 'Cards',
  props: {
    thumbPassed: String,
    pricePassed : String,
    seriesPassed : String,
    typePassed : String,
  },
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">


    div.pz_card {
      width: calc( 100% / 6 );
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
      object-fit: cover;

      div{
        margin-top: 15px;
      }
      .img-container {
        width: 160px;
        height: 160px;
        overflow: hidden;
      }
    }
</style>
