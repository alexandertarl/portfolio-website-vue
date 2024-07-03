<template>
  <main>

  <WelcomeItem>
    <h1>My Art Portfolio</h1>
    <h2 class="green">Traditional Art</h2>
    Painted using Oil or Acrylic Paint <br/>
    <img class="digital" src="../assets/cat1.jpeg" alt="Drawing of a cat 1" />
    <img class="digital" src="../assets/cat2.jpeg" alt="Drawing of a cat 2" />
    <img class="digital" src="../assets/cat3.jpeg" alt="Drawing of a cat 3" />
    <img class="digital" src="../assets/girl and cat.jpeg" alt="Drawing of a cat and woman" />
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Digital Art</h2>
    Drawn using Clip Studio Paint or HeavyPaint <br/>
    <img class="digital" src="../assets/cat.jpg" alt="Drawing of a cat" />
    <img class="digital" src="../assets/banana.png" alt="Drawing of a banana" />
    <img class="digital" src="../assets/conan.png" alt="Drawing of a man" />
    <img class="digital" src="../assets/girl.png" alt="Drawing of a woman" />
    <img class="digital" src="../assets/rx7.png" alt="Drawing of a car" />
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

  .digital {
    height: 200px;
  }
</style>
  
<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
</script>