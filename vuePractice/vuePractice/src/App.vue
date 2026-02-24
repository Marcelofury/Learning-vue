<script setup>
import {ref} from 'vue'
import Header from '@/Header.vue'
import Main from '@/main.vue'


const year = ref('2026')
</script>

<template>
  <Header/>
  <Main/>
 

  
  <footer>
    <p>&copy; {{ year }}</p>
  </footer>
</template>

<style scoped>


footer {
  position: fixed;
bottom: 0;
padding-bottom: 20px;
}
footer p {
  color: blue;

}

</style>
