<template>
    <div class="max-w-7xl mx-auto px-6 py-16">
        <h2 class="text-sm uppercase text-orange-500 font-bold mb-2">Meet the Experts</h2>
        <h1 class="text-3xl font-bold mb-10">Discover Our Team Of Head Business Consultant Experts</h1>
        <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-6">
            <div v-for="(img, i) in [expert1, expert2, expert3]" :key="i"
                class="bg-white rounded-lg overflow-hidden shadow">
                <img :src="img" class="w-full h-64 object-cover" />
                <div class="p-4">
                    <h3 class="font-bold text-lg">Expert {{ i + 1 }}</h3>
                    <p class="text-sm text-gray-500">Senior Consultant</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
const props = defineProps({
    expert1: {
        type: Array,
        default: () => []
    },
    expert2: {
        type: Array,
        default: () => []
    },
    expert3: {
        type: Array,
        default: () => []
    }
})

</script>