<script setup>
import {ref} from 'vue'
const name = ref('Racheal')
</script>

<template>
<main>
    <h1> Hello, {{ name }} !</h1>
    <p>I'm about to learn vue! </p>
  </main>
</template>

<style scoped>
main h1{
  display: block;
}
</style>