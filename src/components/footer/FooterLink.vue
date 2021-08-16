<template>
    <a 
        v-for="link in links"
        :key="link.text"
        class="footer-link"
        aria-disabled="{{link.disabled}}"
        v-bind:href="link.href">
        {{link.text}}
    </a>
</template>

<script>
export default {
    name: 'FooterLink',
    props: {
        links: Array, 
    }
}
</script>