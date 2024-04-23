<script>
    export default{
        name: "HomeFeedback",
    }
</script>

<template>
    <div class="my-wrapper py-5 " >
        <div class="container py-5 text-center" style="z-index: 1;">
            <h3 class="secondary-color">Futio Feedback</h3>
            <h2>What Our Gamers Say</h2>
            <h5 class="secondary-font py-3">Libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. <br> Cras ultricies ligula sed magna dictum porta.</h5>
            <div class="row d-flex">
                <div class="col my-card me-3 text-start">
                    <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    <p class="mt-3">“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.”</p>
                    <div class="d-flex align-items-center">
                        <img src="../assets/img/testimonials-image-1.png" alt="">
                        <div class="ms-4">
                            <h6 class="testimonial-name">Merle Fisher </h6>
                            <h6 class="testimonial-nation">United States</h6>
                        </div>
                    </div>
                </div>
                <div class="col my-card me-3 text-start">
                    <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    <p class="mt-3">“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.”</p>
                    <div class="d-flex align-items-center">
                        <img src="../assets/img/testimonials-image-3.png" alt="">
                        <div class="ms-4">
                            <h6 class="testimonial-name">Kim Ramos </h6>
                            <h6 class="testimonial-nation">Serbia</h6>
                        </div>
                    </div>
                </div>
                <div class="col my-card text-start">
                    <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    <p class="mt-3">“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.”</p>
                    <div class="d-flex align-items-center">
                        <img src="../assets/img/testimonials-image-2.png" alt="">
                        <div class="ms-4">
                            <h6 class="testimonial-name">Garry Francis</h6>
                            <h6 class="testimonial-nation">Kiribati</h6>
                        </div>
                    </div>
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

    .my-card{
        background-color: variable.$brand-blue;
        border-radius: 30px;
        padding: 34px 40px;
        i{
            color: #ffba00;
        }
    }

    p{
        font-size: 24px;
        font-family: "Barlow", sans-serif;
        font-weight: 400;
        color: variable.$brand-white;
    }

    .testimonial-name{
        font-weight: 700;
        font-size: 18px;
        color: variable.$brand-white;
    }

    .testimonial-nation{
        font-size: 18px;
        font-family: "Barlow", sans-serif;
        font-weight: 400;
        color: variable.$secondary-color;
    }

    img{
        width: 40px;
        height: 40px;
    }
</style>