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
Hi😄! I'm Zhiheng Ma (马智恒), an Assistant Professor, PI and Ph.D. Supervisor in the Faculty of Computility Microelectronics (算力微电子学院) at Shenzhen University of Advanced Technology (SUAT, 深圳理工大学). Prior to this, I was an Assistant Research Professor at Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences, where I had the privilege to work with Prof. <a href='https://people.ucas.ac.cn/~lhy2015'>Huiyun Li</a>. I received my Ph.D. in 2021 from Xi'an Jiaotong University, under the supervision of IEEE Fellow Prof. <a href='https://gr.xjtu.edu.cn/web/ygong'>Yihong Gong</a> and co-supervision of Prof. <a href='https://hongxiaopeng.com'>Xiaopeng Hong</a>.

My research lies at the fascinating intersection of Computer Vision, AI for Science, and Brain-inspired Intelligence. I am particularly passionate about three cutting-edge areas: Continual Learning (enabling AI systems to learn and adapt continuously), Data-efficient Learning (making AI more practical with limited data and labels), and Multi-modal Learning (integrating information from multiple sources like human brains do). The ultimate goal of my research is to develop intelligent agents that can mirror human-like capabilities - autonomously conducting scientific exploration, continuously acquiring and adapting knowledge, and maintaining long-term memory.

I have published more than 30 papers in top-tier AI journals and conferences. For more details about my research work, please check my Google Scholar profile <a href='https://scholar.google.com/citations?user=y6ijVukAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. I am actively seeking motivated students who share my passion for advancing the frontiers of AI and developing next-generation intelligent systems. If you're interested in joining my research group, please feel free to reach out!

**We are looking for Ph.D. students, Master students, Postdoctoral researchers, Research Assistants, and Research Interns! If you're interested, please email me (mazhiheng@suat-sz.edu.cn) with your CV.** For admission details and requirements, please check <a href='https://zs.suat-sz.edu.cn/info/1010/1291.htm'>here</a>.


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 Paper accepted by CVPR 2025. Congratulations to AnJia!
- *2025.02*: &nbsp;🎉🎉 Paper accepted by T-CSVT. Congratulations to Yaohui!
- *2025.01*: &nbsp;🎉🎉 Paper accepted by T-PAMI. Congratulations to Hui Lin!
- *2024.12*: &nbsp;🎉🎉 Paper accepted by AAAI 2025. Congratulations to Yaohui!

# 📝 Publications 
<a href='https://scholar.google.com/citations?user=y6ijVukAAAAJ'>[Full List of Publications]</a>

## 💾 Data-efficient Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2019</div><img src='images/bayesian.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Bayesian loss for crowd count estimation with point supervision](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Bayesian_Loss_for_Crowd_Count_Estimation_With_Point_Supervision_ICCV_2019_paper.pdf)
**Zhiheng Ma**<sup>#</sup>, Xing Wei<sup>#</sup>, Xiaopeng Hong<sup>&</sup>, Yihong Gong
[**Code**](https://github.com/zhiheng-ma/Bayesian-Crowd-Counting)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/speed.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Sparse parameterization for epitomic dataset distillation](https://proceedings.neurips.cc/paper_files/paper/2023/file/9e8889198d16fb79926e71adbe38cae4-Paper-Conference.pdf)
Xing Wei, Anjia Cao, Funing Yang, **Zhiheng Ma**<sup>&</sup>
[**Code**](https://github.com/MIV-XJTU/SPEED)
</div>
</div>

## 🧠 Continual Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/isolation.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Isolation and impartial aggregation: A paradigm of incremental learning without interference](https://ojs.aaai.org/index.php/AAAI/article/view/26216/25988)
Yabin Wang<sup>#</sup>, **Zhiheng Ma**<sup>#</sup>, Zhiwu Huang, Yaowei Wang, Zhou Su, Xiaopeng Hong<sup>&</sup>
[**Code**](https://github.com/iamwangyabin/ESN)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-CSVT</div><img src='images/joint.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Joint Memory Optimization for Continual Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10877933)
**Zhiheng Ma**, Yaohui Ma, Xiaopeng Hong, Huiyun Li, Shizhou Zhang<sup>&</sup>
[**Code**](https://github.com/yaohui120/JMOCL)
</div>
</div>

## 📱 Multi-modal Learning 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/edit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ComprehendEdit: A Comprehensive Dataset and Evaluation Framework for Multimodal Knowledge Editing](https://arxiv.org/pdf/2412.12821)
Yaohui Ma, Xiaopeng Hong, Shizhou Zhang, Huiyun Li, Zhilin Zhu, Wei Luo, **Zhiheng Ma**<sup>&</sup>
[**Code**](https://github.com/yaohui120/ComprehendEdit)
</div>
</div>


# 🎖 Honors and Awards
- *2022* World Artificial Intelligence Conference (WAIC) SAIL Award - Rising Star
- *2022* Shenzhen "Pengcheng Peacock" Special Employment Program (Category C)
- *2021* "Science and Innovation China" Young Entrepreneur List
- *2018* Gold Award (1st/5,272) - Alibaba Tianchi FashionAI Global Challenge: Clothing Attribute Recognition
- *2019* Gold Award, Guangdong Industrial Manufacturing Big Data Innovation Application Competition 
- *2021* Gold Award (1st/4,432) - Alibaba Tianchi Guangdong Industrial Manufacturing Big Data Innovation Competition: Tile Defect Detection
- *2016* Silver Award - National Graduate Smart City Technology and Creative Design Competition, Intelligent Technology Challenge (Face Recognition Track)
- *2018* Silver Award, 11th "Challenge Cup" Business Plan Competition
- *2017* Silver Award - National Graduate Smart City Technology and Creative Design Competition, Intelligent Technology Challenge (Abnormal Behavior Detection Track) 
- *2019* Silver Award (2nd/2,972) - Alibaba Tianchi Guangdong Industrial Manufacturing Big Data Innovation Competition: Aluminum Profile Defect Detection


<span class='anchor' id='-students'></span>
# 🧑‍⚖️ Students
- *2021.09 - Now*, Hui Lin, Ph.D. Student, T-PAMI, T-NNLS, CVPR, AAAI ... (co-advised with Prof. Deyu Meng and Prof. Xiaopeng Hong) 
- *2023.09 - Now*, Zhilin Zhu, Ph.D. Student, ECCV (co-advised with Prof. Xiaopeng Hong) 
- *2024.09 - Now*, Yaohui Ma, Ph.D. Student, AAAI, T-CSVT (co-advised with Prof. Xiaopeng Hong and Prof. Shizhou Zhang) 
- *2023.09 - Now*, Anjia Cao, Master Student, NeurIPS，CVPR (co-advised with Prof. Xing Wei)
- *2024.09 - Now*, Xiangyu Zou, Master Student (co-advised with Prof. Huiyun Li)
