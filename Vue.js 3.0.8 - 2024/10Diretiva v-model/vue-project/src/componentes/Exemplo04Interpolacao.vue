<script setup>
// Variáveis
let texto = 'Texto sem tag ';
let texto1 = '<h1>Texto com tag h1!</h1>';
let texto2 = '<h2 style="color:red">Texto com tag h2</h2>';
let texto3 = '<h3>Texto com tag h3</h3>';
let texto4 = '<h4>Texto com tag h4</h4>';
let texto5 = '<h5>Texto com tag h5</h5>';
let texto6 = '<h6>Texto com tag h6</h6>';
let texto7 = '<p> Texto com tag p </p>';
let texto17 = '<p style="color:red"> Texto com tag p </p>';
let texto8 = '<span>Texto com tag span</span>';
let texto9 = '<strong>Texto com tag strong</strong>';
let texto10 = '<em>Texto com tag em</em>';
let texto11 = '<i>Texto com tag i</i>';
let texto12 = '<b>Texto com tag b</b>';
let texto13 = '<u>Texto com tag u</u>';
let texto14 = '<s>Texto com tag s</s>';
let texto15 = '<sub>Texto com tag sub</sub>';
let texto16 = '<sup>Texto com tag sup</sup>';
</script>

<!-- html -->


<template>
    <div>{{ texto }}</div>
    <div v-html="texto"></div>
    <div v-html="texto1"></div>
    <div v-html="texto2"></div>
    <div v-html="texto3"></div>
    <div v-html="texto4"></div>
    <div v-html="texto5"></div>
    <div v-html="texto6"></div>
    <div v-html="texto7"></div>
    <div v-html="texto8"></div>
    <div v-html="texto9"></div>
    <div v-html="texto10"></div>
    <div v-html="texto11"></div>
    <div v-html="texto12"></div>
    <div v-html="texto13"></div>
    <div v-html="texto14"></div>
    <div v-html="texto15"></div>
    <div v-html="texto16"></div>
    <div v-html="texto17"></div>
</template>