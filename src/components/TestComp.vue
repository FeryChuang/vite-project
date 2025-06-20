<template>
  <p>This is a Test Component.</p>
  <br />
  <h1>{{ text }}</h1>
</template>

<script setup>
import { ref } from 'vue'
const text = ref('Meow')
</script>
