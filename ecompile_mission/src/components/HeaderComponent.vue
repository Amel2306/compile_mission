<template>
    <header class="md:flex z-50 top-0 w-full">
      <div class="text-white py-3.5 px-6 md:flex justify-between items-center">
        <button @click="openMenu()" class="absolute md:hidden right-6 top-2 cursor-pointer text-4xl">
          <iconify-icon :icon="open ? 'ph:x' : 'material-symbols:menu'" style="color: white;"></iconify-icon>
        </button>
        <ul
          class="md:flex md:items-center md:w-auto md:ml-[600px] w-full top-14 duration-700 ease-in"
          :class="[open ? 'left-0' : 'left-[-100%] hidden']"
        >
          <li class="md:mx-4 my-6">
            <a href="#" class="text-white hover:text-gray-300">Home</a>
          </li>
          <li class="md:mx-4 my-6">
            <a href="#" class="text-white hover:text-gray-300">Benefits</a>
          </li>
          <li class="md:mx-4 my-6">
            <a href="#" class="text-white hover:text-gray-300">Testimonials</a>
          </li>
          <button class="md:ml-80 mt-4">
            <a
              href="#"
              class="border border-white text-white px-4 py-2 rounded hover:bg-white hover:text-[#355691] md:block "
            >
              Visit our website
            </a>
          </button>
        </ul>
      </div>
    </header>
  </template>
  
  <script>
  export default {
    data() {
      return {
        open: false,
      };
    },
    methods: {
      openMenu() {
        this.open = !this.open;
      },
    },
  };
  </script>
  
  <style scoped>
  </style>
  