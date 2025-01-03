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

I am currently a second-year Master’s student in Computer Science at Xiamen University, where I conduct research under the guidance of [Prof. Rongshan Yu](https://scholar.google.com/citations?user=Uh1EpKQAAAAJ&hl=zh-CN&oi=ao) in the Biomedical AI Lab. 

In parallel, I am interning at the Shanghai Artificial Intelligence Laboratory, where I am fortunate to work under the mentorship of [Dr. Junjun He](https://scholar.google.com/citations?user=Z4LgebkAAAAJ&hl=zh-CN).

My research interests lie at the intersection of Computational Pathology, Multimodal Large Language Models, and AI for Medicine. I am deeply passionate about advancing the frontiers of Medical AI and **aspire to pursue a Ph.D.** to continue contributing to cutting-edge research in these fields.

 Welcome to contact me via email at cying2023@stu.xmu.edu.cn.

# 🔥 News
- *2024.10*: &nbsp; Thrilled to announce our latest work **SlideChat**, the first vision-language assistant capable of understanding gigapixel whole-slide images. 
- *2024.06*: &nbsp; One paper was accepted by **Cell Reports Methods**.
- *2024.02*: &nbsp; One paper was accepted by **CVPR2024**.
- *2023.05*: &nbsp; One paper was accepted by **Neural Networks**.

<style>
    .paper-box img {
        width: 365px; /* 指定固定宽度 */
        height: 200px; /* 指定固定高度 */
        object-fit: cover; /* 确保图像内容不变形 */
    }
</style>

# 📝 Preprint
(#: Co-first authors)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/SlideChat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding](https://arxiv.org/abs/2410.11761)

**Ying Chen**#, Guoan Wang#, Yuanfeng Ji#, Yanjun Li, Jin Ye, Tianbin Li, Bin Zhang, Nana Pei, Rongshan Yu, Yu Qiao, Junjun He

[**Project**](https://uni-medical.github.io/SlideChat.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Arxiv**](https://arxiv.org/abs/2410.11761) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/SurvMamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Survmamba: State space model with multi-grained multi-modal interaction for survival prediction](https://arxiv.org/abs/2404.08027)

**Ying Chen**, Jiajing Xie, Yuxiang Lin, Yuhang Song, Wenxian Yang, Rongshan Yu

[**Arxiv**](https://arxiv.org/abs/2404.08027) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

# 📝 Selected Publications [[Full List](https://scholar.google.com/citations?user=bYfM8fEAAAAJ&hl=zh-CN)]
(#: Co-first authors)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/Five.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalizable Whole Slide Image Classification with Fine-Grained Visual-Semantic Interaction](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Generalizable_Whole_Slide_Image_Classification_with_Fine-Grained_Visual-Semantic_Interaction_CVPR_2024_paper.pdf)

Hao Li, **Ying Chen**, Yifei Chen, Rongshan Yu, Wenxian Yang, Liansheng Wang, Bowen Ding, Yuchen Han

[**Paper**](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Generalizable_Whole_Slide_Image_Classification_with_Fine-Grained_Visual-Semantic_Interaction_CVPR_2024_paper.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/ls1rius/WSI_FiVE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Cell Reports Methods</div><img src='images/BPformer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Tracing unknown tumor origins with a biological-pathway-based transformer model](https://www.cell.com/cell-reports-methods/fulltext/S2667-2375(24)00153-X)

Jiajing Xie#, **Ying Chen**#, Shijie Luo#, Wenxian Yang, Yuxiang Lin, Liansheng Wang, Xin Ding, Mengsha Tong, Rongshan Yu

[**Paper**](https://www.cell.com/cell-reports-methods/fulltext/S2667-2375(24)00153-X) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/xmuyulab/BPformer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Website**](https://cup.bpformer.com/index/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/RAFNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[RAFNet: Restricted attention fusion network for sleep apnea detection](https://www.sciencedirect.com/science/article/abs/pii/S0893608023001454)

**Ying Chen**#, Huijun Yue#, Ruifeng Zou, Wenbin Lei, Wenjun Ma, Xiaomao Fan

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0893608023001454) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

# 📖 Educations
- *2023.09 - 2026.06 (now)*, Master in Computer Science and Technology, Xiamen University, advised by [Prof. Rongshan Yu](https://scholar.google.com/citations?user=Uh1EpKQAAAAJ&hl=zh-CN&oi=ao). 
- *2019.09 - 2023.06*, Bachelor in Artificial Intelligence, South China Normal University, advised by [Prof. Xiaomao Fan](https://scholar.google.com/citations?user=zDwIj2wAAAAJ&hl=zh-CN&oi=ao).


# 💻 Internships
- *2024.05 - present*, Shanghai Artificial Intelligence Laboratory, advised by [Dr. Junjun He](https://scholar.google.com/citations?user=Z4LgebkAAAAJ&hl=zh-CN).

# 🎖 Honors and Awards
- Scholarship of South China Normal University, 2020/2021/2022/2023.
- Second Prize of CUMCM, 2021. 
