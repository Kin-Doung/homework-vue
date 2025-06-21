<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="bg-white shadow-md">
    <div class="max-w-7xl mx-auto px-4 py-4 flex items-center justify-between">
      <!-- Logo / Brand -->
      <h1 class="text-xl font-bold text-purple-700">MyWebsite</h1>

      <!-- Navigation Links -->
      <nav class="space-x-6">
        <RouterLink to="/" class="text-gray-700 hover:text-purple-600 font-medium"
          active-class="text-purple-700 border-b-2 border-purple-700">
          Home
        </RouterLink>
        <RouterLink to="/about" class="text-gray-700 hover:text-purple-600 font-medium"
          active-class="text-purple-700 border-b-2 border-purple-700">
          About
        </RouterLink>
        <RouterLink to="/service" class="text-gray-700 hover:text-purple-600 font-medium"
          active-class="text-purple-700 border-b-2 border-purple-700">
          Service
        </RouterLink>
        <RouterLink to="/contact" class="text-gray-700 hover:text-purple-600 font-medium"
          active-class="text-purple-700 border-b-2 border-purple-700">
          Contact
        </RouterLink>
      </nav>
    </div>
  </header>

  <!-- Page Content -->
  <main class="p-4">
    <RouterView />
  </main>
  <footer class="bg-gray-100 mt-10">
    <div class="max-w-7xl mx-auto px-6 py-10 grid grid-cols-1 md:grid-cols-3 gap-8 text-gray-700">

      <!-- Column 1: Logo & About -->
      <div>
        <h2 class="text-2xl font-bold text-purple-700 mb-2">MyWebsite</h2>
        <p class="text-sm leading-relaxed">
          Your trusted source for tech solutions. We offer custom PC builds, support, and expert advice.
        </p>
      </div>

      <!-- Column 2: Quick Links -->
      <div>
        <h3 class="text-lg font-semibold mb-3 text-purple-600">Quick Links</h3>
        <ul class="space-y-2 text-sm">
          <li>
            <RouterLink to="/" class="hover:text-purple-700">Home</RouterLink>
          </li>
          <li>
            <RouterLink to="/about" class="hover:text-purple-700">About</RouterLink>
          </li>
          <li>
            <RouterLink to="/service" class="hover:text-purple-700">Service</RouterLink>
          </li>
          <li>
            <RouterLink to="/contact" class="hover:text-purple-700">Contact</RouterLink>
          </li>
        </ul>
      </div>

      <!-- Column 3: Contact Info -->
      <div>
        <h3 class="text-lg font-semibold mb-3 text-purple-600">Contact Us</h3>
        <p class="text-sm">📍 Phnom Penh, Cambodia</p>
        <p class="text-sm">📞 +855 123 456 789</p>
        <p class="text-sm">✉️ info@mywebsite.com</p>

        <!-- Social Media -->
        <div class="flex space-x-4 mt-4">
          <a href="#" class="hover:text-purple-700 text-xl">🌐</a>
          <a href="#" class="hover:text-purple-700 text-xl">👍</a>
          <a href="#" class="hover:text-purple-700 text-xl">🐦</a>
          <a href="#" class="hover:text-purple-700 text-xl">📸</a>
        </div>
      </div>
    </div>

    <!-- Bottom Bar -->
    <div class="border-t mt-8 text-center py-4 text-sm text-gray-500">
      © 2025 MyWebsite. All rights reserved.
    </div>
  </footer>

</template>
