<template>
    <a class="nav-link" v-bind:href="hrefNavlink">{{textNavlink}}</a>
</template>

<script>
  export default {
    name: 'NavLink',
    props: {
      textNavlink: String,
      hrefNavlink: String,
    },
  }
</script>

