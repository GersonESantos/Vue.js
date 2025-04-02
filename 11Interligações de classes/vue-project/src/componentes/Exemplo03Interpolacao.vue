<script setup>
// Vetor
let exibir = true;
let nomes = ['Joao','Maria','Jose','Pedro','Ana'];

</script>

<!-- html -->

<template>
    <ul>
        <li v-for="nome in nomes">{{nome}}</li>
    </ul>
    
</template>