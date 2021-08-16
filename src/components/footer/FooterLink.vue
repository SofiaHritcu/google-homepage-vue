<template>
    <a 
        v-for="link in links"
        :key="link.text"
        v-bind:class="link.responsive"
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