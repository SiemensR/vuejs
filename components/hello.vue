<template>
    <h1>{{ greeting }}</h1>
</template>

<script>
    module.exports = {
        data: function() {
            return {
                greeting: 'Hello Vueify! This is the first try'
            }
        }
    }
</script>

<style>
    h1 {
        font-family: 'Roboto', sans-serif;
        color: black;
    }
</style>