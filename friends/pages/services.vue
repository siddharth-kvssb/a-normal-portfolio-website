<template>
  <div>
    <div class="py-3 bg-warning">
      <div class="container text-center">
        <h1>our services</h1>
      </div>
    </div>

    <our-services />
  </div>
</template>

<script>
import OurServices from "../components/OurServices.vue";
export default {
  components: { OurServices },
  name: "services",
  head() {
    return {
      title: "service page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "nuxt js webpage-servicepage",
        },
        {
          hid: "keywords",
          name: "keywords",
          content: "vue,nuxt,js-servicepage",
        },
      ],
    };
  },
};
</script>
