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

<style>
  .rucred {
    display: inline-block;
    background-color: rgb(174, 11, 42);
    color: white;
    font-size: 0.8em;
    padding: 2px 6px;
    border-radius: 3px;
    margin-left: 8px;
    font-weight: bold;
    vertical-align: middle;
  }
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 60px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>

<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

<span class='anchor' id='about-me'></span>



I am **Zongji Yu**. I am currently a senior **undergraduate** at [School of Control Science and Engineering, Shandong University (**SDU**)](https://www.sdu.edu.cn/sdgk/sdjj.htm). I joined the Key Laboratory of Machine Intelligence and System Control, Ministry of Education — the MVP Lab led by Professor **Cong Runmin**, in April 2024. 

I will pursue a PhD degree at the **School of Automation and Perception, Shanghai Jiao Tong University (SJTU)**. In the future, I will work under the supervision of  Professor **Gong Chen**`s LEAP Group to carry out research in the fields of **artificial intelligence** and **embodied intelligence**.


My research interests focus on **embodied intelligence, computer vision, and state space model**. Recently, I am focusing on:  
1. **VLA-Safety**: vision-language-action model and its safety;  
2. **Mamba**: state space model based vision model and its downstream tasks.
   
My research aims to **Build a bridge between artificial intelligence and robotics**, to move toward truly elegant embodied intelligence.


# 🔥 News
- *2025.09*: &nbsp;🎉 I have been invited to serve as a reviewer for TCSVT (IEEE Transactions on Circuits and Systems for Video Technology, IF=11.015).
- *2025.07*: &nbsp;🎉 A paper about Mamba and underwater tasks was accepted by **ACM MM 2025**!
- *2025.06*: &nbsp;🎉 I have been invited to serve as a reviewer for the IEEE Journal of Oceanic Engineering (IF=3.883).
- *2025.05*: &nbsp;🎉 A paper about MPC and optimistic was accepted by **ICITS 2025**!

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/uismamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[UIS-Mamba: Exploring Mamba for Underwater Instance Segmentation via Dynamic Tree Scan and Hidden State Weaken](https://arxiv.org/pdf/2508.00421)

Runmin Cong, **Zongji Yu**, Hao Fang, Haoyan Sun, Sam Kwong

- *Accepted at the 33rd ACM International Conference on Multimedia* <span class="rucred">Oral</span>
- The first underwater instance segmentation model based on visual Mamba, designed with dynamic tree scan and background hidden state weaken modules.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICITS 2025</div><img src='images/hdmpc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HD-MPC: Hierarchical Distributed Model Predictive Control for the Great Lakes Flow Network Optimization](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13682/3073387/HD-MPC)

**Zongji Yu**, Jiaxin Li, Qun Yu

- *Accepted at the 13th International Conference on Information Technology and Science* <span class="rucred">Poster</span>
- Proposed a hierarchical distributed model predictive control system combined with ADMM to dynamically optimize the coordination efficiency of adjacent subsystems and accelerate convergence.

</div>
</div>

# 🎖 Honors and Awards
- *2025.05*: &nbsp;🏆 2025 Mathematical Contest in Modeling (MCM) – *International First Prize (M Award)*
- *2024.11*: &nbsp;💰 Inspur Scholarship – 5,000 CNY
- *2024.04*: &nbsp;🏆 2024 Mathematical Contest in Modeling (MCM) – *International First Prize (M Award)*
- *2023.12*: &nbsp;🏆 2023 Asia and Pacific Mathematical Contest in Modeling (APMCM) – *International First Prize*
- *2023.11*: &nbsp;💰 Shandong Provincial Government Scholarship – 7,000 CNY


# 📖 Educations


- *2022.09 – Present*: &nbsp;🇨🇳 **School of Control Science and Engineering, Shandong University (SDU)**
  
  *- Bachelor of Engineering in Robotics Engineering, Supervisor: [Dr. Cong](https://rmcong.github.io/index.html)*

- _2025.08 – Present_:  🇨🇳 **School of Automation and Perception, Shanghai Jiao Tong University (SJTU)**
    
  *- Major: Control Science and Engineering; Supervisor: [Dr. Gong](https://gcatnjust.github.io/ChenGong/index.html)*

# 🪽 Beyond Academics
I love **music, literature, travel and basketball**. I enjoy exploring hands-on projects related to robotics, as well as keeping up with cutting-edge embodied intelligence.

# 🌍 Visitor Map

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=1838a3&w=400&t=tt&d=opzTPaTNgNUrWvD_vjzXkFUMNo05ptM6XPnZfkpH53E&co=ffffff&cmo=af1616&cmn=1fba1f&ct=000000'></script>

<div class="logo-row">
  <img src="images/SJTU.png"      alt="">
  <img src="images/sdu_logo.png"      alt="">
</div>


<footer class="site-footer">
  <p>&copy; 2025 Zongji Yu. All rights reserved.</p>
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io"
       target="_blank" rel="noopener">Yi Ren</a>.
  </p>
</footer>
