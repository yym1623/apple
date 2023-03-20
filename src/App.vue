<script>
// components
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';

// routers
import Home from './components/Home.vue';

export default {
  components: {
    Header,
    Footer,
    Home,
  }
}
</script>


<template>
  <Header />
  <Home />
  <Footer />
</template>

<style lang="scss">

</style>