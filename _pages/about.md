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
  Hi! I’m Dayoon Ko 😊, a Ph.D. candidate in Computer Science and Engineering at Seoul National University, advised by <a href="https://vision.snu.ac.kr/gunhee/" target="_blank">Prof. Gunhee Kim</a>.
  Currently, I’m a visiting researcher at <strong>UC Berkeley</strong>, working with <a href="https://www.sewonmin.com/" target="_blank">Prof. Sewon Min</a>.
  <br><br>
  I’m broadly interested in how large language models can find, verify, and use information reliably in the noisy, fast-changing multimodal environments where people actually use them.
  <br><br>
  Right now, I’m working on <strong>on-device multimodal retrieval</strong>, where models must search over the photos, videos, and documents people keep on their own devices, under tight memory and compute budgets.
  I have worked on <strong>search agents</strong>, scaling their search reasoning, checking whether they verify what they claim, and evaluating them in realistic settings, as well as on <strong>keeping LLMs and RAG systems up to date</strong> as real-world knowledge evolves.
  <br><br>
  Outside of research, I enjoy dancing 💃 or doing CrossFit 🏋🏻‍♀️. Staying active keeps my brain happy!
</div>


<div class="news-section">
  <h2>🔥 Recent News</h2>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Oct 2026]</strong> Started a visiting research position at <strong>UC Berkeley</strong> with Prof. Sewon Min's group! 🐻
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Oct 2026]</strong> <strong>"ScholarCatalyst"</strong>, a benchmark for retrieving papers that inspire new research, is out on <a href="https://arxiv.org/abs/2610.02202" target="_blank">arXiv</a>!
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Sep 2026]</strong> <a href="https://arxiv.org/abs/2606.02404" target="_blank"><strong>"K-BrowseComp"</strong></a> has been accepted at <strong>EMNLP 2026 Findings</strong>! 🎉
  </div>
  <div class="news-item" style="margin-bottom: 12px;">
    <strong>[Sep 2026]</strong> <a href="https://arxiv.org/abs/2602.07549" target="_blank"><strong>"When Is Enough Not Enough? Illusory Completion in Search Agents"</strong></a> has been accepted at a <strong>COLM 2026 Workshop</strong>!
  </div>
  <!-- <div class="news-item" style="margin-bottom: 12px;">
    <strong>[May 2025]</strong> Two papers accepted at <strong>ACL 2025</strong>! "GradNormIR" (Findings) and "Can LLMs Deceive CLIP?" (Main)
  </div> -->
</div>

<h2 class="section-title">Selected Publications</h2>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/scholarcatalyst.png" alt="ScholarCatalyst">
  </div>
  <div class="pub-detail">
    <div class="pub-title">ScholarCatalyst: A Benchmark for Retrieving Papers That Inspire New Research</div>
    <div class="pub-authors">Sohyeon Kim, Yoonho Lee, Bo Liu, <strong>Dayoon Ko</strong>, Rulin Shao, Seungone Kim, Graham Neubig, Pang Wei Koh, Aakanksha Chowdhery, Akari Asai, Omar Khattab, Yejin Choi, Gunhee Kim, Chelsea Finn</div>
    <div class="pub-venue">arXiv 2026</div>
    <div class="pub-description">A literature inspiration retrieval benchmark grounded in researchers' firsthand knowledge of their own projects: 184 researchers who led 207 recent CS projects verified 894 research questions, labeling which prior papers did or could have advanced their work.</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2610.02202" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/stanford-iris-lab/ScholarCatalyst" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Code]</a>
      <a href="https://huggingface.co/datasets/ScholarCatalyst/ScholarCatalyst" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Dataset]</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/kbrowsecomp.png" alt="K-BrowseComp">
  </div>
  <div class="pub-detail">
    <div class="pub-title">K-BrowseComp: A Web Browsing Agent Benchmark Grounded in Korean Contexts</div>
    <div class="pub-authors">Nahyun Lee, Dongkeun Yoon, Guijin Son, Geewook Kim, <strong>Dayoon Ko</strong>, Jeonghun Park, Haneul Yoo, Jaewon Cho, Junghun Park, Changyoon Lee, Kyochul Jang, Jaeyeon Kim, Eunsu Kim, Woojin Cho, Seungone Kim</div>
    <div class="pub-venue">EMNLP 2026 Findings</div>
    <div class="pub-description">A 400-problem web-browsing agent benchmark grounded in Korean contexts, with a 300-problem subset verified by native Korean speakers. Frontier LLMs reach only 30–46% on the verified subset, a substantial drop from BrowseComp.</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2606.02404" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/prometheus-eval/K-BrowseComp" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/illusory_completion.png" alt="Illusory Completion">
  </div>
  <div class="pub-detail">
    <div class="pub-title">When Is Enough Not Enough? Illusory Completion in Search Agents</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jihyuk Kim, Sohyeon Kim, Haeju Park, Dahyun Lee, Gunhee Kim, Moontae Lee, Kyungjae Lee</div>
    <div class="pub-venue">COLM 2026 Workshop</div>
    <div class="pub-description">A correct final answer does not show whether a search agent verified every constraint. We introduce the Epistemic Ledger to evaluate verification along agent trajectories, revealing illusory completion: agents conclude while constraints remain assumed, refuted, or unchecked, even in their correct answers.</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2602.07549" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/illusory_completion" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/hds.png" alt="HybridDeepSearcher">
  </div>
  <div class="pub-detail">
    <div class="pub-title">Hybrid Deep Searcher: Scalable Parallel and Sequential Search Reasoning</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jihyuk Kim, Haeju Park, Sohyeon Kim, Dahyun Lee, Yongrae Jo, Gunhee Kim, Moontae Lee, Kyungjae Lee</div>
    <div class="pub-venue">ICLR 2026</div>
    <div class="pub-description">A scalable search agent that dynamically integrates parallel and sequential search strategies for multi-hop QA with RAG. We introduce the HDS-QA training dataset and achieve significant improvements.</div>
    <div style="margin-top: 10px;">
      <a href="https://openreview.net/forum?id=rXpTZyucal" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/HybridDeepSearcher" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Code]</a>
      <a href="https://hybriddeepsearcher.github.io/" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Project Page]</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/gradnormir.png" alt="GradNormIR">
  </div>
  <div class="pub-detail">
    <div class="pub-title">When Should Dense Retrievers Be Updated in Evolving Corpora? Detecting Out-of-Distribution Corpora Using GradNormIR</div>
    <div class="pub-authors"><strong>Dayoon Ko</strong>, Jinyoung Kim, Sohyeon Kim, Jinhyuk Kim, Jaehoon Lee, Seonghak Song, Minyoung Lee, Gunhee Kim</div>
    <div class="pub-venue">ACL 2025 Findings</div>
    <div class="pub-description">We propose GradNormIR, an unsupervised method that detects out-of-distribution shifts in document collections using gradient norms, enabling timely updates of dense retrievers without manual intervention.</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2506.01877" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/gradnormir" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/mac.png" alt="MAC">
  </div>
  <div class="pub-detail">
    <div class="pub-title">Can LLMs Deceive CLIP? Benchmarking Adversarial Compositionality of Pre-trained Multimodal Representation via Text Updates</div>
    <div class="pub-authors">Jaewoo Ahn, Heeseung Yun, <strong>Dayoon Ko</strong>, Gunhee Kim</div>
    <div class="pub-venue">ACL 2025</div>
    <div class="pub-description">We introduce MAC benchmark for evaluating the robustness of pre-trained multimodal models against adversarial text updates, revealing vulnerabilities in vision-language models like CLIP.</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2505.22943" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/ahnjaewoo/MAC" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-img">
    <img src="https://dayoon-ko.github.io/images/dynamicer.png" alt="DynamicER">
  </div>
  <div class="pub-detail">
    <div class="pub-title">DynamicER: Resolving Emerging Mentions to Dynamic Entities for RAG</div>
    <div class="pub-authors">Jinyoung Kim, <strong>Dayoon Ko</strong>, Gunhee Kim</div>
    <div class="pub-venue">EMNLP 2024</div>
    <div class="pub-description">This work addresses challenges in resolving temporally evolving mentions to entities. Resolving mentions is key to improving retrieval, enhancing RAG accuracy in dynamic environments.</div>
    <div style="margin-top: 10px;">
      <a href="https://arxiv.org/abs/2410.11494" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/jiny1623/DynamicER" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
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
    <div style="margin-top: 10px;">
      <a href="https://aclanthology.org/2024.acl-long.181/" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px; margin-right: 5px;">[Paper]</a>
      <a href="https://github.com/dayoon-ko/GrowOVER" target="_blank" style="color: #4a90e2; text-decoration: none; font-size: 14px;">[Code]</a>
    </div>
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
    <div class="edu-detail">Hosted by Professor Sewon Min</div>
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
    <div class="edu-detail">Advisor: Professor Gunhee Kim</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">September 2022 - Present</div>
  </div>

  <div class="edu-item">
    <div class="edu-degree">B.S. in Computer Science and Engineering</div>
    <div class="edu-school">Yonsei University</div>
    <div class="edu-detail">GPA: 4.12/4.30 (Rank: 1/28)</div>
    <div style="font-size: 14px; color: #888; font-style: italic; margin-top: 5px;">March 2018 - August 2022</div>
  </div>
</div>
