<template>
  <div>
    <h2>Bài 6:</h2>
    <p>Sở thích: {{ hobbies }}</p>
    <input type="checkbox" value="Code" v-model="hobbies" />Code
    <input type="checkbox" value="Game" v-model="hobbies" />Game
    <input type="checkbox" value="Đá Bóng" v-model="hobbies" />Đá Bóng
    <input type="checkbox" value="Dọn Dẹp" v-model="hobbies" />Dọn Dẹp
  </div>
</template>

<script setup>
import { ref } from "vue";

const hobbies = ref([]);
</script>

<style></style>
