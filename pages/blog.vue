<template>
  <div class="content">
    <h1 class="main-heading">
      Blog
    </h1>

    <div>
      <h2>Heading 2</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Aperiam doloribus excepturi, facere iure perferendis quo recusandae vel voluptatibus.
        Aliquid, laudantium, sint. Assumenda, atque aut, corporis cumque dolorem dolorum earum et eum,
        ex harum id impedit in iste laborum magnam minima mollitia nobis officia
        reprehenderit saepe sed suscipit voluptates.
        Eveniet, odit!
      </p>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Alias amet architecto dolore dolores incidunt laborum magni natus nisi repudiandae temporibus.
      </p>
    </div>

    <div>
      <h2>Heading 2</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Aperiam doloribus excepturi, facere iure perferendis quo recusandae vel voluptatibus.
        Aliquid, laudantium, sint. Assumenda, atque aut, corporis cumque dolorem dolorum earum et eum,
        ex harum id impedit in iste laborum magnam minima mollitia nobis officia
        reprehenderit saepe sed suscipit voluptates.
        Eveniet, odit!
      </p>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Alias amet architecto dolore dolores incidunt laborum magni natus nisi repudiandae temporibus.
      </p>
    </div>

    <div>
      <h2>Heading 2</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Aperiam doloribus excepturi, facere iure perferendis quo recusandae vel voluptatibus.
        Aliquid, laudantium, sint. Assumenda, atque aut, corporis cumque dolorem dolorum earum et eum,
        ex harum id impedit in iste laborum magnam minima mollitia nobis officia
        reprehenderit saepe sed suscipit voluptates.
        Eveniet, odit!
      </p>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Alias amet architecto dolore dolores incidunt laborum magni natus nisi repudiandae temporibus.
      </p>
    </div>

    <div>
      <h2>Heading 2</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Aperiam doloribus excepturi, facere iure perferendis quo recusandae vel voluptatibus.
        Aliquid, laudantium, sint. Assumenda, atque aut, corporis cumque dolorem dolorum earum et eum,
        ex harum id impedit in iste laborum magnam minima mollitia nobis officia
        reprehenderit saepe sed suscipit voluptates.
        Eveniet, odit!
      </p>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Alias amet architecto dolore dolores incidunt laborum magni natus nisi repudiandae temporibus.
      </p>
    </div>

    <div>
      <h2>Heading 2</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Aperiam doloribus excepturi, facere iure perferendis quo recusandae vel voluptatibus.
        Aliquid, laudantium, sint. Assumenda, atque aut, corporis cumque dolorem dolorum earum et eum,
        ex harum id impedit in iste laborum magnam minima mollitia nobis officia
        reprehenderit saepe sed suscipit voluptates.
        Eveniet, odit!
      </p>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Alias amet architecto dolore dolores incidunt laborum magni natus nisi repudiandae temporibus.
      </p>
    </div>

    <div>
      <h2>Heading 2</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Aperiam doloribus excepturi, facere iure perferendis quo recusandae vel voluptatibus.
        Aliquid, laudantium, sint. Assumenda, atque aut, corporis cumque dolorem dolorum earum et eum,
        ex harum id impedit in iste laborum magnam minima mollitia nobis officia
        reprehenderit saepe sed suscipit voluptates.
        Eveniet, odit!
      </p>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Alias amet architecto dolore dolores incidunt laborum magni natus nisi repudiandae temporibus.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'main',
  head: {
    title: 'Blog',
    meta: [
      {
        hid: "description",
        name: "Blog page",
        content:
          "Blog page is a page, where you can read something interesting for you.",
      },
      { property: "og:site_name", content: "My test project on NUXT" },
      { hid: "og:type", property: "og:type", content: "website" },
      {
        hid: "og:url",
        property: "og:url",
        content: "https://bobross.com",
      },
      {
        hid: "og:title",
        property: "og:title",
        content: "My Amazing Blog on The Joy of Painting",
      },
      {
        hid: "og:description",
        property: "og:description",
        content: "Articles focused on the beautiful art of landscape painting.",
      },
      {
        hid: "og:image",
        property: "og:image",
        content: "https://upload.wikimedia.org/wikipedia/commons/f/fd/Pink_flower.jpg",
      },
      { property: "og:image:width", content: "740" },
      { property: "og:image:height", content: "300" },
    ],
  }
}
</script>

<style lang="scss">
.content {
  padding: 15px;

  &-box {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }
}

.main-heading {
  margin: 30px 0;
}

p {
  margin: 30px 0;
}
</style>
