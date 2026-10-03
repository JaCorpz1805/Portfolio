<script setup lang="ts">
import NavBar from '@/components/NavBar.vue'
import HeroSection from '@/components/HeroSection.vue'
import AboutSection from '@/components/AboutSection.vue'
import ProjectsSection from '@/components/ProjectsSection.vue'
import SkillsSection from '@/components/SkillsSection.vue'
import FooterSection from '@/components/FooterSection.vue'
</script>

<template>
  <NavBar />
  <main>
    <HeroSection />
    <AboutSection />
    <ProjectsSection />
    <SkillsSection />
  </main>
  <FooterSection />
</template>
