<template>
<div id='cliente'>
    <h4>Nome: {{client.nome}}</h4>
    <hr>
    <p>Email: {{ client.email }}</p>
    <p v-if="client.idade >= 18">Idade: {{ client.idade }}</p>
    <p v-else>Cliente menor de 18 anos</p>
</div>
    
</template>

<script>
export default {
    data(){
        return{
        }
    },
    props: {
        client: Object,
        showAge: Boolean
    }
}   
</script>

<style scoped>
    #cliente{
        background-color: #ECE5E3;
        color:blue;
        padding: 1%;
        margin-top: 2%;
    }
</style>
