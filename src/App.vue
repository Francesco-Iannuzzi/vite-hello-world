<script>
  export default {
    data(){
      return {
        message: 'Hello Vue',
        greetingsList: ['Ciao Vue', 'Bonjour Vue','Hola Vue', 'Hallo Vue', 'Olà Vue']
      }
    }
  }
</script>

<template>
  <h1>{{ message }}</h1>
  <ul>
    <li v-for="greeting in greetingsList">{{ greeting }}</li>
  </ul>
</template>

<style></style>