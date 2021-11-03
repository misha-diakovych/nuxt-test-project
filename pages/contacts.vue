<template>
  <div class="content">
    <h1>
      Contacts
    </h1>

    <div class="content-box">
      <div>
        <h2>Phones</h2>
        <p>
          +3805590549095
        </p>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <p>
          USA, New Yourt
        </p>
      </div>

      <div>
        <h2>Phones</h2>
        <p>
          +3805590549095
        </p>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <p>
          USA, New Yourt
        </p>
      </div>

      <div>
        <h2>Phones</h2>
        <p>
          +3805590549095
        </p>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <p>
          USA, New Yourt
        </p>
      </div>

      <div>
        <h2>Phones</h2>
        <p>
          +3805590549095
        </p>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <p>
          USA, New Yourt
        </p>
      </div>

      <div>
        <h2>Phones</h2>
        <p>
          +3805590549095
        </p>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <p>
          USA, New Yourt
        </p>
      </div>

      <div>
        <h2>Phones</h2>
        <p>
          +3805590549095
        </p>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <p>
          USA, New Yourt
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'main',
  head: {
    title: 'Contacts',
    meta: [
      {
        hid: "description",
        name: "Contact page",
        content:
          "Contact page is a page, where you can call to me.",
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
