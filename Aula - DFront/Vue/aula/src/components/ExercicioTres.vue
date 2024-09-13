<template>
  <div class="toggle-text">
    <button @click="toggleTexto">{{ mostrarTexto ? 'Ocultar' : 'Mostrar' }} Texto</button>
    <p v-if="mostrarTexto">Este é o texto que pode ser mostrado ou ocultado.</p>
  </div>
</template>

<script>
export default {
  name: 'ToggleTexto',
  data() {
    return {
      mostrarTexto: false
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
}
p {
  font-size: 18px;
  color: #333;
}
</style>
