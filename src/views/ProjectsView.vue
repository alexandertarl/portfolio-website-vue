<template>
  <main>
  <h1>University Projects</h1>
  <WelcomeItem>
    <template #heading>Dissertation Group Project (2024)</template>
    Team of 6... 
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>Engineering Data... (2023)</template>
    Team of 5... 
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>...</template>
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