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
/* --- 全局字体与排版设置 --- */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif !important;
  font-size: 16px !important;
  line-height: 1.6 !important;
  color: #333;
}

/* 针对正文段落和列表的字体强制覆盖 */
p, li, a, div {
  font-family: inherit;
  font-size: inherit;
}

/* 标题样式微调 */
h1, h2, h3, h4 {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif !important;
  margin-top: 25px !important;
  margin-bottom: 12px !important;
  font-weight: 700 !important;
  color: #111;
}

h2 {
    border-bottom: 2px solid #f2f3f3;
    padding-bottom: 8px;
    font-size: 1.4em !important;
}

/* --- 隐藏顶部导航栏 --- */
.masthead, .site-nav, .greedy-nav, .navigation {
  display: none !important;
}
#main {
  margin-top: 30px !important;
}

/* --- 按钮样式 --- */
.btn-outline {
  display: inline-block;
  padding: 3px 8px;
  margin-right: 5px;
  margin-top: 5px;
  font-size: 12px !important;
  font-weight: 600;
  line-height: 1.2;
  color: #444;
  background-color: #fff;
  border: 1px solid #d1d5da;
  border-radius: 6px;
  text-decoration: none !important;
  transition: all 0.2s ease;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
}
.btn-outline:hover {
  background-color: #f3f4f6;
  border-color: #1b1f23;
  color: #000;
  transform: translateY(-1px);
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

/* --- 新闻区域 --- */
.news-box {
  height: 220px;
  overflow-y: scroll; 
  border: 1px solid #e1e4e8; 
  padding: 12px; 
  border-radius: 6px; 
  background-color: #fafbfc; 
  box-shadow: inset 0 0 4px rgba(0,0,0,0.02);
}
.news-date {
  font-family: 'Courier New', Courier, monospace !important;
  color: #666;
  font-weight: bold;
  margin-right: 8px;
  background-color: #f0f3f6;
  padding: 2px 5px;
  border-radius: 4px;
  font-size: 0.85em !important;
}

/* --- 论文列表间距 --- */
ul.pub-list li {
  margin-bottom: 20px !important;
}

/* --- 地图容器限制 --- */
.map-container {
    width: 250px;
    margin: 40px auto 20px auto;
    text-align: center;
}
</style>

<h2 id="about-me">About Me</h2>

<p>
Hi! I am <strong>Zixuan Chen (陈子璇)</strong>. I am currently a Ph.D. Candidate at the School of Computer Science and Technology, <a href="http://www.nju.edu.cn/">Nanjing University (NJU)</a>. I am a member of the <a href="https://cs.nju.edu.cn/rl/index.htm">R&L Group</a>, advised by Prof. <a href="https://is.nju.edu.cn/gy_en/main.htm">Yang Gao</a> and Assoc. Prof. <a href="https://cs.nju.edu.cn/huojing/index.htm">Jing Huo</a>. 
</p>

<p>
Previously, I received my B.E. and M.E. degrees from <a href="https://www.suda.edu.cn/">Soochow University</a>, School of Computer Science and Technology, under the supervision of Prof. <a href="https://ai.nju.edu.cn/zhangzongzhang/index.htm">Zongzhang Zhang</a>. From Nov. 2024 to Nov. 2025, I was a visiting student at the <a href="https://www.nus.edu.sg/">National University of Singapore (NUS)</a>, working with Prof. <a href="https://linsats.github.io/">Lin Shao</a>.
</p>

<h3 id="research-interests">🔬 Research Interests</h3>
<p>
My research focuses on <strong>Robot Learning</strong>, <strong>Reinforcement Learning</strong>, and <strong>Imitation Learning</strong>. I am particularly interested in:
</p>
<ul>
    <li><strong>Long-horizon Manipulation:</strong> Leveraging prior knowledge (e.g., skill chaining, task decomposition) to solve complex, multi-stage tasks.</li>
    <li><strong>Spatial Intelligence:</strong> Enabling robots to possess highly generalizable 3D spatial reasoning capabilities (e.g., 3D manipulation, world models).</li>
</ul>

---

<h2 id="news">🔥 News</h2>
<div class="news-box">
<ul style="padding-left: 20px; margin-top: 0;">
  <li><span class="news-date">2026.01</span> 🎉 4 papers (RoTri-Diff, LaViRA, AdaptPNP and LISN) were accepted to <strong>ICRA 2026</strong>.</li>
  <li><span class="news-date">2026.01</span> 🎉 "DeCo" was accepted to <strong>RAL 2026</strong>.</li>
  <li><span class="news-date">2025.11</span> 🎉 "ManiLong-Shot" was accepted to <strong>AAAI 2026</strong>.</li>
  <li><span class="news-date">2025.10</span> Preprint "<a href="https://chenyt31.github.io/robo-himan.github.io/">RoboHiMan</a>" (Compositional Generalization in Long-horizon Manipulation) was released.</li>
  <li><span class="news-date">2025.05</span> Preprint "<a href="https://arxiv.org/abs/2505.00527">DeCo</a>"(Task Decomposition and Skill Composition for Long-horizon Manipulation) was released.</li>
  <li><span class="news-date">2025.01</span> 🎉 "GravMAD" was accepted to <strong>ICLR 2025</strong>.</li>
  <li><span class="news-date">2025.01</span> Preprint "<a href="https://arxiv.org/abs/2501.06605">RoboHorizon</a>" (World Model for Long-horizon Manipulation) was released.</li> 
  <li><span class="news-date">2024.09</span> 🎉 "SCaR" (Skill Chaining) was accepted to <strong>NeurIPS 2024</strong>.</li>
  <li><span class="news-date">2023.12</span> 🎉 "Cognizing and Imitating Robotic Skills" was accepted to <strong>AAMAS 2024</strong>.</li>
  <li><span class="news-date">2023.01</span> 🎉 "TiLD" was accepted to <strong>AAMAS 2023</strong>.</li>
</ul>
</div>

---

<h2 id="publications">📝 Selected Publications</h2>

<p style="font-size: 0.9em !important; color: #666;">(* equal contribution)</p>

<ul class="pub-list">
    <!-- Paper 0 -->
    <li>
        <strong>DeCo: Task Decomposition and Skill Composition for Zero-Shot Generalization in Long-Horizon 3D Manipulation</strong><br>
        <strong>Zixuan Chen</strong>, Junhui Yin, Yangtao Chen, Jing Huo, Pinzhuo Tian, Jieqi Shi, Yiwen Hou, Yinchuan Li, Yang Gao.<br>
        <em>IEEE Robotics and Automation Letters (<strong>RAL</strong>)</em>, 2026.<br>
        <a href="https://arxiv.org/abs/2505.00527" class="btn-outline">📄 PDF</a>
        <a href="https://deco226.github.io/" class="btn-outline">🌐 Website</a>
        <a href="https://github.com/chenzixuan99/RoboHiMan" class="btn-outline">💻 Code</a>
    </li>

    <!-- Paper 0 -->
    <li>
        <strong>ManiLong-Shot: Interaction-Aware One-Shot Imitation Learning for Long-Horizon Manipulation</strong><br>
        <strong>Zixuan Chen</strong>, Chongkai Gao, Lin Shao, Jieqi Shi, Jing Huo, Yang Gao.<br>
        <em>AAAI Conference on Artificial Intelligence (<strong>AAAI</strong>)</em>, 2026.<br>
        <a href="https://arxiv.org/abs/2512.16302" class="btn-outline">📄 PDF</a>
    </li>

    <!-- Paper 1 (Updated with Code Link) -->
    <li>
        <strong>RoboHiMan: A Hierarchical Evaluation Paradigm for Compositional Generalization in Long-Horizon Manipulation</strong><br>
        Yangtao Chen*, <strong>Zixuan Chen*</strong>, Nga Teng Chan, Junting Chen, Junhui Yin, Jieqi Shi, Yang Gao, Yong-Lu Li, Jing Huo.<br>
        <em>arXiv preprint arXiv:2510.13149</em>, 2025.<br>
        <a href="https://arxiv.org/abs/2510.13149" class="btn-outline">📄 PDF</a>
        <a href="https://chenyt31.github.io/robo-himan.github.io/" class="btn-outline">🌐 Website</a>
        <!-- PLEASE CHECK THIS LINK BELOW -->
        <a href="https://github.com/chenyt31/RoboHiMan" class="btn-outline">💻 Code</a>
    </li>


    <!-- Paper 3 -->
    <li>
        <strong>GravMAD: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation</strong><br>
        Yangtao Chen*, <strong>Zixuan Chen*</strong>, Junhui Yin, Jing Huo, Pinzhuo Tian, Jieqi Shi, Yang Gao.<br>
        <em>International Conference on Learning Representations (<strong>ICLR</strong>)</em>, 2025.<br>
        <a href="https://arxiv.org/abs/2409.20154" class="btn-outline">📄 PDF</a>
        <a href="https://gravmad.github.io/" class="btn-outline">🌐 Website</a>
    </li>

    <!-- Paper 4 -->
    <li>
        <strong>RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation</strong><br>
        <strong>Zixuan Chen</strong>, Jing Huo, Yangtao Chen, Yang Gao.<br>
        <em>arXiv preprint arXiv:2501.06605</em>, 2025.<br>
        <a href="https://arxiv.org/abs/2501.06605" class="btn-outline">📄 PDF</a>
    </li>

    <!-- Paper 5 -->
    <li>
        <strong>SCaR: Refining Skill Chaining for Long-Horizon Robotic Manipulation via Dual Regularization</strong><br>
        <strong>Zixuan Chen</strong>, Ze Ji, Jing Huo, Yang Gao.<br>
        <em>Conference on Neural Information Processing Systems (<strong>NeurIPS</strong>)</em>, 2024.<br>
        <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/ca92ff06d973ece92cecc561757d500e-Paper-Conference.pdf" class="btn-outline">📄 PDF</a>
    </li>

    <!-- Paper 6 -->
    <li>
        <strong>Cognizing and Imitating Robotic Skills via a Dual Cognition-Action Architecture</strong><br>
        <strong>Zixuan Chen</strong>, Ze Ji, Shuyang Liu, Jing Huo, Yiyu Chen, Yang Gao.<br>
        <em>International Conference on Autonomous Agents and Multiagent Systems (<strong>AAMAS</strong>)</em>, 2024.<br>
        <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2204.pdf" class="btn-outline">📄 PDF</a>
    </li>

    <!-- Paper 7 -->
    <li>
        <strong>TiLD: Third-person Imitation Learning by Estimating Domain Cognitive Differences of Visual Demonstrations</strong><br>
        <strong>Zixuan Chen</strong>, Wenbin Li, Yang Gao, Yiyu Chen.<br>
        <em>International Conference on Autonomous Agents and Multiagent Systems (<strong>AAMAS</strong>)</em>, 2023.<br>
        <a href="https://www.ifaamas.org/Proceedings/aamas2023/pdfs/p2421.pdf" class="btn-outline">📄 PDF</a>
    </li>
</ul>

<h2 id="honors-and-awards">🎖 Honors and Awards</h2>
<ul>
    <li><strong>2023.07</strong> China Scholarship Council (CSC) Scholarship</li>
    <li><strong>2022.10</strong> Nanjing University Graduate Talent Scholarship</li>
    <li><strong>2020.06</strong> Outstanding Graduate Student of Soochow University</li>
    <li><strong>2019.10</strong> Soochow University Graduate Academic Scholarship, First Prize</li>
    <li><strong>2018.10</strong> Soochow University Graduate Academic Scholarship, Second Prize</li>
</ul>

<h2 id="services">💼 Services</h2>
<ul>
    <li><strong>Conference Reviewer:</strong> NeurIPS, ICLR, ICRA, IROS, CoRL, AAAI, CVPR</li>
    <li><strong>Journal Reviewer:</strong> IEEE TNNLS, RA-L, TASE</li>
</ul>

<h2 id="internships">💻 Internships</h2>
<ul>
    <li><strong>2019.06 - 2019.10</strong>: Research Intern at <a href="http://fuxi.netease.com/laboratory">NetEase Fuxi Lab</a>, Hangzhou, China.</li>
</ul>

<div class="map-container">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=La_fIwpyduMFqQH5lyX5DOWJy0lqFKQ8XyXviIbi7ls&cl=ffffff&w=300"></script>
</div>
