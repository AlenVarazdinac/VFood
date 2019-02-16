<template>
  <div class="home">
    <Hero/>
    <OurStory/>
    <MenuPart/>
    <ReserveTablePart/>
    <div
      class="image-overlay half-image-size hidden md:block border-b-4 border-red"
      data-sal="slide-up"
      data-sal-duration="900"
    >
      <img src="../assets/menu.jpg" class="half-image bg-contain bg-center bg-fixed">
    </div>
    <Contact/>
    <Footer/>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from "@/components/Hero.vue";
import Contact from "@/components/Contact.vue";
import Footer from "@/components/Footer.vue";
import OurStory from "@/components/OurStory.vue";
import MenuPart from "@/components/MenuPart.vue";
import ReserveTablePart from "@/components/ReserveTablePart.vue";

export default {
  name: "home",
  components: {
    Hero,
    Contact,
    Footer,
    OurStory,
    MenuPart,
    ReserveTablePart
  },
  created() {}
};
</script>

<style lang="scss" >
@import "~sal.js/dist/sal.css";

#app {
  overflow-x: hidden;
}
</style>
