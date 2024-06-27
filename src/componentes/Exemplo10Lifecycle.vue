<!-- SCRIPT -->
<script setup>

// Importações
import { onMounted, ref } from "vue";

// Variável de texto
let texto = ref('Hello World');

// Life cycle onMounteg
onMounted(() => {
    setTimeout(() => {
        texto.value = 'Alterando texto!';
    }, 3000);
})
</script>


<!-- HTML -->
<template>
    <h1>{{ texto }}</h1>
</template>