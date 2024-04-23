<script>
    export default{
        name: "HomeStream",
    }
</script>

<template>
    <div class="my-wrapper py-5 " style="position: relative;">
        <img src="../assets/img/live-streaming-bg.png" alt="" srcset="" style="position: absolute;z-index: 0;top: 0;right: 0;width: 100vw;">
        <div class="container py-5 text-center" style="z-index: 1;">
            <h3 class="secondary-color">Live Streaming</h3>
            <h2>Watch The Streams</h2>
            <h5 class="secondary-font py-3">Libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. <br> Cras ultricies ligula sed magna dictum porta.</h5>
            <div class="mt-5" style="position: relative;">
                <img src="../assets/img/video-bg.png" alt="" srcset="" style="width: 80%;">
                <!-- Absolute content -->
                <div style="position: absolute; top: 48%; left: 50%; transform: translate(-50%, -50%);">
                    <button class="my-btn my-play-btn"><i class="fa-solid fa-play"></i></button>
                    <h5 class="mt-4 stream-title">League Of Legends</h5>
                </div>
                <div style="position: absolute;left: 15%;bottom: 5%;display: flex;">
                    <p><span class="secondary-color">356,599</span> Viewers</p>
                    <p class="ms-5"><span class="secondary-color">23,599 </span> Likes</p>
                </div>
                <div style="position: absolute;right: 15%;top: 0;">
                    <button class="my-btn my-streaming-btn mx-auto my-5" style="display: block;">
                        <img src="../assets/img/icon/live-icon.png" alt="" srcset="">    
                        Live
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '..//style/variables/_variables.scss' as variable;

    .my-wrapper{
        background-color: black;
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

    .stream-title{
        font-size: 24px;
        font-family: "Orbitron", sans-serif;
        font-weight: 700;
        color: variable.$brand-white;
    }

    p{
        font-size: 18px;
        font-weight: 400;
        font-family: "Barlow", sans-serif;
        color: variable.$brand-white;
    }

    .my-streaming-btn{
      background-color: variable.$brand-orange;
      border-radius: 30px;
      font-weight: 600;
      font-size: variable.$font-size-medium;
      font-family: "Barlow", sans-serif;
      font-weight: 400;
      padding: 5px 26px;
    }
</style>