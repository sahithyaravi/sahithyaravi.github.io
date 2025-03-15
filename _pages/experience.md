---
title: "Experience"
permalink: /experience/
author_profile: false
---

<style>
  /* Timeline container */
  .timeline {
    position: relative;
    max-width: 1000px;
    margin: 50px auto;
    padding-left: 10%;
  }

  /* Vertical line */
  .timeline::after {
    content: '';
    position: absolute;
    width: 4px;
    top: 0;
    bottom: 0;
    left: 10px;
    background: #ccc;
  }

  /* Individual timeline items */
  .timeline-item {
    position: relative;
    margin: 20px 0;
    padding-left: 40px;
  }

  /* Dots on the timeline */
  .timeline-item::before {
    content: '';
    position: absolute;
    top: 10px;
    left: 0;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    border: 4px solid white;
    background: #007bff;
    box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
  }

  /* Experience details */
  .experience-card {
    display: flex;
    align-items: center;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    background: white;
  }

  /* Experience logo */
  .experience-card img {
    width: 60px;
    height: 60px;
    object-fit: contain;
    margin-right: 15px;
  }
</style>

<div class="timeline">
  <!-- Experience 1 -->
  <div class="timeline-item">
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="FAIR Logo">
      <div>
        <h3>Research Intern, FAIR Communication and Language</h3>
        <p class="date"><strong>Summer 2024</strong></p>
        <ul>
          <li>Text-guided avatar generation based on social norms</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 2 -->
  <div class="timeline-item">
    <div class="experience-card">
      <img src="../images/msr_logo.jpeg" alt="Microsoft Research Logo">
      <div>
        <h3>Research Intern, Microsoft Research, HCAIX Group</h3>
        <p class="date"><strong>Summer 2024</strong></p>
        <ul>
          <li>Evaluating spatial reasoning abilities of Vision Language Models across multiple frames</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 3 -->
  <div class="timeline-item">
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="Meta Reality Labs Logo">
      <div>
        <h3>AI Research Scientist Intern, Meta Reality Labs</h3>
        <p class="date"><strong>Summer 2023</strong></p>
        <ul>
          <li>Distillation from Large Language Models (LLMs) to Small Language Models (SLMs)</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 4 -->
  <div class="timeline-item">
    <div class="experience-card">
      <img src="../images/ubc_cs_logo.png" alt="UBC Logo">
      <div>
        <h3>Research Assistant, UBC NLP Group</h3>
        <p class="date"><strong>2021 - Present</strong></p>
        <ul>
          <li>Commonsense, abductive, and counterfactual reasoning in Vision Language tasks</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 5 -->
  <div class="timeline-item">
    <div class="experience-card">
      <img src="../images/openml_logo.png" alt="OpenML Logo">
      <div>
        <h3>AI Research Engineer, OpenML & TU/e</h3>
        <p class="date"><strong>2019 - 2021</strong></p>
        <ul>
          <li>Core developer for OpenML and AutoML research infrastructure</li>
          <li>Developed meta-learning approaches for AutoML experiment selection</li>
        </ul>
      </div>
    </div>
  </div>
</div>
