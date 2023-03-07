<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg navbar-light bg-white shadow">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="/images/timepasslogo.jpeg" class="logo-img" alt="" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <NuxtLink to="/" class="nav-link">Home</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/aboutus" class="nav-link">about us</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/services" class="nav-link">our services</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/contact" class="nav-link">contact us</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>
<style>
.logo-img {
  width: 75px;
}
</style>
