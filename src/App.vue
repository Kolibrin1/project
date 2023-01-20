<script>
    import Header from '@/components/Header.vue';
    import Functions from '@/components/Functions.vue'
    export default
    {
        name: 'App',
        components:
        {
            Header,
            Functions,
        },
    }
</script>

<template>
    <Header></Header>
    <Functions></Functions>
</template>

<style scoped>
    #app
    {
        font-family: 'Montserrat', sans-serif;
    }
</style>
