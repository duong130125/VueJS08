<template>
  <div>
    <h2>Bài 1:</h2>
    <label for="email">Email:</label><br />
    <input type="text" v-model="email" />
    <p>Giá trị ô Input: {{ email }}</p>
  </div>
</template>

<script setup>
import { ref } from "vue";
const email = ref("");
</script>

<style></style>
