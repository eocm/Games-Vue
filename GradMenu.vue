<template>
    <div class="container-fluid mt-5">
        <div class="text-center pt-5">
            <h1 class="mb-5">Top 6 de VideoGames más Reconocidos</h1>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/minecrat.jpg')" alt="1" class="comentario">
            </div>
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/fifa2.jpg')" alt="2" class="comentario">
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/left4dead.jpg')" alt="3" class="comentario">
            </div>
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/duty.jpg')" alt="4" class="comentario">
            </div>
        </div>
        <div class="row pb-5">
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/lol.jpg')" alt="5" class="comentario">
            </div>
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/grand.jpg')" alt="6" class="comentario">
            </div>
        </div>
    </div>
</template>
<style scoped>
    .container-fluid{
        background-color: black;
    }
    h1{
        color: white;
    }
    img{
        width: 90%;
        height: auto;
    }
    @media (max-width: 576px){
        img.comentario{
            width: 50%;
            height: auto;
        }
    }
</style>