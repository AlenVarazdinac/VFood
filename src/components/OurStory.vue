<template>
  <div id="our-story" class="our-story flex flex-col md:flex-row w-full">
    <div
      class="flex flex-col justify-center self-center align-center items-center w-full p-8 md:p-0 content-center"
      data-sal="slide-right"
      data-sal-duration="900"
    >
      <h2 class="text-center">OUR STORY</h2>
      <div class="border-b-4 border-red w-12 self-center m-4"></div>
      <p class="md:px-5 md:py-2 lg:p-32 lg:py-2">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit.
        Eaque repellendus amet rerum nemo sint
        commodi molestias maxime? Veritatis dicta tenetur beatae?
        Recusandae reiciendis adipisci quae laborum iure ipsam odio rerum?
      </p>
      <a href="#" class="text-red no-underline mt-4">READ</a>
    </div>
    <div
      class="image-overlay half-image-size bg-fixed w-full"
      data-sal="slide-left"
      data-sal-duration="900"
    >
      <img src="../assets/our_story.jpg" class="half-image bg-cover bg-center bg-fixed">
    </div>
  </div>
</template>

<script>
export default {
  name: "OurStory"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.our-story {
  position: relative;
}
</style>
