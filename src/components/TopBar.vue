<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <header>
    <nav class="container">
      <h1>{{ msg }}</h1>
    </nav>
  </header>
</template>

<style scoped></style>
