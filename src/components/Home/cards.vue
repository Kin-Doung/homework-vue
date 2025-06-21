<template>
  <div class="grid grid-cols-1 h-50 sm:grid-cols-2 md:grid-cols-4 gap-7 p-3 w-3/3 mx-auto mt-5">
    <div
      v-for="(card, index) in cards"
      :key="index"
      class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition duration-300 mt-6"
    >
      <img :src="card.image" alt="Card Image" class="w-44 h-40 mx-auto object-cover" />

      <div class="p-4">
        <h1 class="text-lg font-semibold text-purple-700">{{ card.name }}</h1>
        <p>{{ card.title }}</p>
      </div>
      <button
        class="bg-purple-600 text-white py-2 px-4 hover:bg-purple-700 transition duration-300 mb-5 ml-4 rounded-[10px]"
      >
        Buy Now
      </button>
    </div>
  </div>
</template>

<script setup>

const props = defineProps({
  cards: {
    type: Array,
    default: () => []
  }
})
</script>
