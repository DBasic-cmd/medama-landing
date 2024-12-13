<script setup>
import { RouterLink } from "vue-router";
import logo from "@/assets/img/Materna_logo.png";
</script>

<template>
  <div class="absolute top-0 left-0 w-full z-10">
    <nav class="bg-blue-50">
      <div
        class=" mx-auto px-4 flex justify-between items-center py-4 container"
      >
        <!-- Logo -->
        <div class="text-white text-lg font-semibold">
          <RouterLink to="/">
            <img :src="logo" alt="Akademia" class="h-10 w-auto" />
          </RouterLink>
        </div>

        <!-- Navigation Links -->
        <ul class="flex space-x-6 ms-auto">
          <li>
            <RouterLink
              to="/"
              class="text-black hover:text-white hover:bg-blue-300 p-3 rounded-md focus:bg-blue-600 focus:text-white"
              >Home</RouterLink
            >
          </li>
          <li><a href="#about" class="text-black hover:text-white hover:bg-blue-300 p-3 rounded-md focus:bg-blue-300 focus:text-white">
            About Us</a></li>
          <li>
            <a href="#service" class="text-black hover:text-white  hover:bg-blue-300 p-3 rounded-md focus:bg-blue-300 focus:text-white">
                Services</a>
          </li>
          <li>
            <a href="#contact" class="text-black hover:text-white  hover:bg-blue-300 p-3 rounded-md focus:bg-blue-300 focus:text-white">
                Contact</a>
          </li>

          
        </ul>
<!--        <button class="btn bg-blue-600 hover:bg-blue-600 text-white ms-auto"><a :href="externalUrl">-->
<!--                Preview-->
<!--            </a></button>-->
      </div>
    </nav>
  </div>
</template>
