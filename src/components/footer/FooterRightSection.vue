<template>
    <div class="right-section">
        <FooterLink v-bind:links="links"></FooterLink>
    </div>
</template>

<script>
    import FooterLink from './FooterLink.vue'

    export default {
        name: 'FooterLeftSection',
        props: {
            links: Array, 
            noRef: Boolean
        },
        components: {
            FooterLink
        }
    }
</script>