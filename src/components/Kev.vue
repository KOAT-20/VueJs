<template>
  <div>
    <h2>Datos {{title}}</h2>
    <h3>Your name is {{user.name}} {{user.last}}!</h3>
    <div v-html='custom' />
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
  })
}
</script>

<style scoped>
</style>
