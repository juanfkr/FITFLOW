<template>
  <header>
    <nav-bar />
  </header>
  <main>
    <hero-section />
    <about-us />
    <feedback-section />
    <plans-section />
  </main>
  <footer>
    <p>a</p>
  </footer>
</template>

<script setup>
import navBar from './components/nav-bar.vue';
import heroSection from './components/hero-section.vue';
import aboutUs from './components/about-us.vue';
import feedbackSection from './components/feedback-section.vue';
import plansSection from './components/plans-section.vue';

</script>


<style scoped>
main {
  display: flex;
  flex-direction: column;
  gap: 2em;
  margin: 2em;
}
</style>
