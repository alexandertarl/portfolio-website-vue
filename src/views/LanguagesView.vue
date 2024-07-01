<template>
  <main>
      <h1>My Journey with Lanuages</h1>

  <WelcomeItem>
    <template #heading>Korean</template>
    Started in 2017 when I learned the alphabet but it continued further. Struggled to find consistency with it as I was doing GCSEs and Alevels and eventually Univeristy.
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>German</template>
    Started briefly in 2022 but restarted in 2024 ... <br/>
    German books read: 
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