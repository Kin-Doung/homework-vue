<template>
  <div
    class="bg-cover bg-center h-[400px] flex items-center justify-center text-white"
    :style="{ backgroundImage: `url(${heroImg})` }"
  >
    <div class="bg-black bg-opacity-50 p-8 rounded">
      <h1 class="text-5xl font-bold">About Us</h1>
      <p class="text-sm mt-2">Passionate About Driving Success For Businesses</p>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  heroImg: {
    type: String,
    default: ''
  }
})
</script>
