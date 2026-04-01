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

Hi! I'm  Feiyu Jia (贾飞宇), first-year Pd.D student @ [Shanghai AI Lab](https://www.shlab.org.cn/) and [School of Information Science and Technology](https://sist.ustc.edu.cn/), [University of Science and Technology of China](https://www.ustc.edu.cn/), supervised by [Dahua Lin](http://dahua.site/) and [Jiangmiao Pang](https://oceanpang.github.io/). I received my bachelor's degree from the [School of Automation](https://zdhxy.nwpu.edu.cn/), [Northwestern Polytechnical University](https://www.nwpu.edu.cn/). I am now working with [Jingbo wang](https://wangjingbo1219.github.io/) and [Jiangmiao Pang](https://oceanpang.github.io/) at Shanghai AI Lab. 

My research interest includes **Teleoperation, Humanoid robots and Embodied Ai**. In my free time, I enjoy traveling and painting. Meanwhile, I am an avid fan of LOL and Valorant.


# 🔥 News
- *2025.10*: &nbsp; Two papers ([AdaMimic](https://github.com/InternRobotics/AdaMimic) and [PhysHSI](https://github.com/InternRobotics/PhysHSI)) on learning humanoid control were released.
- *2025.04*: &nbsp;🎉🎉 One paper [HOMIE](https://homietele.github.io/) is accepted by RSS 2025!



# 📝 Publications 
<div class='paper-box paper-box--accent'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/TAG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Feel Robot Feels: Tactile Feedback Array Glove for Dexterous Manipulation](https://roboticsconference.org/program/papers/70/)**

**<u>Feiyu Jia*</u>**, Xiaojie Niu\*, Sizhe Yang\*, Qingwei Ben, Tao Huang, Feng Zhao†, Jingbo Wang†, Jiangmiao Pang†

[**[Project website]**](https://trap-1.github.io/TAG.github.io/) 
[**[Paper]**](https://arxiv.org/pdf/2603.28542)
[**[Code]**](https://trap-1.github.io/TAG.github.io/)

We introduce TAG, a low-cost glove system integrating precise motion capture with high-resolution tactile feedback.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/homie.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit](https://trap-1.github.io/TAG.github.io/)**

Qingwei Ben\*, **<u>Feiyu Jia*</u>**, Jia Zeng, Junting Dong, Dahua Lin, Jiangmiao Pang†

[**[Project website]**](https://homietele.github.io/) 
[**[Paper]**](https://arxiv.org/pdf/2502.13013)
[**[Code]**](https://github.com/OpenRobotLab/OpenHomie/)

HOMIE is a semi-autonomous teleoperation system that combines a reinforcement learning policy for body control mapped to a pedal, an isomorphic exoskeleton arm for arm control, and motion-sensing gloves for hand control, forming a unified cockpit to freely operate humanoids and establish a data flywheel.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/AdaMimic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Gallant: Voxel grid-based humanoid locomotion and local-navigation across 3d constrained terrains](https://gallantloco.github.io/)**

Qingwei Ben\*, Botian Xu\*, Kailin Li\*, **<u>Feiyu Jia</u>**, Wentao Zhang, Jingping Wang, Jingbo Wang†, Dahua Lin†, Jiangmiao Pang†.

[**[Project website]**](https://gallantloco.github.io/) 
[**[Paper]**](https://arxiv.org/pdf/2511.14625)
[**[Code]**](https://github.com/InternRobotics/Gallant)

We introduce Gallant, the first system to run a single policy that handles full-space constraints — including ground-level barriers, lateral clutter, and overhead obstacles on a humanoid robot.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/AdaMimic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Gallant: Voxel grid-based humanoid locomotion and local-navigation across 3d constrained terrains](https://gallantloco.github.io/)**

Qingwei Ben\*, Botian Xu\*, Kailin Li\*, **<u>Feiyu Jia</u>**, Wentao Zhang, Jingping Wang, Jingbo Wang†, Dahua Lin†, Jiangmiao Pang†.

[**[Project website]**](https://gallantloco.github.io/) 
[**[Paper]**](https://arxiv.org/pdf/2511.14625)
[**[Code]**](https://github.com/InternRobotics/Gallant)

We introduce Gallant, the first system to run a single policy that handles full-space constraints — including ground-level barriers, lateral clutter, and overhead obstacles on a humanoid robot.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/AdaMimic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[One-Policy-Fits-All: Geometry-Aware Action Latents for Cross-Embodiment Manipulation](https://mujc2021.github.io/opfa/)**

Juncheng Mu\*, Sizhe Yang\*, Hojin Bae, **<u>Feiyu Jia</u>**, Qingwei Ben, Boyi Li†, Huazhe Xu†, Jiangmiao Pang†.

[**[Project website]**](https://mujc2021.github.io/opfa/) 
[**[Paper]**](https://arxiv.org/pdf/2603.14522)
[**[Code]**](https://mujc2021.github.io/opfa/)

We introduce One-Policy-Fits-All (OPFA), a general framework for cross-embodiment manipulation. OPFA leverages the geometric structures of diverse end-effectors to construct a unified latent action representation, and employs a unified latent retargeting decoder to recover embodiment-specific actions.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/AdaMimic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[AdaMimic: Towards Adaptable Humanoid Control via Adaptive Motion Tracking](https://taohuang13.github.io/adamimic.github.io/)**

Tao Huang, Huayi Wang, Junli Ren, Kangning Yin, Zirui Wang, Xiao Chen, **<u>Feiyu Jia</u>**, Wentao Zhang, Junfeng Long, Jingbo Wang†, Jiangmiao Pang†

[**[Project website]**](https://taohuang13.github.io/adamimic.github.io/) 
[**[Paper]**](https://taohuang13.github.io/adamimic.github.io/assets/paper.pdf)
[**[Code]**](https://github.com/InternRobotics/AdaMimic)

We introduce AdaMimic, a novel motion tracking algorithm that enables adaptable humanoid control from a single reference motion. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/PhysHSI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[PhysHSI: Towards a Real-World Generalizable and Natural Humanoid-Scene Interaction System](https://why618188.github.io/physhsi/)**

Huayi Wang\*, Wentao Zhang\*, Runyi Yu\*,  Tao Huang,  Junli Ren, **<u>Feiyu Jia</u>**,  Xiaojie Niu,  Xiao Chen, Jiahe Chen, Qifeng Chen†,  Jingbo Wang†, Jiangmiao Pang†

[**[Project website]**](https://why618188.github.io/physhsi/) 
[**[Paper]**](https://arxiv.org/abs/2510.11072)
[**[Code]**](https://github.com/InternRobotics/PhysHSI)

We present a physical-world humanoid-scene interaction system, PhysHSI, that enables humanoids to autonomously perform diverse interaction tasks while maintaining natural and lifelike behaviors. PhysHSI comprises a simulation training pipeline and a real-world deployment system. 
</div>
</div>

# 🎖 Honors and Awards
- *2024.09* **National Scholarship**(Highest Honor for undergraduates in China)
- *2023.09* **National Scholarship**
- *2023.09* **RoboCup China, Dance Robot Champion**

# 📖 Educations
- *2025.09 - NOW*, University of Science and Technology of China
- *2021.06 - 2025.06*, Northwestern Polytechnical University

# 💻 Experiences
- *2024.08 - now*, [InternRobotics](https://github.com/InternRobotics), Shanghai AI Laboratory.
