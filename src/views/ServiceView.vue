<template>
  <div class="container mx-auto px-4 py-12">
    <Title Title :title="title" />
    <Cards Cards :cards="cards" />
  </div>
</template>

<script setup>
import Title from '../components/Service/title.vue'
import Cards from '../components/Service/cards.vue'

</script>
