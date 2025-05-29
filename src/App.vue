<script setup>
  import HomeSection from './components/HomeSection.vue';
  import AboutSection from './components/AboutSection.vue';
  import NavHeader from './components/NavHeader.vue';
  import ServicesSection from './components/ServicesSection.vue';
  import FaqSection from './components/FaqSection.vue';
  import ContactSection from './components/ContactSection.vue';
</script>

<template>
  <a href="https://wa.me/5555999856973" target="_blank" class="fixed bottom-5 right-5 z-50">
    <img src="./assets/whatsapp-popup.png" alt="Chamar no WhatsApp" title="Chamar no WhatsApp"
      class="w-14 h-14 sm:w-16 sm:h-16 rounded-full shadow-md hover:scale-110 transition-transform duration-300 ease-in-out" />
  </a>
  <div class="text-gray-700 antialiased bg-white">
    <NavHeader />
    <HomeSection />
    <ServicesSection />
    <AboutSection />
    <FaqSection />
    <ContactSection />
  </div>
</template>

<style></style>
