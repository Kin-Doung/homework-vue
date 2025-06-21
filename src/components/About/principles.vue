<template>
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
</template>

<script setup>
const props = defineProps({
    title:{
        type: String,
        required: true  
    }
});
</script>