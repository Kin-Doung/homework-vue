<template>
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
</template>

<script setup>
const props = defineProps({
    infor: {
        type: String,
        required: true
    }
});
</script>