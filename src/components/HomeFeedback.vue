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
</style>