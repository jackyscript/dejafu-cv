<template>
  <section>
    <article>
      <summary>
        <h4><slot name="institution"></slot></h4>
        <h5><slot name="degree"></slot></h5>
        <h6>
          <slot name="location"></slot>
        </h6>
        <footer>
          <small><slot name="date"></slot></small>
        </footer>
      </summary>
    </article>
  </section>
</template>

<style scoped></style>
