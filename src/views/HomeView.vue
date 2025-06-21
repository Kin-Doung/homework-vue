<template>
  <Title Title :cards="cards"/>
  <Home Home :cards="cards"/>
</template>

<script setup>
import Home from '@/components/Home/cards.vue'
import Title from '@/components/Home/title.vue'

import p1 from '../assets/images/p1.png'
import p2 from '../assets/images/p2.png'
import p3 from '../assets/images/p3.png'
import p4 from '../assets/images/p4.png'
import p5 from '../assets/images/p5.png'
import p6 from '../assets/images/p6.png'


const cards = [
  { name: 'Gaming PC', image: p1, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Workstation', image: p2, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Laptop', image: p3, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Laptop', image: p4, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Laptop', image: p5, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Laptop', image: p6, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Laptop', image: p2, title: 'You can read it for imformation that you need to know about it' },
  { name: 'Laptop', image: p2, title: 'You can read it for imformation that you need to know about it' },
]
</script>
