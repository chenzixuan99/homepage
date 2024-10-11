---
permalink: /
title: ""
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

<span class='anchor' id='about-me'></span>


I'm currently a PhD student of the Department of Computer Science and Technology in [Nanjing University](http://www.nju.edu.cn/) and a member of [R&L Group](https://cs.nju.edu.cn/rl/index.htm), led by professor [Yang Gao](https://cs.nju.edu.cn/gaoyang/index.htm) and [Jing Huo](https://cs.nju.edu.cn/huojing/index.htm). I received my Bachelor degree in June 2017 from [Soochow University of China](https://www.suda.edu.cn/) and Master degree in June 2020 from [Soochow University of China](https://www.suda.edu.cn/) adversed by professor [Zongzhang Zhang](https://ai.nju.edu.cn/zhangzongzhang/index.htm).

My research interest includes computer vision and computer graphics. Particularly in **Few-Shot Semantic Segmentation**, **Multimodal Perception** **3D Gaussian Splatting** and **Neural Radiance Fields** 



# 🔥 News
- *2024.09*: &nbsp;🎉🎉 I was invited to become reviewers in ICLR 2025, AISTATS 2025, ICASSP 2025, WACV 2025.
- *2024.07*: &nbsp;🎉🎉 [**3D Gaussian Splatting: Survey, Technologies, Challenges, and Opportunities**](https://arxiv.org/pdf/2407.17418) is released. [**Project**](https://github.com/qqqqqqy0227/awesome-3DGS)
- *2024.05*: &nbsp;🎉🎉 One paper on [**Zero-Shot Video Editing**](https://arxiv.org/pdf/2406.04888) is released.
- *2024.04*: &nbsp;🎉🎉 One paper on [**Few-Shot Semantic Segmentation**](https://ieeexplore.ieee.org/abstract/document/9440451/) selected as an ESI Highly Cited Paper.
- *2024.04*: &nbsp;🎉🎉 One paper on [**Multimodal Perception**](https://ieeexplore.ieee.org/abstract/document/9493207/) selected as an ESI Highly Cited Paper.
- *2024.01*: &nbsp;🎉🎉 One paper on [**Neural Radiance Fields (NeRF)**](https://openreview.net/forum?id=aHmNpLlUlb) is accepted to [ICLR 2024](https://iclr.cc/Conferences/2024).
- *2023.07*: &nbsp;🎉🎉 One paper on [**Neural Radiance Fields (NeRF)**](https://dl.acm.org/doi/abs/10.1145/3581783.3613769) is accepted to [ACM MM 2023](https://dl.acm.org/doi/proceedings/10.1145/3581783).
- *2023.05*: &nbsp;🎉🎉 One paper on [**Few-Shot Semantic Segmentation**](https://ieeexplore.ieee.org/abstract/document/10015881/) is accepted to [IEEE Transactions on Instrumentation and Measurement](https://ieeexplore.ieee.org/document/9031597).
- *2023.04*: &nbsp;🎉🎉 One paper on [**Multimodal Perception**](https://ieeexplore.ieee.org/abstract/document/9931143/) is accepted to [IEEE/ASME Transactions on Mechatronics](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=3516).
- *2022.08*: &nbsp;🎉🎉 One paper on [**Few-Shot Semantic Segmentation**](https://arxiv.org/pdf/2301.03194) is accepted to [BMVC 2022 Oral](https://bmvc2022.org/).
- *2022.03*: &nbsp;🎉🎉 One paper on [**Few-Shot Semantic Segmentation**](http://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Dynamic_Prototype_Convolution_Network_for_Few-Shot_Semantic_Segmentation_CVPR_2022_paper.pdf) is accepted to [CVPR 2022](https://cvpr2022.thecvf.com/).
- *2021.08*: &nbsp;🎉🎉 One paper on [**Multimodal Perception**](https://ieeexplore.ieee.org/abstract/document/9493207/) is accepted to [IEEE Transactions on Circuits and Systems for Video Technology](https://xplorestaging.ieee.org/xpl/mostRecentIssue.jsp?punumber=76).
- *2021.05*: &nbsp;🎉🎉 One paper on [**Few-Shot Semantic Segmentation**](https://ieeexplore.ieee.org/abstract/document/9440451/) is accepted to [IEEE Transactions on Instrumentation and Measurement](https://ieeexplore.ieee.org/document/9031597).

# 📝 Publications 


- **Yanqi Bao**, Tianyu Ding, Jing Huo, Yaoli Liu, Yuxin Li, Wenbin Li, Yang Gao, Jiebo Luo.  
[3D Gaussian Splatting: Survey, Technologies, Challenges, and Opportunities](https://arxiv.org/pdf/2407.17418).   
_In: arXiv:2407.17418._  
[**[Project]**](https://github.com/qqqqqqy0227/awesome-3DGS).

- Lianghan Zhu, **Yanqi Bao^***, Jing Huo, Jing Wu, Yu-Kun Lai, Wenbin Li, Yang Gao.  
[Zero-Shot Video Editing through Adaptive Sliding Score Distillation](https://arxiv.org/pdf/2406.04888).   
_In: arXiv:2406.04888._  
[**[Project]**](https://nips24videoedit.github.io/zeroshot_videoedit/).

- **Yanqi Bao**, Tianyu Ding, Jing Huo, Wenbin Li, Yuxin Li, Yang Gao  
[InsertNeRF: Instilling Generalizability into NeRF with HyperNet Modules](https://openreview.net/forum?id=aHmNpLlUlb).   
_In: ICLR 2024._  
[**[Code]**](https://github.com/bbbbby-99/InsertNeRF/).

- **Yanqi Bao**, Yuxin Li, Jing Huo, Tianyu Ding, Xinyue Liang, Wenbin Li, Yang Gao  
[Where and how: Mitigating confusion in neural radiance fields from sparse inputs](https://dl.acm.org/doi/abs/10.1145/3581783.3613769).   
_In: ACM MM 2023._  
[**[Code]**](https://github.com/bbbbby-99/WaH-NeRF).

- Lei Zhang, Jie Liu, **Yanqi Bao**, Jie Wang  
[Region-Awared Transformer with Asymmetric Loss in Multi-Label Classification](https://ieeexplore.ieee.org/abstract/document/10095686/).   
_In: ICASSP 2023._  

- Kechen Song, **Yanqi Bao**, Han Wang, Liming Huang, Yunhui Yan  
[A potential vision-based measurements technology: Information flow fusion detection method using RGB-thermal infrared images](https://ieeexplore.ieee.org/abstract/document/10015881/).   
_In: IEEE Transactions on Instrumentation and Measurement._

- Jie Liu, **Yanqi Bao***, Wenzhe Yin, Haochen Wang, Yang Gao, Jan-Jakob Sonke, Efstratios Gavves  
[Few-shot semantic segmentation with support-induced graph convolutional network](https://arxiv.org/pdf/2301.03194).   
_In: BMVC 2022 Oral._

- Kechen Song, Jie Wang, **Yanqi Bao**, Liming Huang, Yunhui Yan  
[A novel visible-depth-thermal image dataset of salient object detection for robotic visual perception](https://ieeexplore.ieee.org/abstract/document/9931143/).   
_In: IEEE/ASME Transactions on Mechatronics._  
[**[Dataset]**](https://github.com/VDT-2048/VDT-Dataset).

- Jie Liu, **Yanqi Bao***, Guo-Sen Xie, Huan Xiong, Jan-Jakob Sonke, Efstratios Gavves  
[Dynamic prototype convolution network for few-shot semantic segmentation](http://openaccess.thecvf.com/content/CVPR2022/html/Liu_Dynamic_Prototype_Convolution_Network_for_Few-Shot_Semantic_Segmentation_CVPR_2022_paper.html).   
_In: CVPR 2022._

- **Yanqi Bao**, Kechen Song, Jie Wang, Liming Huang, Hongwen Dong, Yunhui Yan  
[A novel visible-depth-thermal image dataset of salient object detection for robotic visual perception](https://ieeexplore.ieee.org/abstract/document/9931143/).   
_In: Journal of Visual Communication and Image Representation._  
[**[Code]**](https://github.com/bbbbby-99/V-T-few-shot-semantic-segmentation).

- Jie Wang, Kechen Song, **Yanqi Bao**, Liming Huang, Yunhui Yan  
[CGFNet: Cross-guided fusion network for RGB-T salient object detection](https://ieeexplore.ieee.org/abstract/document/9493207/).   
_In: IEEE Transactions on Circuits and Systems for Video Technology._

- **Yanqi Bao**, Kechen Song, Jie Liu, Yanyan Wang, Yunhui Yan, Han Yu, Xingjie Li  
[Triplet-graph reasoning network for few-shot metal generic surface defect segmentation](https://ieeexplore.ieee.org/abstract/document/9440451/).   
_In: IEEE Transactions on Instrumentation and Measurement._  
[**[Code]**](https://github.com/bbbbby-99/TGRNet-Surface-Defect-Segmentation).


# 🎖 Honors and Awards
- *2023.10* Scholarship in Nanjing University. 

# 💬 Invited Talks
- *2023.07*, CGCKD 2024, Xiamen, China. 

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
