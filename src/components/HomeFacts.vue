<script>
    export default{
        name: "HomeFacts",
    }
</script>

<template>
    <div class="my-wrapper py-5">
        <div class="container py-5 text-center">
            <h2 >Futio Quick Facts</h2>
            <div class="row d-flex my-5">
                <div class="col my-card">
                    <h2>358</h2>
                    <h6 class="card-subtitle">Twitch Streams</h6>
                </div>
                <div class="col my-card">
                    <h2>14</h2>
                    <h6 class="card-subtitle">Total Games</h6>
                </div>
                <div class="col my-card">
                    <h2>309</h2>
                    <h6 class="card-subtitle">Youtube Streams</h6>
                </div>
                <div class="col my-card me-0">
                    <h2>12</h2>
                    <h6 class="card-subtitle">Pro Team</h6>
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

    .my-card{
        border: 1px solid rgba(85, 111, 156, 0.4);
        padding: 60px;
        border-radius: 60px;
        margin-right: 20px;
    }

    .card-subtitle{
        font-family: "Barlow", sans-serif;
        color: variable.$secondary-color;
        font-size: 18px;
        font-weight: 400;
    }
</style>