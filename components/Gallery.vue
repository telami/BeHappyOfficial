<template>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 p-4">
      <div v-for="n in 11" :key="n" class="overflow-hidden">
        <!-- <img :src="`/assets/img/screenshot${n}.png`" alt="" class="w-full h-auto transform hover:scale-110 transition duration-500 ease-in-out"> -->
        <img src="/assets/img/screenshot1.png" alt="" class="w-full h-auto transform hover:scale-110 transition duration-500 ease-in-out">
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Gallery',
  }
  </script>
  
  <style scoped>
  /* 你可以在这里添加额外的样式 */
  </style>
  