<template>

    <h1>Vue 3 com Vite</h1>
    <p>Este é o nosso primeiro projeto real com estrutura de pastas.</p>
    <!-- Enviar uma prop (propriedade) chamada "usuario" para o componente Mensagem -->
    <Mensagem usuario="Velasco"/>

</template>

<script setup> 
// O uso do <script setup> faz com que ele fique automaticamente disponível no template

    // Importa o componente mensagem
    import Mensagem from './components/Mensagem.vue';

</script>