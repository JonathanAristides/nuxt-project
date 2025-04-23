<template>
    <footer>
        <h3>FOOTER</h3>
        <a href="/">INDEX</a>
        <br>
        <a href="/about">ABOUT</a>
        <br>
        <br>
        <br>

        <hr>
        <h1>NUXT</h1>
        {{ runtimeConfig }}
        <br>
        {{ appConfig }}
    </footer>



</template>

<script setup lang="ts">
const runtimeConfig = useRuntimeConfig()
const appConfig = useAppConfig()
</script>

<style scoped>

</style>