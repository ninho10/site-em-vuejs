<template>
    <div>
        <h1>Meu nome e : {{ nome }}</h1>

    </div>
</template>


<script>
    export default {
        name: 'lifeCycle',
        data() {
            return {
                nome: 'Ainda nao sei'
            }
        },
        created() {
            setTimeout(() => {
                this.nome = 'Paulo Roberto' 
            },2000);
           
        },
        mounted() {
            setTimeout(() => {
                this.nome = 'Ninho' 
            },4000);
        }
    }

</script>