---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* ===== 作用域限定在正文，避免影响侧栏/导航 ===== */
.page__content .pub{
  display:flex; gap:20px; padding:16px; margin:14px 0; border-radius:12px;
  border:1px solid transparent; transition:background .15s ease, border-color .15s ease;
}
.page__content .pub:hover{ background:#f7f8fa; }
.page__content .pub.hl{ background:#fffdf4; border-color:#f2e3b3; }
.page__content .pub-thumb{ flex-shrink:0; width:200px; }
.page__content .pub-thumb img{
  width:200px; height:120px; object-fit:cover; border-radius:10px;
  border:1px solid #e6e8eb; background:#fff; display:block;
  box-shadow:0 2px 8px rgba(20,32,64,.06);
}
.page__content .pub-main{ flex:1; min-width:0; }
.page__content a.pub-title{
  font-weight:700; font-size:1.02rem; line-height:1.4; color:#2d2d2d;
  display:block; margin-bottom:4px; text-decoration:none;
}
.page__content a.pub-title:hover{ color:#2f7de1; }
.page__content .pub-authors{ font-size:.92rem; color:#6a737d; margin-bottom:4px; }
.page__content .pub-authors .me{ color:#2d2d2d; font-weight:700; }
.page__content .pub-venue{ font-size:.9rem; color:#2f7de1; font-weight:600; margin-bottom:4px; }
.page__content .pub-venue .tag{
  display:inline-block; margin-left:4px; padding:1px 8px; border-radius:10px;
  background:#eef0f2; color:#6a737d; font-size:.8rem; font-weight:600;
}
.page__content .pub-links{ font-size:.88rem; color:#8a939b; }
.page__content .pub-links a{ text-decoration:none; }

/* ===== 时间线（Experience / Education）===== */
.page__content .tl{ display:flex; flex-direction:column; margin:8px 0; }
.page__content .tl-item{
  display:flex; gap:16px; align-items:flex-start; padding:16px 0;
  border-bottom:1px solid #eef0f2;
}
.page__content .tl-item:last-child{ border-bottom:none; }
.page__content .orglogo{
  width:52px; height:52px; flex-shrink:0; border-radius:12px; object-fit:contain;
  background:#fff; border:1px solid #e6e8eb; padding:7px;
  box-shadow:0 1px 3px rgba(20,32,64,.07);
}
.page__content .tl-body{ flex:1; min-width:0; }
.page__content .tl-top{ display:flex; justify-content:space-between; align-items:baseline; gap:12px; flex-wrap:wrap; }
.page__content .tl-place{ font-weight:700; font-size:1.02rem; color:#2d2d2d; }
.page__content .tl-place a{ color:#2d2d2d; text-decoration:none; }
.page__content .tl-place a:hover{ color:#2f7de1; }
.page__content .tl-date{ font-size:.85rem; font-weight:600; color:#8a939b; white-space:nowrap; }
.page__content .tl-role{ font-size:.94rem; color:#6a737d; margin-top:3px; }
.page__content .tl-role em{ color:#2f7de1; font-style:normal; font-weight:600; }

/* ===== 响应式：窄屏堆叠 ===== */
@media(max-width:768px){
  .page__content .pub{ flex-direction:column; gap:12px; }
  .page__content .pub-thumb, .page__content .pub-thumb img{ width:100%; }
  .page__content .pub-thumb img{ height:150px; }
}
</style>

<span class="anchor" id="about-me"></span>

I am Jiangyang Li (李江洋), a Master's student in Artificial Intelligence at the MIV Lab, Xi'an Jiaotong University (2024–2027), advised by [Prof. Yihong Gong](https://scholar.google.com/citations?user=x2xdU7gAAAAJ&hl=en). I received my Bachelor's degree in Artificial Intelligence from Huazhong University of Science and Technology in 2024.

My research interests include Foundation Models, Multimodal Large Language Models (MLLMs), Reinforcement Learning, and World Models.

# 🔥 News
- *2026.06*: &nbsp;🎉 Started as a Research Intern at Bailing, Ant Group, working on Foundation Models and MLLMs.
- *2026.05*: &nbsp;🎉 **ReMoT** accepted to **CVPR 2026** as a **Highlight** (Top 3.8%)!
- *2026.02*: &nbsp;🎉 Three papers accepted to **CVPR 2026**.
- *2025.12*: &nbsp;🎉 Joined the CV Lab at Amap as a Research Intern.

# 📝 Publications
<sup>\* denotes equal contribution. First-author work is highlighted.</sup>

<div class="pub hl">
  <div class="pub-thumb"><img src="images/publications/prosr.jpg" alt="ProSR"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2605.25524">ProSR: Process-Shaped Spatial Reasoning for Reliable Chain-of-Thought in VLMs</a>
    <div class="pub-authors"><span class="me">Jiangyang Li</span>, Cong Wan, Changjie Wu, SongLin Dong, Lingjun Zhang, Linzhe Shi, Xu Wang, Zhiheng Ma, Hang Zhang, Mu Xu, Yihong Gong</div>
    <div class="pub-venue">NeurIPS 2026 <span class="tag">(Under review)</span></div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2605.25524">arXiv</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb"><img src="images/publications/dataclaw.jpg" alt="DataClaw"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2606.21337">DataClaw: Agentic Tailoring Multimodal Data from Raw Streams</a>
    <div class="pub-authors">Cong Wan, Zeyu Guo, Zijian Cai, <span class="me">Jiangyang Li</span>, SongLin Dong, Lin Peng, Xiangyang Luo, Zhiheng Ma, Yihong Gong</div>
    <div class="pub-venue">NeurIPS 2026 <span class="tag">(Under review)</span></div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2606.21337">arXiv</a> · <a href="https://czjdsg.github.io/MakeAnyData/">Project</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb"><img src="images/publications/vdc-agent.jpg" alt="VDC-Agent"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2511.19436">VDC-Agent: When Video Detailed Captioners Evolve Themselves via Agentic Self-Reflection</a>
    <div class="pub-authors">Qiang Wang, Xinyuan Gao, SongLin Dong, Jizhou Han, <span class="me">Jiangyang Li</span>, Yuhang He, Yihong Gong</div>
    <div class="pub-venue">ECCV 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2511.19436">arXiv</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb"><img src="images/publications/deepsight.jpg" alt="DeepSight"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2605.10564">DeepSight: Long-Horizon World Modeling via Latent States Prediction for End-to-End Autonomous Driving</a>
    <div class="pub-authors">Lingjun Zhang, Changjie Wu, Linzhe Shi, <span class="me">Jiangyang Li</span>, Jiaxin Liu, Lei Yang, Hang Zhang, Mu Xu, Hong Wang</div>
    <div class="pub-venue">ICML 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2605.10564">arXiv</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb"><img src="images/publications/remot.jpg" alt="ReMoT"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2603.00461">ReMoT: Reinforcement Learning with Motion Contrast Triplets</a>
    <div class="pub-authors">Cong Wan, Zeyu Guo, <span class="me">Jiangyang Li</span>, SongLin Dong, Yifan Bai, Lin Peng, Zhiheng Ma, Yihong Gong</div>
    <div class="pub-venue">CVPR 2026 <span class="tag">(Highlight, Top 3.8%)</span></div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2603.00461">arXiv</a></div>
  </div>
</div>

<div class="pub hl">
  <div class="pub-thumb"><img src="images/publications/hash.jpg" alt="Parameter Isolation"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2601.20894">Is Parameter Isolation Better for Prompt-Based Continual Learning?</a>
    <div class="pub-authors"><span class="me">Jiangyang Li</span>, Chenhao Ding, Songlin Dong, Qiang Wang, Jianchao Zhao, Yuhang He, Yihong Gong</div>
    <div class="pub-venue">CVPR 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2601.20894">arXiv</a></div>
  </div>
</div>

<div class="pub hl">
  <div class="pub-thumb"><img src="images/publications/navgrpo.jpg" alt="Trajectory-Diversity VLN"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2603.15370">Trajectory-Diversity-Driven: Robust Vision-and-Language Navigation</a>
    <div class="pub-authors"><span class="me">Jiangyang Li</span>, Cong Wan, SongLin Dong, Chenhao Ding, Qiang Wang, Zhiheng Ma, Yihong Gong</div>
    <div class="pub-venue">CVPR 2026 Findings</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2603.15370">arXiv</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb"><img src="images/publications/ctta.jpg" alt="Continual Test-Time Adaptation"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2507.00502">Shared & Domain Self-Adaptive Experts with Frequency-Aware Discrimination for Continual Test-Time Adaptation</a>
    <div class="pub-authors">Jianchao Zhao, Chenhao Ding, SongLin Dong, <span class="me">Jiangyang Li</span>, Qiang Wang, Yuhang He, Yihong Gong</div>
    <div class="pub-venue">AAAI 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2507.00502">arXiv</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb"><img src="images/publications/sulora.jpg" alt="SuLoRA"></div>
  <div class="pub-main">
    <a class="pub-title" href="https://aclanthology.org/2025.findings-acl.278/">SuLoRA: Subspace Low-Rank Adaptation for Parameter-Efficient Fine-Tuning</a>
    <div class="pub-authors">Chenhao Ding*, <span class="me">Jiangyang Li*</span>, Songlin Dong, Xinyuan Gao, Yuhang He, Yihong Gong</div>
    <div class="pub-venue">ACL 2025 Findings</div>
    <div class="pub-links"><a href="https://aclanthology.org/2025.findings-acl.278/">ACL Anthology</a></div>
  </div>
</div>

# 🎖 Honors and Awards
- Outstanding Undergraduate.
- Special-Class Scholarship.

# 💻 Internships

<div class="tl">
  <div class="tl-item">
    <img class="orglogo" src="images/logos/ant.jpg" alt="Ant Group">
    <div class="tl-body">
      <div class="tl-top">
        <span class="tl-place">Bailing, Ant Group</span>
        <span class="tl-date">Jun 2026 – Now</span>
      </div>
      <div class="tl-role">Research Intern · <em>Foundation Model, MLLM</em> · Shanghai · Led by <a href="https://scholar.google.com/citations?user=11HDEbkAAAAJ&hl=en">Qingpei Guo</a></div>
    </div>
  </div>
  <div class="tl-item">
    <img class="orglogo" src="images/logos/amap.jpg" alt="Amap">
    <div class="tl-body">
      <div class="tl-top">
        <span class="tl-place">CV Lab, Amap</span>
        <span class="tl-date">Dec 2025 – May 2026</span>
      </div>
      <div class="tl-role">Research Intern · <em>Multimodal Understanding, RL</em> · Beijing · Led by <a href="https://scholar.google.com/citations?user=JGi4S0EAAAAJ&hl=en">Mu Xu</a></div>
    </div>
  </div>
</div>

# 📖 Educations

<div class="tl">
  <div class="tl-item">
    <img class="orglogo" src="images/logos/xjtu.jpg" alt="Xi'an Jiaotong University">
    <div class="tl-body">
      <div class="tl-top">
        <span class="tl-place"><a href="http://en.xjtu.edu.cn/">Xi'an Jiaotong University</a></span>
        <span class="tl-date">Sep 2024 – Jun 2027</span>
      </div>
      <div class="tl-role">M.Eng. in Artificial Intelligence · MIV Lab · Advised by <a href="https://scholar.google.com/citations?user=x2xdU7gAAAAJ&hl=en">Prof. Yihong Gong</a></div>
    </div>
  </div>
  <div class="tl-item">
    <img class="orglogo" src="images/logos/hust.jpg" alt="Huazhong University of Science and Technology">
    <div class="tl-body">
      <div class="tl-top">
        <span class="tl-place"><a href="http://english.hust.edu.cn/">Huazhong University of Science and Technology</a></span>
        <span class="tl-date">Sep 2020 – Jun 2024</span>
      </div>
      <div class="tl-role">B.Eng. in Artificial Intelligence</div>
    </div>
  </div>
</div>

# 🧑‍🏫 Academic Service
- Conference Reviewer: NeurIPS.
