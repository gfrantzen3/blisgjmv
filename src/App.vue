<script setup>
import { ref } from 'vue';
</script>

<template>
  <div class="container">
    <header>
      <h1>BLIS Enhancement Project</h1>
    </header>
    <section>
      <h2>Project Description</h2>
      <p>This project aims to enhance the Basic Laboratory Information System (BLIS) by improving system robustness, integrating various technologies for better interoperability, ensuring scalability, and facilitating easy deployment on AWS EC2.</p>
    </section>
    <section>
      <h2>Team Members & Roles</h2>
      <ul>
        <li>Greg Frantzen - Web & Backend Development, AWS EC2 Management. Focus on translating stakeholder requirements into deliverables.</li>
        <li>Jane Bian - Data Analysis and Visualization, Project Review. Aiming to understand information systems for patient/lab tracking and identify challenges in medical data management.</li>
        <li>Mobolaji Moronfolu - Full Stack Development, Stakeholder Liaison. Committed to implementing stakeholder needs and deploying BLIS online through Test-Driven Development and managing codebase bugs.</li>
        <li>Vinay Easwaran - Full Stack Development, BLIS Software Improvement. Dedicated to improving BLIS software onboarding and adjusting reporting tools for user reusability, with a focus on understanding BLIS laboratory usage.</li>
      </ul>
    </section>
    <section>
      <h2>Overall Project Goal</h2>
      <p>Our goal is to make BLIS more robust, user-friendly, and scalable. We aim to ensure that BLIS can be easily deployed and managed on cloud platforms, specifically AWS EC2, enhancing its accessibility and efficiency for laboratories worldwide.</p>
    </section>
    <section>
      <h2>Presentation</h2>
      <p>View our detailed slideshow presentation about the BLIS Enhancement Project:</p>
      <a href="https://docs.google.com/presentation/d/1aOrrnlOiMtO_LzYY9Atqs4fNKH66W1EoaBbpRdHgyao/edit?usp=sharing" target="_blank">BLIS Enhancement Project Presentation</a>
    </section>
    <section>
      <h2>Presentation Video</h2>
      <p>Watch our presentation video for an in-depth discussion on the BLIS Enhancement Project:</p>
      <a href="https://gtvault-my.sharepoint.com/:v:/g/personal/veaswaran3_gatech_edu/EZJQ4Putc_9MhoBDkheT7KUBjnPkk6kYIpcoZMmcUinyPg?referrer=Teams.TEAMS-WEB&referrerScenario=MeetingChicletGetLink.view.view" target="_blank">BLIS Enhancement Project Video</a>
    </section>
    <section>
      <h2>Weekly Updates</h2>
      <p>Last week we added the functionality for customised fields to be exported. Challenges: A team member leaving us. Data issues when testing our new functionality.</p>
    </section>
    <section>
      <h2>Survey Link</h2>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSe7oTxBJ9mQbkSNKZKJEh14CUAYXsjnTIzT4wgUyUKAjmdomA/viewform?usp=sharing">Survey Link</a>
    </section>
    <section>
      <h2>Project Link in Cloud</h2>
      <a href="http://164.92.110.13/login.php">Project Link</a>
    </section>
    <section>
      <h2>Lighthouse Scores</h2>
      <p>Performance: 100, Accessibility: 100, Best Practices: 100, SEO: 91</p>
      <p>Note: These are preliminary scores and subject to change as we progress in the project.</p>
    </section>
  </div>
</template>

<style scoped>
.container {
  max-width: 800px;
  margin: auto;
  padding: 20px;
  background-color: #f0f0f0; /* Light grey background */
}

h1, h2, p, li {
  color: #333; /* Dark grey text color for better readability */
}

h1 {
  color: #1976D2; /* Slightly darker blue for headers */
}

ul {
  list-style-type: none;
  padding: 0;
}
</style>
