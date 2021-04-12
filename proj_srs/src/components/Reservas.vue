<template>
    <div class="table-container">

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

        <h3 class="titulo-salas">Solicitações Recentes</h3>
        <table class="table is-narrow">
            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>ALUNO: Rute Cristina da Silva Pereira</th>
                <th>05/03</th>
                <th>Tarde CD</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>ALUNO: Rute Cristina da Silva Pereira</th>
                <th>05/03</th>
                <th>Tarde CD</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>ALUNO: Rute Cristina da Silva Pereira</th>
                <th>05/03</th>
                <th>Tarde CD</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>
            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

            <tr>
                <th>PROFESSOR: Francisco Lopes Albuquerque</th>
                <th>02/03</th>
                <th>Manhã AB</th>
                <th><img src="../../public/eye (1).png" alt=""></th>
            </tr>

        </table>
    </div>
</template>

<script>
export default {
    setup() {
        
    },
}
</script>

<style>
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

    .titulo-salas{
        margin-top: -400px;
        margin-bottom: -20px;
        color: #16697A;
    }

    table{
        margin: 40px;
        width: 100px;
        margin-left: -5px;
        font-size: 15px;
    }
    table tr th{
        padding: 20px;
        font-weight: lighter;
    }

</style>