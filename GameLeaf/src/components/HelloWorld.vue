<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <div class="text-5xl font-bold text-green-600">
        <span class="bg-clip-text text-transparent bg-gradient-to-r from-green-400 via-blue-500 to-purple-600">
          GameLeaf
        </span>
      </div>
      <p class="font-light text-lg text-gray-700 w-full mt-5 md:w-2/3">
        Dive into the world of gaming. Explore, review, and track your video game journey.
      </p>
  </div>
</template>

<style scoped>
</style>
