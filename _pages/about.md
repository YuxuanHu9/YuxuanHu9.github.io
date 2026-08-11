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

Hello! I am **Yuxuan Hu** (胡雨璇), a Ph.D. student in Electronic and Information Engineering at **Fudan University**, advised by [Prof. Feng Xu](https://scholar.google.com/citations?user=i-N1K9oAAAAJ&hl=en). I am currently a Visiting Ph.D. Student at the School of Mechanical and Aerospace Engineering, **Nanyang Technological University (NTU)**, Singapore, with the [MARS Lab](https://marslab.tech/), working with [Prof. Jianfei Yang](https://scholar.google.com/citations?hl=zh-CN&user=V25k08UAAAAJ&view_op=list_works).

My research centers on **Embodied mmWave Sensing**, at the intersection of millimeter-wave radar, robotics, and machine learning. I am broadly interested in how embodied agents can actively perceive and understand the physical world, making wireless sensing robust and practical beyond controlled environments.

# 🔥 News
- *2025.10*: &nbsp;✈️ Started as a Visiting Ph.D. Student at NTU, Singapore.
- *2024*: &nbsp;🏆 Best Student Paper Award at ICMMT 2024.
- *2023.09*: &nbsp;🎓 Started my Ph.D. at the EMW Lab, Fudan University.
- *2020.09*: &nbsp;🎓 Joined the EMW Lab, Fudan University as an M.Sc. student.

# 📝 Publications

## Recent Highlights

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TII 2026</div><img src='images/waveman.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WaveMan: mmWave-Based Room-Scale Human Interaction Perception for Humanoid Robots](https://arxiv.org/abs/2601.07454)

**Yuxuan Hu**, Kuangji Zuo, Boyu Ma, Shihao Li, Zhaoyang Xia, Feng Xu, Jianfei Yang

*IEEE Transactions on Industrial Informatics, 2026*

- Room-scale mmWave gesture interaction for humanoid robots — removes the fixed-position constraint; 97.67% accuracy, only 2.54 pp drop at unseen positions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2026</div><img src='images/activevital.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ActiveVital: Geometry-Aware Embodied Vital Signs Monitoring for Home Healthcare Robots](https://arxiv.org/abs/2606.30275)

**Yuxuan Hu**, Shihao Li, Yang Xiao, Gen Li, Feng Xu, Jianfei Yang

*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026*

- A vision-guided robot actively steers its radar to near-normal incidence on the chest; respiration interval error 0.87→0.14 s, heart rate 13.59→2.22 bpm.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2026</div><img src='images/emfall.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EM-Fall: Embodied mmWave Sensing for Day-and-Night Fall Detection on Humanoid Robots](https://arxiv.org/abs/2606.11109)

Yanshuo Lu, **Yuxuan Hu**, Shenghai Yuan, Xinyu Zhou, Kuangji Zuo, Bofan Lyu, XiChen Yuan, Jianfei Yang

*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026*

- A mobile humanoid robot repositions itself to keep a person visible under occlusion and poor lighting for day-and-night mmWave fall detection; validated across eight indoor spaces.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM 2025</div><img src='images/har_tim2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Human Activity Recognition Trained on Simulated Millimeter-Wave Radar Data With Domain Adaptation](https://doi.org/10.1109/TIM.2025.3558216)

**Yuxuan Hu**, Xianghan Yang, Zhaoyang Xia, Feng Xu

*IEEE Transactions on Instrumentation and Measurement, vol. 74, 2025*

- Train radar HAR mostly on MoCap-simulated FMCW data with domain adaptation; 97.31% cross-domain accuracy (+21.56 pp over pix2pix).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM 2024</div><img src='images/respiration_tim2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Investigating Respiration–Heartbeat Separation Through a Multipoint Scattering Chest Wall Motion Model: 60-GHz FMCW Radar Assessment](https://doi.org/10.1109/TIM.2024.3420356)

**Yuxuan Hu**, Zhaoyang Xia, Feng Xu

*IEEE Transactions on Instrumentation and Measurement, vol. 73, 2024*

- A 9-point cylindrical chest-wall scattering model that separates respiration and heartbeat; respiration PCC 0.994, heart-rate PCC 0.941.
</div>
</div>

## Talks
- *2023*, **The Feasibility of Q-band Millimeter Wave on Hand-Gesture Recognition for Indoor FTTR Scenario** — oral presentation at IEEE MTT-S International Wireless Symposium (IWS) 2023.

## Conference
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

# 💻 Internships
- *2021.08 - 2022.08*, Radar-Visual Fusion Algorithm Intern, **Huawei Technologies Co., Ltd.**, China.
