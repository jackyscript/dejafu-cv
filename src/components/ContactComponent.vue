<script setup>
import ContactItem from './items/ContactItem.vue'
</script>

<template>
  <p>
    Hello, I am Dezhi Jacky Fu, I work as an application developer. I have a passion for human
    focused development, I care for a11y, UX and DX. I am focused, dedicated, hard-working and
    willing to learn in a changing and challenging environment. I am a trained engineer (M. Sc.) in
    the field of geodesy, the science of mapping, and geospatial information.
  </p>
  <section>
    <article>
      <ul>
        <ContactItem value="Berlin">
          <template #icon>
            <img
              aria-hidden="true"
              class="logo"
              src="../assets/icons/pin.svg"
              alt="An address pin icon"
          /></template>
          <template #heading>Address</template>
        </ContactItem>

        <ContactItem value="Please ask per mail">
          <template #icon>
            <img
              aria-hidden="true"
              class="logo"
              src="../assets/icons/phone.svg"
              alt="A phone icon"
            />
          </template>
          <template #heading>Phone</template>
        </ContactItem>

        <ContactItem value="dezhijacky.fu [ at ] gmail.com">
          <template #icon>
            <img aria-hidden="true" class="logo" src="../assets/icons/mail.svg" alt="A mail icon" />
          </template>
          <template #heading>E-Mail</template>
        </ContactItem>
        <ContactItem>
          <template #icon>
            <img
              aria-hidden="true"
              class="logo"
              src="../assets/icons/github.svg"
              alt="The icon of github"
            />
          </template>
          <template #heading>Github</template>

          <template #link>
            <a href="https://github.com/jackyscript" target="_blank" rel="noopener"
              >Click here to see my github page</a
            ></template
          >
        </ContactItem>
      </ul>
    </article>
  </section>
</template>

<style scoped>
.logo {
  width: 20px;
}

ul li {
  list-style: none;
}
</style>
