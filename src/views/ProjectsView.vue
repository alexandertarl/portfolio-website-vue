<template>
  <main class="scrollable">
    <WelcomeItem>
    <h1>Notable Coding Projects</h1>
    <h2 class="green">Portfolio Website (2024)</h2>
    <li>
      Developed in Vue JS because recent experience with Nuxt 3 meant I had better understanding of Vue of React.
    </li>
    <li>
      No backend as just displays static information
    </li>
    <a href="https://github.com/alexandertarl/portfolio-website-vue">Link to the Project's Repository </a>
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Dissertation Group Project for Cardiff University (2024)</h2>
    <li>
      Produced a website with University Chatbot which uses data from relevant Cardiff
      University websites/resources to respond to questions related to student life at Cardiff
      University. In addition, Cardiff University account holders were given further personal
      functionality.
    </li>
    <li>
      Used FastAPI (Python) and Nuxt 3 with multiple APIs.
    </li>
    <li>
      Implemented chat history saved based on a title generated using Mixtral AI. Conversations
      were saved into a Postgres database.
    </li>
    <li>
      Developed suggested questions that appear once the chatbot has responded, which are
      clickable and created using Mixtral AI
    </li>
    <li>
      Implemented the ability to share and make conversations public, so anyone could view the
      conversation when they had the unique URL
    </li>
    <li>
      Using NewRelic, I outputted Open Telemetry data as graphs using ChartJS on the admin
      page
    </li>
    <li>
      Deployed using Docker
    </li>
    <a href="https://cu-chatbot.kavin.rocks/">Link to the deployed project </a> <br>
    <a href="https://github.com/alexandertarl/dissertation-cardiffuni-chatbot">GitHub Repository link to my contribution</a>
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Team Client Project for Cardiff Univeristy School of Engineering (2023)</h2>
    <li>
      Produced a website to display energy visualisation graphs for the UK
    </li>
    <li>
      Using the MERN JavaScript stack
    </li>
    <li>
      Used Nivo as the library for creating graphs for gas and electricity data we were provided
      with, which was handled from .csv files
    </li>
    <li>
      Created the login page with backend functionality using AXIOS and JSON web tokens for
      authentication, and wrote tests using Jest
    </li>
    <li>
      Used GitLab for the CI/CD pipeline
    </li>
    <a href="https://github.com/alexandertarl/year3-client-project-1">GitHub Repository link to my contribution</a>
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Mobile Development Application (2023)</h2>
    <li>
      Book review application which used Google Books API for searching books titles based on
      user input
    </li>
    <li>
      Used Java and Gradle to build, with the Android Studio IDE
    </li>
    <li>
      Created input system that allowed users to record reviews of books and add a rating
    </li>
    <li>
      A list of favourited and want-to-read books in a separate tab
    </li>
    <li>
      Used JUnit for testing the application
    </li>
    <a href="https://github.com/alexandertarl/book-review-android-app">GitHub Repository link to my contribution</a>
  </WelcomeItem>

  <WelcomeItem>
    <h2 class="green">Team Client Project for Newport City Council (2022)</h2>
    <li>
      Produced a recycling website with a renting items marketplace
    </li>
    <li>
      Using Java and incorporating the Scrum Workflow, each team member had a week to lead
      as Scrum Master
    </li>
    <li>
      Implemented a CI/CD pipeline using Terraform and Jenkins
    </li>
    <li>
      Added cyber security fixes to secure the application
    </li>
    <li>
      Used MariaDB to update the database and get relevant records to post to the website
    </li>
    <a href="https://github.com/alexandertarl/year2-client-project">GitHub Repository link to my contribution</a>
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

/* .main {
    height: 100%;
   overflow-y: auto;
} */
</style>

<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
</script>