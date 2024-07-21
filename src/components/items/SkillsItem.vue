<template>
  <section>
    <article>
      <li>
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
</style>
