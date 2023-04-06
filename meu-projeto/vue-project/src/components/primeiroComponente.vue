<template>
  <div>
  <h1>Olá, Vue</h1>
  <p>MEU NOME É {{ nome }}</p>
</div>
</template>

<script>
  export default {
    name: 'primeiroComponents',
    data(){
      return {
        nome: "Paulo"
      }
    }
  }


</script>
