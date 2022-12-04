<script>
    export default {
    }
</script>
<template>
    <div class="container d-flex justify-content-between align-items-center ">
        <div class="container-logo">
            <img src="../assets/dc-logo.png" alt="logo DC" class="w-50">
        </div>
        <!-- <div> <font-awesome-icon icon="fa-solid fa-bars" /></div> -->
        <div class="menu d-none d-lg-block">
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">MOVIES</a>
                </li>
                <li>
                    <a href="#">TV</a>
                </li>
                <li>
                    <a href="#">GAMES</a>
                </li>
                <li>
                    <a href="#">COLLECRIBLES</a>
                </li>
                <li>
                    <a href="#">VIDEOS</a>
                </li>
                <li>
                    <a href="#">FANS</a>
                </li>
                <li>
                    <a href="#">NEWS</a>
                </li>
                <li>
                    <a href="#">SHOP</a>
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
}
</style>
