<template>
    <div id="main">
        <Header/>
        <Tabber/>
        hello cinema
    </div>
</template>

<script>
    import Header from "@/components/Header";
    import Tabber from '@/components/Tabber';
    export default {
        name: "Cinema",
        components: {
            Header,
            Tabber,
        },
    }
</script>

<style scoped>

</style>