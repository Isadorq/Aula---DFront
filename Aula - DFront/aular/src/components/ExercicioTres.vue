<template> 

    <div class="toggle-text"> 
      <button @click="toggleTexto">{{ mostrarTexto ? 'Ocultar' : 'Mostrar' }} Texto</button>
      <p v-if="mostrarTexto">Escondidinho</p>
  
    </div> 
  
  </template> 
 
  <script> 

  export default { 
    name: 'ToggleTexto', 
    data() { 
      return { 
        mostrarTexto: false,
      }; 
    }, 
    methods: { 
      toggleTexto() { 
        this.mostrarTexto = !this.mostrarTexto;
      } 
    } 
  }; 
  
  </script>

  <style scoped>

  .toggle-text { 
    text-align: center; 
    margin-top: 20px; 
  } 
  
  button { 
    font-size: 16px; 
    padding: 10px 20px; 
    cursor: pointer; 
    background-color: lightgreen;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
  } 
  
  p { 
    font-size: 18px; 
    color: #333; 
    font-family: 'Times New Roman', Times, serif;
  } 
  
  </style> 