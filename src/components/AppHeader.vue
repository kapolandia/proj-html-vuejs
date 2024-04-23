<script>
    export default{
        name: "AppHeader",
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
                    <a href="#">Home</a>
                </nav>
            </div>
            <button class="ms-2 my-btn my-btn-primary"a>LIVE STREAMING</button>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    a{
        color: white;
        text-decoration: none;
        font-weight: 600;
    }
</style>