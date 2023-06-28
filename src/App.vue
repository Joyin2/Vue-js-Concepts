<script setup>
import Event from './components/Event.vue';
import HelloWorld from './components/HelloWorld.vue'
import Home from "./components/Home.vue"
</script>

<template>
  <div class="container">
    <h1>hello app </h1>
    <Home name="Joyin"/>  <!-- props -->
    <Event/>
  </div>
  
</template>

<style scoped>

</style>
