<template>
  <div>
    <h2>Bài 2:</h2>
    <label for="color">Màu sắc</label><br />
    <input type="color" v-model="color" />
    <p>Mã màu: {{ color }}</p>
  </div>
</template>

<script setup>
import { ref } from "vue";

const color = ref("");
</script>

<style></style>
