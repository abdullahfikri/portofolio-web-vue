<script setup>
import Navbar from "@/components/Navbar.vue";
import Home from '@/views/Home.vue'
import Tech from "@/views/Tech.vue";
import About from "@/views/About.vue";
import Project from "@/views/Project.vue";
import Testimonials from "@/views/Testimonials.vue";
import Contact from "@/views/Contact.vue";
import Footer from "@/views/Footer.vue";
</script>

<template>
  <div class="bg-white font-[Inter]">
    <Navbar />

    <main>
      <Home />
      <Tech />
      <About />
      <Project />
      <Testimonials />
      <Contact />
    </main>
    <Footer />
  </div>
</template>

<style scoped>

</style>
