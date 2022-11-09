<template>
    <main>
        <h2>{{titolo}}</h2>
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
        height: auto;
        width: 100%;
    }

    h2{
        text-align: center;
    }
</style>