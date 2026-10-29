<script setup>
import { ref } from 'vue'
const greeting = ref('Novo opažanje')
</script>

<template>
    <h1>Novo opažanje</h1>
    <p class="greeting">{{ greeting }}</p>
</template>

<style>
.greeting {
  color: red;
  font-weight: bold;
}
</style>