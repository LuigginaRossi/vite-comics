<script >
    import TheHeader from './components/TheHeader.vue';
    import TheFooter from './components/TheFooter.vue';
    import Shop from './components/Shop.vue';
    import SingUp from './components/SingUp.vue';
    import ComicsList from './components/ComicsList.vue';

    export default{
        components: { TheHeader, TheFooter, Shop, SingUp, ComicsList }
        
    }
</script>

<template>
    <TheHeader></TheHeader>

    <div class="py-5 bg-dark text-light "> 
        <div class="container">
            --> Content goes here &lt;-- 
        </div> 
    </div>

    <ComicsList></ComicsList>

    <Shop></Shop>

    <TheFooter></TheFooter>

    <SingUp></SingUp>
</template>

<style lang="scss">
@use "./styles/general.scss";

</style>
