<template> 

  <div> 
    <!-- <ExercicioUm/> --> 
    <!-- <ExercicioDois /> --> 
    <!-- <ExercicioTres />  -->
    <!-- <ExercicioQuatro/>  -->
    <!-- <ExercicioCinco/> -->
    <ExercicioSeis/>
  </div> 

</template> 

 

<script> 

// import ExercicioUm from './components/ExercicioUm.vue'; 
// import ExercicioDois from './components/ExercicioDois.vue'; 
// import ExercicioTres from './components/ExercicioTres.vue' 
// import ExercicioQuatro from './components/ExercicioQuatro.vue'; 
// import ExercicioCinco from './components/ExercicioCinco.vue';
import ExercicioSeis from './components/ExercicioSeis.vue';

export default { 

  name: 'App', 

  components: { 

    // ExercicioUm, 
    // ExercicioDois,  
    // ExercicioTres 
    // ExercicioQuatro,   
    // ExercicioCinco,
    ExercicioSeis,

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