<!-- SCRIPT -->
<script setup>
// Variável
let exibir = true;
let media = 8;

</script>

<!-- HTML -->
<template>
    <h1 v-if="exibir">Hello  World</h1>

    <p v-if="media >= 7">Aprovado</p>
    <p v-else-if="media >= 5">Em exame</p>
    <p v-else>Reprovado</p>
</template>