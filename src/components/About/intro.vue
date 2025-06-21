<template>
    <div class="max-w-7xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-10 items-center">
        <div>
            <img :src="expert1" alt="Team" class="rounded-lg shadow" />
        </div>
        <div>
            <h2 class="text-sm uppercase text-orange-500 font-bold mb-2">About Us</h2>
            <h1 class="text-3xl font-bold mb-4">We Are Business Consultants Dedicated To Driving Your Success</h1>
            <p class="text-gray-600 mb-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus,
                luctus nec ullamcorper mattis.</p>
            <p class="italic text-gray-500 mb-4">"Lorem ipsum dolor sit amet, consectetur adipiscing elit."</p>
            <p class="text-sm text-gray-700 flex items-center gap-2 mb-2">
                ✅ 15+ Years of Experience
            </p>
            <button class="mt-4 px-6 py-2 bg-orange-500 text-white rounded hover:bg-orange-600 transition">Learn
                More</button>
        </div>
    </div>
</template>

<script setup>
const props = defineProps({
  expert1: {
    type: String,
    required: true
  }
})
</script>
