---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.intro-section {
  font-size: 16px;
  line-height: 1.7;
  margin-bottom: 35px;
  color: #333;
}

.news-section {
  background-color: #f8f9fa;
  padding: 20px;
  border-radius: 8px;
  margin-bottom: 40px;
  border-left: 4px solid #4a90e2;
}

.news-section h2 {
  margin-top: 0;
  color: #2c3e50;
  font-size: 22px;
  margin-bottom: 15px;
}

.news-item {
  font-size: 15px;
  line-height: 1.6;
  color: #555;
}

.section-title {
  font-size: 26px;
  font-weight: 600;
  color: #2c3e50;
  margin-top: 40px;
  margin-bottom: 25px;
  padding-bottom: 10px;
  border-bottom: 2px solid #e0e0e0;
}

.pub-item {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 25px;
  margin-bottom: 30px;
  background-color: #ffffff;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: transform 0.2s, box-shadow 0.2s;
}

.pub-item:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.12);
}

.pub-img {
  flex: 0 0 280px;
  max-width: 280px;
}

.pub-img img {
  width: 100%;
  height: auto;
  border-radius: 6px;
  object-fit: cover;
}

.pub-detail {
  flex: 1;
  min-width: 260px;
}

.pub-title {
  font-size: 17px;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 12px;
  line-height: 1.4;
}

.pub-authors {
  font-size: 14px;
  color: #555;
  margin-bottom: 8px;
}

.pub-venue {
  font-size: 14px;
  color: #4a90e2;
  font-weight: 500;
  margin-bottom: 12px;
}

.pub-description {
  font-size: 14px;
  color: #666;
  line-height: 1.6;
}

.edu-section {
  margin-top: 40px;
}

.edu-item {
  margin-bottom: 30px;
  padding: 20px;
  background-color: #fafafa;
  border-radius: 8px;
}

.edu-degree {
  font-size: 16px;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 8px;
}

.edu-school {
  font-size: 15px;
  color: #555;
  margin-bottom: 5px;
}

.edu-detail {
  font-size: 14px;
  color: #777;
}

@media (max-width: 768px) {
  .pub-item {
    flex-direction: column;
  }
  
  .pub-img {
    flex: 1 1 100%;
    max-width: 100%;
  }
}
</style>

<div class="intro-section">
Hi! I'm <strong>Dayoon Ko</strong>, a Ph.D. student in Computer Science and Engineering at Seoul National University, advised by Professor Gunhee Kim. My research focuses on <strong>model evaluation</strong>, <strong>retrieval-augmented generation (RAG)</strong>, and <strong>multimodal learning</strong>, with the goal of enhancing the scalability and adaptability of large language models (LLMs). 

I am particularly interested in developing methods that enable LLMs to effectively integrate and process both text and video data, pushing the boundaries of multimodal understanding and generation.
</div>

<div class="news-section">
  <h2>🔥 Recent News</h2>
  <div class="news-item">
    Our paper <strong>"DynamicER: Resolving Emerging Mentions to Dynamic Entities for RAG"</strong> was accepted at <strong>EMNLP 2024 Main</strong>!
  </div>
</div>

<h2 class="section-title">Selected Publications</h2>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/dynamicer.png" alt="DynamicER">
  </div>
  <div class="pub-detail">
    <div class="pub-title">DynamicER: Resolving Emerging Mentions to Dynamic Entities for RAG</div>
    <div class="pub-authors">Jinyoung Kim, <strong>Dayoon Ko</strong>, Gunhee Kim</div>
    <div class="pub-venue">EMNLP 2024</div>
    <div class="pub-description">This work addresses challenges in resolving temporally evolving mentions to entities. Resolving mentions is key to improving retrieval, enhancing RAG accuracy in dynamic environments.</div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/growover.png" alt="GrowOVER">
  </div>
  <div class="pub-detail">
    <div class="pub-title">GrowOVER: How Can LLMs Adapt to Growing Real-World Knowledge?</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jinyoung Kim, Hahyeon Choi, Gunhee Kim</div>
    <div class="pub-venue">ACL 2024</div>
    <div class="pub-description">We propose QA & dialogue benchmarks that are continuously and automatically updated to assess whether LLMs can handle evolving knowledge. By making LLMs evaluate their confidence, we enable RAG systems to adapt to new knowledge without retraining.</div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/exfuntube.png" alt="ExFunTube">
  </div>
  <div class="pub-detail">
    <div class="pub-title">Can Language Models Laugh at YouTube Short-form Videos?</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Sangho Lee, Gunhee Kim</div>
    <div class="pub-venue">EMNLP 2023</div>
    <div class="pub-description">A video humor explanation benchmark via a multimodal-filtering pipeline to evaluate LLMs' understanding of complex multimodal tasks like humor. We generate several frame captions and filter them based on video segments to enhance LLMs with vision capabilities.</div>
  </div>
</div>

<div class="edu-section">
  <h2 class="section-title">Education</h2>
  
  <div class="edu-item">
    <div class="edu-degree">M.S./Ph.D. in Computer Science and Engineering (2022.9 - Present)</div>
    <div class="edu-school">Seoul National University</div>
    <div class="edu-detail">Advisor: Professor Gunhee Kim</div>
  </div>

  <div class="edu-item">
    <div class="edu-degree">B.S. in Computer Science and Engineering (2018.3 - 2022.8)</div>
    <div class="edu-school">Yonsei University</div>
    <div class="edu-detail">GPA: 4.12/4.30 (Rank: 1/28)</div>
  </div>
</div>
