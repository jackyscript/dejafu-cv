<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <h1>{{ msg }}</h1>
  <a href="#main">Skip to main content</a>
</template>

<style scoped></style>
