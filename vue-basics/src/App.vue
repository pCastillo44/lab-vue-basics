<template>
  
  <Header />
  <p> {{ 2 + 2 }}</p>
  <p :class="show">Texto condicional</p>

<Footer />
</template>

<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

const show = ref('show');
</script>

<style>

.show {
  display: block;
 
}

.hidden {
    display: none;
  }
</style>