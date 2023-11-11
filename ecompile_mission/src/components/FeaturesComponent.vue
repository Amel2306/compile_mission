<!-- Features.vue -->
<template>
    <div>
        <div class="flex flex-col items-center justify-center mt-16 mb-8 md:mt-28 text-center">
        <p class="mb-4 text-[#F15692] font-bold">FEATURES</p>
        <p class="md:text-4xl text-3xl text-[#4A4A4A] font-bold ">What Benefits you Get</p>
      </div>
      <div id="container" class="flex items-center justify-center text-[#4A4A4A] flex-wrap pb-16">
        <div id="card-container" class="shadow-xl rounded-lg flex flex-col items-center justify-center m-4 p-8">
          <iconify-icon class="my-8" id="icon" icon="icon-park-outline:good-two" height="36"></iconify-icon>
          <h1 class="text-2xl font-bold mb-3">Better Choices</h1>
          <p class="text-lg text-center">Make unbiased choices thanks to reviews, testimonials</p>
        </div>  
        <div id="card-container" class="shadow-xl rounded-lg flex flex-col items-center justify-center m-4 p-8">
          <iconify-icon class="my-8" id="icon" icon="bx:money-withdraw" height="36"></iconify-icon>
          <h1 class="text-2xl font-bold mb-3">Save Money</h1>
          <p class="text-lg text-center">Save time & money reducing time-to-hire by 86% and cost-to-hire by 35% </p>
        </div>  
        <div id="card-container" class="shadow-xl rounded-lg flex flex-col items-center justify-center m-4 p-8">
          <iconify-icon class="my-8" id="icon" icon="mdi:file-find-outline" height="36"></iconify-icon>
          <h1 class="text-2xl font-bold mb-3">Easy Access</h1>
          <p class="text-lg text-center">Access to over 350 Trainers regionally</p>
        </div>       
      </div>
    </div>
  </template>
  
  <script>
  export default {
    // Ajoutez vos propriétés ou méthodes nécessaires ici
  };
  </script>
  
  <style scoped>
    #card-container {
        max-width:  342px;
        height: 271px;
    }

    #icon {
      color: #5cce4c;
    }
  </style>
  