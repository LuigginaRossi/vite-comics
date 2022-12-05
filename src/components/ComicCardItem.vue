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
        <div class="card border-dark">
            <img :src="card.thumb" class="card-img-top" alt="comic image">
            <div class="card-body bg-dark">
                <h6 class="card-title text-light">{{card.series}}</h6>        
            </div>
        </div>
</template>

<style lang="scss">
        img{
            aspect-ratio: 1/1;
            object-fit: cover;
        }
</style>