<script setup>

let texto = '';


</script>

<template>
  <div>
    <h1>Exemplo 05 - Model</h1>
    <input type="text" v-model="texto" />
    <p>{{ texto }}</p>
  </div>
</template>