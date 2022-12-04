<script >
    import TheHeader from './components/TheHeader.vue';
    import TheFooter from './components/TheFooter.vue';
    import Shop from './components/Shop.vue';
    import SingUp from './components/SingUp.vue';

    export default{
        components: { TheHeader, TheFooter, Shop, SingUp }
        
    }
</script>

<template>
    <TheHeader></TheHeader>

    <div class="py-5 bg-dark text-light "> 
        <div class="container">
            --> Content goes here &lt;-- 
        </div> 
    </div>

    <Shop></Shop>

    <TheFooter></TheFooter>

    <SingUp></SingUp>
</template>

<style lang="scss">
@use "./styles/general.scss";

</style>
