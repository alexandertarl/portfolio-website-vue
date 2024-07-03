<template>
  <main>

  <WelcomeItem>
    <h1>My Art Portfolio</h1>
    <h2 class="green">Traditional Art</h2>
    images
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Digital Art</h2>
    images
  </WelcomeItem>
  </main>
  </template>
  
  <style>
  @media (min-width: 1024px) {
    .about {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  
  <script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
</script>