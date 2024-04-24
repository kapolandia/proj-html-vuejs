<script>
    export default{
        name: "HomeDiscount",
    }
</script>

<template>
    <div class="my-wrapper py-5 " >
        <div class="container-fluid text-center">
            <div style="position: relative;overflow: hidden;">
                <img src="../assets/img/banner-item-bg.png" alt="" srcset="" style="max-width: 100%;">
                <!-- Absolute content -->
                <div style="position: absolute;top: 55%; left: 50%; transform: translate(-50%, -50%);" class="w-100">
                    <h4>Make Offer</h4>
                    <h2 class="w-100">Get 70% Offer Discount</h2>
                    <button class="my-btn my-offer-btn mx-auto my-5" style="display: block;">Get Offers</button>
                </div>
                <img src="../assets/img/banner-item-obj1.png" alt="" srcset="" style="position: absolute;left: 100px;bottom: -200px;width: 20%;">
                <img src="../assets/img/banner-item-obj2.png" alt="" srcset="" style="position: absolute;right: 100px;top: -100px;width: 20%;">
                
                <!-- Absolute content -->
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
        font-size: 57px;
        color: variable.$brand-white;
        font-weight: 700;
    }

    h4{
        color: variable.$brand-white;
        font-size: 24px;
        font-weight: 700;
    }

    .my-offer-btn{
      background-color: #1a8f3d;
      color: variable.$brand-white;
      border-radius: 30px;
      font-weight: 600;
      font-size: variable.$font-size-medium;
      font-family: "Barlow", sans-serif;
      font-weight: 400;
      padding: 15px 70px;
    }
</style>