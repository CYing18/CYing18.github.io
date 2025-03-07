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

I am a second-year Master's student in Computer Science at Xiamen University, where I conduct research in medical artificial intelligence under the supervision of [Prof. Rongshan Yu](https://scholar.google.com/citations?user=Uh1EpKQAAAAJ&hl=zh-CN&oi=ao) at the Biomedical AI Laboratory. Concurrently, I hold a research internship position at Shanghai Artificial Intelligence Laboratory, under the mentorship of [Dr. Junjun He](https://scholar.google.com/citations?user=Z4LgebkAAAAJ&hl=zh-CN) on Generalist Medical Artificial Intelligence.

My research focuses on how AI can transform healthcare, with particular interests in 1) Computational Pathology, 2) Multi-omics, and 3) Multimodal Large Language Models. These experiences have reinforced my commitment to pursuing a Ph.D. to further contribute to the development of clinically reliable AI systems. I am actively **seeking Ph.D. opportunities for Fall 2026** to continue my work in this area.

 Welcome to contact me via email at cying2023@stu.xmu.edu.cn.

# 🔥 News
- *2025.02*: &nbsp; One paper was accepted by **CVPR2025**.
- *2024.06*: &nbsp; One paper was accepted by **Cell Reports Methods**.
- *2024.02*: &nbsp; One paper was accepted by **CVPR2024**.
- *2023.05*: &nbsp; One paper was accepted by **Neural Networks**.

# 📖 Educations
- *2023.09 - 2026.06*, Xiamen University, Master in Computer Science and Technology.
- *2019.09 - 2023.06*, South China Normal University, Bachelor in Artificial Intelligence.

# 💻 Internships
- *2024.05 - present*, Shanghai Artificial Intelligence Laboratory.

<style>
    .paper-box img {
        width: 320px; /* 指定固定宽度 */
        height: 150px; /* 指定固定高度 */
        object-fit: cover; /* 确保图像内容不变形 */
    }
</style>

# 📝 Selected Publications [[Full List](https://scholar.google.com/citations?user=bYfM8fEAAAAJ&hl=zh-CN)]<span style="font-size: x-small; font-style: italic;"> (*#: Co-first authors*)</span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR2025</div><img src='images/SlideChat.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding](https://arxiv.org/abs/2410.11761)

**Ying Chen**#, Guoan Wang#, Yuanfeng Ji#, Yanjun Li, Jin Ye, Tianbin Li, Bin Zhang, Nana Pei, Rongshan Yu, Yu Qiao, Junjun He

IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**), 2025.

[**Project**](https://uni-medical.github.io/SlideChat.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Paper**](https://arxiv.org/abs/2410.11761) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/SurvMamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Survmamba: State space model with multi-grained multi-modal interaction for survival prediction](https://arxiv.org/abs/2404.08027)

**Ying Chen**, Jiajing Xie, Yuxiang Lin, Yuhang Song, Wenxian Yang, Rongshan Yu

[**Paper**](https://arxiv.org/abs/2404.08027) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/RAFNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[RAFNet: Restricted attention fusion network for sleep apnea detection](https://www.sciencedirect.com/science/article/abs/pii/S0893608023001454)

**Ying Chen**#, Huijun Yue#, Ruifeng Zou, Wenbin Lei, Wenjun Ma, Xiaomao Fan

<span>Neural Networks, 2023. </span><span style="color: gray;">IF: 6.0</span>

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0893608023001454) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/Five.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalizable Whole Slide Image Classification with Fine-Grained Visual-Semantic Interaction](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Generalizable_Whole_Slide_Image_Classification_with_Fine-Grained_Visual-Semantic_Interaction_CVPR_2024_paper.pdf)

Hao Li, **Ying Chen**, Yifei Chen, Rongshan Yu, Wenxian Yang, Liansheng Wang, Bowen Ding, Yuchen Han

IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**), 2024.

[**Paper**](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Generalizable_Whole_Slide_Image_Classification_with_Fine-Grained_Visual-Semantic_Interaction_CVPR_2024_paper.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/ls1rius/WSI_FiVE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Cell Reports Methods</div><img src='images/BPformer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Tracing unknown tumor origins with a biological-pathway-based transformer model](https://www.cell.com/cell-reports-methods/fulltext/S2667-2375(24)00153-X)

Jiajing Xie#, **Ying Chen**#, Shijie Luo#, Wenxian Yang, Yuxiang Lin, Liansheng Wang, Xin Ding, Mengsha Tong, Rongshan Yu

Cell Reports Methods, 2024. 

[**Paper**](https://www.cell.com/cell-reports-methods/fulltext/S2667-2375(24)00153-X) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/xmuyulab/BPformer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Website**](https://cup.bpformer.com/index/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BIBM</div><img src='images/bibm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SE-MSCNN: a lightweight multi-scaled fusion network for sleep apnea detection using single-lead ECG signals](https://ieeexplore.ieee.org/abstract/document/9669358)

Xianhui Chen#, **Ying Chen**#, Wenjun Ma, Xiaomao Fan, Ye Li

IEEE International Conference on Bioinformatics and Biomedicine (**BIBM**), 2021. 

[**Paper**](https://ieeexplore.ieee.org/abstract/document/9669358) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/Bettycxh/Toward-Sleep-Apnea-Detection-with-Lightweight-Multi-scaled-Fusion-Network) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


# 🎖 Honors and Awards
- Scholarship of South China Normal University, 2020/2021/2022/2023.
- Second Prize of CUMCM, 2021.

# 🗂️ Professional Activities
- Conference Reviewers: CVPR, ICCV.
- Journal Reviewers: BSCP, JDIM.
