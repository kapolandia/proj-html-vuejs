<script>
    export default{
        name: "AppFooter",
        props: {
            footer: {
                type: Object,
            }
        }
    }
</script>

<template>
    <div class="my-wrapper py-5 ">
        <div class="container text-center pt-5 " style="margin-top: 150px;">
            <div class="row justify-content-start text-left">
                <div class="col-4 text-start">
                    <img src="../assets/img/logo.png" alt="">
                    <h5 class="subtitle">Lorem ipsum dolor sit amet, elit. varius enim in eros elementum Duis mi quis viverra ornare</h5>
                    <div class="d-flex align-items-center mt-5">
                        <a href="#" class="my-social-btn"><i class="fab fa-youtube"></i></a>
                        <a href="#" class="my-social-btn ms-3"><i class="fab fa-twitch"></i></a>
                        <a href="#" class="my-social-btn ms-3"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="my-social-btn ms-3"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="col-2 text-start">
                    <h5>Quick Links</h5>
                    <ul>
                        <li v-for="(link, index) in footer.quicklinks" :key="index">
                            <a href="#">{{ link }}</a>
                        </li>
                    </ul>
                </div>
                <div class="col-2 text-start">
                    <h5>Help</h5>
                    <ul>
                        <li v-for="(link, index) in footer.help" :key="index">
                            <a href="#">{{ link }}</a>
                        </li>
                    </ul>
                </div>
                <div class="col-2 text-start">
                    <h5>Follow Us</h5>
                    <ul>
                        <li v-for="(link, index) in footer.followUs" :key="index">
                            <a href="#">{{ link }}</a>
                        </li>
                    </ul>
                </div>
                <div class="col-2 text-start">
                    <h5>Contact</h5>
                    <ul>
                        <li>
                            <a href=""><span class="span-contact">Location: <br></span>{{ footer.contactUs[0] }}</a>
                        </li>
                        <li>
                            <a href=""><span class="span-contact">Phone: <br></span>{{ footer.contactUs[1] }}</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <!-- Second footer -->
    <div class="my-wrapper-2 p-4">
        <h5 class="subtitle m-0">Copyright © 2024 <span class="secondary-color">FUTIO</span> &nbsp | &nbsp All rights reserved.</h5>
    </div>
</template>

<style lang="scss" scoped>
    @use '..//style/variables/_variables.scss' as variable;

    .my-wrapper{
        background-color: #283449;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .my-wrapper-2{
        background-color: #1B222E;
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
        color: variable.$brand-white;
        font-size: 24px;
        font-weight: 700;
    }

    ul{
        list-style: none;
        padding: 0;
    }

    li{
        line-height: 30px;
        margin-top: 8px;
    }

    a{
        color: #cccccc;
        font-family: "Barlow", sans-serif;
        font-size: 18px;
        transition: 0.3s;
        text-decoration: none;

        &:hover{
            color: variable.$secondary-color;
        }
    }

    .span-contact{
        color: variable.$secondary-color;
        font-family: "Barlow", sans-serif;
        font-size: 18px;
    }

    .subtitle{
        color: variable.$brand-white;
        font-family: "Barlow", sans-serif;
        font-size: 18px;
        font-weight: 400;
        margin-top: 30px;
    }

    .my-social-btn{
        width: 40px;
        height: 40px;
        border-radius: 20px;
        background-color: transparent;
        border: 1px solid rgba(127, 108, 152, 0.5);
        display: flex;
        align-items: center;
        justify-content: center;

        &:hover{
            background-color: variable.$secondary-color;
            color: variable.$brand-white;
        }
    }
</style>