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

        <h3 class="titulo-salas">Buscar salas</h3>

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

        <div class="busca">

            <div class="field">
                <label class="label" id="tipo-conta">Hora inicial</label>
                <div class="control">
                    <div class="select is-rounded">
                    <select>
                        <option>escolha uma opção</option>
                        <option>Manhã AB</option>
                        <option>Manhã CD</option>
                        <option>Tarde AB</option>
                        <option>Tarde CD</option>
                        <option>Noite AB</option>
                        <option>Noite CD</option>
                    </select>
                    </div>
                </div>
            </div>

            <div class="field">
                <label class="label" id="tipo-conta">Hora final</label>
                <div class="control">
                    <div class="select is-rounded">
                    <select>
                        <option>escolha uma opção</option>
                        <option>Manhã AB</option>
                        <option>Manhã CD</option>
                        <option>Tarde AB</option>
                        <option>Tarde CD</option>
                        <option>Noite AB</option>
                        <option>Noite CD</option>
                    </select>
                    </div>
                </div>
            </div>

            <b-calendar class="calendar"
                selected-variant="success"
                today-variant="info"
                nav-button-variant="primary"
            ></b-calendar>
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
                </div>
            </div>
        </div>

        <div class="card" id="card-sala2">
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
                </div>
            </div>
        </div>

        <div class="card" id="card-sala3">
            <div class="card-content">
                <div class="content">
                    <div id="titulo-card"><h2 class="titulo-card">Sala 2 - Bloco 1</h2></div>

                    <div class="card-info">
                        <ul>
                            <li>Tamanho grande</li>
                            <li>Limite de pessoas: 45</li>
                            <li>Projetor: 1</li>
                            <li>Ar-condicionado: 2</li>
                        </ul>
                    </div>
                </div>
            </div>
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

    .titulo-salas{
        margin-top: 40px;
        margin-bottom: -20px;
        color: #16697A;
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

    .busca{
        margin-top: -400px;
        margin-right: -80px;
        margin-bottom: 50px;
    }
    .busca .field{
        display: inline-block;
        margin: 20px;
        
    }
    .busca .calendar{
        border-radius:20px;
        margin-left: 10px;
        margin-top: 10px;
    }

    #card-sala1, #card-sala2, #card-sala3{
        width: 700px;
        height: 300px;
        border: 1px solid #16697A;
        margin: 20px;
        margin-left: 350px;
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
</style>