<template>
    <footer class="footer-country">
        <FooterLeftSection v-bind:links="links" v-bind:href="links.href" v-bind:noRef="true"></FooterLeftSection>
    </footer>
</template>

<script>
    import FooterLeftSection from './FooterLeftSection'

    export default {
        name: 'FooterCountry',
        components: {
            FooterLeftSection, 
        },
        data: function () {
            return {links: [
                {
                    text: 'România',
                    href: '', 
                }
            ]}
        }
    }
</script>