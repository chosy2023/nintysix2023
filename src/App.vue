<template>
  <div class="font-sans text-gray-800">
    <HeroSection />
    <ResumeSection />
    <ContactSection />
  </div>
</template>

<script setup>
import HeroSection from './components/HeroSection.vue'
import ResumeSection from './components/ResumeSection.vue'
import ContactSection from './components/ContactSection.vue'
</script>

<style>
/* 전역 스타일은 Tailwind 사용을 권장하지만 필요한 경우 여기에 추가 */
</style>
