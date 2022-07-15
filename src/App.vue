<template>
  <section id="app" >

    <Header />
        <Main />
  </section>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main

  }
}
</script>

<style lang="scss">

  @import "~bootstrap/scss/bootstrap.scss";

</style>
