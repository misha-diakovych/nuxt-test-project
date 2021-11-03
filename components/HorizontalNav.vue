<template>
  <header>
    <nav class="header">
      <ul class="header__list">
        <li class="header__item">
          <nuxt-link to="/">Home</nuxt-link>
        </li>


        <li class="header__item">
          <nuxt-link to="/about">About</nuxt-link>
        </li>


        <li class="header__item">
          <nuxt-link to="/contacts">Contacts</nuxt-link>
        </li>


        <li class="header__item">
          <nuxt-link to="/blog">Blog</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HorizontalNav.vue"
}
</script>

<style lang="scss">
  .header {
    &__list {
      display: flex;
      align-items: center;
      justify-content: center;
    }

    &__item {
      padding: 5px 15px;
      margin: 5px 15px;

      a {
        font-size: 30px;
        text-transform: uppercase;
      }
    }
  }
</style>
