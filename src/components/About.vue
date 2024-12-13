<script setup>
import aboutImage from "@/assets/img/about.png"
</script>

<template>
  <section class="hero min-h-screen" id="about">
    <div class="hero-content flex-col lg:flex-row" >
      <img
          :src="aboutImage"
          class="max-w-sm rounded-lg " />
      <div>
        <h3 class="text-5xl font-bold text-center">About Us</h3>
        <p class="p-24">
          At Medama, we provide cutting-edge hospital management solutions to streamline
          healthcare operations.Our platform empowers medical institutions with tools to
          enhance efficiency, improve patient care, and simplify administrative tasks.
          Our mission is to bridge the gap between technology and
          healthcare, ensuring that hospitals and clinics can focus on what matters
          most—saving lives.
        </p>

      </div>
    </div>
  </section>
</template>