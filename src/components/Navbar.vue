<script setup>
import logo from "@/assets/img/Materna_logo.png";
</script>

<template>
  <div class="absolute top-0 left-0 w-full z-10">
    <nav class="bg-transparent container mx-auto">
      <div
        class="container mx-auto px-4 flex justify-between items-center py-4"
      >
        <!-- Logo -->
        <div class="text-white text-lg font-semibold">
          <img :src="logo" alt="Akademia" class="h-5 w-auto ms-5" />
        </div>

        <!-- Navigation Links -->
        <ul class="flex space-x-6 mx-auto">
          <li>
            <a
              href="#"
              class="text-white hover:text-white hover:bg-blue-500 p-3 rounded-md focus:bg-blue-500 focus:text-white" 
              >Home</a
            >
          </li>
          <li><a href="#about" class="text-white hover:text-white hover:bg-blue-500 p-3 rounded-md focus:bg-blue-500 focus:text-white">
            About</a></li>
          <li>
            <a href="#service" class="text-white hover:text-white  hover:bg-blue-500 p-3 rounded-md focus:bg-blue-500 focus:text-white">
                Services</a>
          </li>
          <li>
            <a href="#" class="text-white hover:text-white  hover:bg-blue-500 p-3 rounded-md focus:bg-blue-500 focus:text-white">
                Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>
