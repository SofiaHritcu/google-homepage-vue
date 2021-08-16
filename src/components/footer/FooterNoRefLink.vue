<template>
    <a 
        v-for="link in links"
        :key="link.text"
        class="footer-link"
        aria-disabled="true"
        style="pointer-events: none">
        {{link.text}}
    </a>
</template>

<script>
export default {
    name: 'FooterNoRefLink',
    props: {
        links: Array, 
    }
}
</script>