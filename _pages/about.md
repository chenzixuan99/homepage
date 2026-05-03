---
permalink: /
title: "Zixuan Chen (陈子璇)"
excerpt: "Ph.D. Candidate at Nanjing University"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<style>
/* ---------- Global ---------- */
html {
  scroll-behavior: smooth;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif !important;
  font-size: 16px !important;
  line-height: 1.7 !important;
  color: #334155;
  background: #fafbfc;
}

p, li, a, div, span {
  font-family: inherit;
  font-size: inherit;
}

a {
  color: #2563eb;
  text-decoration: none;
}

a:hover {
  color: #1d4ed8;
  text-decoration: underline;
}

h1, h2, h3, h4 {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif !important;
  font-weight: 700 !important;
  color: #0f172a;
  margin-top: 25px !important;
  margin-bottom: 12px !important;
}

h2 {
  font-size: 1.42em !important;
  border-bottom: 1px solid #edf1f5;
  padding-bottom: 10px;
}

h3 {
  font-size: 1.12em !important;
}

/* ---------- Hide top nav ---------- */
.masthead, .site-nav, .greedy-nav, .navigation {
  display: none !important;
}

#main {
  margin-top: 28px !important;
}

/* ---------- Section cards ---------- */
.section-card {
  background: #ffffff;
  border: 1px solid #e8edf3;
  border-radius: 18px;
  padding: 22px 24px;
  margin-bottom: 24px;
  box-shadow: 0 10px 28px rgba(15, 23, 42, 0.05);
}

.section-card h2:first-child,
.section-card h3:first-child {
  margin-top: 0 !important;
}

.lead-text {
  color: #475569;
}

.tag-row {
  margin-top: 14px;
}

.tag-chip {
  display: inline-block;
  background: #eff6ff;
  color: #1d4ed8;
  border: 1px solid #dbeafe;
  border-radius: 999px;
  padding: 4px 10px;
  margin-right: 8px;
  margin-top: 8px;
  font-size: 0.88em !important;
  font-weight: 600;
}

/* ---------- Buttons ---------- */
.btn-outline {
  display: inline-block;
  padding: 4px 10px;
  margin-right: 6px;
  margin-top: 8px;
  font-size: 12px !important;
  font-weight: 600;
  line-height: 1.2;
  color: #334155;
  background-color: #ffffff;
  border: 1px solid #d6dee8;
  border-radius: 999px;
  text-decoration: none !important;
  transition: all 0.2s ease;
  box-shadow: 0 1px 2px rgba(0,0,0,0.03);
}

.btn-outline:hover {
  background-color: #eff6ff;
  border-color: #93c5fd;
  color: #1d4ed8;
  transform: translateY(-1px);
  box-shadow: 0 4px 10px rgba(37, 99, 235, 0.08);
}

/* ---------- News ---------- */
.news-box {
  max-height: 260px;
  overflow-y: auto;
  padding: 4px 4px 4px 2px;
}

.news-list {
  list-style: none;
  padding-left: 14px;
  margin: 0;
  border-left: 2px solid #e2e8f0;
}

.news-list li {
  position: relative;
  margin-bottom: 14px;
  padding-left: 18px;
  color: #334155;
}

.news-list li::before {
  content: "";
  position: absolute;
  left: -6px;
  top: 0.72em;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #60a5fa;
  border: 2px solid #ffffff;
  box-shadow: 0 0 0 2px #dbeafe;
  transform: translateY(-50%);
}

.news-date {
  font-family: "Courier New", Courier, monospace !important;
  color: #475569;
  font-weight: 700;
  margin-right: 8px;
  background-color: #f1f5f9;
  padding: 2px 7px;
  border-radius: 6px;
  font-size: 0.84em !important;
}

/* custom scrollbar */
.news-box::-webkit-scrollbar {
  width: 8px;
}
.news-box::-webkit-scrollbar-track {
  background: #f8fafc;
  border-radius: 8px;
}
.news-box::-webkit-scrollbar-thumb {
  background: #cbd5e1;
  border-radius: 8px;
}
.news-box::-webkit-scrollbar-thumb:hover {
  background: #94a3b8;
}

/* ---------- Publications ---------- */
.pub-note {
  font-size: 0.92em !important;
  color: #64748b;
  margin-bottom: 14px;
}

.year-badge {
  display: inline-block;
  background: linear-gradient(135deg, #eff6ff 0%, #eef2ff 100%);
  color: #1e40af;
  border: 1px solid #dbeafe;
  border-radius: 999px;
  padding: 5px 12px;
  margin: 10px 0 14px 0;
  font-size: 0.95em !important;
  font-weight: 700;
  letter-spacing: 0.2px;
}

.pub-list {
  list-style: none;
  padding-left: 0;
  margin-top: 0;
}

.pub-card {
  margin-bottom: 16px !important;
  background: linear-gradient(180deg, #ffffff 0%, #fcfdff 100%);
  border: 1px solid #e7ecf3;
  border-left: 4px solid #4f46e5;
  border-radius: 14px;
  padding: 16px 18px;
  transition: all 0.22s ease;
}

.pub-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 24px rgba(15, 23, 42, 0.08);
  border-color: #d7e0ea;
}

.paper-title {
  font-size: 1.02em !important;
  font-weight: 700;
  color: #0f172a;
  margin-bottom: 6px;
}

.paper-authors {
  color: #475569;
}

.paper-venue {
  color: #334155;
  margin-top: 4px;
}

.paper-links {
  margin-top: 4px;
}

/* ---------- Lists ---------- */
.interest-list li,
.simple-list li {
  margin-bottom: 10px;
}

/* ---------- Two-column layout ---------- */
.info-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 24px;
}

/* ---------- Map ---------- */
.map-card {
  text-align: center;
}

.map-container {
  width: 250px;
  margin: 0 auto;
  text-align: center;
}

/* ---------- Responsive ---------- */
@media (max-width: 768px) {
  .section-card {
    padding: 18px 16px;
    border-radius: 14px;
  }

  .info-grid {
    grid-template-columns: 1fr;
    gap: 0;
  }

  .news-box {
    max-height: none;
  }

  .pub-card {
    padding: 14px 14px;
  }
}
</style>

<div class="section-card">
  <h2 id="about-me">About Me</h2>

  <p class="lead-text">
    Hi! I am <strong>Zixuan Chen (陈子璇)</strong>. I received my Ph.D. degree from the School of Computer Science and Technology, <a href="http://www.nju.edu.cn/">Nanjing University (NJU)</a> in March 2026, advised by Prof. <a href="https://is.nju.edu.cn/gy_en/main.htm">Yang Gao</a> and Assoc. Prof. <a href="https://cs.nju.edu.cn/huojing/index.htm">Jing Huo</a>. I will be joining the <a href="https://is.nju.edu.cn/">School of Intelligent Science and Technology</a>, Nanjing University (Suzhou Campus).
  </p>

  <p>
    Previously, I received my B.E. and M.E. degrees from <a href="https://www.suda.edu.cn/">Soochow University</a>, School of Computer Science and Technology, under the supervision of Prof. <a href="https://ai.nju.edu.cn/zhangzongzhang/index.htm">Zongzhang Zhang</a>. From Nov. 2024 to Nov. 2025, I was a visiting student at the <a href="https://www.nus.edu.sg/">National University of Singapore (NUS)</a>, working with Prof. <a href="https://linsats.github.io/">Lin Shao</a>.
  </p>

  <h3 id="research-interests">🔬 Research Interests</h3>
  <p>
    My research focuses on <strong>Robot Learning</strong>, <strong>Reinforcement Learning</strong>, and <strong>Imitation Learning</strong>. I am particularly interested in:
  </p>
  <ul class="interest-list">
    <li><strong>Long-horizon Manipulation:</strong> Leveraging prior knowledge (e.g., skill chaining, task decomposition) to solve complex, multi-stage tasks.</li>
    <li><strong>Spatial Intelligence:</strong> Enabling robots to possess highly generalizable 3D spatial reasoning capabilities (e.g., 3D manipulation, world models).</li>
  </ul>

  <div class="tag-row">
    <span class="tag-chip">Robot Learning</span>
    <span class="tag-chip">Reinforcement Learning</span>
    <span class="tag-chip">Imitation Learning</span>
    <span class="tag-chip">Long-horizon Manipulation</span>
    <span class="tag-chip">Spatial Intelligence</span>
  </div>
</div>

<div class="section-card">
  <h2 id="news">🔥 News</h2>
  <div class="news-box">
    <ul class="news-list">
      <li><span class="news-date">2026.04</span> 🎤 Invited talk at <strong>Zhuoyu Technology (卓驭科技)</strong>, Shenzhen, China.</li>
      <li><span class="news-date">2026.02</span> 🎉 "AGiLe" was accepted to <strong>CVPR 2026</strong>.</li>
      <li><span class="news-date">2026.01</span> 🎉 4 papers (RoTri-Diff, LaViRA, AdaptPNP and LISN) were accepted to <strong>ICRA 2026</strong>.</li>
      <li><span class="news-date">2026.01</span> 🎉 "DeCo" was accepted to <strong>RAL 2026</strong>.</li>
      <li><span class="news-date">2025.11</span> 🎉 "ManiLong-Shot" was accepted to <strong>AAAI 2026</strong>.</li>
      <li><span class="news-date">2025.10</span> Preprint "<a href="https://chenyt31.github.io/robo-himan.github.io/">RoboHiMan</a>" (Compositional Generalization in Long-horizon Manipulation) was released.</li>
      <li><span class="news-date">2025.05</span> Preprint "<a href="https://arxiv.org/abs/2505.00527">DeCo</a>" (Task Decomposition and Skill Composition for Long-horizon Manipulation) was released.</li>
      <li><span class="news-date">2025.01</span> 🎉 "GravMAD" was accepted to <strong>ICLR 2025</strong>.</li>
      <li><span class="news-date">2025.01</span> Preprint "<a href="https://arxiv.org/abs/2501.06605">RoboHorizon</a>" (World Model for Long-horizon Manipulation) was released.</li>
      <li><span class="news-date">2024.09</span> 🎉 "SCaR" (Skill Chaining) was accepted to <strong>NeurIPS 2024</strong>.</li>
      <li><span class="news-date">2023.12</span> 🎉 "Cognizing and Imitating Robotic Skills" was accepted to <strong>AAMAS 2024</strong>.</li>
      <li><span class="news-date">2023.01</span> 🎉 "TiLD" was accepted to <strong>AAMAS 2023</strong>.</li>
    </ul>
  </div>
</div>

<div class="section-card">
  <h2 id="publications">📝 Selected Publications</h2>
  <p class="pub-note">(* equal contribution)</p>

  <div class="year-badge">2026</div>
  <ul class="pub-list">
    <li class="pub-card">
      <div class="paper-title">AGiLe: Learning Robust Long-Horizon Manipulation via Affordance-Grounded Bidirectional Latent Planning</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Xiangrong Feng, Jieqi Shi, Lin Shao, Jing Huo, Yang Gao.</div>
      <div class="paper-venue"><em>IEEE/CVF Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>)</em>, 2026.</div>
    </li>

    <li class="pub-card">
      <div class="paper-title">RoTri-Diff: A Spatial Robot-Object Triadic Interaction-Guided Diffusion Model for Bimanual Manipulation</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Nga Teng Chan, Yiwen Hou, Chenrui Tie, Zixuan Liu, Haonan Chen, Junting Chen, Jieqi Shi, Yang Gao, Jing Huo, Lin Shao.</div>
      <div class="paper-venue"><em>IEEE International Conference on Robotics and Automation (<strong>ICRA</strong>)</em>, 2026.</div>
      <div class="paper-links">
        <a href="https://arxiv.org/abs/2603.07165" class="btn-outline">📄 PDF</a>
      </div>
    </li>

    <li class="pub-card">
      <div class="paper-title">DeCo: Task Decomposition and Skill Composition for Zero-Shot Generalization in Long-Horizon 3D Manipulation</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Junhui Yin, Yangtao Chen, Jing Huo, Pinzhuo Tian, Jieqi Shi, Yiwen Hou, Yinchuan Li, Yang Gao.</div>
      <div class="paper-venue"><em>IEEE Robotics and Automation Letters (<strong>RAL</strong>)</em>, 2026.</div>
      <div class="paper-links">
        <a href="https://arxiv.org/abs/2505.00527" class="btn-outline">📄 PDF</a>
        <a href="https://deco226.github.io/" class="btn-outline">🌐 Website</a>
        <a href="https://github.com/chenzixuan99/RoboHiMan" class="btn-outline">💻 Code</a>
      </div>
    </li>

    <li class="pub-card">
      <div class="paper-title">ManiLong-Shot: Interaction-Aware One-Shot Imitation Learning for Long-Horizon Manipulation</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Chongkai Gao, Lin Shao, Jieqi Shi, Jing Huo, Yang Gao.</div>
      <div class="paper-venue"><em>AAAI Conference on Artificial Intelligence (<strong>AAAI</strong>)</em>, 2026.</div>
      <div class="paper-links">
        <a href="https://arxiv.org/abs/2512.16302" class="btn-outline">📄 PDF</a>
      </div>
    </li>
  </ul>

  <div class="year-badge">2025</div>
  <ul class="pub-list">
    <li class="pub-card">
      <div class="paper-title">RoboHiMan: A Hierarchical Evaluation Paradigm for Compositional Generalization in Long-Horizon Manipulation</div>
      <div class="paper-authors">Yangtao Chen*, <strong>Zixuan Chen*</strong>, Nga Teng Chan, Junting Chen, Junhui Yin, Jieqi Shi, Yang Gao, Yong-Lu Li, Jing Huo.</div>
      <div class="paper-venue"><em>arXiv preprint arXiv:2510.13149</em>, 2025.</div>
      <div class="paper-links">
        <a href="https://arxiv.org/abs/2510.13149" class="btn-outline">📄 PDF</a>
        <a href="https://chenyt31.github.io/robo-himan.github.io/" class="btn-outline">🌐 Website</a>
        <a href="https://github.com/chenyt31/RoboHiMan" class="btn-outline">💻 Code</a>
      </div>
    </li>

    <li class="pub-card">
      <div class="paper-title">GravMAD: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation</div>
      <div class="paper-authors">Yangtao Chen*, <strong>Zixuan Chen*</strong>, Junhui Yin, Jing Huo, Pinzhuo Tian, Jieqi Shi, Yang Gao.</div>
      <div class="paper-venue"><em>International Conference on Learning Representations (<strong>ICLR</strong>)</em>, 2025.</div>
      <div class="paper-links">
        <a href="https://arxiv.org/abs/2409.20154" class="btn-outline">📄 PDF</a>
        <a href="https://gravmad.github.io/" class="btn-outline">🌐 Website</a>
      </div>
    </li>

    <li class="pub-card">
      <div class="paper-title">RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Jing Huo, Yangtao Chen, Yang Gao.</div>
      <div class="paper-venue"><em>arXiv preprint arXiv:2501.06605</em>, 2025.</div>
      <div class="paper-links">
        <a href="https://arxiv.org/abs/2501.06605" class="btn-outline">📄 PDF</a>
      </div>
    </li>
  </ul>

  <div class="year-badge">2024</div>
  <ul class="pub-list">
    <li class="pub-card">
      <div class="paper-title">SCaR: Refining Skill Chaining for Long-Horizon Robotic Manipulation via Dual Regularization</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Ze Ji, Jing Huo, Yang Gao.</div>
      <div class="paper-venue"><em>Conference on Neural Information Processing Systems (<strong>NeurIPS</strong>)</em>, 2024.</div>
      <div class="paper-links">
        <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/ca92ff06d973ece92cecc561757d500e-Paper-Conference.pdf" class="btn-outline">📄 PDF</a>
      </div>
    </li>

    <li class="pub-card">
      <div class="paper-title">Cognizing and Imitating Robotic Skills via a Dual Cognition-Action Architecture</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Ze Ji, Shuyang Liu, Jing Huo, Yiyu Chen, Yang Gao.</div>
      <div class="paper-venue"><em>International Conference on Autonomous Agents and Multiagent Systems (<strong>AAMAS</strong>)</em>, 2024.</div>
      <div class="paper-links">
        <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2204.pdf" class="btn-outline">📄 PDF</a>
      </div>
    </li>
  </ul>

  <div class="year-badge">2023</div>
  <ul class="pub-list">
    <li class="pub-card">
      <div class="paper-title">TiLD: Third-person Imitation Learning by Estimating Domain Cognitive Differences of Visual Demonstrations</div>
      <div class="paper-authors"><strong>Zixuan Chen</strong>, Wenbin Li, Yang Gao, Yiyu Chen.</div>
      <div class="paper-venue"><em>International Conference on Autonomous Agents and Multiagent Systems (<strong>AAMAS</strong>)</em>, 2023.</div>
      <div class="paper-links">
        <a href="https://www.ifaamas.org/Proceedings/aamas2023/pdfs/p2421.pdf" class="btn-outline">📄 PDF</a>
      </div>
    </li>
  </ul>
</div>

<div class="info-grid">
  <div class="section-card">
    <h2 id="honors-and-awards">🎖 Honors and Awards</h2>
    <ul class="simple-list">
      <li><strong>2023.07</strong> China Scholarship Council (CSC) Scholarship</li>
      <li><strong>2022.10</strong> Nanjing University Graduate Talent Scholarship</li>
      <li><strong>2020.06</strong> Outstanding Graduate Student of Soochow University</li>
      <li><strong>2019.10</strong> Soochow University Graduate Academic Scholarship, First Prize</li>
      <li><strong>2018.10</strong> Soochow University Graduate Academic Scholarship, Second Prize</li>
    </ul>
  </div>

  <div class="section-card">
    <h2 id="services">💼 Services</h2>
    <ul class="simple-list">
      <li><strong>Conference Reviewer:</strong> NeurIPS, ICLR, ICRA, IROS, CoRL, AAAI, CVPR</li>
      <li><strong>Journal Reviewer:</strong> IEEE TNNLS, RA-L, TASE</li>
    </ul>
  </div>
</div>

<div class="section-card">
  <h2 id="internships">💻 Internships</h2>
  <ul class="simple-list">
    <li><strong>2019.06 - 2019.10</strong>: Research Intern at <a href="http://fuxi.netease.com/laboratory">NetEase Fuxi Lab</a>, Hangzhou, China.</li>
  </ul>
</div>

<div class="section-card map-card">
  <h2 id="visitors">🌍 Visitors</h2>
  <div class="map-container">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=La_fIwpyduMFqQH5lyX5DOWJy0lqFKQ8XyXviIbi7ls&cl=ffffff&w=300"></script>
  </div>
</div>
