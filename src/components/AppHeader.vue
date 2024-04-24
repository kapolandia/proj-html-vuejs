<script>
    export default{
        name: "AppHeader",
        props: {
            header: {
                type: Array,
            }
        }
    }
</script>

<template>
    <div class="container d-flex align-items-center py-4 justify-content-between" style="z-index: 100;">
        <div class="d-flex w-25">
            <img src="../assets/img/logo.png" alt="">
        </div>
        <div class="d-flex justify-content-between align-items-center w-75 ms-5" style="z-index: 100;">
            <div class="me-auto">
                <nav>
                    <ul class="d-flex">
                        <li v-for="(item, index) in header" :key="index">
                            <a :class="{ active: item.active}" class="nav-a-link" type="button" data-bs-toggle="dropdown" aria-expanded="false">{{ item.title }}</a>
                            <i v-if="item.hasSubMenu" class="fa-solid fa-chevron-down ms-1" type="button" data-bs-toggle="dropdown" aria-expanded="false"></i>
                            <div class="dropdown">
                                <ul class="dropdown-menu ">
                                    <li v-for="link in item.subMenu"><a class="dropdown-item" href="#">{{ link }}</a></li>
                                </ul>
                            </div>
                        </li>
                    </ul>
                </nav>
            </div>
            <div>
                <a href="" style="position: relative;" class="me-3">
                    <div class="cart-icon" style="position: absolute;right: -10px;">
                        <p>3</p>
                    </div>
                    <img src="../assets/img/icon/cart-icon.png" alt="" srcset="">
                </a>
                <button class="ms-2 my-btn my-btn-primary"a>LIVE STREAMING</button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '..//style/variables/_variables.scss' as variable;
    ul{
        list-style: none;
        padding: 0;
    }

    .cart-icon{
        background-color: variable.$primary-color;
        border-radius: 100%;
        height: 25px;
        width: 25px;
        margin: 0;
        display: flex;
        justify-content: center;
        color: variable.$brand-black;

    }

    .dropdown-menu{
        background-color: variable.$brand-blue;

        a{
            color: variable.$brand-white;   
            font-weight: 600;
            font-size: 18px;
        }

        a:hover{
            color: variable.$secondary-color;
            background-color: variable.$brand-blue;

            .fa-chevron-down{
                color: variable.$secondary-color;
            }
        }

    }

    li{
        line-height: 30px;
        margin-top: 8px;
    }
    
    .nav-a-link{
        color: white;
        text-decoration: none;
        font-weight: 600;
        margin-left: 20px;

        &:hover{
            color: variable.$secondary-color;
        }
    }

    .nav-a-link:hover + i {
        color: variable.$secondary-color;
    }

    .active{
        color: variable.$secondary-color;
    }
</style>