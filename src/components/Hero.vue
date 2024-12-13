<script setup>
import heroImage from "@/assets/img/hero.png"
import herOne from "@/assets/img/hero1-removebg-preview.png"
</script>

<template>
  <div class="hero bg-blue-50 min-h-screen ">
    <div class="hero-content flex-col lg:flex-row-reverse container">
      <div class="relative w-64 h-64 hidden md:block">
        <!-- Background Image -->
        <img
            :src="heroImage"
            alt="Background"
            class="w-full h-full object-cover"
        />

        <!-- Overlay Image -->
        <img
            :src="herOne"
            alt="Overlay"
            class="absolute top-10 right-4 w-100 h-100 object-cover"
        />
      </div>

      <div class="px-6 md:pt-3">
        <h1 class="text-2xl text-gray-400">MEDICAL CHECKUP</h1>
        <h1 class="text-5xl font-bold py-6">Your Trusted Partner In Exceptional  Healthcare Services</h1>
        <p class="py-6">
          We’re committed to delivering reliable, high quality care for you and your family.
        </p>
        <button class="btn bg-blue-300 text-black hover:bg-blue-300 hover:text-black">Get Started</button>
      </div>
    </div>
  </div>
</template>
