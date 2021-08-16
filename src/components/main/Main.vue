<template>
    <main class="main">
        <img src="../../assets/logo.png" class="logo-image">
        <MainSearch></MainSearch>
        <MainActionButtons></MainActionButtons>
        <MainLanguages></MainLanguages>
    </main>
</template>

<script>
    import MainSearch from './MainSearch.vue'
    import MainActionButtons from './MainActionButtons.vue'
    import MainLanguages from './MainLanguages.vue'
    export default {
        name: 'Main',
        components: {
            MainSearch, MainActionButtons, MainLanguages
        },
    }
</script>

<style src="../../styles/main.css"></style>