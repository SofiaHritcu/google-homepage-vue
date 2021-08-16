// template for html page rendering
<template>
  <Navbar></Navbar>
  <Main></Main>
</template>

// exporting the new vue component
<script>
  import Navbar from './navbar/Navbar.vue'
  import Main from './main/Main.vue'
  export default {
    name: 'Homepage',
    components: {
      Navbar, Main
    }
  }
</script>


