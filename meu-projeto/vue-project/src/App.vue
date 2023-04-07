<template>
  <div>
  <primeiro-componente/>
  <p>O dade de ep e {{ testando }}</p>
 </div>
</template>

<script>
import primeiroComponente from './components/primeiroComponente.vue';

export default{
  name: 'App',
  components: {
    primeiroComponente
  },
  data(){
    return {
      testando: 'Teste'
    }
  }
}


</script>