<template>
  <header class="d-flex justify-content-between container">
    <div class="img-container">
      <img src="../assets/images/dc-logo.png" alt="">
    </div>
    <div >
      <ul class="d-flex align-items-center">
        <li v-for="(page, index) in menuPages" 
        :key="index"
        :class="{active: page.isActive == true} ">
        {{page.title}}
        </li> 
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  data: function() {
    return {
      menuPages: [
        {
          title: "Characters",
          isActive: false
        },
        {
          title: "COMICS",
          isActive: true
        },
        {
          title: "MOVIES",
          isActive: false
        },
        {
          title: "TV",
          isActive: false
        },
        {
          title: "GAMES",
          isActive: false
        },
        {
          title: "COLLECTIBLES",
          isActive: false
        },
        {
          title: "VIDEOS",
          isActive: false
        },
        {
          title: "FANS",
          isActive: false
        },
        {
          title: "NEWS",
          isActive: false
        },
        {
          title: "SHOP",
          isActive: false
        }, ]}},
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
        text-transform: uppercase;

        font-size: .8rem;
        padding: 0.5rem;
        height: 100%;

        &:hover{
          cursor: pointer;
          background-color: #3880F1;
          color: white;
        }
        &.active{
          color: #3880F1;
          border-bottom: 3px solid #3880F1;
        }
      }
    }
  }

</style>
