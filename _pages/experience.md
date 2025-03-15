---
title: "Experience"
permalink: /experience/
author_profile: true
---

<style>
/* Timeline container */
.timeline {
  position: relative;
  max-width: 1000px;
  margin: 50px auto;
}

/* Vertical line */
.timeline::after {
  content: '';
  position: absolute;
  width: 4px;
  top: 0;
  bottom: 0;
  left: 50%;
  background: #ccc;
  transform: translateX(-50%);
}

/* Individual timeline items */
.timeline-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: relative;
  margin: 30px 0;
}

/* Timeline symbol (diamond) */
.timeline-item::before {
  content: '\25C6'; /* Unicode for a diamond (◆) */
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  font-size: 18px;
  color: #007bff;
  background: white;
  padding: 2px;
}

/* Left side (Year) */
.timeline-year {
  flex: 1;
  text-align: right;
  font-weight: bold;
  padding-right: 30px;
}

/* Right side (Experience card) */
.experience-card {
  flex: 3;
  display: flex;
  align-items: center;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  background: #f3e3e3;
  margin-left: 50px; /* Ensures spacing from the timeline */
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
    <div class="timeline-year">Summer 2024</div>
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="FAIR Logo">
      <div>
        <h3>Research Intern, FAIR Communication and Language</h3>
        <ul>
          <li>Text-guided avatar generation based on social norms</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 2 -->
  <div class="timeline-item">
    <div class="timeline-year">Summer 2024</div>
    <div class="experience-card">
      <img src="../images/msr_logo.jpeg" alt="Microsoft Research Logo">
      <div>
        <h3>Research Intern, Microsoft Research, HCAIX Group</h3>
        <ul>
          <li>Evaluating spatial reasoning abilities of Vision Language Models across multiple frames</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 3 -->
  <div class="timeline-item">
    <div class="timeline-year">Summer 2023</div>
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="Meta Reality Labs Logo">
      <div>
        <h3>AI Research Scientist Intern, Meta Reality Labs</h3>
        <ul>
          <li>Distillation from Large Language Models (LLMs) to Small Language Models (SLMs)</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 4 -->
  <div class="timeline-item">
    <div class="timeline-year">2021 - Present</div>
    <div class="experience-card">
      <img src="../images/ubc_cs_logo.png" alt="UBC Logo">
      <div>
        <h3>Research Assistant, UBC NLP Group</h3>
        <ul>
          <li>Commonsense, abductive, and counterfactual reasoning in Vision Language tasks</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 5 -->
  <div class="timeline-item">
    <div class="timeline-year">2019 - 2021</div>
    <div class="experience-card">
      <img src="../images/openml_logo.png" alt="OpenML Logo">
      <div>
        <h3>AI Research Engineer, OpenML & TU/e</h3>
        <ul>
          <li>Core developer for OpenML and AutoML research infrastructure</li>
          <li>Developed meta-learning approaches for AutoML experiment selection</li>
        </ul>
      </div>
    </div>
  </div>
</div>
