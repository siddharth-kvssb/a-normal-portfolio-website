<template>
  <div
    id="carouselExampleControls"
    class="carousel slide"
    data-bs-ride="carousel"
  >
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://www.alstrongindia.com/images/yootheme/widgetkit/gallery/image1.jpg"
          class="a-block w-100"
          alt="slider1"
          height="500"
        />
      </div>
      <div class="carousel-item">
        <img
          src="https://hirko.sk/images/yootheme/widgetkit/gallery/zoom/image2.jpg"
          class="d-block w-100"
          alt="slider2"
          height="500"
        />
      </div>
      <div class="carousel-item">
        <img
          src="https://hirko.sk/images/yootheme/widgetkit/gallery/zoom/image3.jpg"
          class="d-block w-100"
          alt="slider3"
          height="500"
        />
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleControls"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleControls"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>

<script>
export default {
  name: "slider",
};
</script>
