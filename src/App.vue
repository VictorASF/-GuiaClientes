<template>
  <div id="app">
    <h1>Guia Clientes</h1>
    <Cliente :client='clients[0]' />
    <Cliente :client='clients[1]' />
  </div>
</template>

<script>
import Cliente from "./components/Cliente"

export default {
  name: 'App',
  data(){
    return{
      clients:[
        {
          nome: "Victor Fonseca",
          email: "teste@victor.com",
          idade: 21
        },
        {
          nome: "Anne Badu",
          email: "teste@anne.com",
          idade: 22
        }
      ]
    }
  },
  components:{
    Cliente
  }
}
</script>

<style>
</style>
