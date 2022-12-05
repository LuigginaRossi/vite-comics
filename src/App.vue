<script >
    import TheHeader from './components/TheHeader.vue';
    import TheFooter from './components/TheFooter.vue';
    import Shop from './components/Shop.vue';
    import SingUp from './components/SingUp.vue';
    import ComicsList from './components/ComicsList.vue';
    import Jumbotron from './components/Jumbotron.vue';

    export default{
        components: { TheHeader, TheFooter, Shop, SingUp, ComicsList, Jumbotron }
        
    }
</script>

<template>
    <TheHeader></TheHeader>

    <Jumbotron></Jumbotron>

    <ComicsList></ComicsList>

    <Shop></Shop>

    <TheFooter></TheFooter>

    <SingUp></SingUp>
</template>

<style lang="scss">
@use "./styles/general.scss";

</style>
