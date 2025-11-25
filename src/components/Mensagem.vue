<template>
    <p>Bem-vindo {{ usuario }}!</p>
</template>

<script setup>
    // Definir a prop chamadada "usuario"
    defineProps({
        usuario: String
    })
</script>