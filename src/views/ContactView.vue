<script setup>
import mapImg from '@/assets/images/p1.png' // or use a real map iframe
</script>

<template>
  <section class="bg-white text-gray-800">

    <!-- Hero Section -->
    <div class="bg-gradient-to-br from-blue-900 to-indigo-900 text-white py-24 text-center">
      <h1 class="text-5xl font-bold mb-2">Contact Us</h1>
      <p class="text-sm text-purple-200">Home / Contact</p>
    </div>

    <!-- Contact Info Cards -->
    <div class="max-w-7xl mx-auto grid sm:grid-cols-2 md:grid-cols-4 gap-6 px-6 py-16 text-center">
      <div class="bg-blue-50 p-6 rounded-lg shadow">
        <h2 class="text-blue-600 text-lg font-semibold mb-2">📍 Location</h2>
        <p class="text-sm">Sunshine Business Park, Sector 94, Poland</p>
      </div>
      <div class="bg-blue-50 p-6 rounded-lg shadow">
        <h2 class="text-blue-600 text-lg font-semibold mb-2">📞 Contact</h2>
        <p class="text-sm">+800 555-0198<br />+800 555-0117</p>
      </div>
      <div class="bg-blue-50 p-6 rounded-lg shadow">
        <h2 class="text-blue-600 text-lg font-semibold mb-2">📧 Email</h2>
        <p class="text-sm">techco@example.com<br />gmail@example.com</p>
      </div>
      <div class="bg-blue-50 p-6 rounded-lg shadow">
        <h2 class="text-blue-600 text-lg font-semibold mb-2">⏰ Visit</h2>
        <p class="text-sm">Mon–Sat: 8:00–5:00<br />Sunday: Closed</p>
      </div>
    </div>

    <!-- Contact Form + Map -->
    <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-10 px-6 py-10 items-start">
      <!-- Form -->
      <form class="bg-white shadow-md rounded-lg p-6 space-y-4">
        <h2 class="text-2xl font-bold text-gray-700 mb-4">Send Us A Message</h2>
        <div class="grid sm:grid-cols-2 gap-4">
          <input type="text" placeholder="Full Name" class="p-3 border rounded w-full" />
          <input type="email" placeholder="Your Email" class="p-3 border rounded w-full" />
        </div>
        <input type="text" placeholder="Your Phone" class="p-3 border rounded w-full" />
        <textarea rows="4" placeholder="Message" class="p-3 border rounded w-full"></textarea>
        <button class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700 transition">
          Send Message →
        </button>
      </form>

      <!-- Map -->
      <div>
        <iframe
          class="w-full h-full min-h-[400px] rounded-lg shadow"
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d387190.2799145322!2d-74.25987684717478!3d40.697670063350424!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzTCsDQxJzU0LjYiTiA3NMKwMTUnMjQuNCJX!5e0!3m2!1sen!2sus!4v1630597593522!5m2!1sen!2sus"
          allowfullscreen=""
          loading="lazy"
        ></iframe>
      </div>
    </div>

    <!-- Call To Action -->
    <div class="bg-blue-950 text-white py-16 text-center">
      <h2 class="text-3xl font-bold mb-2">Ready to Work, Let's Chat</h2>
      <p class="text-blue-300 mb-6">
        Our team of experts is ready to collaborate with you at every step.
      </p>
      <RouterLink
        to="/contact"
        class="inline-block px-6 py-2 bg-blue-600 rounded hover:bg-blue-700 transition"
      >
        Contact Us Today →
      </RouterLink>
    </div>

  </section>
</template>
