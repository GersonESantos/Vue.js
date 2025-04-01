<script setup>
// Variáveis
let exibir = true;

</script>

<!-- html -->

<template>
    <h1 v-if="exibir">Este é um texto que será exibido</h1>
    <!-- <h1 v-else>Este é um texto que será escondido</h1>
    <button @click="exibir = !exibir">Alternar</button> -->
</template>