<template>
  <Navbar />

  <section class="h-[300px] m-10">
    <h1 class="text-3xl my-5">Ejercicios Day1 week9</h1>
    <p class="my-5">Ejercicio operación "2+2"= {{2+2}}</p>
    <p class="my-5">{{stringFunction()}}</p>
  </section>

  <Footer />

</template>

<script setup>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import {ref} from 'vue';
function stringFunction() {
  return("Esto es una string de ejemplo")
}
</script>

<style>

</style>