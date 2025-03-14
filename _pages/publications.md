---
title: "Publications"
permalink: /publications/
author_profile: true
---

**Black Swan: Abductive and Defeasible Video Reasoning in Unpredictable Events**  
  Aditya Chinchure<sup>◆</sup>, **Sahithya Ravi<sup>◆</sup>**, Raymond Ng, Vered Shwartz, Boyang Li, and Leonid Sigal  
  CVPR 2024
  [(link)](https://arxiv.org/abs/2412.05725)

**From Local Concepts to Universals: Evaluating the Multicultural Understanding of Vision-Language Models**  
  Mehar Bhatia, **Sahithya Ravi<sup>◆</sup>**, Aditya Chinchure<sup>◆</sup>, Eunjeong Hwang, and Vered Shwartz  
  *EMNLP 2024*  
  [(link)](https://arxiv.org/abs/2407.00263)

**Small But Funny: A Feedback-Driven Approach to Humor Distillation**  
  **Sahithya Ravi**, Patrick Huber, Akshat Shrivastava, Vered Shwartz  
  *ACL 2024*  
  [(link)](https://aclanthology.org/2024.acl-long.706.pdf)

**Empowering Air Travelers: A Chatbot for Canadian Air Passenger Rights**  
  Maksym Taranukhin, **Sahithya Ravi**, Gábor Lukács, Evangelos Milios, and Vered Shwartz  
  *NLLP 2024*

**COMET-M: Reasoning about Multiple Events in Complex Sentences**  
  **Sahithya Ravi**, Raymond Ng, Vered Shwartz  
  *Findings of EMNLP 2023*  
  [(link)](https://www.semanticscholar.org/reader/d0f108b8f5fcfb81e4354b498f3f8491740ece7e)

**VLC-BERT: Visual Question Answering with Contextualized Commonsense Knowledge**  
  **Sahithya Ravi<sup>◆</sup>**, Aditya Chinchure<sup>◆</sup>, Renjie Lio, Vered Shwartz, and Leonid Sigal  
  *Proceedings of WACV 2023*  
  [(link)](https://openaccess.thecvf.com/content/WACV2023/papers/Ravi_VLC-BERT_Visual_Question_Answering_With_Contextualized_Commonsense_Knowledge_WACV_2023_paper.pdf)

**What Happens Before and After: Multi-Event Commonsense in Event Coreference Resolution**  
  **Sahithya Ravi**, Chris Tanner, Raymond Ng, and Vered Shwartz  
  *EACL 2023*  
  [(link)](https://arxiv.org/pdf/2302.09715.pdf)

**CASE: Commonsense-Augmented Score with an Expanded Answer Space**  
  Wenkai Chen, **Sahithya Ravi**, and Vered Shwartz  
  *Findings of EMNLP 2023*  
  [(link)](https://arxiv.org/pdf/2311.01684.pdf)

**OpenML-Python: An Extensible Python API for OpenML**  
  M. Feurer, **S. Ravi**, et al.  
  *Journal of Machine Learning Research (JMLR), 2020*  
  [(link)](https://arxiv.org/pdf/1911.02490.pdf)

(◆-Equal Contribution)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}