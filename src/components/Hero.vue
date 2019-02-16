<template>
  <div class="hero">
    <div class="image-overlay">
      <img
        alt="Hero section"
        src="../assets/hero_image.jpg"
        class="hero-image bg-contain bg-top lg:h-screen"
      >
      <div
        class="hero-text justify-center self-center content-center items-center text-white text-center w-3/4"
        data-sal="fade"
        data-sal-duration="1300"
      >
        <h1 class="text-5xl font-bold tracking-tight">VFood</h1>
        <h1 class="text-2xl font-normal tracking-wide mb-8">#1 Fast Food in NY</h1>
        <a
          href="#"
          class="bg-red hover:bg-red-dark text-white font-bold py-3 px-5 rounded no-underline"
        >RESERVE</a>
      </div>
    </div>
  </div>
</template>

<script>
import sal from "sal.js";

export default {
  name: "Hero"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.hero {
  position: relative;
}
.hero-image {
  width: 100%;
  padding: 0;
  margin: 0;
  display: block;
}
.image-overlay {
  position: relative;
}
.image-overlay:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background: rgba(0, 0, 0, 0.2);
  z-index: 0;
}
.hero-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 10;
}

.half-image {
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
  display: block;
  object-fit: cover;
}
.half-image-size {
  width: 100%;
  height: 16rem;
}
@media (min-width: 576px) {
  .half-image-size {
    height: 20rem;
  }
}

@media (min-width: 992px) {
  .half-image-size {
    height: 32rem;
  }
}
</style>
