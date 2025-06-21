<template>

  <div
    class=" flex justify-center mx-auto mt-5 bg-white rounded-2xl max-w-7xl w-full p-8 flex flex-col md:flex-row items-center gap-8">

    <!-- Left: Text Section -->
    <div class="md:w-2/2 text-center md:text-left">
      <h1 class="text-3xl font-bold text-purple-700 mb-4">Computers</h1>
      <p class="text-gray-600">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti enim beatae molestiae ratione unde ducimus, voluptas et sed aperiam quae expedita eum voluptatibus rem optio nam, magnam nobis accusamus iusto a facere inventore animi! Impedit, sapiente? Architecto voluptas enim delectus!
      </p>

      <button
        class="mt-6 px-6 py-2 bg-purple-600 text-white rounded-lg shadow hover:bg-purple-700 transition duration-300">
        Read More
      </button>
    </div>
    <div class="md:w-1/2">
      <img src="../assets/images/p1.png" alt="Computer" class="w-full rounded-lg shadow-md object-cover" />
    </div>
  </div>

  <div class="grid grid-cols-1 h-50 sm:grid-cols-2 md:grid-cols-4 gap-7 p-3 w-3/3 mx-auto mt-5">
    <div v-for="(card, index) in cards" :key="index"
      class="bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition duration-300 mt-6">
      <img :src="card.image" alt="Card Image" class="w-44 h-40 mx-auto object-cover" />

      <div class="p-4">
        <h1 class="text-lg font-semibold text-purple-700">{{ card.name }}</h1>
        <p>{{ card.title }}</p>
      </div>
      <button class="bg-purple-600 text-white py-2 px-4 hover:bg-purple-700 transition duration-300 mb-5 ml-4 rounded-[10px]">
        Buy Now
      </button>
    </div>
  </div>


</template>

<script setup>

import p1 from '../assets/images/p1.png'
import p2 from '../assets/images/p2.png'
import p3 from '../assets/images/p3.png'
import p4 from '../assets/images/p4.png'
import p5 from '../assets/images/p5.png'
import p6 from '../assets/images/p6.png'


const cards = [
  { name: 'Gaming PC', image: p1, title: 'You can read it for imformation that you need to know about it'},
  { name: 'Workstation', image: p2, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Laptop', image: p3, title: 'You can read it for imformation that you need to know about it'},
  { name: 'Laptop', image: p4, title: 'You can read it for imformation that you need to know about it'},
  { name: 'Laptop', image: p5, title: 'You can read it for imformation that you need to know about it'},
  { name: 'Laptop', image: p6, title: 'You can read it for imformation that you need to know about it'},
  { name: 'Laptop', image: p2, title: 'You can read it for imformation that you need to know about it'},
  { name: 'Laptop', image: p2, title: 'You can read it for imformation that you need to know about it'},
]
</script>
