<template>
    <main class="main">
        <img src="../../assets/logo.png" class="logo-image">
        <MainSearch></MainSearch>
        <MainActionButtons></MainActionButtons>
        <div class="languages">
            <p>Google oferit în:
                <a href="https://www.google.com/" hreflang="/hu/">magyar</a>
                <a href="https://www.google.com/" hreflang="/de/">Deutsch</a>
            </p>
            
        </div>
    </main>
</template>

<script>
    import MainSearch from './MainSearch.vue'
    import MainActionButtons from './MainActionButtons.vue'
    export default {
        name: 'Main',
        components: {
            MainSearch, MainActionButtons,
        },
    }
</script>

<style src="../../styles/main.css"></style>