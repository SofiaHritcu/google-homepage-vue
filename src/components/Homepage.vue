// template for html page rendering
<template>
  <Navbar></Navbar>
</template>

// exporting the new vue component
<script>
  import Navbar from './navbar/Navbar.vue'
  export default {
    name: 'Homepage',
    components: {
      Navbar
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

