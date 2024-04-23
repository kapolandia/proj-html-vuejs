<script>
    export default{
        name: "HomeGame",
    }
</script>

<template>
    <div class="my-wrapper py-5">
        <div class="container text-center py-5">
            <h3 class="secondary-color">Trending Battle</h3>
            <h2>Keep Eyes & Manage <br> Upcoming Battle</h2>
            <h5 class="secondary-font py-3">Libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. <br> Cras ultricies ligula sed magna dictum porta.</h5>
        
                    <!-- Cards Column -->
            <div class="row d-flex my-4 justify-content-between">
                <!-- First column -->
                <div class="col my-card me-5">
                    <div class="d-flex justify-content-between p-4 align-items-center">
                        <img src="../assets/img/game-img-1.png" alt="" srcset="">
                        <img src="../assets/img/verus-icon.png" alt="" srcset="" style="max-width: 100px;max-height: 100px;">
                        <img src="../assets/img/game-img-2.png" alt="" srcset="">
                    </div>
                    <div class="title-wrapper mt-3">
                        <h5 class="card-title">Call Of Duty</h5>
                        <h6 class="card-subtitle mt-3">December 25, 2022 4:00 PM</h6>
                    </div>
                    <div class="d-flex align-items-center justify-content-center p-5">
                        <div class="d-flex align-items-center">
                            <img src="../assets/img/icon/youtube-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Youtube</h6>
                        </div>
                        <div class="d-flex align-items-center ms-4">
                            <img src="../assets/img/icon/twitch-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Twitch</h6>
                        </div>
                    </div>
                </div>
                <!-- Second column -->
                <div class="col my-card">
                    <div class="d-flex justify-content-between p-4 align-items-center">
                        <img src="../assets/img/game-img-3.png" alt="" srcset="">
                        <img src="../assets/img/verus-icon.png" alt="" srcset="" style="max-width: 100px;max-height: 100px;">
                        <img src="../assets/img/game-img-4.png" alt="" srcset="">
                    </div>
                    <div class="title-wrapper mt-3">
                        <h5 class="card-title">Legendary Battles</h5>
                        <h6 class="card-subtitle mt-3">December 25, 2022 4:00 PM</h6>
                    </div>
                    <div class="d-flex align-items-center justify-content-center p-5">
                        <div class="d-flex align-items-center">
                            <img src="../assets/img/icon/youtube-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Youtube</h6>
                        </div>
                        <div class="d-flex align-items-center ms-4">
                            <img src="../assets/img/icon/twitch-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Twitch</h6>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Second row -->
            <div class="row d-flex my-4 justify-content-between">
                <!-- Third column -->
                <div class="col my-card me-5">
                    <div class="d-flex justify-content-between p-4 align-items-center">
                        <img src="../assets/img/game-img-5.png" alt="" srcset="">
                        <img src="../assets/img/verus-icon.png" alt="" srcset="" style="max-width: 100px;max-height: 100px;">
                        <img src="../assets/img/game-img-6.png" alt="" srcset="">
                    </div>
                    <div class="title-wrapper mt-3">
                        <h5 class="card-title">Nay Corral Gundown</h5>
                        <h6 class="card-subtitle mt-3">December 25, 2022 4:00 PM</h6>
                    </div>
                    <div class="d-flex align-items-center justify-content-center p-5">
                        <div class="d-flex align-items-center">
                            <img src="../assets/img/icon/youtube-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Youtube</h6>
                        </div>
                        <div class="d-flex align-items-center ms-4">
                            <img src="../assets/img/icon/twitch-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Twitch</h6>
                        </div>
                    </div>
                </div>

                <!-- Fourth column -->
                <div class="col my-card">
                    <div class="d-flex justify-content-between p-4 align-items-center">
                        <img src="../assets/img/game-img-7.png" alt="" srcset="">
                        <img src="../assets/img/verus-icon.png" alt="" srcset="" style="max-width: 100px;max-height: 100px;">
                        <img src="../assets/img/game-img-8.png" alt="" srcset="">
                    </div>
                    <div class="title-wrapper mt-3">
                        <h5 class="card-title">League Of Legends</h5>
                        <h6 class="card-subtitle mt-3">December 25, 2022 4:00 PM</h6>
                    </div>
                    <div class="d-flex align-items-center justify-content-center p-5">
                        <div class="d-flex align-items-center">
                            <img src="../assets/img/icon/youtube-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Youtube</h6>
                        </div>
                        <div class="d-flex align-items-center ms-4">
                            <img src="../assets/img/icon/twitch-icon.png" alt="" srcset="">
                            <h6 class="card-social-font">Twitch</h6>
                        </div>
                    </div>
                </div>
            </div>
            <button class="my-btn my-btn-primary mx-auto my-5" style="display: block;">VIEW ALL MATCH <i class="fa-solid fa-angles-right"></i></button>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '..//style/variables/_variables.scss' as variable;

    .my-wrapper{
        background-color: #222832;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    h2{
        font-size: 55px;
        color: white;
        font-weight: 700;
    }

    h5{
        color: #ebebebcf;
        font-family: "Barlow", sans-serif;
        font-size: 18px;
        font-weight: 400;
    }

    .my-card{
        border: 1px solid #556f9c;
        border-radius: 20px;
        background-color: #283449;
        padding: 0;
        overflow: hidden;
    }

    .title-wrapper{
        background-color: variable.$brand-blue;
        padding: 30px;
    }

    .card-title{
        font-family: "Orbitron", sans-serif;
        font-size: 24px;
        font-weight: 700;
        color: variable.$brand-white;
    }

    .card-subtitle{
        font-family: "Barlow", sans-serif;
        color: variable.$secondary-color;
        font-size: 18px;
        font-weight: 400;
    }

    .card-social-font{
        font-family: "Barlow", sans-serif;
        color: variable.$brand-white;
        font-size: 18px;
        font-weight: 400;
        margin: 0;
        margin-left: 5px;
    }
</style>