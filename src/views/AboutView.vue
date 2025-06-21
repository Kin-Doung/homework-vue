<script setup>
import Hero from '../components/About/hero.vue'
import Intro from '../components/About/intro.vue'
import Principles from '../components/About/principles.vue'
import Team from '../components/About/team.vue'
import CTA from '../components/About/cta.vue'

import heroImg from '@/assets/images/p1.png'
import expert1 from '@/assets/images/p2.png'
import expert2 from '@/assets/images/p3.png'
import expert3 from '@/assets/images/p4.png'
</script>

<template>
  <section class="bg-white text-gray-800">
    <!-- Hero Section -->
    <Hero Hero :heroImg="heroImg" />
    <!-- Intro Section -->
    <Intro Intro :expert1="expert1" />
    <!-- Principles Section -->
    <Principles title :title="title" />
    <!-- Team Section -->
    <Team :expert1="expert1" :expert2="expert2" :expert3="expert3" />
    <!-- CTA -->
    <CTA title :title="title"/>
  </section>
</template>
