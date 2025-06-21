<script setup>
import Contact from '../components/Contact/contact.vue'
import Infor from '../components/Contact/infor.vue'
import ContactForm from '../components/Contact/contactForm.vue'
import Call from '../components/Contact/callToaction.vue'
import mapImg from '@/assets/images/p1.png' // or use a real map iframe
</script>

<template>
  <section class="bg-white text-gray-800">

    <!-- Hero Section -->
     <Contact contact :contact="contact"/>
    <!-- Contact Info Cards -->
    <Infor infor :infor="infor"/>
    <!-- Contact Form + Map -->
    <ContactForm contactForm :contactForm="contactForm"/>
    <!-- Call To Action -->
    <Call call :call="call"/>
  </section>
</template>
