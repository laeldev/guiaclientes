<template>
  
  <div id="app">
    <h1>Guia Clientes</h1>

    <Cliente/>

    <hr>
    <h4> Lista de Produto</h4>
    <hr>
    <Produto/>
  </div>
</template>

<script>
import Cliente from './components/Cliente';
import Produto from './components/Produto';


export default {
  name: 'App',
  components:{
    Cliente,
    Produto
  }
}
</script>

<style>

</style>
