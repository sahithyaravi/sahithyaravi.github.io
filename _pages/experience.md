<style>
  /* Timeline container */
  .timeline {
    position: relative;
    max-width: 800px;
    margin: 50px auto;
  }

  /* Vertical line */
  .timeline::after {
    content: '';
    position: absolute;
    width: 4px;
    background-color: #b3cde0; /* Pastel blue */
    top: 0;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
  }

  /* Individual timeline items */
  .timeline-item {
    position: relative;
    width: 50%;
    padding: 20px 40px;
    box-sizing: border-box;
  }

  /* Left timeline items */
  .timeline-item.left {
    text-align: right;
    padding-right: 60px;
  }

  /* Right timeline items */
  .timeline-item.right {
    left: 50%;
    padding-left: 60px;
  }

  /* Dots on the timeline */
  .timeline-item::after {
    content: '';
    position: absolute;
    top: 20px;
    left: calc(100% - 10px);
    width: 20px;
    height: 20px;
    background-color: #6497b1; /* Slightly darker pastel blue */
    border-radius: 50%;
    border: 4px solid white;
    box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
  }

  .timeline-item.right::after {
    left: -10px;
  }

  /* Experience details */
  .experience-card {
    background: #f0f8ff; /* Light pastel background */
    border-radius: 8px;
    padding: 15px;
    display: flex;
    align-items: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  /* Experience logo */
  .experience-card img {
    width: 60px;
    height: 60px;
    object-fit: contain;
    margin-right: 15px;
  }

  /* Responsive Design */
  @media screen and (max-width: 768px) {
    .timeline::after {
      left: 20px;
    }
    
    .timeline-item {
      width: 100%;
      padding-left: 50px;
      padding-right: 0;
    }

    .timeline-item.left,
    .timeline-item.right {
      left: 0;
      text-align: left;
    }

    .timeline-item::after {
      left: 10px;
    }
  }
</style>

<div class="timeline">
  <!-- Experience 1 -->
  <div class="timeline-item left">
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="FAIR Logo">
      <div class="experience-details">
        <h3>Research Intern, FAIR Communication and Language</h3>
        <p class="date"><strong>Summer 2024</strong></p>
        <ul>
          <li>Text-guided avatar generation based on social norms</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 2 -->
  <div class="timeline-item right">
    <div class="experience-card">
      <img src="../images/msr_logo.jpeg" alt="Microsoft Research Logo">
      <div class="experience-details">
        <h3>Research Intern, Microsoft Research, HCAIX Group</h3>
        <p class="date"><strong>Summer 2024</strong></p>
        <ul>
          <li>Evaluating spatial reasoning abilities of Vision Language Models across multiple frames</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 3 -->
  <div class="timeline-item left">
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="Meta Reality Labs Logo">
      <div class="experience-details">
        <h3>AI Research Scientist Intern, Meta Reality Labs</h3>
        <p class="date"><strong>Summer 2023</strong></p>
        <ul>
          <li>Distillation from Large Language Models (LLMs) to Small Language Models (SLMs)</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 4 -->
  <div class="timeline-item right">
    <div class="experience-card">
      <img src="../images/ubc_cs_logo.png" alt="UBC Logo">
      <div class="experience-details">
        <h3>Research Assistant, UBC NLP Group</h3>
        <p class="date"><strong>2021 - Present</strong></p>
        <ul>
          <li>Commonsense, abductive, and counterfactual reasoning in Vision Language tasks</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Experience 5 -->
  <div class="timeline-item left">
    <div class="experience-card">
      <img src="../images/openml_logo.png" alt="OpenML Logo">
      <div class="experience-details">
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
