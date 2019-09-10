<template>
    <div id="main">
        <Header title="我的电影"/>

            <Login/>

        <Tabber/>

    </div>
</template>

<script>
    import Header from "@/components/Header";
    import Tabber from '@/components/Tabber';
    import Login from '@/components/Login'
    export default {
        name: "Mine",
        components: {
            Header,
            Tabber,
            Login
        },
    }
</script>

<style scoped>

</style>