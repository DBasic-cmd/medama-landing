<script setup>
import heroImage from "@/assets/img/hero.jpg";
const externalUrl = "https://demo.medama.com.ng"

defineProps({
  title: {
    type: String,
    default: "Medama, the future of hospital management ",
  },
  subtitle: {
    type: String,
    default: "Making it a little easier for our heroes to save lives",
  },
});
</script>

<template>
  <div>
    <div class="hero bg-white min-h-screen">
      <div
        class="hero min-h-screen"
        :style="{ backgroundImage: `url(${heroImage})` }"
      >
        <div class="hero-overlay bg-opacity-60"></div>
        <div class="hero-content text-neutral-content text-center">
          <div class="">
            <h1 class="mb-5 text-6xl font-bold">{{ title }}</h1>
            <p class="mb-5">
              {{ subtitle }}
            </p>
            <button class="btn btn-primary" :href="externalUrl"><a>
                Preview
            </a></button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
