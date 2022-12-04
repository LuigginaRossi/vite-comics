<script>
export default {
    data() {
        return {
            // shopDc : {
            //     img: "",
            //     text:"",
            //     contructor(_img, _text){
            //         this.img = _img;
            //         this.text = _text;
            //     }
            // },
            ShopObjs: [
                {
                img: "../src/assets/buy-comics-digital-comics.png",
                text:"DIGITAL COMICS",
                },
                {
                img: "../src/assets/buy-comics-merchandise.png",
                text:"DC MERCHANDISE",
                },
                {
                img: "../src/assets/buy-comics-subscriptions.png",
                text:"SUBSCRIPTION",
                },
                {
                img: "../src/assets/buy-comics-shop-locator.png",
                text:"COMIX SHOP LOCATOR",
                },
                {
                img: "../src/assets/buy-dc-power-visa.svg",
                text:"COMIC SHOP LOCATOR",
                },
            ],
        }
    },
}
</script>

<template>
    <div class="bg-primary text-light">
       <div class="container py-5 d-flex justify-content-between">
            <div class="shop-item d-flex align-items-center gap-3"
            v-for="element, i in ShopObjs">
                <div class="img-container">
                    <img :src="element.img" alt="">
                </div>
                <small>
                    <a href="#">{{element.text}}</a>
                </small>
            </div>
       </div>
    </div>
</template>

<style lang="scss">
    .shop-item .img-container img{ 
        width: 4vw; 
        aspect-ratio: 1/1;
        object-fit: contain;
    }

small    a {
        color: white;
        text-decoration: none;
        padding: 1.5rem 0;  
        &:hover{
            color: black;
        }
    }
</style>
