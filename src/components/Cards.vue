<template>

    <div class="pz_card">
      <img :src="thumbPassed" alt="Default">
      <p>{{ pricePassed }}</p>
      <p>{{ seriesPassed }}</p>
      <p>{{ typePassed }}</p>
    </div>

</template>

<script>

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


  .pz_card{
    width: 160px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    div.pz_card img{
      width: 100px;
      height: 100px;
    }
  }


</style>
