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

Hi! I'm **Feiyu Jia (贾飞宇)**, an incoming Ph.D. student (Fall 2026) at [MMLab@HKU](https://mmlab.hk/), [The University of Hong Kong](https://www.hku.hk/), advised by [Prof. Ping Luo](https://luoping.me/). I received my bachelor's degree from [Northwestern Polytechnical University](https://www.nwpu.edu.cn/). Previously, I worked at [Shanghai AI Lab](https://www.shlab.org.cn/) with [Dr. Jiangmiao Pang](https://oceanpang.github.io/), and [Dr. Jingbo Wang](https://wangjingbo1219.github.io/). My research interest includes **Teleoperation, Humanoid robots and Embodied Ai**. My CV is available [here](/images/FeiyuJia_CV.pdf). Feel free to drop me an [email](mailto:feiyujia635@gmail.com) or reach me on WeChat: jy54796666.


# 🔥 News
- *2026.4*: &nbsp; Our paper [TAG](https://trap-1.github.io/TAG.github.io/) was released.
- *2025.10*: &nbsp; Two papers ([AdaMimic](https://github.com/InternRobotics/AdaMimic) and [PhysHSI](https://github.com/InternRobotics/PhysHSI)) on learning humanoid control were released.
- *2025.04*: &nbsp;🎉🎉 One paper [HOMIE](https://homietele.github.io/) is accepted by RSS 2025!



# 📝 Publications 
<div class='paper-box paper-box--accent'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/TAG_NEW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Feel Robot Feels: Tactile Feedback Array Glove for Dexterous Manipulation](https://arxiv.org/pdf/2603.28542)**

**<u>Feiyu Jia*</u>**, Xiaojie Niu\*, Sizhe Yang\*, Qingwei Ben, Tao Huang, Feng Zhao†, Jingbo Wang†, Jiangmiao Pang†

[**[Project website]**](https://trap-1.github.io/TAG.github.io/) 
[**[Paper]**](https://arxiv.org/pdf/2603.28542)
[**[Code]**](https://github.com/InternRobotics/TAG)

</div>
</div>



<div class='paper-box paper-box--accent'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/homie.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit](https://homietele.github.io/)**

Qingwei Ben\*, **<u>Feiyu Jia*</u>**, Jia Zeng, Junting Dong, Dahua Lin, Jiangmiao Pang†

<p class="oral-presentation">(Oral Presentation)</p>

[**[Project website]**](https://homietele.github.io/) 
[**[Paper]**](https://arxiv.org/pdf/2502.13013)
[**[Code]**](https://github.com/OpenRobotLab/OpenHomie/)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/Image2real.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Imagine2Real: Towards Zero-shot Humanoid-Object Interaction via Video Generative Priors](https://arxiv.org/pdf/2605.22272)**

Jiahe Chen\*, ZiRui Wang\*, **<u>Feiyu Jia</u>**, Xiao Chen, Xiaojie Niu, Weishuai Zeng, Tianfan Xue, Xiaowei Zhou, Jiangmiao Pang†, Jingbo Wang†

[**[Project website]**](https://arxiv.org/pdf/2605.22272) 
[**[Paper]**](https://arxiv.org/pdf/2605.22272)
[**[Code]**](https://arxiv.org/pdf/2605.22272)


</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/Gallant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Gallant: Voxel grid-based humanoid locomotion and local-navigation across 3d constrained terrains](https://gallantloco.github.io/)**

Qingwei Ben\*, Botian Xu\*, Kailin Li\*, **<u>Feiyu Jia</u>**, Wentao Zhang, Jingping Wang, Jingbo Wang†, Dahua Lin†, Jiangmiao Pang†

[**[Project website]**](https://gallantloco.github.io/) 
[**[Paper]**](https://arxiv.org/pdf/2511.14625)
[**[Code]**](https://github.com/InternRobotics/Gallant)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/One4all.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[One-Policy-Fits-All: Geometry-Aware Action Latents for Cross-Embodiment Manipulation](https://mujc2021.github.io/opfa/)**

Juncheng Mu\*, Sizhe Yang\*, Hojin Bae, **<u>Feiyu Jia</u>**, Qingwei Ben, Boyi Li†, Huazhe Xu†, Jiangmiao Pang†

[**[Project website]**](https://mujc2021.github.io/opfa/) 
[**[Paper]**](https://arxiv.org/pdf/2603.14522)
[**[Code]**](https://mujc2021.github.io/opfa/)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/teleopbeacn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[TeleOpBench: A Simulator-Centric Benchmark for Dual-Arm Dexterous Teleoperation](https://arxiv.org/pdf/2505.12748)**

Hangyu Li\*, Qin Zhao\*, Haoran Xu, Xinyu Jiang, Qingwei Ben, **<u>Feiyu Jia</u>**, Haoyu Zhao, Liang Xu, Jia Zeng, Hanqing Wang, Bo Dai, Junting Dong†, Jiangmiao Pang†

[**[Project website]**](https://gorgeous2002.github.io/TeleOpBench/) 
[**[Paper]**](https://arxiv.org/pdf/2505.12748)
[**[Code]**](https://github.com/cyjdlhy/TeleOpBench)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/PhysHSI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[PhysHSI: Towards a Real-World Generalizable and Natural Humanoid-Scene Interaction System](https://why618188.github.io/physhsi/)**

Huayi Wang\*, Wentao Zhang\*, Runyi Yu\*,  Tao Huang,  Junli Ren, **<u>Feiyu Jia</u>**,  Xiaojie Niu,  Xiao Chen, Jiahe Chen, Qifeng Chen†,  Jingbo Wang†, Jiangmiao Pang†

[**[Project website]**](https://why618188.github.io/physhsi/) 
[**[Paper]**](https://arxiv.org/abs/2510.11072)
[**[Code]**](https://github.com/InternRobotics/PhysHSI)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/AdaMimic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[AdaMimic: Towards Adaptable Humanoid Control via Adaptive Motion Tracking](https://taohuang13.github.io/adamimic.github.io/)**

Tao Huang, Huayi Wang, Junli Ren, Kangning Yin, Zirui Wang, Xiao Chen, **<u>Feiyu Jia</u>**, Wentao Zhang, Junfeng Long, Jingbo Wang†, Jiangmiao Pang†

[**[Project website]**](https://taohuang13.github.io/adamimic.github.io/) 
[**[Paper]**](https://taohuang13.github.io/adamimic.github.io/assets/paper.pdf)
[**[Code]**](https://github.com/InternRobotics/AdaMimic)

</div>
</div>



# 🎖 Honors and Awards
- *2022 - 2024* **National Scholarship**(Highest Honor for undergraduates in China)
- *2023.09* **RoboCup China, Dance Robot Champion**



# 📖 Education

<div class="profile-entry">
  <div class="profile-entry__logo">
    <img src="/images/hku-logo.jpg" alt="The University of Hong Kong logo">
  </div>
  <div class="profile-entry__details">
    <h3><a href="https://www.hku.hk/">The University of Hong Kong</a></h3>
    <p><strong>2026.09 - Present</strong> · <em>Ph.D. Student</em></p>
    <p><a href="https://mmlab.hk/">MMLab</a>, School of Computing and Data Science (CDS)</p>
    <p>Advisor: <a href="https://luoping.me/">Prof. Ping Luo</a></p>
  </div>
</div>

<div class="profile-entry">
  <div class="profile-entry__logo">
    <img src="/images/npu-logo.gif" alt="Northwestern Polytechnical University logo">
  </div>
  <div class="profile-entry__details">
    <h3><a href="https://www.nwpu.edu.cn/">Northwestern Polytechnical University</a></h3>
    <p><strong>2021.06 - 2025.06</strong> · <em>Bachelor's Degree</em></p>
    <p>School of Automation</p>
  </div>
</div>

# 💻 Experience

<div class="profile-entry">
  <div class="profile-entry__logo">
    <img src="/images/ailab_logo.png" alt="InternRobotics logo">
  </div>
  <div class="profile-entry__details">
    <h3><a href="https://github.com/InternRobotics">InternRobotics</a> @ <a href="https://www.shlab.org.cn/">Shanghai AI Laboratory</a></h3>
    <p><strong>2024.08 - 2026.03</strong></p>
    <p>Advisors: <a href="https://oceanpang.github.io/">Dr. Jiangmiao Pang</a> and <a href="https://wangjingbo1219.github.io/">Dr. Jingbo Wang</a></p>
  </div>
</div>
