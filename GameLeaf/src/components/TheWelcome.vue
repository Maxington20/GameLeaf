<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div class="min-h-screen bg-gray-100 flex flex-col">
    
    <!-- Hero Section -->
    <div class="mx-auto text-center p-4 space-y-8">
      <!-- Logo and Title -->

      <!-- Description -->
      <p class="font-light text-lg text-gray-700 mx-auto w-full mt-5">
        Dive into the world of gaming!
      </p>

      <!-- CTA Buttons -->
      <div class="space-x-4">
        <button class="bg-green-600 hover:bg-green-700 text-white font-medium py-2 px-6 rounded-full shadow-md transition duration-300">
          Get Started
        </button>
        <button class="bg-transparent hover:bg-gray-200 text-green-600 font-medium py-2 px-6 rounded-full transition duration-300">
          Learn More
        </button>
      </div>
    </div>
    
  </div>
</template>






