<template>
    <div class="languages">
        <p>Google oferit în:
            <MainLanguage hrefMain="https://www.google.com/" hrefLangMain="/hu/" languageMain="Magyar"></MainLanguage>
            <MainLanguage hrefMain="https://www.google.com/" hrefLangMain="/de/" languageMain="Deutsch"></MainLanguage>
        </p>
    </div>
</template>

<script>
    import MainLanguage from './MainLanguage.vue'
    export default {
        name: 'MainLanguages',
        components: {
            MainLanguage, 
        }
    }
</script>