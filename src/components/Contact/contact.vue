<template>
    <div class="bg-gradient-to-br from-blue-900 to-indigo-900 text-white py-24 text-center">
        <h1 class="text-5xl font-bold mb-2">Contact Us</h1>
    </div>
</template>

<script setup>
  const props = defineProps({
    contact: {
        type: String,
        required: true
    }
  });
</script>