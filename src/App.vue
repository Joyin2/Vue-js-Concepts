<script setup>
import Event from './components/Event.vue';
import HelloWorld from './components/HelloWorld.vue'
import Home from "./components/Home.vue"
import IfElse from './components/If-else.vue';
</script>

<template>
  <div class="container">
    <h1>hello app </h1>
    <Home name="Joyin"/>  <!-- props -->
    <Event/>

    <IfElse/>
  </div>
  
</template>

<style scoped>

</style>
