<template>
  <header class="d-flex justify-content-between container">
    <div class="img-container">
      <img src="../assets/images/dc-logo.png" alt="">
    </div>
    <div >
      <ul class="d-flex align-items-center">
        <li class="d-flex align-items-center">Characters</li>
        <li class="active d-flex align-items-center">COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  header{
    .img-container{
      padding: 0.5rem 0;
    height: 100px;
      img {
        height: 100%;
        }
    }

    ul{
      height: 100%;
      display: flex;
      align-items: center;
      li{
        display: flex;
        align-items: center;
        text-decoration: none;
        list-style: none;

        font-size: .8rem;
        padding: 0.5rem;
        height: 100%;

        &.active{
          
          color: #3880F1;
          border-bottom: 3px solid #3880F1;
        }
      }
    }
  }

</style>
