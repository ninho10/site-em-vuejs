<template>
  <div>
  <primeiro-componente/>
  <p>O dade de ep e {{ testando }}</p>
  <life-cycle/>
  <pessoa/>
 </div>
</template>

<script>
import primeiroComponente from './components/primeiroComponente.vue';
import lifeCycle from './components/lifeCycle.vue'; 
import Pessoa from './components/pessoa.vue';



export default{
  name: 'App',
  components: {
    primeiroComponente,
    lifeCycle,
    Pessoa,
   
  },
  data(){
    return {
      testando: 'Teste'
    }
  }
}


</script>