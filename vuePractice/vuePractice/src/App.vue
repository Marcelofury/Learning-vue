<script setup>
import {ref} from 'vue'
import Header from '@/Header.vue'
const name = ref('Racheal')

const year = ref('2026')
</script>

<template>
  <Header/>
 

  <main>
    <h1> Hello, {{ name }} !</h1>
    <p>I'm about to learn vue! </p>
  </main>
  <footer>
    <p>&copy; {{ year }}</p>
  </footer>
</template>

<style scoped>

main h1{
  display: block;
}
footer {
  position: fixed;
bottom: 0;
padding-bottom: 20px;
}
footer p {
  color: blue;

}

</style>
