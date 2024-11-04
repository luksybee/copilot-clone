<template>
  <div class="max-w-screen-md mx-auto space-y-8 p-4">
    <!-- Greeting Header -->
    <h1 class="text-2xl font-semibold mb-6 text-center">Good morning, Luqman</h1>

    <!-- For Your Evening Section -->
    <h2 class="text-xl font-semibold mb-4 text-center">For your evening</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Primary Card with fixed height -->
      <div class="md:col-span-1 flex items-stretch">
          <PrimaryCard
            image="https://picsum.photos/300/300?random=1"
            title="Kemi Badenoch's historic win, and more"
            subtitle="Copilot Daily"
          />
      </div>

      <!-- Secondary Cards stacked vertically with consistent spacing -->
      <div class="flex flex-col space-y-3">
          <SecondaryCard
            image="https://picsum.photos/300/300?random=2"
            title="Becoming a more confident public speaker"
          />
          <SecondaryCard
            image="https://picsum.photos/300/300?random=3"
            title="I’ll share pop culture news with a rhyme"
          />
      </div>
    </div>

    <!-- Topics Section -->
    <h2 class="text-xl font-semibold mb-4 text-center">Topics I thought you'd enjoy</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Primary Card with fixed height -->
      <div class="md:col-span-1 flex items-stretch">
          <PrimaryCard
            image="https://picsum.photos/300/300?random=4"
            title="Practice for a difficult conversation together"
            subtitle=""
          />
      </div>

      <!-- Secondary Cards stacked vertically with consistent spacing -->
      <div class="flex flex-col space-y-1">
          <SecondaryCard
            image="https://picsum.photos/300/300?random=5"
            title="I’ll help you relax"
          />
          <SecondaryCard
            image="https://picsum.photos/300/300?random=6"
            title="Ask me to create a workshop"
          />
      </div>
    </div>

    <!-- Message Input -->
    <MessageInput />
  </div>
</template>
