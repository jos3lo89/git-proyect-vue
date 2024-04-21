<script setup lang="ts">
import { ref } from "vue";

const numero = ref(0);
</script>

<template>
  <h1>hola mundo wadafa</h1>
  <h2>hola soy el contribuidor</h2>

  <button @click="numero++">{{ numero }}</button>
</template>
