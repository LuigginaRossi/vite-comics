<!-- -->

<script>
    export default{
        props:{
            //mi aspetto un obj che è la singola card:
            card:{
                type: Object,
                required: true,
            }
        }

    }
</script>

<template>
        <div class="card">
            <img :src="card.thumb" class="card-img-top" alt="comic image">
            <div class="card-body bg-dark">
                <h6 class="card-title text-light">{{card.series}}</h6>        
            </div>
        </div>
</template>

<style lang="scss">
    .card{
        --bs-card-border-width: 0;
        --bs-card-border-color: none;
    }
</style>