<script>
    import Header from '@/components/Header.vue';
    import Functions from '@/components/Functions.vue';
    import Support from '@/components/Support.vue';
    import SupportWrapper from '@/components/SupportWrapper.vue';
    import Plans from '@/components/Plans.vue';
    import Cases from './components/Cases.vue';
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
            Cases,
        },
    }
</script>

<template>
    <Header></Header>
    <Functions></Functions>
    <Support></Support>
    <SupportWrapper></SupportWrapper>
    <Plans></Plans>
    <Cases></Cases>
</template>

<style scoped>
    #app
    {
        font-family: 'Montserrat', sans-serif;
    }
</style>
