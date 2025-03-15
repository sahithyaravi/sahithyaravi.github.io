---
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  .publications-container {
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
  
  .pub-year {
    font-size: 1.5em;
    font-weight: bold;
    color: #f3e3e3;
    border-bottom: 2px solid #789DBC;
    margin-top: 20px;
    padding-bottom: 5px;
  }
  
  .publication-card {
    background: #f3e3e3;
    padding: 12px 16px;
    border-radius: 6px;
    box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
    border-left: 5px solid #789DBC;
  }
  
  .pub-authors, .pub-venue {
    display: block;
    font-size: 0.95em;
    color: #555;
    margin-top: 3px;
  }
  
  .pub-link {
    display: inline-block;
    margin-top: 5px;
    color: #789DBC;
    text-decoration: none;
    font-weight: bold;
  }
  
  .pub-link:hover {
    text-decoration: underline;
  }

  .pub-scholar {
    margin-top: 20px;
  }

  .pub-scholar-link {
    font-weight: bold;
    color: #789DBC;
  }
</style>


<div class="publications-container">
  
  <!-- 2025 -->
  <h2 class="pub-year">2025</h2>
  
  <div class="publication-card">
    <strong>Black Swan: Abductive and Defeasible Video Reasoning in Unpredictable Events</strong>  
    <span class="pub-authors">Aditya Chinchure<sup>◆</sup>, <b>Sahithya Ravi<sup>◆</sup></b>, Raymond Ng, Vered Shwartz, Boyang Li, and Leonid Sigal</span>  
    <span class="pub-venue">CVPR 2025</span>  
    <a href="https://arxiv.org/abs/2412.05725" class="pub-link">🔗 Paper</a>
  </div>

  <!-- 2024 -->
  <h2 class="pub-year">2024</h2>

  <div class="publication-card">
    <strong>From Local Concepts to Universals: Evaluating the Multicultural Understanding of Vision-Language Models</strong>  
    <span class="pub-authors">Mehar Bhatia, <b>Sahithya Ravi<sup>◆</sup></b>, Aditya Chinchure<sup>◆</sup>, Eunjeong Hwang, and Vered Shwartz</span>  
    <span class="pub-venue">EMNLP 2024</span>  
    <a href="https://arxiv.org/abs/2407.00263" class="pub-link">🔗 Paper</a>
  </div>

  <div class="publication-card">
    <strong>Small But Funny: A Feedback-Driven Approach to Humor Distillation</strong>  
    <span class="pub-authors"><b>Sahithya Ravi</b>, Patrick Huber, Akshat Shrivastava, Vered Shwartz</span>  
    <span class="pub-venue">ACL 2024</span>  
    <a href="https://aclanthology.org/2024.acl-long.706.pdf" class="pub-link">🔗 Paper</a>
  </div>

  <div class="publication-card">
    <strong>Empowering Air Travelers: A Chatbot for Canadian Air Passenger Rights</strong>  
    <span class="pub-authors">Maksym Taranukhin, <b>Sahithya Ravi</b>, Gábor Lukács, Evangelos Milios, and Vered Shwartz</span>  
    <span class="pub-venue">NLLP 2024</span>
  </div>

   <!-- 2023 -->
  <h2 class="pub-year">2023</h2>

  <div class="publication-card">
    <strong>COMET-M: Reasoning about Multiple Events in Complex Sentences</strong>  
    <span class="pub-authors"><b>Sahithya Ravi</b>, Raymond Ng, Vered Shwartz</span>  
    <span class="pub-venue">Findings of EMNLP 2023</span>  
    <a href="https://www.semanticscholar.org/reader/d0f108b8f5fcfb81e4354b498f3f8491740ece7e" class="pub-link">🔗 Paper</a>
  </div>

  <div class="publication-card">
    <strong>VLC-BERT: Visual Question Answering with Contextualized Commonsense Knowledge</strong>  
    <span class="pub-authors"><b>Sahithya Ravi<sup>◆</sup></b>, Aditya Chinchure<sup>◆</sup>, Renjie Lio, Vered Shwartz, and Leonid Sigal</span>  
    <span class="pub-venue">WACV 2023</span>  
    <a href="https://openaccess.thecvf.com/content/WACV2023/papers/Ravi_VLC-BERT_Visual_Question_Answering_With_Contextualized_Commonsense_Knowledge_WACV_2023_paper.pdf" class="pub-link">🔗 Paper</a>
  </div>

  <div class="publication-card">
    <strong>What Happens Before and After: Multi-Event Commonsense in Event Coreference Resolution</strong>  
    <span class="pub-authors"><b>Sahithya Ravi</b>, Chris Tanner, Raymond Ng, and Vered Shwartz</span>  
    <span class="pub-venue">EACL 2023</span>  
    <a href="https://arxiv.org/pdf/2302.09715.pdf" class="pub-link">🔗 Paper</a>
  </div>

  <div class="publication-card">
    <strong>CASE: Commonsense-Augmented Score with an Expanded Answer Space</strong>  
    <span class="pub-authors">Wenkai Chen, <b>Sahithya Ravi</b>, and Vered Shwartz</span>  
    <span class="pub-venue">Findings of EMNLP 2023</span>  
    <a href="https://arxiv.org/pdf/2311.01684.pdf" class="pub-link">🔗 Paper</a>
  </div>

  <!-- 2020 -->
  <h2 class="pub-year">2020</h2>

  <div class="publication-card">
    <strong>OpenML-Python: An Extensible Python API for OpenML</strong>  
    <span class="pub-authors">M. Feurer, <b>S. Ravi</b>, et al.</span>  
    <span class="pub-venue">JMLR, 2020</span>  
    <a href="https://arxiv.org/pdf/1911.02490.pdf" class="pub-link">🔗 Paper</a>
  </div>

</div>

</div>

(◆ - Equal Contribution)

{% if author.googlescholar %}
  <p class="pub-scholar">You can also find my articles on <a href="{{author.googlescholar}}" class="pub-scholar-link">Google Scholar</a>.</p>
{% endif %}
