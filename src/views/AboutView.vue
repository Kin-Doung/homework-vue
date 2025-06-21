<script setup>
import heroImg from '@/assets/images/p1.png'
import expert1 from '@/assets/images/p2.png'
import expert2 from '@/assets/images/p3.png'
import expert3 from '@/assets/images/p4.png'
</script>

<template>
  <section class="bg-white text-gray-800">

    <!-- Hero Section -->
    <div
      class="bg-cover bg-center h-[400px] flex items-center justify-center text-white"
      :style="{ backgroundImage: `url(${heroImg})` }"
    >
      <div class="bg-black bg-opacity-50 p-8 rounded">
        <h1 class="text-5xl font-bold">About Us</h1>
        <p class="text-sm mt-2">Passionate About Driving Success For Businesses</p>
      </div>
    </div>

    <!-- Intro Section -->
    <div class="max-w-7xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <img :src="expert1" alt="Team" class="rounded-lg shadow" />
      </div>
      <div>
        <h2 class="text-sm uppercase text-orange-500 font-bold mb-2">About Us</h2>
        <h1 class="text-3xl font-bold mb-4">We Are Business Consultants Dedicated To Driving Your Success</h1>
        <p class="text-gray-600 mb-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis.</p>
        <p class="italic text-gray-500 mb-4">"Lorem ipsum dolor sit amet, consectetur adipiscing elit."</p>
        <p class="text-sm text-gray-700 flex items-center gap-2 mb-2">
          ✅ 15+ Years of Experience
        </p>
        <button class="mt-4 px-6 py-2 bg-orange-500 text-white rounded hover:bg-orange-600 transition">Learn More</button>
      </div>
    </div>

    <!-- Principles Section -->
    <div class="bg-blue-900 text-white py-20 text-center px-6">
      <h2 class="text-sm uppercase text-orange-300 mb-2">Our Mission & Vision</h2>
      <h1 class="text-3xl font-bold mb-10">Discover The Core Principles That Guide Us</h1>
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-6 max-w-6xl mx-auto">
        <div class="bg-white text-gray-800 p-6 rounded shadow">
          <h3 class="text-lg font-bold mb-2">Our Vision</h3>
          <p class="text-sm">Quis aute iure dolor in reprehenderit in voluptate velit esse cillum dolore.</p>
        </div>
        <div class="bg-white text-gray-800 p-6 rounded shadow">
          <h3 class="text-lg font-bold mb-2">Our Mission</h3>
          <p class="text-sm">Quis aute iure dolor in reprehenderit in voluptate velit esse cillum dolore.</p>
        </div>
        <div class="flex flex-col justify-center items-center">
          <div class="text-4xl font-bold">15Y+</div>
          <p class="text-sm text-gray-300 mt-2">Years of Experience</p>
        </div>
      </div>

      <!-- Stats -->
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6 mt-12 text-center">
        <div>
          <h2 class="text-4xl font-bold">680+</h2>
          <p class="text-sm text-gray-300">Business Trust Us</p>
        </div>
        <div>
          <h2 class="text-4xl font-bold">1,354</h2>
          <p class="text-sm text-gray-300">Projects Done</p>
        </div>
        <div>
          <h2 class="text-4xl font-bold">97%</h2>
          <p class="text-sm text-gray-300">Success Rate</p>
        </div>
        <div>
          <h2 class="text-4xl font-bold">15Y+</h2>
          <p class="text-sm text-gray-300">Experience</p>
        </div>
      </div>
    </div>

    <!-- Team Section -->
    <div class="max-w-7xl mx-auto px-6 py-16">
      <h2 class="text-sm uppercase text-orange-500 font-bold mb-2">Meet the Experts</h2>
      <h1 class="text-3xl font-bold mb-10">Discover Our Team Of Head Business Consultant Experts</h1>
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-6">
        <div v-for="(img, i) in [expert1, expert2, expert3]" :key="i" class="bg-white rounded-lg overflow-hidden shadow">
          <img :src="img" class="w-full h-64 object-cover" />
          <div class="p-4">
            <h3 class="font-bold text-lg">Expert {{ i + 1 }}</h3>
            <p class="text-sm text-gray-500">Senior Consultant</p>
          </div>
        </div>
      </div>
    </div>

    <!-- CTA -->
    <div class="bg-blue-800 text-white py-16 text-center px-6">
      <h2 class="text-3xl font-bold mb-4">Let's Discuss Your Business Goals</h2>
      <p class="text-blue-200 mb-6">Schedule a free consultation with our expert team today.</p>
      <RouterLink
        to="/contact"
        class="inline-block px-6 py-2 bg-orange-500 text-white rounded hover:bg-orange-600 transition"
      >
        Get a Quote →
      </RouterLink>
    </div>


  </section>
</template>
