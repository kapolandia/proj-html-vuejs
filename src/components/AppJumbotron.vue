<script>
    export default{
        name: "AppJumbotron",
    }
</script>

<template>
    <div class="container d-flex align-items-center justify-content-center">
        <div class="d-flex flex-column w-50 justify-content-center " style="margin-top: 200px;z-index: 1;">
            <h3 class="secondary-color">Game With Live Streaming</h3>
            <h1 >Future Of Esports</h1>
            <h5 class="secondary-font">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudanti</h5>
            <div class="py-5 d-flex">
                <button class="ms-2 my-btn my-btn-primary">EXPLORE GAMES <i class="fa-solid fa-angles-right"></i></button>
                <button class="mx-5 my-btn my-play-btn"><i class="fa-solid fa-play"></i></button>
            </div>
        </div>
        <div style="width: 70%;">
            <img src="../assets/img/index-banner-illus.png" alt="" srcset="" style="position: absolute;top: 0;right: 50px;z-index: 0">
            <img src="../assets/img/game-controler.png" alt="" style="position: absolute;left: 0;z-index: 0;top: 50%;">
        </div>
    </div>
</template>

<style lang="scss" scoped>
    h1{
        font-size: 80px;
    }

    h5{
        font-size: 24px;
        font-weight: 400;
        color: #ebebebcf;
    }
</style>