<script>
    export default{
        name: "HomeNews",
    }
</script>

<template>
    <div class="my-wrapper py-5">
        <div class="container text-center pt-5 pm-5">
            <h3 class="secondary-color">Latest News</h3>
            <h2>Stay Updated With Our <br> Latest News Articles</h2>
            <h5 class="secondary-font py-3">Libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. <br> Cras ultricies ligula sed magna dictum porta.</h5>
            
            <!-- Articles -->
            <div class="row d-flex my-5 justify-content-between">
                <div class="col my-card">
                    <img src="../assets/img/blog-item-1.png" alt="" srcset="">
                    <!-- Icons -->
                    <div class="p-4">
                        <div class="d-flex align-items-center my-3">
                            <img src="../assets/img/icon/clock.png" alt="" style="max-width: 20px;max-height: 20px;">
                            <p>10 Min</p>
                            <img src="../assets/img/icon/eye.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                            <p>240</p>
                            <img src="../assets/img/icon/calendar.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                            <p>Apr 11,2022</p>
                        </div>
                        <h4 >Secrets To An Amazing Role Playing Game</h4>
                    </div>
                </div>

             <!-- Second Column with rows  -->
                <div class="col">
                    <div class="d-flex my-card-2 align-items-center">
                        <!-- image wrapper -->
                        <div style="border-radius: 20px;overflow: hidden;max-width: 100%;width: 310px;">
                            <img src="../assets/img/blog-item-2.png" alt="" >
                        </div>
                        <!-- image wrapper -->
                        <div class="ps-3">
                        <div class="d-flex align-items-center my-3">
                            <img src="../assets/img/icon/clock.png" alt="" style="max-width: 20px;max-height: 20px;">
                            <p>10 Min</p>
                            <img src="../assets/img/icon/eye.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                            <p>240</p>
                            <img src="../assets/img/icon/calendar.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                            <p>Apr 11,2022</p>
                        </div>
                        <h4 class="mini-title">Top 5 Most Important Aspects Of Your Game</h4>
                    </div>
                    </div>
                    <div class="d-flex my-card-2" style="margin-top: 32px;margin-bottom: 32px;">
                        <!-- image wrapper -->
                        <div style="border-radius: 20px;overflow: hidden;max-width: 100%;width: 310px;">
                            <img src="../assets/img/blog-item-3.png" alt="" >
                        </div>
                        <!-- image wrapper -->
                        <div class="ps-3">
                            <div class="d-flex align-items-center my-3">
                                <img src="../assets/img/icon/clock.png" alt="" style="max-width: 20px;max-height: 20px;">
                                <p>10 Min</p>
                                <img src="../assets/img/icon/eye.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                                <p>240</p>
                                <img src="../assets/img/icon/calendar.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                                <p>Apr 11,2022</p>
                            </div>
                            <h4 class="mini-title">The Rise Of Fantasy Sports And Online Games</h4>
                        </div>
                    </div>
                    <div class="d-flex my-card-2 align-items-center">
                        <!-- image wrapper -->
                        <div style="border-radius: 20px;overflow: hidden;max-width: 100%;width: 310px;">
                            <img src="../assets/img/blog-item-4.png" alt="" >
                        </div>
                        <!-- image wrapper -->
                        <div class="ps-3">
                            <div class="d-flex align-items-center my-3">
                                <img src="../assets/img/icon/clock.png" alt="" style="max-width: 20px;max-height: 20px;">
                                <p>10 Min</p>
                                <img src="../assets/img/icon/eye.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                                <p>240</p>
                                <img src="../assets/img/icon/calendar.png" alt="" style="max-width: 20px;max-height: 20px;" class="ms-4">
                                <p>Apr 11,2022</p>
                            </div>
                            <h4 class="mini-title">Benefits Of Gaming - PC And Video Games</h4>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Articles -->

            <div class="my-card p-5 news-container d-flex align-items-center" style="background-color: #2F3F5F">
                <div class="w-50">
                    <h4 class="subscribe-title">Subscribe <br> Newsletter</h4>
                    <h5 class="secondary-font py-3 text-white text-start">Libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus.</h5>
                </div>
                <div class="w-50">
                    <div class="form-telegram">
                        <input type="text" class="my-input" placeholder="Enter your email">
                        <img src="../assets/img/icon/send-icon.png" alt="" class="telegram" style="width: 45px;height: 45px;">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '..//style/variables/_variables.scss' as variable;

    .my-wrapper{
        background-color: variable.$brand-black;
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

    h4{
        font-size: 32px;
        color: white;
        font-weight: 700;
        text-align: left;
    }

    .mini-title{
        font-size: 24px;
        color: white;
        font-weight: 700;
        text-align: left;
    }

    .my-card{
        border-radius: 20px;
        background-color: variable.$brand-blue;
        padding: 0px;
        overflow: hidden;

        img{
            width: 100%;
        }
    }

    .my-card-2{
        border-radius: 20px;
        background-color: variable.$brand-blue;
        padding: 0px;
    }

    p{
        color: variable.$secondary-color;
        font-family: "Barlow", sans-serif;
        font-size: 18px;
        font-weight: 400;
        margin:0;
        margin-left: 10px;
    }

    .subscribe-title{
        font-size: 43px;
        color: white;
        font-weight: 700;
    }

    .news-container{
        margin: 0 100px;
        position: relative;
        top: 150px;
    }

    .my-input{
        background: transparent;
        border: none;
        border-radius: 10px;
        padding: 12px;
        width: 80%;
        margin: 10px;
        outline-color: transparent;
        outline: none;
        font-family: "Barlow", sans-serif;
        font-size: 18px;
        color: variable.$brand-white;
    }

    .telegram{
        background-color: variable.$secondary-color;
        padding: 10px;
        border-radius: 100%;
        overflow: visible;
        cursor: pointer;
    }

    .form-telegram{
        background-color: #425374;
        outline: 1px solid #556f9c;
        border-radius: 15px;
        width: 80%;
        margin-left: 30px;
    }

    
</style>