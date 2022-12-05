<script>
    export default {
        data() {
            return {
                navList: ["Characters", "Comics", "Movies", "TV", "Games", "Collectibles", "Videos", "Fans", "News", "Shop"],
            }
        },
    }
</script>
<template>
    <div class="container d-flex justify-content-between align-items-center ">
        <div class="container-logo">
            <img src="../assets/dc-logo.png" alt="logo DC" class="w-50">
        </div>
        <div><i class="fa-solid fa-bars d-lg-none "></i></div>
        <div class="menu d-none d-lg-block">
            <ul>
                <li v-for="element, i in navList" :key="(element + i)" :class="{'active' : i === 1}">
                    <a href="#">{{element}}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss">
.menu ul{
    margin-bottom: 0;
    a{
        padding: 3.05rem 1rem;
        &:hover{
            margin-bottom: -4px;
            border-bottom: 4px solid #0d6efd;
        }
    }
    .active {
        border-bottom: 4px solid #0d6efd;
        a{
            color: #0d6efd;
         }
    }
}
</style>
