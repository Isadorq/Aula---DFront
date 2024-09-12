<template>
  <div>
    <!-- <ExercicioDois /> -->
    <ExercicioTres />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import ExercicioDois from './components/ExercicioDois.vue'
import ExercicioTres from './components/ExercicioTres.vue'
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // ExercicioDois, 
    ExercicioTres  
    // HelloWorld // Adicione se for usar
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
