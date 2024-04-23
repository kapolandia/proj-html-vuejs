<script>
    export default{
        name: "HomeMakeMark",
    }
</script>

<template>
    <div class="my-wrapper py-5">
        <div class="container d-flex py-5">
            <div class="w-50">
                <img src="../../src/assets/img/features-illus.png" alt="" srcset="" style="position: relative;left: -300px;">
            </div>
            <div class="d-flex flex-column w-75 ms-5">
                <h4 class="secondary-color">The Ultimate Competitive Gaming Platfrom</h4>
                <h2>Make Your Mark On The Battle Field</h2>
                <h5>Libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Cras ultricies ligula sed magna dictum porta.</h5>
                <div class="d-flex py-4">
                    <div class="me-5">
                        <img src="../../src/assets/img/icon/features-icon-1.png" alt="" srcset="">
                    </div>
                    <div>
                        <h4 class="text-white">Live Streaming</h4>
                        <h5 class="text-white">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor.</h5>
                    </div>
                </div>
                <div class="d-flex">
                    <div class="me-5">
                        <img src="../../src/assets/img/icon/features-icon-2.png" alt="" srcset="">
                    </div>
                    <div>
                        <h4 class="text-white">Great Tournament</h4>
                        <h5 class="text-white">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor.</h5>
                    </div>
                </div>
                <div class="d-flex py-4">
                    <div class="me-5">
                        <img src="../../src/assets/img/icon/features-icon-3.png" alt="" srcset="">
                    </div>
                    <div>
                        <h4 class="text-white">Gaming News</h4>
                        <h5 class="text-white">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor.</h5>
                    </div>
                </div>
                <button class="ms-2 my-btn my-btn-primary my-5" style="display: block;">PLAY NOW <i class="fa-solid fa-angles-right"></i></button>
            </div>
        </div>
    </div>
</template>

<style scoped>
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
    }
</style>