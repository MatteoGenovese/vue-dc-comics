<template>
  <section id="app">
    <Header />
    <Main />
    <OtherProducts />
    <Footer />
  </section>
</template>

<script>

import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import OtherProducts from './components/OtherProducts.vue';


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
    OtherProducts,
}
}
</script>

<style lang="scss">

  @import "~bootstrap/scss/bootstrap.scss";

</style>
