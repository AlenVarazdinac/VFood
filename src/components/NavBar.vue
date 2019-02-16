<template>
  <!-- <div id="nav">
    <router-link to="/">Home</router-link>|
    <router-link to="/about">About</router-link>
  </div>-->
  <div class="font-sans antialiased">
    <nav
      class="flex items-center justify-between flex-wrap bg-red sm:bg-transparent sm:absolute p-6 w-full"
      style="z-index: 10000;"
    >
      <div class="flex items-center flex-no-shrink text-white mr-6">
        <a href="/" class="no-underline text-white hover:text-grey">
          <h1 class="font-semibold text-2xl tracking-tight">VFood</h1>
        </a>
      </div>
      <div class="block sm:hidden">
        <button
          @click="toggle"
          class="flex items-center px-3 py-2 text-3xl text-white hover:text-grey-lighter focus:outline-none"
        >
          <i class="fas fa-bars"></i>
        </button>
      </div>
      <div
        :class="open ? 'block': 'hidden'"
        class="w-full flex-grow sm:flex-none sm:flex sm:items-center sm:w-auto"
      >
        <div class="text-base sm:flex-grow mx-auto text-center">
          <a
            href="#our-story"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-white hover:text-grey mr-3"
          >OUR STORY</a>
          <a
            href="#menu"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-white hover:text-grey mr-3"
          >MENU</a>
          <a
            href="#reserve-table"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-white hover:text-grey mr-3"
          >RESERVE TABLE</a>
          <a
            href="#contact"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-white hover:text-grey"
          >CONTACT</a>
        </div>
        <!-- <div>
          <a
            href="#"
            class="no-underline inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal hover:bg-white mt-4 sm:mt-0"
          >CONTACT</a>
        </div>-->
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "navbar",
  data() {
    return {
      open: false
    };
  },
  methods: {
    toggle() {
      this.open = !this.open;
    }
  }
};
</script>

<style lang="scss">
// #nav {
//   padding: 30px;
//   a {
//     font-weight: bold;
//     color: #2c3e50;
//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>
