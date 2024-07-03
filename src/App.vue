<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import '@fortawesome/fontawesome-free/css/all.css';

const shareOnGitHub = () => {
  window.open('https://github.com/alexandertarl');
};

const shareOnLinkedIn = () => {
  window.open('https://www.linkedin.com/in/alexander-tarling-576613230/');
};

const copyEmail = () => {
  navigator.clipboard.writeText("tarlingalex@gmail.com");
  alert("Email Address Copied");
}
</script>

<template>
  <header>
    <img alt="Self-drawn art of me" class="logo" src="@/assets/me.png" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Hi, It's Alex!" />

      <div>
        <nav>
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
          <RouterLink to="/projects">Projects</RouterLink>
          <RouterLink to="/art-portfolio">Art Portfolio</RouterLink>
          <RouterLink to="/languages">Languages</RouterLink>
        </nav>
      </div>

      <div class="social-share-buttons">
        <button @click="shareOnGitHub" class="btn btn-github">
          <i class="fab fa-github"></i>
        </button>
        <button @click="shareOnLinkedIn" class="btn btn-linkedin">
          <i class="fab fa-linkedin"></i>
        </button>
        <button @click="copyEmail" class="btn btn-email">
          <i class="fa-solid fa-envelope"></i> 
          <p>tarlingalex@gmail.com</p>
        </button>
      </div>

    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}

.social-share-buttons {
  display: flex;
  gap: 10px;
}

.btn {
  display: inline-flex;
  align-items: center;
  padding: 10px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

.btn-github {
  background-color: #333;
  color: white;
}

.btn-linkedin {
  background-color: #0077b5;
  color: white;
}

.btn-email {
  background-color: #a21a38;
  color: white;
}

.btn p {
  font-size: 14px;
  margin-left: 6px; 
}

.btn i {
  /* margin-right: 5px; */
  font-size: 20px;
}

</style>
