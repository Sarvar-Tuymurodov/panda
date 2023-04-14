<template>
    <Navbar />
    <router-view />
    <Footer />
</template>
<script setup>
import Navbar from "@/components/navigation/Navbar.vue";
import Footer from "@/components/navigation/Footer.vue";
</script>

<style lang="sass">
*
    box-sizing: border-box
    margin: 0
    padding: 0

body
    background-color:#FFF

html
    +intReg()
    color: $color-text

.container
    max-width: 1600px
    width: 100%
    margin: 0 auto
</style>
