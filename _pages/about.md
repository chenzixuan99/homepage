---
permalink: /
title: "Zixuan Chen"
excerpt: ""
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

<h2 id="about-me">About Me</h2>
<p>I am currently a PhD student of the School of Computer Science and Technology in <a href="http://www.nju.edu.cn/">Nanjing University</a> and a member of <a href="https://cs.nju.edu.cn/rl/index.htm">R&L Group</a>, led by Professor <a href="https://cs.nju.edu.cn/gaoyang/index.htm">Yang Gao</a> and <a href="https://cs.nju.edu.cn/huojing/index.htm">Jing Huo</a>. I received my Bachelor's degree and my Master's degree from <a href="https://www.suda.edu.cn/">Soochow University</a>, under the supervision of Professor <a href="https://ai.nju.edu.cn/zhangzongzhang/index.htm">Zongzhang Zhang</a>. From November 2024, I will begin a one-year visiting at the <a href="https://www.nus.edu.sg/">National University of Singapore</a> under the supervision of Professor <a href="https://linsats.github.io/">Lin Shao</a>.</p>

<p>My research interest includes <strong>robot learning</strong>, <strong>reinforcement learning</strong> and <strong>imitation learning</strong>. Specifically, I am interested in two robot learning problems: 1) How to leverage prior knowledge to enhance a robot's capability in long-horizon tasks. 2) How to enable a robot to possess highly generalizable spatial intelligence in 3D environments.</p>

<h2 id="news">🔥 News</h2>
<ul>
    <li><strong>2025.01</strong>: 🎉🎉 Our <a href="https://arxiv.org/abs/2409.20154">GravMAD </a> is accepted to <a href="https://iclr.cc/">ICLR 2025</a>. <a href="https://gravmad.github.io/">Project</a></li>
   <li><strong>2025.01</strong>: 🎉🎉 One paper on <a href="https://arxiv.org/abs/2501.06605">Robotic World Model for Long-horizon Manipulation</a> is released. 
    <li><strong>2024.09</strong>: 🎉🎉 One paper on <a href="https://arxiv.org/abs/2409.20154">Generalized 3D Manipulation</a> is released. <a href="https://gravmad.github.io/">Project</a></li>
    <li><strong>2024.09</strong>: 🎉🎉 One paper on <a href="https://openreview.net/forum?id=RnxJc4vTVi&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2024%2FConference%2FAuthors%23your-submissions)">Skill Chaining for Long-horizon Manipulation</a> is accepted to <a href="https://neurips.cc/">NeurIPS 2024</a>.</li>
  <li><strong>2023.12</strong>: 🎉🎉 One paper on <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2204.pdf">Imitation Learning for Long-horizon Manipulation</a> is accepted to <a href="https://www.ifaamas.org/Proceedings/aamas2024/">AAMAS 2024</a>.</li>
  <li><strong>2023.01</strong>: 🎉🎉 One paper on <a href="https://www.ifaamas.org/Proceedings/aamas2023/pdfs/p2421.pdf">Third-person Imitation Learning for Robotics</a> is accepted to <a href="https://aamas2023.soton.ac.uk/">AAMAS 2023</a>.</li>
</ul>

<h2 id="publications">📝 Publications</h2>
<ul>
    <li>Yangtao Chen*, <strong>Zixuan Chen*</strong>, Junhui Yin, Jing Huo, Pinzhuo Tian, Jieqi Shi, Yang Gao.  
    <a href="https://arxiv.org/abs/2409.20154">GravMAD: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation</a>.   
    <em>In: ICLR 2025.</em>  
    <a href="https://gravmad.github.io/">Project</a></li>
    <li><strong>Zixuan Chen</strong>, Jing Huo, Yangtao Chen, Yang Gao.  
    <a href="https://arxiv.org/abs/2501.06605">RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation</a>.   
    <em>In: arXiv:2501.06605.</em> 
    <li><strong>Zixuan Chen</strong>, Ze Ji, Jing Huo, Yang Gao.  
    <a href="https://openreview.net/forum?id=RnxJc4vTVi&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2024%2FConference%2FAuthors%23your-submissions)">SCaR: Refining Skill Chaining for Long-Horizon Robotic Manipulation via Dual Regularization</a>.   
    <em>In: NeurIPS 2024.</em>  
    </li>
  <li><strong>Zixuan Chen</strong>, Ze Ji, Shuyang Liu, Jing Huo, Yiyu Chen, Yang Gao.  
    <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2204.pdf">Cognizing and Imitating Robotic Skills via a Dual
Cognition-Action Architecture</a>.   
    <em>In: AAMAS 2024.</em>  
    </li>
  <li><strong>Zixuan Chen</strong>, Wenbin Li, Yang Gao, Yiyu Chen.  
    <a href="https://www.ifaamas.org/Proceedings/aamas2023/pdfs/p2421.pdf">TiLD: Third-person Imitation Learning by Estimating Domain Cognitive Differences of Visual Demonstrations</a>.   
    <em>In: AAMAS 2023.</em>  
    </li>
  <li><strong>Zixuan Chen*</strong>, Zhirui Zhu*, Guang Yang, Yang Gao.  
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-20868-3_6">HiSA: Facilitating Efficient Multi-Agent Coordination and Cooperation by Hierarchical Policy with Shared Attention</a>.   
    <em>In: PRICAI 2022.</em>  
  </li>
  <li><strong>Zixuan Chen</strong>, Zongzhang Zhang.  
    <a href="https://link.springer.com/chapter/10.1007/978-3-030-30487-4_46">Deep Recurrent Policy Networks for Planning Under Partial Observability</a>.   
    <em>In: ICANN 2019.</em>  
  </li>
  <li><strong>Zixuan Chen</strong>, Zongzhang Zhang, Zhiyuan Pan, Linjing Zhang.  
    <a href="https://www.jos.org.cn/josen/article/abstract/6077">Planning Network Model Based on Generalized Asynchronous Value Iteration
(in Chinese)</a>.   
    <em>In: Journal of Software(软件学报) 2021.</em>  
  </li>
  <li>Zhenxing Ge, Shangdong Yang, Pinzhuo Tian, <strong>Zixuan Chen</strong>, Yang Gao.  
    <a href="https://ieeexplore.ieee.org/abstract/document/9999061/">Modeling Rationality: Toward Better Performance Against Unknown Agents in Sequential Games</a>.   
    <em>In: IEEE Transactions on Cybernetics.</em>  
  </li>
  <li>Chong Jiang, Zongzhang Zhang, <strong>Zixuan Chen</strong>, Jiacheng Zhu, Junpeng Jiang.  
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/7181">Third-Person Imitation Learning via Image Difference and Variational Discriminator Bottleneck</a>.   
    <em>In: AAAI 2019.</em>  
  </li>
  <li>Zhiyuan Pan, Zongzhang Zhang, <strong>Zixuan Chen</strong>.  
    <a href="https://link.springer.com/chapter/10.1007/978-3-030-04179-3_15">Asynchronous Value Iteration Network</a>.   
    <em>In: ICONIP 2018.</em>  
  </li>
  <li>Shuyang Liu*, <strong>Zixuan Chen*</strong>, Shi Ge, Ji Wang, Changjie Fan, Yu Xiong, Runze Wu Yujing Hu, Ze Ji, Yang Gao.  
    <a href="https://arxiv.org/pdf/2310.04821">Rethinking Baseline of Integrated Gradients from the Perspective of Shapley
Value</a>.   
    <em>In: arXiv:2310.04821.</em>  
  </li>
</ul>

<h2 id="honors-and-awards">🎖 Honors and Awards</h2>
<ul>
    <li><strong>2018.10</strong> Soochow University Graduate Academic Scholarship, Second Prize</li>
    <li><strong>2019.10</strong> Soochow University Graduate Academic Scholarship, First Prize</li>
    <li><strong>2020.6</strong> Outstanding Graduate Student of Soochow University</li>
    <li><strong>2022.10</strong> Nanjing University Graduate Talent Scholarship</li>
    <li><strong>2023.7</strong> 2023 China Scholarship Council - Visiting PhD Student</li>
</ul>

<h2 id="services">💼 Services</h2>
<ul>
    <li>Reviewer for ICLR, ICRA, TNNLS, PRCV, etc.</li>
</ul>

<h2 id="invited-talks">💬 Invited Talks</h2>
<ul>
    <li><strong>2019.07</strong>, CCML 2019, Guiyang, China.</li>
</ul>

<h2 id="internships">💻 Internships</h2>
<ul>
    <li><strong>2019.06 - 2019.10</strong>, <a href="http://fuxi.netease.com/laboratory">NetEase Fuxi Lab</a>, China.</li>
</ul>
