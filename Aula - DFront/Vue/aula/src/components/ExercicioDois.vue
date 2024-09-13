<template>
  <div class="contador">
    <p>Contador: {{ count }}</p>
    <button @click="incrementar">Incrementar</button>
  </div>
</template>

<script>
export default {
  name: 'ContadorComponente',
  data() {
    return {
      count: 0
    };
  },
  methods: {
    incrementar() {
      this.count++;
    }
  }
};
</script>

<style scoped>
.contador {
  text-align: center;
  font-family: monospace;
}
button {
  font-family: monospace;
  font-size: 18px;
  padding: 10px 20px;
  margin: 5px;
}
</style>