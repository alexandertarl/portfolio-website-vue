<template>
  <main>

  <WelcomeItem>
    <h1>My Journey with Lanuages</h1>
    <h2 class="green">Korean/한국어</h2>
    Started in 2017 when I learned the alphabet, but continued to learn the language itself. 
    Struggled to find consistency with it as I was doing GCSEs, A-Levels, and Univeristy since I started studying it.
    I Currently have less motivation for it, so I am not focusing on it.
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Mandarin Chinese/简体中文</h2>
    Studied to upper beginner level around 2019, but have not picked it up since so my level is a lot lower.
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">German/Deutsch</h2>
    Started briefly in 2022 but restarted in 2024. German is currently my main focus as I spend lots of time reading and listening to native content. 
    I am probably an upper beginner level, but will continue to focus on it until I read lower intermediate. <br/> <br/>
    <h3>German Books I Have Read: </h3>
    <li>Der Fantastische Mr. Fox (Fantastic Mr Fox, German Edition)</li>
    <li>Heartstopper Volume 1 German Edition</li>
    <li>Nick und Charlie (Nick and Charlie, German Edition)</li>
    <li>Die Geschichte von Herrn Sommer (The Story of Mr Sommer)</li>
    <li>Heartstopper Volume 2 German Edition</li>
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Italian/Italiano</h2>
    My next language, and I have just started learning in July 2024.
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