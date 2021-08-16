<template>
    <div class="left-section">
        <FooterLink v-bind:links="links" v-if="!noRef"></FooterLink>
        <FooterNoRefLink v-bind:links="links" v-else></FooterNoRefLink>
    </div>
</template>

<script>
    import FooterLink from './FooterLink.vue'
    import FooterNoRefLink from './FooterNoRefLink.vue'

    export default {
        name: 'FooterLeftSection',
        props: {
            links: Array, 
            noRef: Boolean
        },
        components: {
            FooterLink, FooterNoRefLink
        }
    }
</script>