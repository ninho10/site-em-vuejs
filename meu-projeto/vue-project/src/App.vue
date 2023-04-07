<template>
  <div>
  <primeiro-componente/>
  <p>O dade de ep e {{ testando }}</p>
  <life-cycle/>
 </div>
</template>

<script>
import primeiroComponente from './components/primeiroComponente.vue';
import lifeCycle from './components/lifeCycle.vue'; 

export default{
  name: 'App',
  components: {
    primeiroComponente,
    lifeCycle
  },
  data(){
    return {
      testando: 'Teste'
    }
  }
}


</script>