<script setup>
import ContactItem from './items/ContactItem.vue'
</script>

<template>
  <ul>
    <ContactItem src="src/assets/icons/pin.svg" value="Berlin">
      <template #heading>Address</template>
    </ContactItem>

    <ContactItem src="src/assets/icons/phone.svg" value="Ask me per mail">
      <template #heading>Phone</template>
    </ContactItem>

    <ContactItem src="src/assets/icons/mail.svg" value="dezhijacky.fu [ at ] gmail.com">
      <template #heading>E-Mail</template>
    </ContactItem>

    <ContactItem src="src/assets/icons/github.svg">
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
