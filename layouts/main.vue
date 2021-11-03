<template>
  <div class="main-content">
    <horizontal-nav />
    <Nuxt />
  </div>
</template>

<script>
import HorizontalNav from '@/components/HorizontalNav'

export default {
  name: "main.vue",
  components: {
    HorizontalNav,
  },
}
</script>

<style lang="scss">
  html,
  body,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  p,
  ul,
  li,
  ol,
  a {
    margin: 0;
    padding: 0;
    color: #000;
    text-decoration: none;
    list-style-type: none;
    font-family: Roboto, sans-serif;
  }

  body {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #000;
    min-height: 100vh;
  }

  .main-content {
    width: 80vw;
    background-color: #fff;
    min-height: 100vh;
  }
</style>
