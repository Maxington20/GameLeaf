<script setup>
import { RouterLink, RouterView } from 'vue-router'
import LogoTagline from './components/LogoTagline.vue'
</script>

<template>
  <header class="bg-white shadow-lg px-4 py-2">
    <div class="container mx-auto flex justify-between items-center">
      <LogoTagline/>

      <nav class="space-x-4">
        <RouterLink 
          class="hover:text-green-500 transition-colors text-lg" 
          activeClass="text-green-600 font-semibold"
          to="/">Home</RouterLink>
        <RouterLink
          class="hover:text-green-500 transition-colors text-lg"
          activeClass="text-green-600 font-semibold"
          to="/my-games">My Games</RouterLink>
        <RouterLink 
          class="hover:text-green-500 transition-colors text-lg" 
          activeClass="text-green-600 font-semibold"
          to="/about">About</RouterLink>
        </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
