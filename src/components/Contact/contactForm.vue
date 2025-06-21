<template>
    <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-10 px-6 py-10 items-start">
        <!-- Form -->
        <form class="bg-white shadow-md rounded-lg p-6 space-y-4">
            <h2 class="text-2xl font-bold text-gray-700 mb-4">Send Us A Message</h2>
            <div class="grid sm:grid-cols-2 gap-4">
                <input type="text" placeholder="Full Name" class="p-3 border rounded w-full" />
                <input type="email" placeholder="Your Email" class="p-3 border rounded w-full" />
            </div>
            <input type="text" placeholder="Your Phone" class="p-3 border rounded w-full" />
            <textarea rows="4" placeholder="Message" class="p-3 border rounded w-full"></textarea>
            <button class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700 transition">
                Send Message →
            </button>
        </form>

        <!-- Map -->
        <div>
            <iframe class="w-full h-full min-h-[400px] rounded-lg shadow"
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d387190.2799145322!2d-74.25987684717478!3d40.697670063350424!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzTCsDQxJzU0LjYiTiA3NMKwMTUnMjQuNCJX!5e0!3m2!1sen!2sus!4v1630597593522!5m2!1sen!2sus"
                allowfullscreen="" loading="lazy"></iframe>
        </div>
    </div>
</template>

<script setup>
const props = defineProps({
    contactForm: {
        type: String,
        required: true
    }
});
</script>