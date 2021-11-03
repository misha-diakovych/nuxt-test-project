<template>
  <div class="content">
    <h1>
      Home
    </h1>

    <div>
      <h2>Lorem ipsum dolor sit amet.</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus aliquid aspernatur at
        consectetur consequatur culpa cum cumque distinctio dolore dolorem dolorum eligendi est excepturi
        exercitationem fugit impedit incidunt inventore iusto maiores, non officia pariatur perspiciatis,
        praesentium provident quam quas reiciendis reprehenderit soluta sunt tempora tempore unde veniam
        voluptatibus. Alias blanditiis debitis, doloremque dolorum et id in minus molestiae neque nisi
        nostrum quisquam quo rerum vitae voluptatem? A accusantium animi, earum iusto nihil odio veniam.
        Asperiores consectetur corporis culpa eveniet ex incidunt repellendus? Amet autem debitis explicabo
        in natus omnis optio sunt? Accusamus atque autem consectetur cum cumque delectus dolores dolorum ex
        explicabo facilis illo inventore ipsam iure laborum laudantium magnam magni maiores modi natus neque
        odit officiis optio quo quos rem repellendus, reprehenderit rerum ullam ut veritatis. Aperiam at
        doloremque, ea eaque enim eveniet ex exercitationem expedita fuga fugiat labore maxime minus natus
        neque nihil non nulla numquam odit officia officiis omnis quibusdam quidem quisquam, reprehenderit
        repudiandae sequi similique tempore vel vero voluptatibus! Adipisci architecto deleniti dolorem
        error, harum, inventore, ipsa ipsam laboriosam maxime modi obcaecati omnis quidem sequi vero voluptate
        voluptates voluptatibus. Accusamus aperiam blanditiis cupiditate dignissimos dolorem doloremque ea
        eius explicabo illo iure laudantium non odio perferendis perspiciatis quis, quod rerum sequi soluta
        sunt, velit. Accusantium aliquid blanditiis debitis, distinctio doloribus ea eveniet facilis hic
        incidunt ipsa, ipsam, iste labore maxime nemo nihil omnis quia quidem quis quod ratione saepe sequi
        similique totam velit vero vitae voluptas voluptate. Commodi deserunt est facilis hic, ipsam maiores
        maxime molestiae natus placeat quos unde velit. Aliquam, assumenda dolorum non quam rerum voluptatem.
        Animi doloribus tempore voluptate? Distinctio, dolor et ex ipsam tenetur voluptates. Doloribus dolorum
        enim laudantium molestiae necessitatibus sequi voluptatem. Adipisci alias aliquid autem exercitationem
        id illum nam optio possimus ut voluptate? A delectus enim iusto perferendis quae recusandae.
        A, ab alias animi earum eos esse excepturi fugit iusto laborum maiores minus natus nostrum numquam
        odit omnis perspiciatis recusandae, rerum velit. Adipisci alias aut beatae blanditiis corporis culpa
        deserunt distinctio dolorem dolores enim est et ex, fuga fugiat inventore ipsam iusto laborum libero
        natus necessitatibus nihil odio possimus quis sequi similique unde vel velit. A ab accusamus accusantium
        animi aut beatae commodi culpa dicta dignissimos dolorem enim eos eum eveniet expedita id illum laudantium
        nam nemo nesciunt nisi nulla numquam obcaecati officia, pariatur perspiciatis placeat qui quidem quisquam
        quo quod rem repellendus reprehenderit sapiente sit tempora temporibus voluptatem? Architecto asperiores
        atque, consequatur deserunt dolorem fuga neque nihil, nisi odio placeat quam recusandae sapiente!
        Autem commodi, deleniti doloribus expedita laboriosam maiores quaerat quibusdam ratione repellendus
        sequi vitae voluptates. Atque distinctio dolores ducimus fuga id inventore ipsa ipsum labore necessitatibus
        neque numquam quam qui rem repellat sunt tenetur, veniam? Aliquam earum eius est ex excepturi harum ipsam
        labore, maxime minus necessitatibus obcaecati pariatur quis quos, saepe sint tenetur voluptate! Aliquam
        aspernatur assumenda culpa dolore iste neque praesentium saepe. Adipisci, blanditiis consectetur eaque nisi
        praesentium ratione repellendus tempora unde veritatis voluptatibus! Deserunt doloribus fuga inventore ipsam
        molestias nisi nulla officiis optio quo voluptatum?
      </p>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'main',
  head: {
    title: 'Home',
    meta: [
      {
        hid: "description",
        name: "Home page",
        content:
          "Home page is a page.",
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
