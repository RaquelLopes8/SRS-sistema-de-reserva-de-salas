<template>
    <div class="conteiner">
        <nav>
            <div class="nav-corpo">
                <h1 class="sigla">SRS</h1>
                <h3 class="titulo">Sistema de Reserva de Sala</h3>
                <div class="deslogar">
                    <button class="button is-rounded" href="">Sair</button>
                </div>
            </div>
        </nav>

        <div class="card" id="card">
            <div class="card-content">
                <div class="content">
                    <div class="but">
                        <button>
                            <span><img src="../../public/clipboard-text-outline.png" alt=""></span><br>
                            <span>Minhas reservas</span>
                        </button>
                    </div>

                    <div class="but">
                        <button>
                            <span><img src="../../public/clipboard-check-outline.png" alt=""></span><br>
                            <span>Confirmar presença</span>
                        </button>
                    </div>
                </div>
            </div>
        </div>

        <div class="card" id="card-sala1">
            <div class="card-content">
                <div class="content">
                    <div><h2 class="titulo-card">Sala 2 - Bloco 1</h2></div>

                    <div class="card-info">
                        <ul>
                            <li>Tamanho grande</li>
                            <li>Limite de pessoas: 45</li>
                            <li>Projetor: 1</li>
                            <li>Ar-condicionado: 2</li>
                        </ul>
                    </div>

                    <div class="field is-horizontal" id="text">
                        <div class="field-body">
                            <div class="field">
                            <div class="control">
                                <textarea class="textarea is-info small" placeholder="Justificativa" rows="1" cols="60"></textarea>
                            </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div>
            <button class="button" id="but-enviar">Enviar</button>
        </div>
    </div>
</template>

<script>
export default {
    setup() {
        
    },
}
</script>

<style>
    .nav-corpo{
        background-color: #16697A;
        color: white;
        border-radius: 0px 0px 15px 15px;
        margin-top: -60px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .nav-corpo h1{
        margin-left: -1000px;
        font-size: 55px;
    }
    .nav-corpo h3{
        margin-top: -60px;
        font-size: 30px;
        padding-bottom: 25px;
    }
    .deslogar{
        color: white;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        margin-left: 1100px;
        margin-top: -90px;
        padding: 20px;
    }

    #card{
        width: 300px;
        height: 400px;
        margin-top: 50px;
        border-radius: 15px;
        box-shadow: #489FB5 2px 2px;
        margin-left: -50px;

    }
    .but{
        margin: 20px;
        margin-left: 50px;
        margin-top: 50px;
    }
    .but button{
        background-color: #489FB5;
        padding: 15px;
        color: white;
        border: #489FB5 solid 1px;
        border-radius: 15px;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }

    #card-sala1{
        width: 700px;
        height: 300px;
        border: 1px solid #16697A;
        margin: 20px;
        margin-left: 400px;
        margin-top: -350px;
        border-radius: 20px;
        box-shadow: #16697A 1px 1px;
    }

    .card .card-content .content div{
        display: inline-block;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }

    div .titulo-card{
        margin-left: -120px;
        text-align: left;
        margin-top: -50px;

    }

    .card-info{
        margin-left: 40px;
        text-align: left;
        font-size: 20px;
    }
    .card-info ul li{
        list-style: none;
    }
    #text{
        display: block;
        margin-top: 15px;
    }
    .control textarea{
        border-radius: 20px;
    }
    
    #but-enviar{
        background-color: #489FB5;
        color: white;
        width: 200px;
        margin-left: 140px;
        border-radius: 20px;
    }
</style>