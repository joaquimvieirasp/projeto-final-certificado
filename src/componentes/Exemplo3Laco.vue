<!-- SCRIPT -->
<script setup>
    // Vetor
    let nomes = ['Alice', 'Bruna', 'Caio', 'Danile', 'Ellen'];
</script>

<!-- HTML -->
<template>
    <ul>
        <li v-for="(nome, index) in nomes" :key="index">{{ nome }}</li>
    </ul>
</template>
