<template>
  <div class="w-full h-full aspect-w-1 p-3 bg-white aspect-h-1 relative rounded-2xl overflow-hidden shadow-lg transform hover:scale-105 transition duration-300 ease-in-out">
    <!-- Background Image -->
    <img :src="image" alt="Card background" class="w-full h-full object-cover rounded-xl" />

    <!-- Dark Overlay -->
    <div class="absolute inset-0 bg-black bg-opacity-50"></div>

    <!-- Content -->
    <div class="absolute bottom-0 p-6 text-white z-10">
      <h2 class="text-2xl font-semibold mb-1">{{ title }}</h2>
      <p class="text-gray-300 text-sm mb-4">{{ subtitle }}</p>

      <!-- Listen Button -->
      <button class="flex items-center bg-white bg-opacity-20 text-white rounded-full py-1 px-4 hover:bg-opacity-30 transition duration-300">
        <span class="material-icons mr-2 text-base">headphones</span> Listen
      </button>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  image: String,
  title: String,
  subtitle: String
});
</script>

<style scoped>

</style>
