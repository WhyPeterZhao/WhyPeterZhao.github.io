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


<div class="photo-wall-banner">
  <img src="images/cover.jpg" alt="Cover">
</div>

# About Me
<span class='anchor' id='about-me'></span>

<div style="display: flex; align-items: center; margin-bottom: 0.5em;">
  <span style="flex:1;">
    Hi👋! I'm <strong>Yanping ZHAO (赵彦平)</strong>, a first-year master’s student at Tongji University supervised by Prof.Junqiao Zhao. I am interested in reinforcement learning, embodied intelligence, with a focus on improving agent generalization in dynamic environments. Ultimately, I aim to build generalizable action models to enable intelligent and versatile robot behaviors.
    <!-- currently working with <a href="https://yaomarkmu.github.io/" target="_blank">Yao (Mark) Mu</a> in <a href="https://scalelab-sjtu.github.io/" target="_blank">ScaleLab@SJTU</a>. Previously, I was a Research Assistant at 
    <a href="https://milab.westlake.edu.cn/index.html" target="_blank">MiLab</a>, 
    <a href="https://www.westlake.edu.cn/" target="_blank"><strong>Westlake University</strong></a> 
    advised by 
    <a href="https://scholar.google.com/citations?user=-fo6wdwAAAAJ&hl=zh-CN" target="_blank">Donglin Wang</a>.
    I got my B.Eng in Automation from 
    <a href="https://www.xmu.edu.cn/" target="_blank"><strong>Xiamen University</strong></a> 
    advised by 
    <a href="https://scholar.google.com/citations?user=yLQpYYYAAAAJ" target="_blank">Qifeng Zhou</a>. -->
  </span>
  <!-- <img src="images/head_.jpg" alt="Head" style="height:164px; margin-left:10px;"> -->
</div>

<!-- <div style="display: flex; align-items: center; margin-bottom: 0.5em;">
  <span style="flex:1;">
  I am looking for research collaborations and a PhD position starting from <strong>2026 Fall</strong>.
  Please drop me an email if you are interested in my research or just want to chat! Email: <strong>xiaowei2002103@foxmail.com</strong>
  </span>
</div> -->

<div style="display: flex; align-items: center; margin-bottom: 0.5em;">
  <span style="flex:1;">
  I like <strong>Robotic Learning</strong> (Embodied AI?), <strong>Reinforcement Learning</strong>, and <strong>World Model</strong>. I am focusing on building end-to-end robots with <strong>Universality, Generalizability, and Robustness</strong>, utilizing learning‑based methods that scale with data and computation. I am currently passionate about <strong>Manipulation and Locomotion</strong> tasks.
  </span>
</div>

# Experience
<span class='anchor' id='-experience'></span>

<div style="display: flex; align-items: center; margin-bottom: 0.5em;">
  <span style="flex:1;">
    - <em>2025.9-Now</em>: Master of Computer Science and Technology, Tongji University<br>
    - <em>2021.9-2025.7</em>: Bachelor of Computer Science and Technology, Tongji University
  </span>
  <img src="images/tju.png" alt="Tongji University" style="height:64px; margin-left:10px;">
</div>

<!-- <div style="display: flex; align-items: center; margin-bottom: 0.5em;">
  <span style="flex:1;">- <em>2024.7-2025.6</em>: Research Assistant in Machine Intelligence Lab (MiLAB), Westlake University</span>
  <img src="images/westlake.png" alt="Westlake University" style="height:64px; margin-left:10px;">
</div> -->

<!-- <div style="display: flex; align-items: center; margin-bottom: 0.5em;">
  <span style="flex:1;">- <em>2025.6-Now</em>: Research Intern in Spatial Cognition and Robotic Automative Learning Laboratory (ScaleLAB), Shanghai Jiao Tong University</span>
  <img src="images/sjtu.png" alt="Shanghai Jiao Tong University" style="height:70px; margin-left:10px;">
</div> -->

<!-- # News
<span class='anchor' id='-news'></span>
- *2025.7*: &nbsp;⭐ A summary of VLA+RL - [Awesome-VLA-RL](https://github.com/OpenHelix-Team/Awesome-VLA-RL) - is available in Github.
- *2025.5*: &nbsp;🎉 Our works [PORL](https://arxiv.org/abs/2505.16856) and [LIT](https://arxiv.org/abs/2503.10484v1) are available in arxiv.
- *2024.11*: &nbsp;🎉 Homepage has been set up.
- *2024.09*: &nbsp;🎉 Our paper [PT4Rec](https://link.springer.com/article/10.1007/s10994-024-06658-0) is accepted by ACML2024 and Machine Learning Journal. -->

# Publications 
<span class='anchor' id='-publications'></span>

## Embodied AI & RL
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/papers/astro.png' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**ASTRO: Adaptive Stitching via Dynamics-Guided Trajectory Rollouts**

Hang Yu, Di Zhang, Qiwei Du, **Yanping Zhao**, Hai Zhang, Guang Chen, Junqiao Zhao†, Eduardo E. Veas†

- *under preview*

<!-- **Wei Xiao***, [Jiacheng Liu](https://jiachengliu3.github.io/), [Zifeng Zhuang](https://scholar.google.com/citations?user=-KANvNMAAAAJ&hl=zh-CN), Runze Suo, [Shangke Lyu](https://lsk-robot.github.io/)†, [Donglin Wang](https://scholar.google.com/citations?user=-fo6wdwAAAAJ&hl=zh-CN)† -->
<!-- - [**Arxiv**](https://arxiv.org/abs/2505.16856) -->
</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/papers/lit.png' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**Learning Robotic Policy with Imagined Transition: Mitigating the Trade-off between Robustness and Optimality**

**Wei Xiao***, [Shangke Lyu](https://lsk-robot.github.io/)†, [Zhefei Gong](https://zhefeigong.github.io/), Renjie Wang, [Donglin Wang](https://scholar.google.com/citations?user=-fo6wdwAAAAJ&hl=zh-CN)†
- [**Arxiv**](https://arxiv.org/abs/2503.10484v1) | 
[**Video**](https://www.bilibili.com/video/BV1wbQDYmENv/)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/papers/trajbooster.gif' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**TrajBooster: Boosting Humanoid Whole-Body Manipulation via Trajectory-Centric Learning**

[Jiacheng Liu](https://jiachengliu3.github.io/)*, [Pengxiang Ding](https://dingpx.github.io/)*, Qihang Zhou, Yuxuan Wu, Da Huang, Zimian Peng, **Wei Xiao**, Weinan Zhang, Lixin Yang, Cewu Lu†, Donglin Wang†
- [**Arxiv**](https://arxiv.org/pdf/2509.11839) | 
[**Code**](https://github.com/jiachengliu3/OpenTrajBooster).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/papers/to.png' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**Integrating Trajectory Optimization and Reinforcement Learning for Quadrupedal Jumping with Terrain-Adaptive Landing**

Renjie Wang*, [Shangke Lyu](https://lsk-robot.github.io/)†, Xin Lang, **Wei Xiao**, [Donglin Wang](https://scholar.google.com/citations?user=-fo6wdwAAAAJ&hl=zh-CN)†
- The 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2025 Oral).
- [**Arxiv**](https://arxiv.org/pdf/2509.12776)
</div>
</div> -->



<!-- ## Recommender System
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/papers/ss4rec.png' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**Continuous-Time Sequential Recommendation with State Space Models**

**Wei Xiao***, Huiying Wang*, [Qifeng Zhou](https://scholar.google.com/citations?user=yLQpYYYAAAAJ)†, [Qing Wang](https://kesyren.github.io/)
- [**Arxiv**](https://arxiv.org/pdf/2502.08132) | 
[**Code**](https://github.com/XiaoWei-i/SS4Rec)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/papers/pt4rec.png' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**PT4Rec: A Universal Prompt-Tuning Framework for Graph Contrastive Learning-Based Recommendations**

**Wei Xiao***, [Qifeng Zhou](https://scholar.google.com/citations?user=yLQpYYYAAAAJ)†
- The 16th Asian Conference on Machine Learning, Machine Learning Journal, (ACML2024).
- [**Paper**](https://link.springer.com/article/10.1007/s10994-024-06658-0) | 
[**Code**](https://github.com/XiaoWei-i/PT4Rec)
</div>
</div> -->

# Honors and Awards
<span class='anchor' id='-honors-and-awards'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/awards/sxjm.jpg' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**The 22nd HUAWEI CUP China Postgraduate Mathematical Modeling Competition**

Team: **Yanping Zhao***, Xiying Chen, Jia Ma
- National Second Prize - *2025.11* 
<!-- - [**Leaderboard**](https://pre-prod.kaiwu.pvp.qq.com/aiarena/zh/news/b751f28065b7904f0913004a6c413002) -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/awards/iot.jpg' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">

**2024 HUAWEI CUP National Undergraduate IOT Design Contest**

Team: Tiantian Lin, Yirun He, **Yanping Zhao***, Shuyang Fu, Lei Jiang†, Jie Lu†
- First Prize in Final Contest - *2024.08*
<!-- - [**Technical Blog**](https://zhuanlan.zhihu.com/p/672741107) | 
[**Video1**](https://www.bilibili.com/video/BV1ca411u7DV/) | 
[**Video2**](https://www.bilibili.com/video/BV1tZ4y1471m/) -->
</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='awards/awards.png' alt="sym" height="200px" width=auto></div></div>
<div class='paper-box-text' markdown="1">
- The 13th Mathorcup Mathematical Modelling Competition, Third prize.
- Huawei Software Elite Challenge, Third Prize.
- National Mathematical Modelling Competition for College Students, Second Prize in Fujian Province.
- National Algorithm Competition for College Students, Excellence Award.
- and so on.
</div>
</div> -->

# Visitors
<div style="text-align:center; margin: auto; width: 28%;">
<script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=dAcb2_BoXDEP42aMIh1ZNj-pstz0Q-KSFcWpECxil0E"></script>
</div>