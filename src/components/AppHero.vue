<template>
    <div class="hero">
    </div>
    <div><h1>Sono un jumbotron fatto male</h1></div>
</template>

<script>
    export default {
        name: 'AppHero'
    }
</script>

<style lang="css" scoped>

    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    .hero{
        width: 50%;
        height: 200px;
        margin: 0 auto;
        background-position: center;
        background-image: url(../../public/favicon.ico);
        background-repeat: no-repeat;
        background-size: contain;
    }

    h1{
        text-align: center;
    }


</style>