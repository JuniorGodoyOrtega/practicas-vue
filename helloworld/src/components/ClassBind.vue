<template>
  <p
    v-bind:class="{
      danger: hasError,
    }"
  >
    El mensaje se ha enviado sastifactoriamente.
  </p>
</template>
<script setup>
    let hasError = false;
</script>
<style>
.danger {
  color: red;
}
</style>
