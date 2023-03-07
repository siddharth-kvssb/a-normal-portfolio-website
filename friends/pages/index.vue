<template>
  <div>
    <slider />
    <div>
      <div class="py-5 container">
        <div class="row">
          <div class="col-md-12 text-center">
            <h1 class="main-heading">About us</h1>
            <div class="underline mx-auto"></div>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vitae,
              qui id. Dolorem enim consequatur eum eaque ipsa numquam porro
              error, architecto deleniti perferendis libero. Qui, cum similique!
              Dignissimos, ratione nobis? Lorem ipsum, dolor sit amet
              consectetur adipisicing elit. Vitae, qui id. Dolorem enim
              consequatur eum eaque ipsa numquam porro error, architecto
              deleniti perferendis libero. Qui, cum similique! Dignissimos,
              ratione nobis?
            </p>
            <div class="col-md-12 text-center my-auto">
              <NuxtLink to="/aboutus" class="px-5 py-2 btn btn-primary"
                >see more about us</NuxtLink
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <div>
      <div class="py-5 container">
        <div class="row">
          <div class="col-md-12 text-center">
            <h1 class="main-heading">our services</h1>
            <div class="underline mx-auto"></div>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vitae,
              qui id. Dolorem enim consequatur eum eaque ipsa numquam porro
              error, architecto deleniti perferendis libero. Qui, cum similique!
              Dignissimos, ratione nobis? Lorem ipsum, dolor sit amet
              consectetur adipisicing elit. Vitae, qui id. Dolorem enim
              consequatur eum eaque ipsa numquam porro error, architecto
              deleniti perferendis libero. Qui, cum similique! Dignissimos,
              ratione nobis?
            </p>
            <div class="col-md-12 text-center my-auto">
              <NuxtLink to="/services" class="px-5 py-2 btn btn-primary"
                >see more about our services</NuxtLink
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <h1 class="main-heading">do you want to contact us ?</h1>
            <h4>please reach out us at contact@example.com</h4>
          </div>
          <div class="col-md-2 text-center my-auto">
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
import slider from "~/components/slider.vue";
export default {
  name: "IndexPage",
  components: { slider },
  head() {
    return {
      title: "home page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "nuxt js webpage-homepage",
        },
        {
          hid: "keywords",
          name: "keywords",
          content: "vue,nuxt,js-homepage",
        },
      ],
    };
  },
};
</script>
