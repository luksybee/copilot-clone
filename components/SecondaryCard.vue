<template>
  <div class="flex flex-row flex-1 items-center bg-white rounded-xl shadow-md p-3 hover:shadow-lg transition transform hover:scale-105 duration-300">
    <!-- Image -->
    <img :src="image" alt="Card thumbnail" class="w-[45%] h-auto object-cover rounded-lg mr-4" />

    <!-- Content -->
    <div class="flex-1"> <!-- Use flex-1 to take remaining space -->
      <h3 class="text-base md:text-lg font-medium">{{ title }}</h3>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  image: String,
  title: String
});
</script>

<style scoped>
/* Add any additional styles here if necessary */
</style>
