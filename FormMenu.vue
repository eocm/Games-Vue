<template>
    <div class="container-fluid fondo-color">
        <div class="cont-form">
            <div class="hombre-form">
                <img v-bind:src="require('../assets/messi.jpg')" alt="hombre" class="hombre">
            </div>
            <div class="frase-form">
                <p class="gris">Tienda THE GOAT<span class="salto peq"></span> VideoGames</p>
                <p class="azul">Reconocidos a Nivel<span class="salto peq"> Internacional</span></p>
            </div>
            <div class="cuerpo-form">
                <div class="cuerpo">
                    <div class="frase-cuerpo text-center">
                        <p>Registrarse Ahora<span class="salto"></span></p>
                    </div>
                    <div class="form">
                        <div class="input-nombre mb-3 d-flex justify-content-center">
                            <input type="text" class="nombre-completo" placeholder="Correo Electronico">
                        </div>
                        <div class="input-tel mb-3 d-flex justify-content-center">
                            <input type="tel" class="tel" placeholder="Password">
                        </div>
                        <div class="boton d-flex justify-content-center">
                            <input class="btn btn-warning" type="submit" value="Entrar a la plataforma">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
    @media (max-width: 576px){
        .fondo-color{
            padding-top: 10px;
            padding-left: 0;
            padding-right: 0;
        }
        .cont-form{
            display: grid;
            grid-template-columns: 50% 50%;
            gap: 10px;
        }
        .hombre{
            width: 60%;
            height: auto;
        }
        .hombre-form{
            display: flex;
            justify-content:end
        }
        .gris{
            color: white;
            font-size: 40px;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .azul{
            
            color: white;
            font-size: 40px;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .cuerpo-form{
            grid-row: 2/3;
            grid-column: 1/3;
            background-image: url("../assets/Fondo azul escritorio.png");
            background-position: center;
            background-repeat: no-repeat;
        }
        div.frase-cuerpo p{
            color: white;
            font-size: 15px;
            font-weight: 700;
            margin: 10px 0;
        }
        input.nombre-completo,
        input.tel{
            width: 65%;
            height: 30px;
        }
        input.btn-warning{
            color: blue;
            font-weight: 700;
        }
        .boton{
            padding-bottom: 10px;
        }
        .peq{
            display: block;
        }
    }
    @media (min-width: 992px){
        .fondo-color{
            background-color: black;
            padding-top: 60px;
        }
        .cont-form{
            display: grid;
            grid-template-columns: 33% 33% 33%;
        }
        img.hombre{
            width: 90%;
            height: auto;
        }
        .gris{
            color: white;
            font-size: 40px;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .azul{
            color: white;
            font-size: 40px;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .salto{
            display: block;
        }
        .cuerpo{
            width: 100%;
            height: 85%;
            background-image: url("../assets/Fondo azul escritorio.png");
            background-position: center;
            background-repeat: no-repeat;
        }
        div.frase-cuerpo p{
            color: white;
            font-size: 30px;
            font-weight: 700;
            padding: 50px 0;
        }
        .form{
            justify-content: center;
        }
        input.nombre-completo,
        input.tel{
            width: 85%;
            height: 50px;
        }
        input.btn-warning{
            color: blue;
            font-weight: 700;
            width: 45%;
        }
    }
</style>


