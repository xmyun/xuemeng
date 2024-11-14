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

<!-- I am currently a Postdoctoral Researcher with Hong Kong University of Science and Technology. -->


<span class='anchor' id='about-me'></span>

I am currently a Postdoctoral Researcher with <a href='https://hkust.edu.hk/'>the Hong Kong University of Science and Technology (HKUST)</a>, under the guidance of <a href='https://scholar.google.com/citations?user=XTlaQMkAAAAJ&hl=zh-CN'>Prof. Qian Zhang</a>. Prior to HKUST, I received my Ph.D. in Computer Science at <a href='https://www.whu.edu.cn/'>Wuhan University</a> in 2022, under the guidance of <a href='https://scholar.google.com/citations?user=ax6CbMgAAAAJ'>Prof. Yanjiao Chen</a> and <a href='https://cs.whu.edu.cn/szdw/zrjs.htm'>Prof. Jian Zhang</a>. I obtained my master's degree from Wuhan University. I spent my senior year as a visiting student at <a href='https://usslab.org/'> USSLAb</a> of <a href='https://www.zju.edu.cn/'>Zhejiang University (ZJU)</a>. 

My research interests include mobile and ubiquitous computing, smart healthcare, and IoT/AI security. The total google scholar citations <a href='https://scholar.google.com/citations?user=Q0JYVicAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News 
- *2024.9*: &nbsp;🎉🎉 One paper is accepted by IEEE TDSC 2024! 
- *2023.10*: &nbsp;🎉🎉 One paper is accepted by ACM Ubicomp 2024! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ubicomp 2024</div><img src='images/SDE-img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SDE: Early Screening for Dry Eye Disease with Wireless Signals](https://programs.sigchi.org/ubicomp-iswc/2024/program/content/174703/)

**Meng Xue**, Yuyang Zeng, Shengkang Gu, Qian Zhang, Bowei Tian, and Changzheng Chen 
- [**Demo**](https://dl.acm.org/doi/abs/10.1145/3631438) 

- In this paper, we propose SDE, a contactless, convenient, and ubiquitous DED screening system based on RF signals. By constructing frame chirps variance, we extract fine-grained spontaneous blinking action from RF signals.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TDSC 2024</div><img src='images/Artemis.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[ARTEMIS: Defending against Backdoor Attacks via Distribution Shift](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10702439)

**Meng Xue**, Zhixian Wang, Qian Zhang, Xueluan Gong, Zhihang Liu, and Yanjiao Chen 
- [**Code**](https://github.com/xmyun/Artemis) 
- In this work, we propose a novel backdoor defense approach called ARTEMIS, which utilizes distribution shifts to eliminate the discrepancy between poisoned and benign samples in the feature space. Additionally, ARTEMIS learns from domain-invariant features after the shift. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ubicomp 2023</div><img src='images/Echo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Echo: Reverberation-based Fast Black-Box Adversarial Attacks on Intelligent Audio Systems](https://dl.acm.org/doi/pdf/10.1145/3534599)

**Meng Xue**, Peng Kuang, Xueluan Gong, Qian ZHANG, and Yanjiao Chen
- [**Projects**](https://echodisplay.github.io/)
- In this paper, we propose a physical adversarial attack that exploits reverberation, a natural indoor acoustic effect, to realize imperceptible, fast, and targeted black-box attacks. Moreover, we generate reverberation-alike perturbations that blend naturally with the original voice sample. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ubicomp 2022</div><img src='images/WetRa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Wet-Ra: Monitoring Diapers Wetness with Wireless Signals](https://dl.acm.org/doi/pdf/10.1145/3534599)

**Meng Xue**, Yanjiao Chen, Xueluan Gong, Jian Zhang, and Chunkai Fan
- [**Presentaion**](https://www.youtube.com/watch?v=_HmM2UIYrUI) 
- Diaper wetness monitoring is essential in various situations (e.g., babies and patients) to guarantee hygiene and avoid embarrassment. In this paper, we introduce Wet-Ra, a contactless, ubiquitous, and user-friendly diaper wetness monitoring system based on RF signals. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ubicomp 2021</div><img src='images/ChestLive.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ChestLive: Fortifying Voice-based Authentication with Chest Motion Biometric on Smart Devices](https://dl.acm.org/doi/abs/10.1145/3494962)

Yanjiao Chen, **Meng Xue**, Jian Zhang, Qianyun Guan, Zhiyuan Wang, Qian Zhang, and Wei Wang
- In this paper, we propose to leverage the distinctive chest motions during speaking to establish a secure multi-factor authentication system, named ChestLive. We use acoustic sensing to monitor chest motions with a built-in speaker and microphone on smartphones.  
</div>
</div>


[Meta-Learning for Human-Centered Wireless Sensing: Architecture, Applications, and Challenges](https://ieeexplore.ieee.org/abstract/document/9846941/). **Xue, Meng**, Yanjiao Chen, Xueluan Gong, Houze Cao, Jian Zhang, and Qian Zhang. *IEEE Network*, 2022.

[DetectDUI: An In-Car Detection System for Drink Driving and BACs](https://ieeexplore.ieee.org/abstract/document/9626572). Yanjiao Chen, **Meng Xue**, Jian Zhang, Runmin Ou, Qian Zhang, Peng Kuang. *IEEE/ACM TON*, 2021.

[D-DAE: Defense-Penetrating Model Extraction Attacks](https://ieeexplore.ieee.org/abstract/document/10179406). Yanjiao Chen, Rui Guan, Xueluan Gong, Jianshuo Dong, **Meng Xue**. *IEEE Symposium on Security and Privacy*, 2023.

[Kaleidoscope: Physical Backdoor Attacks against Deep Neural Networks with RGB Filters](https://ieeexplore.ieee.org/abstract/document/10024758). Xueluan Gong, Ziyao Wang, Yanjiao Chen, **Meng Xue**, Qian Wang, Yuzhe Gu. *IEEE TDSC*, 2023.



# 🎖 Honors and Awards
- *2024.9* HKUST Research Travel Grant, HKUST. 
- *2022.10* Academic Innovation Scholarship, WuHan University. 

# 📖 Educations
- *2022.09 - now*, HKUST.
- *2021.5-2022.4, Zhejiang university (Visiting).
- *2017.09 - 2022.06, Wuhan University. 

# 💬 Services
- Reviewer of IEEE Transactions on Information Forensics and Security. 
- Reviewer of IMWUT/Ubicomp.
- Reviewer of IEEE network.
- Teaching Assistant of Computer Networking, at Wuhan University, 2019.9 - 2020.1

# 💻 Internships
- *2018.06 - 2018.09*, [Huawei](https://github.com/), China.
