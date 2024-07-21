<script setup>
defineProps({
  id: {
    type: String,
    required: true
  },
  value: {
    type: String,
    required: false
  }
})
</script>
<template>
  <li>
    <slot name="icon"></slot>
    <label :for="id"> <slot name="heading"></slot></label>
    <input :id="id" v-if="value !== undefined" readonly type="text" :value="value" />
    <slot name="link"></slot>
  </li>
</template>

<style scoped>
.logo {
  width: 20px;
}
</style>
