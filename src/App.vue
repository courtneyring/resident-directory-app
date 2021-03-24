<template>
    <div id="app">
        <MainNav />
        <router-view />
    </div>
</template>

<script>
    import MainNav from "@/components/Navbar.vue";

    export default {
        name: 'App',
        components: { MainNav }
    }
</script>


<style lang="scss">
@import '~@/assets/stylesheets/global.scss';

#app {
    font-family: 'Lato', Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
</style>
