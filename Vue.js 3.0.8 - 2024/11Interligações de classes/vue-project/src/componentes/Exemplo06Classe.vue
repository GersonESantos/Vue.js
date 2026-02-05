<!-- scrip -->
<script setup>

let validacao = true;

</script>

<!-- CSS -->
<style>

.ok {
    color: green;
    font-weight: bold;
}
.falha {
    color: red;
    font-weight: bold;
}

</style>
<!-- HTML -->

<template>

<p :class="validacao ? 'ok' : 'falha'" >Utilizando Diretiva de Class  </p>

</template>