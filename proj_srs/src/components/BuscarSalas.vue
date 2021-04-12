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

        <h3>Buscar salas</h3>

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

            <b-calendar
                selected-variant="success"
                today-variant="info"
                nav-button-variant="primary"
            ></b-calendar>
        </div>

        <div class="card">
            <div class="card-content">
                <div class="content">
                Lorem ipsum leo risus, porta ac consectetur ac, vestibulum at eros. Donec id elit non mi porta gravida at eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Cras mattis consectetur purus sit amet fermentum.
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-content">
                <div class="content">
                Lorem ipsum leo risus, porta ac consectetur ac, vestibulum at eros. Donec id elit non mi porta gravida at eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Cras mattis consectetur purus sit amet fermentum.
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-content">
                <div class="content">
                Lorem ipsum leo risus, porta ac consectetur ac, vestibulum at eros. Donec id elit non mi porta gravida at eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Cras mattis consectetur purus sit amet fermentum.
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
    button{
        background-color: #489FB5;
        border-radius: 20px;
        padding: 20px;
        color: white;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }

    .card{
        width: 500px;
        height: 300px;
        border: 1px solid #16697A;
    }

</style>