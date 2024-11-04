<template>
  <div class="message-input fixed bottom-6 left-1/2 transform -translate-x-1/2 w-10/12 md:w-1/2 bg-white rounded-full shadow-lg flex items-center px-4 py-2">
    <button class="material-icons text-gray-500 mr-2">add</button>
    <input
      type="text"
      placeholder="Message Copilot"
      class="flex-grow bg-transparent outline-none placeholder-gray-500"
    />
  </div>
</template>

<style scoped>
.message-input {
  max-width: 600px;
}
</style>
