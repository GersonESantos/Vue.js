<script setup>
// Variáveis
const nome = 'Fulano';
const idade = 30;
</script>

<!-- html -->

<template>
  <h1>{{ 'Olá ' + nome + ' voce tem ' + idade + ' anos !?'}}</h1>
  <p>{{ idade }}</p>
</template>