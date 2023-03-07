<template>
  <div>
    <div class="py-3 bg-warning">
      <div class="container text-center">
        <h1>contact us</h1>
      </div>
    </div>

    <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <h1 class="main-heading">do you want to contact us ?</h1>
            <h4>please reach out us at contact@example.com</h4>
          </div>
          <div class="col-md-4 text-center my-auto">
            <NuxtLink to="/contact" class="px-5 py-2 btn btn-primary"
              >contact us</NuxtLink
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "contact",
  head() {
    return {
      title: "contact page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "nuxt js webpage-contactpage",
        },
        {
          hid: "keywords",
          name: "keywords",
          content: "vue,nuxt,js-contactpage",
        },
      ],
    };
  },
};
</script>
