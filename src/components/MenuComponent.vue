<script setup>
function darken() {
  document.documentElement.setAttribute('data-theme', 'dark')
}
function brighten() {
  document.documentElement.setAttribute('data-theme', 'light')
}
</script>

<template>
  <div class="flex">
    <button role="button" title="Darken" @click="darken">
      <img aria-hidden="true" class="logo" src="../assets/icons/darken.svg" alt="Darken" />
      <span hidden>Darken</span>
    </button>
    <button role="button" title="Brighten" @click="brighten">
      <img aria-hidden="true" class="logo" src="../assets/icons/brighten.svg" alt="Brighten" />
      <span hidden>Brighten</span>
    </button>
  </div>
</template>

<style scoped>
.msg {
  margin-right: auto;
}

.logo {
  width: 20px;
}

.flex {
  display: flex;
  justify-content: flex-end;
}
</style>
