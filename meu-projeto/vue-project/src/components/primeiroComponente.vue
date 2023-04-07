<template>
  <div>
  <h1>Olá, Vue</h1>
  <p>Meu nome e {{ nome }} e trabalho como {{ profissao }}</p>
</div>
</template>

<script>
  export default {
    name: 'primeiroComponents',
    data(){
      return {
        nome: "Paulo",
        profissao:"Programador"
      }
    }
  }


</script>
