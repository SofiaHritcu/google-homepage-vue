// template for html page rendering
<template>
  <Navbar></Navbar>
  <Main></Main>
  <Footer></Footer>
</template>

// exporting the new vue component
<script>
  import Navbar from './navbar/Navbar.vue'
  import Main from './main/Main.vue'
  import Footer from './footer/Footer.vue'
  export default {
    name: 'Homepage',
    components: {
      Navbar, Main, Footer
    }
  }
</script>


