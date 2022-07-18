<template>
  <section id="app">
    <Header />
    <Main />
    <Products />
    <Footer />
  </section>
</template>

<script>

import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import Products from './components/Products.vue';



export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
    Products,
}
}
</script>

<style lang="scss">

  @import "~bootstrap/scss/bootstrap.scss";

</style>
