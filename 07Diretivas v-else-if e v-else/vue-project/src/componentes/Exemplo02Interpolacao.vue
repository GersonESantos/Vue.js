<script setup>
// Variáveis
let exibir = true;
let media = 7;

</script>

<!-- html -->

<template>
    <h1 v-if="exibir">Este é um texto que será exibido</h1>
    <p v-if="media >=7">Aprovado</p>
    <p v-else-if="media >= 5">Em Exame</p>
    <p v-else="">Reprovado</p>
    
</template>