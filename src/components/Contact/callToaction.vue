<template>
    <div class="bg-blue-950 text-white py-16 text-center">
        <h2 class="text-3xl font-bold mb-2">Ready to Work, Let's Chat</h2>
        <p class="text-blue-300 mb-6">
            Our team of experts is ready to collaborate with you at every step.
        </p>
        <RouterLink to="/contact" class="inline-block px-6 py-2 bg-blue-600 rounded hover:bg-blue-700 transition">
            Contact Us Today →
        </RouterLink>
    </div>
</template>

<script setup>
const props = defineProps({
    call: {
        type: String,
        required: true
    }
});
</script>

