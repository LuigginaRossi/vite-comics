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
            <div class="card-body">
                <h5 class="card-title">{{card.series}}</h5>        
            </div>
        </div>
</template>