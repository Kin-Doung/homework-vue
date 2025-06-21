<template>

    <div class="mt-12 text-center">
        <h3 class="text-2xl font-bold text-gray-800 mb-4">Our Popular Services</h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-white p-6 rounded-lg shadow-lg">
                <img src="@/assets/images/p2.png" alt="Financial Planning"
                    class="w-full h-48 object-cover rounded-t-lg">
                <h4 class="text-xl font-semibold mt-4">Financial Planning</h4>
                <p class="text-gray-600 mt-2">Facilitat vero eros et accumsan odio idlisis.</p>
                <a href="#" class="text-teal-500 mt-4 inline-block">Continue Reading &rarr;</a>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-lg">
                <img src="@/assets/images/p3.png" alt="Investment Advisor"
                    class="w-full h-48 object-cover rounded-t-lg">
                <h4 class="text-xl font-semibold mt-4">Investment Advisor</h4>
                <p class="text-gray-600 mt-2">Facilitat vero eros et accumsan odio idlisis.</p>
                <a href="#" class="text-teal-500 mt-4 inline-block">Continue Reading &rarr;</a>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-lg">
                <img src="@/assets/images/p4.png" alt="Saving Money" class="w-full h-48 object-cover rounded-t-lg">
                <h4 class="text-xl font-semibold mt-4">Saving Money</h4>
                <p class="text-gray-600 mt-2">Facilitat vero eros et accumsan odio idlisis.</p>
                <a href="#" class="text-teal-500 mt-4 inline-block">Continue Reading &rarr;</a>
            </div>
        </div>
    </div>

</template>

<script setup>
const props = defineProps({
    cards: {
        type: String,
        required: true
    }
});
</script>