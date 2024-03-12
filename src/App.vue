<script setup>
  import { ref } from 'vue'
  import { RouterView } from 'vue-router';
  import Nav from './components/Nav.vue';

  const randomState = ref("")
</script>

<template>
  <div>
    {{ randomState }}
    <button @click="randomState= 'hello'">x</button>
    <Nav />
    <RouterView />
  </div>
</template>