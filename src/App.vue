<script setup lang="ts">
import About from "./components/About.vue"
import NavBar from "./components/NavBar.vue"
import Projects from "./components/Projects.vue";
import Contact from "./components/Contact.vue";
import aFooter from "./components/Footer.vue";
</script>

<template>
  <header>
    <NavBar />
  </header>

  <main>
    <About />
    <Projects />
    <Contact />

  </main>
  <footer>
    <aFooter />
  </footer>
</template>

<style scoped>

@media (max-width: 1024px) {
}
</style>
