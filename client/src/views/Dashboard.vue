<script>
import Header from "../components/Header.vue"
import Footer from "../components/Footer.vue"
export default {
    components: {
        Header,
        Footer
    }
}
</script>

<template>
    <Header />
    <RouterView />
    <Footer />
</template>

<style>
body {
    margin: 0
}
</style>