<!-- SCRIPT -->
<script setup>

// Importação do ref
import { ref } from "vue";

// Variável
let texto = ref('');

</script>

<!-- HTML -->
<template>
    <input type="text" v-model="texto">
    <p>{{ texto }}</p>
</template>