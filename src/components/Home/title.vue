<template>
  <div
    class="flex justify-center mx-auto mt-5 bg-white rounded-2xl max-w-7xl w-full p-8 flex-col md:flex-row items-center gap-8"
  >
    <!-- Left: Text Section -->
    <div class="md:w-1/2 text-center md:text-left">
      <h1 class="text-3xl font-bold text-purple-700 mb-4">Computers</h1>
      <p class="text-gray-600">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minus aliquam delectus necessitatibus, aperiam voluptatem excepturi similique odio hic libero earum perferendis eos. Possimus facilis veniam velit praesentium sunt nobis voluptatum. Aperiam molestias dolor sint exercitationem qui, explicabo atque quam iure!
      </p>
      <button
        class="mt-6 px-6 py-2 bg-purple-600 text-white rounded-lg shadow hover:bg-purple-700 transition duration-300"
      >
        Read More
      </button>
    </div>

    <!-- Right: Show only first card's image -->
    <div class="md:w-1/2" v-if="cards.length > 0">
      <img :src="cards[0].image" alt="Computer" class="w-45 rounded-lg shadow-md object-cover" />
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
