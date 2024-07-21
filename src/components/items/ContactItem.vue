<script setup>
defineProps({
  value: {
    type: String,
    required: false
  }
})
</script>
<template>
  <li>
    <label> <slot name="heading"></slot></label>
    <input v-if="value !== undefined" readonly type="text" :value="value" />
    <slot name="link"></slot>
  </li>
</template>

<style scoped>
.logo {
  width: 20px;
}
</style>
