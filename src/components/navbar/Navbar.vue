<template>
    <nav class="nav">
        <NavLink textNavlink="Gmail" hrefNavlink="https://accounts.google.com/b/0/AddMailService"></NavLink>
        <NavLink textNavlink="Imagini" hrefNavlink="https://www.google.ro/imghp?hl=ro&ogbl"></NavLink>
        <NavAppsButton></NavAppsButton>
        <NavAvatar></NavAvatar>
    </nav>
</template>

<script>
    import NavLink from './NavLink.vue'
    import NavAppsButton from './NavAppsButton.vue'
    import NavAvatar from './NavAvatar.vue'
    export default {
        name: 'Navbar',
        components: {
            NavLink, NavAppsButton, NavAvatar
        }
  }
</script>

<style src="../../styles/navbar.css"></style>