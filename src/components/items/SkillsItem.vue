<template>
  <section>
    <article>
      <li tabindex="0">
        <h4><slot name="type"></slot></h4>
        <slot name="skills"></slot>
      </li>
    </article>
  </section>
</template>

<style scoped>
ul li {
  list-style: none;
}

article li:focus {
  outline: var(--pico-outline-width) solid var(--pico-primary-focus);
  outline-offset: calc(var(--pico-spacing, 1rem) * 0.5);
  color: var(--pico-primary);
}
</style>
