<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
    <h1 class="msg">{{ msg }}</h1>
  </div>
</template>

<style scoped>
.msg {
  margin-right: auto;
}

.logo {
  width: 20px;
}
</style>
