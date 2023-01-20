<script>
    import Header from '@/components/Header.vue';
    import Functions from '@/components/Functions.vue';
    import Support from '@/components/Support.vue';
    import SupportWrapper from '@/components/SupportWrapper.vue';
    import Plans from '@/components/Plans.vue';
    export default
    {
        name: 'App',
        components:
        {
            Header,
            Functions,
            Support,
            SupportWrapper,
            Plans,
        },
    }
</script>

<template>
    <Header></Header>
    <Functions></Functions>
    <Support></Support>
    <SupportWrapper></SupportWrapper>
    <Plans></Plans>
</template>

<style scoped>
    #app
    {
        font-family: 'Montserrat', sans-serif;
    }
</style>
