<template>
  <div id="app">
    <Login/>
    <!--<BuscarSalas/>
    <ReservarSala/>
    <Reservas/>
    <Solicitacao/>-->
  </div>
</template>

<script>
import Login from './components/Login.vue';
//import BuscarSalas from './components/BuscarSalas.vue';
//import ReservarSala from './components/ReservarSala.vue';
//import Reservas from './components/Reservas.vue';
//import Solicitacao from './components/Solicitacao.vue';

export default {
  name: 'App',
  components: {
    Login,
    //BuscarSalas,
    //ReservarSala,
   // Reservas,
    //Solicitacao
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
