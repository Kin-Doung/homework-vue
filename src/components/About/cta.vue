<template>
    <div class="bg-blue-800 text-white py-16 text-center px-6">
        <h2 class="text-3xl font-bold mb-4">Let's Discuss Your Business Goals</h2>
        <p class="text-blue-200 mb-6">Schedule a free consultation with our expert team today.</p>
        <RouterLink to="/contact"
            class="inline-block px-6 py-2 bg-orange-500 text-white rounded hover:bg-orange-600 transition">
            Get a Quote →
        </RouterLink>
    </div>
</template>

<script setup>
    const props = defineProps({
        title:{
            type: String,
            required: true
        }
    });
</script>