---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Hi! I am a Ph.D. candidate at the Univeristy of British Columbia (UBC) and the Vector Institute for AI advised by [Vered Shwartz](https://www.cs.ubc.ca/~vshwartz/) and [Raymond NG](https://www.cs.ubc.ca/people/raymond-ng) in the [Natural Language Processing group](http://www.cs.ubc.ca/cs-research/lci/research-groups/natural-language-processing/). I frequently collaborate with [Leonid Sigal](https://www.cs.ubc.ca/~lsigal/) in the Computer Vision group.

My research focuses on enabling models to reason about the visual world beyond what is **explicitly** shown, similar to how humans build mental models. I study how Vision-Language Models (VLMs) infer implicit information such as object properties, spatial relations, and causal event dynamics. Currently, I am investigating how models update their internal beliefs when they encounter [surprising  events](https://arxiv.org/abs/2509.23433) in video streams.

During my PhD, I have had the opportunity to intern at industry research groups, including FAIR (Meta), Microsoft Research in Summer 2024 and Meta Reality labs in Summer 2023.

<div class="news-section">
  <h2>Updates</h2>
  <div class="news-scrollable">
    <ul>
      {% for item in site.data.news %}
      <li>
        <span class="news-date">{{ item.date | date: "%b %d, %Y" }}</span>
        {{ item.description | markdownify | remove: '<p>' | remove: '</p>' }}
      </li>
      {% endfor %}
    </ul>
  </div>
</div>
