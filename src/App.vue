<script>
    import Header from '@/components/Header.vue';
    import Functions from '@/components/Functions.vue';
    import Support from '@/components/Support.vue';
    import SupportWrapper from '@/components/SupportWrapper.vue';
    export default
    {
        name: 'App',
        components:
        {
            Header,
            Functions,
            Support,
            SupportWrapper,
        },
    }
</script>

<template>
    <Header></Header>
    <Functions></Functions>
    <Support></Support>
    <SupportWrapper></SupportWrapper>
</template>

<style scoped>
    #app
    {
        font-family: 'Montserrat', sans-serif;
    }
</style>
