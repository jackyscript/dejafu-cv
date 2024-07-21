<template>
  <section>
    <article>
      <summary>
        <h4><slot name="title"></slot></h4>
        <h5><slot name="occupation"></slot></h5>
        <h6>
          <slot name="location"></slot>
        </h6>
        <footer>
          <small><slot name="date"></slot></small>
        </footer>
      </summary>
      <slot></slot>
    </article>
  </section>
</template>

<style scoped></style>
