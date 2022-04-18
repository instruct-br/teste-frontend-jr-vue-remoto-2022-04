<script setup lang="ts">
import Logo from './components/Logo.vue'
</script>

<template>
  <Logo/>
  <div class="countries">
    <h1 class="countries__title">Countries</h1>
  </div>
</template>

<style>
body {
  font-family: 'Roboto', sans-serif;
}

.countries__title {
  margin: 1.4rem 0;
  padding: 1.4rem 0;
  border-top: #ECF0F1 1px solid;
}
</style>
