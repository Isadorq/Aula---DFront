<template>
    <div>
        <input type="text" v-model="nome" placeholder="Digite seu nome"/>        
        <p>Você digitou {{nome}}</p>
    </div>
</template>

<script>
export default {
    data(){
        return{
            nome: ''
        }
    }
}
</script>

<style scooped>
    
    input {
        background-color: blanchedalmond;
        font-family: sans-serif;
    }

    p {
        font-family: sans-serif;
    }
</style>