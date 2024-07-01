<template>
  <main>
  <WelcomeItem>
    <template #heading>Software Engineering Experience</template>
    - Python with generative AI <br/>
    ... (from old cv)
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
