
<script>
export default {
    data() {
        return {
            dcComicsList: ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"],
            shopList: ["Shop Dc", "Shop Dc Collectibles"],
            dcList: ["Term Of Use", "Privacy policy (New)", "Ad Choise", "Adversting", "Jobs", "Subscriptions", "Talent Workshops", "CPSC Certificateds", "Rating", "Shop Help", "Contact Us"],
            sitesList: ["DC", "MAD Magazine", "DC Kids", "DC Universe", "DC Power Visa",], 
        }
    },
}
</script>

<template>
    <footer class="py-5">
        <div class="container">
            <div class="row">

                <div class="col-auto">
                    <ul class="d-block">
                        <li>
                            <a href="#" class="text-light py-3 d-block">DC COMICS</a>
                        </li>
                        <li v-for="(element, i) in dcComicsList" :key="(element + i)">
                            <a href="#">{{element}}</a>
                        </li>
                    </ul>

                    <ul class="d-block">
                        <li>
                            <a href="#" class="text-light py-3 d-block">SHOP</a>
                        </li>
                        <li  v-for="(element, i) in shopList" :key="(element + i)">
                            <a href="#">{{element}}</a>
                        </li>
                  
                    </ul>
                </div>

                <div class="col-auto">
                    <ul class="d-block">
                        <li>
                            <a href="#" class="text-light py-3 d-block">DC</a>
                        </li>
                        <li v-for="(element, i) in dcList" :key="(element + i)" >
                            <a href="#">{{element}}</a>
                        </li>
                    </ul>
                </div>
                <div class="col-auto">
                    <ul class="d-block">
                        <li>
                            <a href="#" class="text-light py-3 d-block">SITES</a>
                        </li>
                        <li  v-for="(element, i) in sitesList" :key="(element + i)" >
                            <a href="#">{{element}}</a>
                        </li>
                    </ul>
                </div>
            </div>
            
        </div>
        
    </footer>
</template>

<style scoped>
    footer{
        background-image: url("../assets/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;   
    }

    ul a{
        color: grey;
        font-weight: 400;
    }

</style>