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

本人目前正在攻读硕士学位，就读于中山大学电子与通信工程学院 <a href='https://sysu-sail.net/'>空间智能实验室</a>，师从 <a href='https://jimmyqing.github.io/'>高庆 副教授</a>。本科毕业于湘潭大学自动化与电子信息学院自动化专业。在学期间，多次获得学业奖学金。研究方向主要包括机器人灵巧操作、运动重定向与具身智能。
<a href='https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&user=Rw4JzosAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


# 🔥 近期新闻|News
- *2026.08*: &nbsp;🎉🎉 论文《Vision-Guided Arm-Hand Decoupled Motion Retargeting Using Graph Networks for Cross-Platform Robots》被IEEE TASE Journal接收。
- *2026.03*: &nbsp;🎉🎉 论文《ObjRetarget: An Object-Aware Motion Retargeting Framework with Anthropomorphic Arm Constraints and Polyhedral Hand Modeling》被IROS 2026接收。
- *2026.01*: &nbsp;🎉🎉 论文《DexTele: A Dual-Arm Dexterous Teleoperation System Based on Motion Retargeting and Adaptive Force Control》被ICRA 2026接收。
- *2025.07*: &nbsp;🎉🎉 发明专利《一种基于图神经网络的机器人重定向方法》被授权。
- *2024.12*: &nbsp;🎉🎉 论文《Motion Retargeting Using Graph Neural Network for Vision-Guided Dexterous Robot Teleoperation》被IEEE i-CREATe接收。

# 📝 发表文章|Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TASE Journal</div><img src='images/TASE1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Vision-Guided Motion Retargeting Based on Graph Neural Network for Dexterous Robot

**Yuanchuan Lai**, Qing Gao*, Xin Zhang, Zhaojie Ju

[**Project**](https://3469627147abc.github.io/GNNRetarget./) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- 提出了一种面向人类视频学习的跨平台机器人运动重定向框架 GNNRetarget，通过臂-手解耦架构与图神经网络潜在空间优化，实现了无需配对数据的高精度运动映射与异构平台泛化，并在 RMC-DA、YuMi 和 Unitree H1 等多种机器人上验证了良好的泛化性能与重定向精度。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2026</div><img src='images/iros2026_1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

ObjRetarget: An Object-Aware Motion Retargeting Framework with Anthropomorphic Arm Constraints and Polyhedral Hand Modeling

**Yuanchuan Lai**, Qing Gao*, Ziyan Liang, Junjie Hu, Zhaojie Ju

[**Project**](https://3469627147abc.github.io/ObjRetarget/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- 提出了一种面向人类视频学习的机器人运动重定向框架 ObjRetarget，通过拟人化轨迹优化与几何接触建模，实现了自然运动映射与稳定灵巧操作，并在多种任务中验证了良好的泛化性能。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/ICRA2026_3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DexTele: A Dual-Arm Dexterous Teleoperation System Based on Motion Retargeting and Adaptive Force Control

**Yuanchuan Lai**, Qing Gao*, Ziyan Liang, Xianfeng Cheng, Junjie Hu, Zhaojie Ju

[**Project**](https://3469627147abc.github.io/DexTele/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- 提出了一种基于运动重定向与自适应力控制的双臂灵巧遥操作系统 DexTele，实现了跨平台精确运动映射与顺应性抓取，并在多种机器人平台上验证了良好的泛化性能。

</div>
</div>

- [Motion Retargeting Using Graph Neural Network for Vision-Guided Dexterous Robot Teleoperation](https://ieeexplore.ieee.org/abstract/document/10776535) , **Yuanchuan Lai**, Zhaojie Ju , Qing Gao*, **i-CREATe 2024**


# 📝 发表专利|Patents
- *2025.07*: 《一种基于图神经网络的机器人重定向方法》  发明专利

# 💻 实习
- 2026.05 - 至今, [智元机器人(Agibot)](https://www.agibot.com.cn/), 上海.
 - 双臂遥操作系统项目：基于 Wuji 灵巧手 与 Genie G2 机器人搭建 VR 遥操作系统，实现人手动作到机器人双臂与灵巧手的实时运动映射；负责遥操作系统集成、运动控制及真机调试，为后续 VLA 数据采集与策略训练提供稳定的数据采集平台。
 - 共享控制 Type-Conditioned VLA 灵巧操作框架： 构建共享控制的 VLA 灵巧操作框架，通过 VR 遥操作完成机械臂接近目标，灵巧手结合物体类别自主生成抓取手势并完成抓取；完成网络框架设计、数据采集与模型训练，并部署至真实机器人平台进行验证，相关工作已投稿 ICRA 2027。

# 📝 项目经历|Project

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025.10</div><img src='images/IMG_20260209_154925.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[天奇-面向机器人具身智能的数据采集方法](https://3469627147abc.github.io/Tianqi/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025.01</div><img src='images/teleoperation_on_RM65b.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[先汇智能-面向仓储物流场景的遥操作抓取](https://3469627147abc.github.io/Xianhui/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024.12</div><img src='images/fig3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[2024深圳市智能机器人灵巧手大赛](https://z-mingyu.github.io/Dexteroushand/)

</div>
</div>

# 🎖 获奖情况|Awards
- *2025.09* 获中山大学硕士研究生一等奖助金、小米奖学金
- *2024.12* 获深圳市智能机器人灵巧手大赛三等奖 



# 📖 教育背景|Educations
- *2024.09 - 2026.03 (now)*, 硕士, 电子与通信工程学院, 中山大学 (推免).
- *2020.09 - 2024.06*, 本科, 自动化与电子信息学院, 湘潭大学.
