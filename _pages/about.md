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

Hello! I am **Yuxuan Hu** (胡雨璇), a Ph.D. student in Electronic and Information Engineering at the Key Laboratory of Electromagnetic Wave Information Science, **Fudan University**, advised by Prof. Feng Xu. I am currently a Visiting Ph.D. Student at the School of Mechanical and Aerospace Engineering, **Nanyang Technological University (NTU)**, Singapore, working with Prof. Jianfei Yang.

My research focuses on **millimeter-wave (mmWave) radar sensing for robots** — including contactless human vital-sign monitoring, human activity and gesture recognition, and embodied perception for human–robot interaction.

# 🔥 News
- *2025.10*: &nbsp;✈️ Started as a Visiting Ph.D. Student at NTU, Singapore.
- *2024*: &nbsp;🏆 Best Student Paper Award at ICMMT 2024.
- *2023.09*: &nbsp;🎓 Started my Ph.D. at the EMW Lab, Fudan University.
- *2020.09*: &nbsp;🎓 Joined the EMW Lab, Fudan University as an M.Sc. student.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/waveman.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WaveMan: mmWave-Based Room-Scale Human Interaction Perception for Humanoid Robots](#)

**Yuxuan Hu**, Kuangji Zuo, Boyu Ma, Shihao Li, Zhaoyang Xia, Feng Xu, Jianfei Yang

*Under review, 2026*

- A room-scale mmWave gesture-interaction framework for humanoid robots that removes the fixed-position constraint, using geometry-aware alignment, CycleGAN spectrum enhancement, and a dual-branch channel-attention network (DBCA).
- Achieves 97.67% multi-position accuracy with only a 2.54 pp gap at unseen positions; introduces the first room-scale mmWave gesture benchmark (6 positions × 5 gestures × 12,000 samples).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM 2025</div><img src='images/har_tim2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Human Activity Recognition Trained on Simulated Millimeter-Wave Radar Data With Domain Adaptation](https://doi.org/10.1109/TIM.2025.3558216)

**Yuxuan Hu**, Xianghan Yang, Zhaoyang Xia, Feng Xu

*IEEE Transactions on Instrumentation and Measurement, vol. 74, 2025*

- A MoCap-driven FMCW data-generation pipeline plus Attention UNet++ domain adaptation that lets radar HAR be trained largely on simulated data.
- Reaches 97.31% cross-domain accuracy (+21.56 pp over pix2pix) with 90% of training data simulated.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM 2024</div><img src='images/respiration_tim2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Investigating Respiration–Heartbeat Separation Through a Multipoint Scattering Chest Wall Motion Model: 60-GHz FMCW Radar Assessment](https://doi.org/10.1109/TIM.2024.3420356)

**Yuxuan Hu**, Zhaoyang Xia, Feng Xu

*IEEE Transactions on Instrumentation and Measurement, vol. 73, 2024*

- A 9-point cylindrical dynamic scattering chest-wall model with radial position tracking and adaptive Gaussian filtering to separate respiration from heartbeat.
- Achieves respiration PCC 0.994 and heart-rate PCC 0.941, with 99% of heart-rate errors under 4 BPM.
</div>
</div>

- [The Feasibility of Q-band Millimeter Wave on Hand-Gesture Recognition for Indoor FTTR Scenario](https://doi.org/10.1109/IWS58240.2023.10222835), **Yuxuan Hu**, Zhaoyang Xia, Yanbo Zhao, Feng Xu, **IEEE MTT-S IWS 2023** &nbsp;🎤 *Oral*
- [An Attention-Enhanced Hand-Gesture Recognition Method on Millimeter Wave Radar](https://doi.org/10.1109/ICMMT61774.2024.10672055), Yanbo Zhao, Zhaoyang Xia, **Yuxuan Hu**, Feng Xu, **ICMMT 2024** &nbsp;🏆 *Best Student Paper*
- [Using FMCW Millimeter-Wave Radar to Realize the Detection of Vital Signs](https://doi.org/10.1109/ICMMT52847.2021.9617873), **Yuxuan Hu**, Zhaoyang Xia, Feng Xu, **ICMMT 2021**

# 🎖 Honors and Awards
- *2024*, Best Student Paper Award, ICMMT 2024.
- *2024*, Outstanding Student, Fudan University.
- *2023*, Huawei Scholarship.
- *2022*, National Scholarship.

# 📖 Educations
- *2023.09 - 2027.06 (expected)*, Ph.D. in Electronic and Information Engineering, Fudan University, Shanghai, China.
- *2025.10 - present*, Visiting Ph.D. Student, School of Mechanical and Aerospace Engineering, Nanyang Technological University, Singapore.
- *2020.09 - 2023.06*, M.Sc. in Electronic and Information Engineering, Fudan University, Shanghai, China.
- *2016.09 - 2020.06*, B.Sc. in Electronic and Information Engineering, Shanghai University, Shanghai, China.

# 💬 Oral Presentations
- *2023*, Oral presentation at **IEEE MTT-S International Wireless Symposium (IWS) 2023**: *The Feasibility of Q-band Millimeter Wave on Hand-Gesture Recognition for Indoor FTTR Scenario*.

# 💻 Internships
- *2021.08 - 2022.08*, Radar-Visual Fusion Algorithm Intern, **Huawei Technologies Co., Ltd.**, China.
