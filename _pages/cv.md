---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-section {
  margin-bottom: 40px;
}

.cv-section h2 {
  font-size: 24px;
  color: #2c3e50;
  border-bottom: 2px solid #4a90e2;
  padding-bottom: 8px;
  margin-bottom: 20px;
}

.cv-item {
  margin-bottom: 25px;
  padding-left: 20px;
  border-left: 3px solid #e0e0e0;
}

.cv-item-title {
  font-size: 17px;
  font-weight: 600;
  color: #333;
  margin-bottom: 5px;
}

.cv-item-institution {
  font-size: 15px;
  color: #555;
  margin-bottom: 5px;
}

.cv-item-detail {
  font-size: 14px;
  color: #777;
  line-height: 1.6;
}

.cv-item-period {
  font-size: 14px;
  color: #888;
  font-style: italic;
}
</style>

<div class="cv-section">
  <h2>Education</h2>
  
  <div class="cv-item">
    <div class="cv-item-title">M.S./Ph.D. in Computer Science and Engineering</div>
    <div class="cv-item-institution">Seoul National University</div>
    <div class="cv-item-detail">Advisor: Professor Gunhee Kim</div>
    <div class="cv-item-period">September 2022 - Present</div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">B.S. in Computer Science and Engineering</div>
    <div class="cv-item-institution">Yonsei University</div>
    <div class="cv-item-detail">GPA: 4.12/4.30 (Rank: 1/28)</div>
    <div class="cv-item-period">March 2018 - August 2022</div>
  </div>
</div>

<div class="cv-section">
  <h2>Research Interests</h2>
  <ul style="font-size: 15px; line-height: 1.8; color: #555;">
    <li>Retrieval-Augmented Generation (RAG)</li>
    <li>Multimodal Learning and Vision-Language Models</li>
    <li>Model Evaluation and Benchmarking</li>
    <li>Large Language Models (LLMs)</li>
    <li>Video Understanding</li>
  </ul>
</div>

<div class="cv-section">
  <h2>Publications</h2>
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
</div>
