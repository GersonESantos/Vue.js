<script setup>
// Variáveis
const nome = 'Fulano';
const idade = 30;
let numero1 = 10;
let numero2 = 5;
</script>

<!-- html -->

<template>
  <h1>{{ 'Olá ' + nome + ' voce tem ' + idade + ' anos. '}}</h1>
  <p>{{ idade }}</p>
  <p>{{ numero1 + numero2 }}</p>
  <p>{{ numero1 - numero2 }}</p>
  <p>{{ numero1 * numero2 }}</p>
  <p>{{ numero1 / numero2 }}</p>
</template>