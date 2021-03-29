<template>
<div id='cliente'>
    <h2 id='cliente-nome'>{{nome}}</h2>
    <h2>{{idade}} anos </h2>
    <h3>
        Descrição do cliente
    </h3>
    {{
        2+2*2
    }}
</div>
    
</template>

<script>
export default {
    data(){
        return{
            nome:'Victor',
            numero:'',
            email:'',
            idade:21
        }
    }
}   
</script>

<style scoped>
    #cliente{
        color:blue;
        max-width: 600px;

    }
    #cliente-nome{
        color:blue;
    }
</style>
