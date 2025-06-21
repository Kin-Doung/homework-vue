<template>
    <h2 class="text-3xl font-bold text-center text-gray-800 mb-8">Our Services</h2>
    <p class="text-center text-gray-600 mb-12">We have over 25 years of experience.</p>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-teal-500 text-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-2">01. Idea Generate</h3>
            <p class="text-gray-200">Lorem ipsum dolor sit amet consectetur adipiscing elit sed diam nonummy nibh.
            </p>
        </div>
        <div class="bg-gray-800 text-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-2">02. Free Consultancy</h3>
            <p class="text-gray-200">Lorem ipsum dolor sit amet consectetur adipiscing elit sed diam nonummy nibh.
            </p>
        </div>
        <div class="bg-teal-500 text-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-2">03. Best Services</h3>
            <p class="text-gray-200">Lorem ipsum dolor sit amet consectetur adipiscing elit sed diam nonummy nibh.
            </p>
        </div>
        <div class="bg-gray-800 text-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-2">04. Idea Generate</h3>
            <p class="text-gray-200">Lorem ipsum dolor sit amet consectetur adipiscing elit sed diam nonummy nibh.
            </p>
        </div>
        <div class="bg-teal-500 text-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-2">05. Free Consultancy</h3>
            <p class="text-gray-200">Lorem ipsum dolor sit amet consectetur adipiscing elit sed diam nonummy nibh.
            </p>
        </div>
        <div class="bg-gray-800 text-white p-6 rounded-lg shadow-lg">
            <h3 class="text-xl font-semibold mb-2">06. Best Services</h3>
            <p class="text-gray-200">Lorem ipsum dolor sit amet consectetur adipiscing elit sed diam nonummy nibh.
            </p>
        </div>
    </div>
</template>

<script setup>
const props = defineProps({
    title: {
        type: String,
        required: true
    }
});
</script>