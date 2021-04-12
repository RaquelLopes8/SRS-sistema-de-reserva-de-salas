<template>
    <div class="conteiner">
        <nav>
            <div class="nav-corpo">
                <h1 class="sigla">SRS</h1>
                <h3 class="titulo">Sistema de Reserva de Sala</h3>
            </div>

        </nav>

        <div class="card-login">
            <div class="card">
                <div class="card-content">
                    <div class="content">
                        <h4>Login</h4>

                        <div class="field">
                            <label class="label" id="cpf">CPF:</label>
                            <div class="control">
                                <input class="input is-rounded" type="text" placeholder="Digite seu CPF...">
                            </div>
                        </div>

                        <div class="field">
                            <p class="control has-icons-left">
                                <label class="label" for="senha" id="lab-senha">Senha</label>
                                <input class="input is-rounded" id="senha" type="password" placeholder="senha">
                            </p>
                        </div>

                        <div class="field">
                            <label class="label" id="tipo-conta">Tipo de conta</label>
                            <div class="control">
                                <div class="select is-rounded">
                                <select>
                                    <option>escolha uma opção</option>
                                    <option>Aluno</option>
                                    <option>Professor</option>
                                    <option>Secretário</option>
                                </select>
                                </div>
                            </div>
                        </div>

                        <div class="field is-grouped">
                            <div class="control">
                                <button class="button" href="./BuscarSalas">Entrar</button>
                            </div>
                        </div>
                        <p class="is-info">Acesse com as credenciais da Base Centralizada</p>
                    </div>
                </div>
            </div>
            

            

            
        </div>
    </div>
</template>

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

    .card-login .card{
        margin-top: 30px;
        width: 500px;
        border-radius: 15px;
        left: 400px;
        box-shadow: #489FB5 1px 1px 2px 1px;
    }

    .field .label{
        margin-left: -380px;
    }
    .field #cpf{
        margin-left: -385px;
    }
    .field #tipo-conta{
        margin-left: -330px;
    }
    .select select{
        width: 450px;
    }


    .control button{
        margin-left: 100px;
        width: 250px;
        background-color: #489FB5;
        color: white;
        border-radius: 20px;
    }
    .control button:hover{
        background-color: #16697A;
    }

    .is-info{
        color:#16697A;
    }

</style>