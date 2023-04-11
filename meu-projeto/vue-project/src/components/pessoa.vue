<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }} </h2>
       <info/> 
       <Form/>
    </div>
    
</template>

<script>
import info from './info.vue'
import Form from './Form.vue'

export default{
  components: { 
    info,
    Form
},
    name: 'pessoa',
    data() {
        return{
            nome: 'Paulo Roberto'
        }
        
    },
}
</script>
