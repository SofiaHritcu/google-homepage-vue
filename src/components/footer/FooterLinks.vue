<template>
    <footer class="footer-links">
        <FooterLeftSection v-bind:links="linksLeft" v-bind:noRef="false"></FooterLeftSection>
        <FooterRightSection v-bind:links="linksRight"></FooterRightSection>
    </footer>
</template>

<script>
    import FooterLeftSection from './FooterLeftSection'
    import FooterRightSection from './FooterRightSection'

    export default {
        name: 'FooterLinks',
        components: {
            FooterLeftSection, FooterRightSection
        },
        data: function () {
            return {
                linksLeft: [
                    {
                        text: 'Despre',
                        href: 'https://about.google/?utm_source=google-RO&utm_medium=referral&utm_campaign=hp-footer&fg=1',
                        responsive: 'footer-link col-my-s-3 col-my-xs-4' 
                    },
                    {
                        text: 'Publicitate',
                        href: 'https://ads.google.com/intl/ro_ro/home/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpafooter&fg=1',
                        responsive: 'footer-link col-my-s-3 col-my-xs-4'  
                    },
                    {
                        text: 'Companii',
                        href: 'https://www.google.com/services/?subid=ww-ww-et-g-awa-a-g_hpbfoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpbfooter&fg=1#?modal_active=none',
                        responsive: 'footer-link col-my-s-3 col-my-xs-4'  
                    },
                    {
                        text: 'Cum funcționează Căutarea',
                        href: 'https://www.google.com/search/howsearchworks/?fg=1',
                        responsive: 'footer-link col-my-s-3 col-my-xs-1'  
                    },
                ],
                linksRight: [
                    {
                        text: 'Confidențialitate',
                        href: 'https://policies.google.com/privacy?hl=ro&fg=1',
                        responsive: 'footer-link col-my-s-4 col-my-xs-4' 
                    },
                    {
                        text: 'Termeni',
                        href: 'https://policies.google.com/terms?hl=ro&fg=1',
                        responsive: 'footer-link col-my-s-4 col-my-xs-4' 
                    },
                    {
                        text: 'Setări',
                        href: '#',
                        responsive: 'footer-link col-my-s-4 col-my-xs-4' 
                    },
                ]
                }
        }
    }
</script>