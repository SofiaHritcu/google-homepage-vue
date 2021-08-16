<template>
    <a href="hrefMain" hreflang="hrefLangMain">{{languageMain}}</a>
</template>

<script>
export default {
    name: 'MainLanguage',
    props: {
        hrefMain: String,
        hrefLangMain: String,
        languageMain: String,
    }
}
</script>