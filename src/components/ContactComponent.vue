<script setup>
import ContactItem from './items/ContactItem.vue'
</script>

<template>
  <ul>
    <img aria-hidden="true" class="logo" src="../assets/icons/pin.svg" />
    <ContactItem value="Berlin">
      <template #heading>Address</template>
    </ContactItem>

    <img aria-hidden="true" class="logo" src="../assets/icons/phone.svg" />
    <ContactItem value="Ask me per mail">
      <template #heading>Phone</template>
    </ContactItem>

    <img aria-hidden="true" class="logo" src="../assets/icons/mail.svg" />
    <ContactItem value="dezhijacky.fu [ at ] gmail.com">
      <template #heading>E-Mail</template>
    </ContactItem>

    <img aria-hidden="true" class="logo" src="../assets/icons/github.svg" />
    <ContactItem>
      <template #heading>Github</template>

      <template #link>
        <a href="https://github.com/jackyscript" target="_blank" rel="noopener"
          >Click here to see my github page</a
        ></template
      >
    </ContactItem>
  </ul>
</template>

<style scoped>
.logo {
  width: 20px;
}
</style>
