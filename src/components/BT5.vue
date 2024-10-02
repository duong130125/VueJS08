<template>
  <div>
    <h2>Bài 5:</h2>
    <p>Giới tính: {{ gender }}</p>
    <input type="radio" value="Nam" v-model="gender" />Nam
    <input type="radio" value="Nữ" v-model="gender" />Nữ
    <input type="radio" value="Khác" v-model="gender" />Khác
  </div>
</template>

<script setup>
import { ref } from "vue";

const gender = ref("");
</script>

<style></style>
