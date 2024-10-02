<template>
  <div>
    <h2>Bài 3:</h2>
    <p>Ngày sinh: {{ date }}</p>
    <input type="date" v-model="date" />
  </div>
</template>

<script setup>
import { ref } from "vue";

const date = ref("");
</script>

<style></style>
