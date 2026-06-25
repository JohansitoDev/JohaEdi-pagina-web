<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import TechFeatures from './components/TechFeatures.vue'
import ContributeInstall from './components/ContributeInstall.vue'
</script>

<template>
  <div class="bg-hacker-bg text-hacker-text min-h-screen antialiased selection:bg-hacker-neon selection:text-black">
    <Navbar />
    
    <main>
      <Hero />
      <TechFeatures />
      <ContributeInstall />
    </main>

    <footer class="border-t border-hacker-border/40 py-8 bg-black text-center text-xs text-gray-600 font-mono">
      <p>JohaEdi Core &copy; 2026. Diseñado y Desarrollado por Johan Mancebo.</p>
      <p class="mt-1 text-hacker-border">Código fuente disponible públicamente en mi cuenta oficial de GitHub.</p>
    </footer>
  </div>
</template>

<style>

:root {
  --hacker-bg: #050a05;
  --hacker-card: #0a140a;
  --hacker-border: #1f5f0f;
  --hacker-neon: #39ff14;
  --hacker-text: #b0e0b0;
}

body {
  background-color: var(--hacker-bg);
}


.bg-hacker-bg { background-color: var(--hacker-bg); }
.bg-hacker-card { background-color: var(--hacker-card); }
.border-hacker-border { border-color: var(--hacker-border); }
.border-hacker-neon { border-color: var(--hacker-neon); }
.text-hacker-neon { color: var(--hacker-neon); }
.text-hacker-text { color: var(--hacker-text); }
</style>