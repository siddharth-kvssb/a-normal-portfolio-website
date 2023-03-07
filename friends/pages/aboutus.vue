<template>
  <div>
    <div class="py-3 bg-warning">
      <div class="container text-center">
        <h1>About Us</h1>
      </div>
    </div>
    <About />
  </div>
</template>

<script>
import About from "~/components/About.vue";
export default {
  name: "about",
  Comments: { About },

  head() {
    return {
      title: "about page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "nuxt js webpage-aboutpage",
        },
        {
          hid: "keywords",
          name: "keywords",
          content: "vue,nuxt,js-aboutpage",
        },
      ],
    };
  },
};
</script>
