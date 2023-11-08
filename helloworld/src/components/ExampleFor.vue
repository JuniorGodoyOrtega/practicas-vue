<template>
  <ul>
    <li v-for="country in countries" v-bind:key="country.code">{{ country.name }}</li>
  </ul>
</template>
<script setup>
import { ref } from "vue";
let countries = ref([
  {
    code: "es",
    name: "España",
  },
  {
    code: "fr",
    name: "Francia",
  },
  {
    code: "it",
    name: "Italia",
  },
  {
    code: "pt",
    name: "Portugal",
  },
]);
</script>
<style scoped></style>
