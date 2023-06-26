<script setup lang="ts">
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Jumbotron from './components/Jumbotron.vue'
import SiteSection from './components/SiteSection.vue'
const yearNow = new Date().getFullYear().toString()
</script>

<template>
  <Header />
  <Jumbotron />
  <SiteSection />
  <Footer :year="yearNow" />
</template>

<style scoped>

</style>
