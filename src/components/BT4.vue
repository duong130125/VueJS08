<template>
  <div>
    <h2>Bài 4:</h2>
    <p>Tiến độ thành công: {{ range }} %</p>
    <input type="range" v-model="range" />
  </div>
</template>

<script setup>
import { ref } from "vue";

const range = ref(0);
</script>

<style></style>
