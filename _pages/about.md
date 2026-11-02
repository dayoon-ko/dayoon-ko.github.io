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
  font-size: 20px;
  margin-bottom: 15px;
}

.news-item {
  font-size: 15px;
  line-height: 1.6;
  color: #555;
}

.section-title {
  font-size: 20px;
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
  gap: 20px 36px;
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
  min-width: 240px;
}

.pub-title {
  font-size: 15px;
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
  Hi! I’m Dayoon Ko 😊, a Ph.D. candidate in Computer Science and Engineering at SNU, advised by <a href="https://vision.snu.ac.kr/gunhee/" target="_blank">Gunhee Kim</a>. Currently, I’m a visiting researcher at <strong>UC Berkeley</strong>, working with <a href="https://www.sewonmin.com/" target="_blank">Sewon Min</a>.
  <br><br>
  I love to define practical problems that appear when people use AI in the real world. Recently, I’ve been focusing on on-device multimodal retrieval, where models search over what people see and keep on their own devices, under tight memory and compute budgets. Before that, I asked whether search agents can find the papers researchers actually need and verify what they claim, and how LLMs and RAG systems keep up with evolving knowledge. Also, I feel excited when I finally find out how to solve the problems! That has meant scaling search agents with parallel and sequential reasoning, and detecting when a retriever needs an update. My first project explored video humor, an extreme case of implicit multimodal understanding.
  <br><br>
  Outside of research, I enjoy dancing 💃 or doing CrossFit 🏋🏻‍♀️. Staying active keeps my brain happy!
</div>

{% include research-map.html %}

<div class="news-section">
  <h2>🔥 Recent News</h2>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Oct 2026]</strong> Joined Sewon Min's group at <strong>UC Berkeley</strong> 🐻 as a visiting researcher!
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Oct 2026]</strong> New paper release! <a href="https://dayoon-ko.github.io/CompLit/" target="_blank"><strong>"CompLit"</strong></a>: a scientific literature search benchmark for implicit, cumulative, and unmet needs.
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Oct 2026]</strong> New paper release! <a href="https://arxiv.org/abs/2610.02202" target="_blank"><strong>"ScholarCatalyst"</strong></a>: a benchmark for finding papers that inspire new research.
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Sep 2026]</strong> Received the <strong>Youlchon AI Star Fellowship</strong>! 🎉
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Sep 2026]</strong> <a href="https://arxiv.org/abs/2606.02404" target="_blank"><strong>"K-BrowseComp"</strong></a> accepted to <strong>EMNLP 2026 Findings</strong>! 🎉
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Sep 2026]</strong> <a href="https://arxiv.org/abs/2602.07549" target="_blank"><strong>"Illusory Completion in Search Agents"</strong></a> accepted to the <strong>Workshop on Agent Behavior</strong> at COLM 2026! 🎉
  </div>
  <!-- <div class="news-item" style="margin-bottom: 12px;">
    <strong>[May 2025]</strong> Two papers accepted at <strong>ACL 2025</strong>! "GradNormIR" (Findings) and "Can LLMs Deceive CLIP?" (Main)
  </div> -->
</div>

<h2 class="section-title" id="publications">Publications</h2>
<div class="pub-filter" id="pub-filter"></div>

<div class="pub-item" id="pub-complit" data-thread="literature" data-first="true">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/complit.png" alt="CompLit">
  </div>
  <div class="pub-detail">
    <div class="pub-title">CompLit: Scientific Literature Search Benchmarks Must Cover Implicit, Cumulative, and Unmet Needs</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jihyuk Kim, Soyeong Jeong, Young-Jun Lee, Dahyun Lee, Juyeon Kim, Gunhee Kim, Moontae Lee, Kyungjae Lee</div>
    <div class="pub-venue">arXiv 2026</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2610.28658" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://dayoon-ko.github.io/CompLit/" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Project Page]</a>
      <a href="https://github.com/dayoon-ko/CompLit" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Code]</a>
      <a href="https://huggingface.co/datasets/dayoon/CompLit" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Dataset]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-scholarcatalyst" data-thread="literature" data-first="false">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/scholarcatalyst.png" alt="ScholarCatalyst">
  </div>
  <div class="pub-detail">
    <div class="pub-title">ScholarCatalyst: A Benchmark for Retrieving Papers That Inspire New Research</div>
    <div class="pub-authors">Sohyeon Kim, Yoonho Lee, Bo Liu, <strong>Dayoon Ko</strong>, Rulin Shao, Seungone Kim, Graham Neubig, Pang Wei Koh, Aakanksha Chowdhery, Akari Asai, Omar Khattab, Yejin Choi, Gunhee Kim, Chelsea Finn</div>
    <div class="pub-venue">arXiv 2026</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2610.02202" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/stanford-iris-lab/ScholarCatalyst" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Code]</a>
      <a href="https://huggingface.co/datasets/ScholarCatalyst/ScholarCatalyst" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Dataset]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-kbrowsecomp" data-thread="agents" data-first="false">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/kbrowsecomp.png" alt="K-BrowseComp">
  </div>
  <div class="pub-detail">
    <div class="pub-title">K-BrowseComp: A Web Browsing Agent Benchmark Grounded in Korean Contexts</div>
    <div class="pub-authors">Nahyun Lee, Dongkeun Yoon, Guijin Son, Geewook Kim, <strong>Dayoon Ko</strong>, Jeonghun Park, Haneul Yoo, Jaewon Cho, Junghun Park, Changyoon Lee, Kyochul Jang, Jaeyeon Kim, Eunsu Kim, Woojin Cho, Seungone Kim</div>
    <div class="pub-venue">EMNLP 2026 Findings</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2606.02404" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/prometheus-eval/K-BrowseComp" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-illusory" data-thread="agents" data-first="true">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/illusory_completion.png" alt="Illusory Completion">
  </div>
  <div class="pub-detail">
    <div class="pub-title">When Is Enough Not Enough? Illusory Completion in Search Agents</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jihyuk Kim, Sohyeon Kim, Haeju Park, Dahyun Lee, Gunhee Kim, Moontae Lee, Kyungjae Lee</div>
    <div class="pub-venue">COLM 2026 Workshop on Agent Behavior</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2602.07549" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/illusory_completion" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-hybrid" data-thread="agents" data-first="true">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/hds.png" alt="HybridDeepSearcher">
  </div>
  <div class="pub-detail">
    <div class="pub-title">Hybrid Deep Searcher: Scalable Parallel and Sequential Search Reasoning</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jihyuk Kim, Haeju Park, Sohyeon Kim, Dahyun Lee, Yongrae Jo, Gunhee Kim, Moontae Lee, Kyungjae Lee</div>
    <div class="pub-venue">ICLR 2026</div>
    <div style="margin-top: 10px;">
      <a href="https://openreview.net/forum?id=rXpTZyucal" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/HybridDeepSearcher" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Code]</a>
      <a href="https://hybriddeepsearcher.github.io/" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Project Page]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-gradnormir" data-thread="evolving" data-first="true">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/gradnormir.png" alt="GradNormIR">
  </div>
  <div class="pub-detail">
    <div class="pub-title">When Should Dense Retrievers Be Updated in Evolving Corpora? Detecting Out-of-Distribution Corpora Using GradNormIR</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jinyoung Kim, Sohyeon Kim, Jinhyuk Kim, Jaehoon Lee, Seonghak Song, Minyoung Lee, Gunhee Kim</div>
    <div class="pub-venue">ACL 2025 Findings</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2506.01877" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/gradnormir" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-mac" data-thread="multimodal" data-first="false">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/mac.png" alt="MAC">
  </div>
  <div class="pub-detail">
    <div class="pub-title">Can LLMs Deceive CLIP? Benchmarking Adversarial Compositionality of Pre-trained Multimodal Representation via Text Updates</div>
    <div class="pub-authors">Jaewoo Ahn, Heeseung Yun, <strong>Dayoon Ko</strong>, Gunhee Kim</div>
    <div class="pub-venue">ACL 2025</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2505.22943" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/ahnjaewoo/MAC" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-dynamicer" data-thread="evolving" data-first="false">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/dynamicer.png" alt="DynamicER">
  </div>
  <div class="pub-detail">
    <div class="pub-title">DynamicER: Resolving Emerging Mentions to Dynamic Entities for RAG</div>
    <div class="pub-authors">Jinyoung Kim, <strong>Dayoon Ko</strong>, Gunhee Kim</div>
    <div class="pub-venue">EMNLP 2024</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2410.11494" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/jiny1623/DynamicER" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-growover" data-thread="evolving" data-first="true">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/growover.png" alt="GrowOVER">
  </div>
  <div class="pub-detail">
    <div class="pub-title">GrowOVER: How Can LLMs Adapt to Growing Real-World Knowledge?</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jinyoung Kim, Hahyeon Choi, Gunhee Kim</div>
    <div class="pub-venue">ACL 2024</div>
    <div style="margin-top: 10px;">
      <a href="https://aclanthology.org/2024.acl-long.181/" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/GrowOVER" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item" id="pub-exfuntube" data-thread="multimodal" data-first="true">
  <div class="pub-img">
    <img src="/images/exfuntube_fig1.png" alt="Figure 1 of the ExFunTube paper">
  </div>
  <div class="pub-detail">
    <div class="pub-title">Can Language Models Laugh at YouTube Short-form Videos?</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Sangho Lee, Gunhee Kim</div>
    <div class="pub-venue">EMNLP 2023</div>
    <div style="margin-top: 10px;">
      <a href="https://aclanthology.org/2023.emnlp-main.176/" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/ExFunTube" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="edu-section">
  <h2 class="section-title">Experiences</h2>
  
  <div class="edu-item">
    <div class="edu-degree">Visiting Researcher</div>
    <div class="edu-school">UC Berkeley</div>
    <div class="edu-detail">Hosted by Sewon Min</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">October 2026 - Present</div>
  </div>

  <div class="edu-item">
    <div class="edu-degree">Research Intern</div>
    <div class="edu-school">LG AI Research, Superintelligence Lab</div>
    <div class="edu-detail">Worked on agentic reasoning and retrieval systems for large language models</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">March 2025 - September 2026</div>
  </div>
</div>

<div class="edu-section">
  <h2 class="section-title">Education</h2>
  
  <div class="edu-item">
    <div class="edu-degree">M.S./Ph.D. in Computer Science and Engineering</div>
    <div class="edu-school">Seoul National University</div>
    <div class="edu-detail">Advisor: Gunhee Kim</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">September 2022 - Present</div>
  </div>

  <div class="edu-item">
    <div class="edu-degree">B.S. in Computer Science and Engineering</div>
    <div class="edu-school">Yonsei University</div>
    <div class="edu-detail">GPA: 4.12/4.30 (Rank: 1/28)</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">March 2018 - August 2022</div>
  </div>
</div>

<div class="edu-section">
  <h2 class="section-title">Honors</h2>
  <div class="edu-item">
    <div class="edu-degree">Youlchon AI Star Fellowship</div>
    <div class="edu-school">Youlchon Foundation and Seoul National University AI Institute</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">2026</div>
  </div>
  <div class="edu-item">
    <div class="edu-degree">Graduation Exhibition Excellence Award</div>
    <div class="edu-school">Yonsei University, Computer Science</div>
    <div class="edu-detail">Project on mitigating data imbalance in image classification</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">Feb 2022</div>
  </div>
  <div class="edu-item">
    <div class="edu-degree">Udeok Scholarship</div>
    <div class="edu-school">Udeok Foundation</div>
    <div class="edu-detail">Academic excellence scholarship, with full tuition during undergraduate years</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">Feb 2019 - Aug 2022</div>
  </div>
  <div class="edu-item">
    <div class="edu-degree">Academic Excellence Award</div>
    <div class="edu-school">Yonsei University</div>
    <div class="edu-detail">For semester grades</div>
  </div>
</div>
