<template>
  <div id="contact" class="contact">
    <div
      class="w-full flex flex-col md:flex-row justify-center items-center self-center p-8 sm:p-12 content-center"
    >
      <div
        class="w-full md:w-2/4 justify-center md:justify-start flex flex-col"
        data-sal="slide-right"
        data-sal-duration="900"
      >
        <h2 class="text-center self-center">CONTACT</h2>
        <div class="border-b-4 border-red w-12 self-center m-4"></div>

        <div class="flex w-3/4 md:w-1/2 justify-between mb-4 self-center">
          <p class="text-red text-left">Phone :</p>
          <p class="text-black text-right">806-209-4788</p>
        </div>
        <div class="flex w-3/4 md:w-1/2 justify-between mb-4 self-center">
          <p class="text-red text-left">E-Mail :</p>
          <p class="text-black text-right">info@name.com</p>
        </div>
        <div class="flex w-3/4 md:w-1/2 justify-between self-center">
          <p class="text-red text-left">Location :</p>
          <p class="text-black text-right">44 Bowery, New York</p>
        </div>
      </div>

      <div
        class="flex flex-row justify-center text-red mt-12 md:w-1/2"
        data-sal="slide-left"
        data-sal-duration="900"
      >
        <a href="#" class="text-red hover:text-red-lighter">
          <i class="fab fa-facebook-square fa-2x mr-3"></i>
        </a>
        <a href="#" class="text-red hover:text-red-lighter">
          <i class="fab fa-twitter-square fa-2x mr-3"></i>
        </a>
        <a href="#" class="text-red hover:text-red-lighter">
          <i class="fab fa-instagram fa-2x"></i>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
