<template>
  <main>
  <WelcomeItem>
    <h1>University Projects</h1>
    <h2 class="green">Dissertation Group Project (2024)</h2>
    Team of 6... 
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Engineering Data... (2023)</h2>
    Team of 5... 
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">...</h2>
    ...
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