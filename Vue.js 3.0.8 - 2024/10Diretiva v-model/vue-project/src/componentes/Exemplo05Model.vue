<script setup>

import { ref } from 'vue';

let texto = ref('Texto inicial');

</script>

<template>
    <input type="text" v-model="texto" />
    <p>{{ texto }}</p>
</template>