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
      <h2>Lighthouse Scores</h2>
      <p>Performance: XX, Accessibility: XX, Best Practices: XX, SEO: XX</p>
      <p>Note: These are preliminary scores and subject to change as we progress in the project.</p>
    </section>
  </div>
</template>

<style scoped>
.container {
  max-width: 800px;
  margin: auto;
  padding: 20px;
}

h1, h2 {
  color: #2c3e50;
}

p, li {
  color: #34495e;
}

ul {
  list-style-type: none;
  padding: 0;
}
</style>
