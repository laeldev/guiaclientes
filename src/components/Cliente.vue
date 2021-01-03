<template>
 
  <div id="cliente">
    <h2 id="cliente-nome">{{ nome }} </h2>

    <h3> Descrição Cliente: {{ descricao }} </h3>
  </div> 

</template>

<script>
export default {
  data() {
    return{
      nome: "Andre Lael",
      numero: " ",
      email:" ",
      idade: 0,
      descricao: "descriçao reativa"

    }
  }
    
}
</script>

<style scoped>
  #cliente{
    color: green;
    background-color: black;
    max-width: 600px;
  }
</style>