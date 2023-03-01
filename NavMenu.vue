<template>
    <div>
        <nav class="navbar bg-primary navbar-expand-md navbar-light">
            <div class="container-fluid">
                <img src="../assets/principal.jpg" alt="logo" class="logo">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse derecha" id="navbarSupportedContent">
                    <div class="alinear">
                        <div>
                            <button type="button" class="btn btn-info">Iniciar Sesion</button>
                        </div>
                    </div>
                </div>
            </div>
        </nav>
    </div>
</template>
<style scoped>
    @media (max-width: 576px){
        img.logo{
            width: 100px;
            height: 100px;
        }
        a.link{
            text-decoration: none;
        }
        a.link,
        button{
            color: white;
            font-weight: 500;
            font-size: 20px;
        }
    }
    @media (min-width: 992px){
        img.logo{
            width: 100px;
            height: 100px;
        }
        a.link,
        button{
            color: white;
            font-weight: 500;
            font-size: 20px;
            margin: 0 5px
        }
        a.link{
            text-decoration: none;
        }
        .alinear{
            display: flex;
            align-items: center;
        }
        .derecha{
            display: flex;
            justify-content: flex-end;
        }
    }
</style>