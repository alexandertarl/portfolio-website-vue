<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
</script>

<template>
  <WelcomeItem>
    <template #heading>Brief Introduction</template>
    I'm a graduate Software Engineer with a passion for all things coding and spoken/foreign languages. 
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>Coding Languages Experience</template>
    Python  <br/>
    Java  <br/>
    Javascript and Typescript  <br/>
    C#
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>Foreign Language Proficiency</template>
    English - Native Speaker <br/>
    Korean - Lower Intermediate <br/>
    German - Upper Beginner <br/>
    Italian - Soon!
  </WelcomeItem>
</template>
