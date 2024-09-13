<template>
    <div>
        <ul>
        <li v-for="(item, index) in itens" :key="index">{{item}}</li>
        </ul>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                itens: ['Maçã', 'Abacaxi', 'Banana', 'Morango']
            }
        }
        
    }
</script>

<style scooped>
    ul {
        list-style: none;
    }
</style>