---
title: "Experience"
permalink: /experience/
author_profile: true
---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {

  padding: 40px 20px;
  min-height: 100vh;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

h1 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 50px;
  color: #1a1a2e;
  font-weight: 700;
}

.experience-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.exp-card {
  background: white;
  border-radius: 16px;
  padding: 30px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.exp-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg,rgb(168, 162, 162) 0%, #764ba2 100%);
  transform: scaleX(0);
  transform-origin: left;
  transition: transform 0.3s ease;
}

.exp-card:hover::before {
  transform: scaleX(1);
}

.exp-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 40px rgba(0,0,0,0.15);
}

.card-header {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 20px;
}

.logo {
  width: 60px;
  height: 60px;
  border-radius: 12px;
  padding: 8px;
  background: #f8f9fa;
  display: flex;
  align-items: center;
  justify-content: center;
}

.logo img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.card-title-section {
  flex: 1;
}

.company-name {
  font-size: 0.85rem;
  color: #667eea;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-bottom: 4px;
}

.role-title {
  font-size: 1.15rem;
  color: #1a1a2e;
  font-weight: 600;
  line-height: 1.3;
}

.period {
  display: inline-block;
  background: linear-gradient(90deg,rgb(152, 143, 143) 0%,rgb(18, 14, 22) 100%);
  color: white;
  padding: 6px 14px;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
  margin-bottom: 16px;
}

.description {
  color: #4a5568;
  line-height: 1.7;
  font-size: 0.95rem;
}

.description a {
  color: #667eea;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s;
}

.description a:hover {
  color: #764ba2;
  text-decoration: underline;
}

@media (max-width: 768px) {
  h1 {
    font-size: 2rem;
    margin-bottom: 30px;
  }
  
  .experience-grid {
    grid-template-columns: 1fr;
  }
}
</style>
</head>
<body>
<div class="container">

  
  <div class="experience-grid">
    <!-- Card 1 -->
    <div class="exp-card">
      <div class="card-header">
        <div class="logo">
          <img src="../images/meta_logo.png" alt="FAIR">
        </div>
        <div class="card-title-section">
          <div class="company-name">Meta AI (FAIR)</div>
          <div class="role-title">Research Intern</div>
        </div>
      </div>
      <div class="period">Summer 2024</div>
      <div class="description">
        Generating fine-grained facial expressions using semantically meaningful pose tokens, improving predictability and precise control crucial for controllable video generation.
        Mentors: Vasu Sharma & LP Morency
      </div>
    </div>

    <!-- Card 2 -->
    <div class="exp-card">
      <div class="card-header">
        <div class="logo">
          <img src="../images/msr_logo.jpeg" alt="Microsoft Research">
        </div>
        <div class="card-title-section">
          <div class="company-name">Microsoft Research</div>
          <div class="role-title">Research Intern</div>
        </div>
      </div>
      <div class="period">Summer 2024</div>
      <div class="description">
        Evaluating 3D spatial reasoning abilities of Vision Language Models in ego-centric videos.
        Mentors: Bala Kumaravel, Andy Wilson & Vibhav Vineet
      </div>
    </div>

    <!-- Card 3 -->
    <div class="exp-card">
      <div class="card-header">
        <div class="logo">
          <img src="../images/meta_logo.png" alt="Meta Reality Labs">
        </div>
        <div class="card-title-section">
          <div class="company-name">Meta Reality Labs</div>
          <div class="role-title">Research Intern</div>
        </div>
      </div>
      <div class="period">Summer 2023</div>
      <div class="description">
        Iterative-DPO and ranking methods for teaching creative abilities to smaller LMs.
        Mentors: Arash Einolgozhati, Patrick Huber
      </div>
    </div>

    <!-- Card 4 -->
    <div class="exp-card">
      <div class="card-header">
        <div class="logo">
          <img src="../images/openml_logo.png" alt="OpenML">
        </div>
        <div class="card-title-section">
          <div class="company-name">OpenML & TU/e</div>
          <div class="role-title">AI Research Engineer</div>
        </div>
      </div>
      <div class="period">2019 - 2021</div>
      <div class="description">
        I worked as an AI research engineer in the Machine Learning group at Eindhoven University of Technology. Together with an amazing <a href="https://github.com/orgs/openml/people">team</a> supervised by <a href="https://joaquinvanschoren.github.io/home/#lab">Joaquin Vanschoren</a>, I worked on research and development of open-source software for <a href="https://github.com/openml">open and automated machine learning</a>. I also worked with <a href="https://www.win.tue.nl/~mpechen/">Mykola Pechenizkiy</a> on active learning and interpretability of NLP models.
      </div>
    </div>
  </div>
</div>
</body>
</html>