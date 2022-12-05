<script>
import ComicCardItem from './ComicCardItem.vue';
import comicsList from '../comicsList';

export default {
    data() {
        return {
            comicsList,
        };
    },
    components: { ComicCardItem }
};
</script>

<template>
    <div class="bg-dark py-5">
        <div class="container">
        <div class="row row-cols-1 row-cols-md-6 g-4">
            <div class="col" v-for="(singleCard, i) in comicsList" :key="(singleCard.series + i)">
                <ComicCardItem :card="singleCard"></ComicCardItem>
            </div>
        </div>
    </div>
    </div>
    
   
    
</template>