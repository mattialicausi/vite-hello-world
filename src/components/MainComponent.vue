<template>
    <main>
        <h1>{{titolo}}</h1>
    </main>
</template>

<script>
    export default {
        name: 'MainComponent',
        data() {
            return {
                titolo: 'Vite Hello World'
            }
        }
    }
</script>

<style lang="css">
    main {
        margin: 0 auto;
    }

    h1{
        text-align: center;
    }
</style>