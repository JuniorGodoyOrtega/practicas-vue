<template>
  <p
    v-bind:style="{
      backgroundColor: '#ccc',
      color: c,
      padding: '10px',
      borderRadius: '5px',
    }"
  >
    El mensaje se ha enviado sastifactoriamente.
  </p>
  <button @click="handleClick()">Cambia color</button>
</template>

<script setup>
import { ref } from "vue";
let c = ref("#fff");
const handleClick = () => {
  c.value = "#ff0000";
};
</script>

<style></style>
