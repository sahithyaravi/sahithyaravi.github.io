---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a Ph.D. student at the Univeristy of British Columbia (UBC) CS advised by [Vered Shwartz](https://www.cs.ubc.ca/~vshwartz/) and [Raymond NG](https://www.cs.ubc.ca/people/raymond-ng) in the [Natural Language Processing group](http://www.cs.ubc.ca/cs-research/lci/research-groups/natural-language-processing/). I frequently collaborate with [Leonid Sigal](https://www.cs.ubc.ca/~lsigal/) in the Computer Vision group.

I work at the intersection of NLP, Vision and cognitively-inspired reasoning. Specifically, I evaluate and improve critical reasoning capabilities across multiple modalities (text, images, videos) - which are fundamental for safe and effective deployment in real-world applications such as embodied agents and AR/VR.

My recent work [Black Swan](https://blackswan.cs.ubc.ca/) evaluates models on abductive and defeasible reasoning in unpredictable video settings, testing whether models can revise their beliefs when presented with new evidence. In my ongoing work [SPIKE](https://www.arxiv.org/pdf/2509.23433), I am working on post-training methods that teach VLMs to be revise beliefs and become resilient to such scenarios. 

If you are reading this and would like to collaborate on multimodal reasoning, robustness and post-training approaches feel free to reach out. 

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>

  /* Timeline container */
  .timeline {
    position: relative;
    max-width: 900px;
    margin: 0 auto;
  }

  /* Vertical line */
  .timeline::after {
    content: '';
    position: absolute;
    width: 1px;
    top: 10px;
    bottom: 10px;
    left: 100px;
    background: #e0e0e0;
  }

  /* Individual timeline items */
  .timeline-item {
    display: flex;
    align-items: flex-start;
    position: relative;
    margin: 0 0 12px 0;
  }

  /* Timeline dot */
  .timeline-item::before {
    content: '';
    position: absolute;
    left: 96px;
    top: 10px;
    width: 9px;
    height: 9px;
    border-radius: 50%;
    background: #2c2c2c;
    z-index: 1;
  }

  /* Year */
  .timeline-year {
    width: 85px;
    text-align: right;
    font-size: 0.75rem;
    font-weight: 500;
    color: #888;
    padding-top: 8px;
    flex-shrink: 0;
    letter-spacing: 0.3px;
  }

  /* Experience card */
  .experience-card {
    flex: 1;
    display: flex;
    gap: 14px;
    margin-left: 30px;
    padding: 14px 18px;
    background: #fafafa;
    border-radius: 6px;
    border-left: 3px solid #2c2c2c;
    transition: all 0.25s ease;
  }

  .experience-card:hover {
    background: #f5f5f5;
    border-left-color: #666;
    transform: translateX(3px);
  }

  /* Logo */
  .experience-card img {
    width: 42px;
    height: 42px;
    object-fit: contain;
    flex-shrink: 0;
    opacity: 0.9;
  }

  /* Content */
  .experience-content {
    flex: 1;
  }

  .experience-content h3 {
    margin: 0 0 6px 0;
    font-size: 0.95rem;
    font-weight: 600;
    color: #2c2c2c;
    letter-spacing: -0.2px;
  }

  .experience-content p {
    margin: 0;
    font-size: 0.85rem;
    line-height: 1.5;
    color: #666;
  }

  .experience-content a {
    color: #2c2c2c;
    text-decoration: underline;
    text-decoration-color: #ccc;
    text-decoration-thickness: 1px;
    transition: all 0.2s ease;
  }

  .experience-content a:hover {
    text-decoration-color: #2c2c2c;
  }

  h2 {
    text-align: center;
    color: #2c2c2c;
    margin-bottom: 35px;
    font-weight: 600;
    font-size: 1.5rem;
    letter-spacing: -0.5px;
  }
</style>
</head>
<body>

<h2>Experience</h2>

<div class="timeline">
  <!-- Experience 1 -->
  <div class="timeline-item">
    <div class="timeline-year">Summer 2024</div>
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="FAIR Logo">
      <div class="experience-content">
        <h3>Research Intern, FAIR Communication and Language</h3>
        <p>Generating fine-grained facial expressions using semantically meaningful pose tokens, improving predictability and precise control crucial for controllable video generation.</p>
      </div>
    </div>
  </div>

  <!-- Experience 2 -->
  <div class="timeline-item">
    <div class="timeline-year">Summer 2024</div>
    <div class="experience-card">
      <img src="../images/msr_logo.jpeg" alt="Microsoft Research Logo">
      <div class="experience-content">
        <h3>Research Intern, Microsoft Research</h3>
        <p>Evaluating 3D spatial reasoning abilities of Vision Language Models in ego-centric videos.</p>
      </div>
    </div>
  </div>

  <!-- Experience 3 -->
  <div class="timeline-item">
    <div class="timeline-year">Summer 2023</div>
    <div class="experience-card">
      <img src="../images/meta_logo.png" alt="Meta Reality Labs Logo">
      <div class="experience-content">
        <h3>Research Intern, Meta Reality Labs</h3>
        <p>Iterative-DPO and ranking methods for teaching creative abilities to smaller LMs.</p>
      </div>
    </div>
  </div>

  <!-- Experience 4 -->
  <div class="timeline-item">
    <div class="timeline-year">2019 - 2021</div>
    <div class="experience-card">
      <img src="../images/openml_logo.png" alt="OpenML Logo">
      <div class="experience-content">
        <h3>AI Research Engineer, OpenML & TU/e</h3>
        <p>
          I worked as an AI research engineer in the Machine Learning group at Eindhoven University of Technology. 
          Together with an amazing <a href="https://github.com/orgs/openml/people">team</a> supervised by 
          <a href="https://joaquinvanschoren.github.io/home/#lab">Joaquin Vanschoren</a>, I worked on research and development of open-source software for 
          <a href="https://github.com/openml">open and automated machine learning</a>. I also worked with 
          <a href="https://www.win.tue.nl/~mpechen/">Mykola Pechenizkiy</a> on active learning and interpretability of NLP models.
        </p>
      </div>
    </div>
  </div>
</div>

</body>
</html>