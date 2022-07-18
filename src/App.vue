<template>
  <div id="app">
    <Header />
    <ComicCards />
    <Products />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import ComicCards from './components/ComicCards.vue';
import Products from './components/Products.vue'
import Footer from './components/Footer.vue';


export default {
  name: 'App',
  components: {
    Header,
    ComicCards,
    Products,
    Footer,
  }
}
</script>

<style lang="scss">
    @import "~bootstrap/scss/bootstrap.scss";
    div#app{
      background-color: #1C1C1C;
    }

</style>
