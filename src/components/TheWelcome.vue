<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
</script>

<template>
  <WelcomeItem>
    <template #heading>Brief Introduction</template>
    I'm a graduate Software Engineer with a passion for all things coding as well as foreign languages. 
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>Coding Languages Experience</template>
    Python - Longest exposure and practice with  <br/>
    Java - Used the most at University <br/>
    Javascript and Typescript - During a few projects at University <br/>
    SQL - Lots of practice <br/>
    C# - Some practice as learnt on my own
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>Foreign Language Proficiency</template>
    English - Native Speaker <br/>
    Korean - Lower Intermediate <br/>
    German - Upper Beginner <br/>
  </WelcomeItem>
</template>
