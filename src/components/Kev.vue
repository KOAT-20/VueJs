<template>
  <div>
    <h2>Datos {{title}}</h2>
    <h3>Your name is {{user.name}} {{user.last}}!</h3>
    <div v-html='custom' />
    <hr />
    <input type='text' v-model='user.name'>
    <button type='button'v-on:click='saludo(user.name)'  >Saludar</button>
  </div>
</template>

<script>
export default {
  // name: "",
  data: () => ({
    title: 'de Prueba',
    user: {
      name: 'Kevin',
      last: 'Torres'
    },
    custom: '<h4>Custom</h4>'
  }),
  methods: {
    saludo (name) {
      alert(`Hola ${name}`);
    }
  }
}
</script>

<style scoped>
h2 {
  color: grey;
}

div. h4 {
  color: blue;
}
</style>
