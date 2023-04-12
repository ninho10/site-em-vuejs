<template>
    <div>
        <p v-if="esta_trabalhando">estou trabalhando no momento</p>
        <p v-else>"estou em busca de novas oportunidades "</p>
        <p>utilizando as seguintes tecnologias</p>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>

        <p v-show="mostrar_email">manda uma mensagem para : {{ email }}</p>
        <p>meu site entre aqui <a v-bind:href="meu_link" target="_blank">basta clicar aqi</a></p>
    </div>
    
</template>

<script>
export default{
    name: 'info',
    data(){
        return{
           esta_trabalhando: false,
           mostrar_email: false,
           email: 'paulo@gmail.com',
           meu_link: 'http://google.com'
        }
    }
  
}
</script>
