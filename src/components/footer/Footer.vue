<template>
        <FooterCountry></FooterCountry>
        <FooterLinks></FooterLinks>
</template>

<script>
    import FooterLinks from './FooterLinks.vue'
    import FooterCountry from './FooterCountry.vue'
    export default {
        name: 'Footer',
        components: {
            FooterLinks, FooterCountry
        }
    }
</script>

<style src="../../styles/footer.css"></style>