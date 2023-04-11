<template>
<div>
    <h2>Meu Formulario</h2>
    <form action="">
    <inputText/>
    <inputText/>
    <submit/>
    </form>
</div>
</template>

<script>

import inputText from'./form/inputText.vue'
import submit from './form/submit.vue'

    export default{
        name: 'Form',
        components:{
            inputText,
            submit
        }
    }


</script>