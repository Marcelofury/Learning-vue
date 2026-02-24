<script setup>
import {ref} from 'vue'
const name = ref('Racheal')
const emoji = ref('✌️')
const year = ref('2026')
</script>

<template>
  <header>
    <span>{{ emoji }}</span>
  </header>

  <main>
    <h1> Hello, {{ name }} !</h1>
    <p>I'm about to learn vue! </p>
  </main>
  <footer>
    <p>&copy; {{ year }}</p>
  </footer>
</template>

<style scoped>
span{
  font-size: 3rem;

}
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
