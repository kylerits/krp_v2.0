<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        Kyle Rodgers Portfolio
      </h1>
      <h2 class="subtitle">
        A web development portfolio for Kyle Rodgers
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="btn btn-primary">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="btn btn-secondary">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
