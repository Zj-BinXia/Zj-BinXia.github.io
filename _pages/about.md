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

I am currently a 1st year PhD student in the Department of Computer Science and Engineering, Chinese University of Hong Kong, advised by Prof. [Jiaya Jia](https://scholar.google.com/citations?user=XPAkzTEAAAAJ). Previously, I received my master degree from Tsinghua University in 2023, advised by Prof. [Wenming Yang](https://scholar.google.com/citations?hl=en&user=vsE4nKcAAAAJ). During my study in Tsinghua University, I spent a good time with prof. [Yapeng Tian](https://scholar.google.com/citations?user=lxCqdpoAAAAJ), prof. [Yulun Zhang](https://scholar.google.com/citations?user=ORmLjWoAAAAJ), prof. [Radu Timofte](https://scholar.google.com/citations?user=u3MwH5kAAAAJ), and prof. [Luc Van Gool](https://scholar.google.com/citations?user=TwMib_QAAAAJ). Before that, I obtained my B.E degree from Xidian University in 2020. 

Recently, my research interests focus on generative models and LLM. Previously, I focused on low-level vision and model compression.

<span class='anchor' id='-news'></span>

# News
- **2023.11**	We release [LLMGA](https://github.com/dvlab-research/LLMGA).
- **2023.09**	1 papers are accepted by NeurIPS 2023 (Soptlight).
- **2023.10**	We release [DiffI2I](https://arxiv.org/pdf/2308.13767).
- **2023.07**	1 papers are accepted by ICCV 2023.
- **2023.06**	1 papers are accepted by TIP.
- **2023.02**	1 papers are accepted by CVPR 2023.
- **2023.01**	2 papers are accepted by ICLR 2023.
- **2021.12**	2 papers are accepted by AAAI 2022.

# Publications 


<!-- LLMGA -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/llmga-arxiv2023.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[LLMGA: Multimodal Large Language Model based Generation Assistant](https://arxiv.org/pdf/2311.16500)

**Bin Xia**, , Shiyin Wang, Yingfan Tao, Yitong Wang, Jiaya Jia

[**[Paper]**](https://arxiv.org/pdf/2311.16500)&nbsp;
[**[Code]**](https://github.com/dvlab-research/LLMGA)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- DiffI2I -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/diffi2i-arxiv2023.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffI2I: Efficient Diffusion Model for Image-to-Image Translation](https://arxiv.org/pdf/2308.13767)

**Bin Xia**, Yulun Zhang, Shiyin Wang, Yitong Wang, Xinglong Wu, Yapeng Tian, Wenming Yang, Radu Timotfe, Luc Van Gool

[**[Paper]**](https://arxiv.org/pdf/2308.13767)&nbsp;
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- Hi-Diff -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS2023</div><img src='images/hidiff-nips2023.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[Hierarchical Integration Diffusion Model for Realistic Image Deblurring](https://arxiv.org/pdf/2305.12966.pdf)

Zheng Chen, Yulun Zhang, Ding Liu, **Bin Xia**, Jinjin Gu, Linghe Kong, and Xin Yuan

[**[Paper]**](https://arxiv.org/pdf/2305.12966.pdf)&nbsp;
[**[Code]**](https://github.com/zhengchen1999/HI-Diff)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>


<!-- DiffIR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV2023</div><img src='images/diffir-iccv2023.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffIR: Efficient diffusion model for image restoration](https://arxiv.org/pdf/2303.09472.pdf)

**Bin Xia**, Yulun Zhang, Shiyin Wang, Yitong Wang, Xinglong Wu, Yapeng Tian, Wenming Yang, Luc Van Gool

[**[Paper]**](https://arxiv.org/pdf/2303.09472.pdf)&nbsp;
[**[Code]**](https://github.com/Zj-BinXia/DiffIR)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>



<!-- SSL -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR2023</div><img src='images/ssl-cvpr2023.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[Structured Sparsity Learning for Efficient Video Super-Resolution](https://arxiv.org/pdf/2206.07687.pdf)

**Bin Xia**, Jingwen He, Yulun Zhang, Yitong Wang, Yapeng Tian, Wenming Yang, Luc Van Gool

[**[Paper]**](https://arxiv.org/pdf/2206.07687.pdf)&nbsp;
[**[Code]**](https://github.com/Zj-BinXia/SSL)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- BBCU -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2023</div><img src='images/bbcu-iclr2023.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[Basic Binary Convolution Unit for Binarized Image Restoration Network](https://arxiv.org/pdf/2210.00405.pdf)

**Bin Xia**, Yulun Zhang, Yitong Wang, Yapeng Tian, Wenming Yang, Radu Timofte, Luc Van Gool

[**[Paper]**](https://arxiv.org/pdf/2210.00405.pdf)&nbsp;
[**[Code]**](https://github.com/Zj-BinXia/BBCU)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- KDSR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2023</div><img src='images/kdsr-iclr2023.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[Knowledge Distillation based Degradation Estimation for Blind Super-Resolution](https://arxiv.org/pdf/2211.16928.pdf)

**Bin Xia**, Yulun Zhang, Yitong Wang, Yapeng Tian, Wenming Yang, Radu Timofte, Luc Van Gool

[**[Paper]**](https://arxiv.org/pdf/2211.16928.pdf)&nbsp;
[**[Code]**](https://github.com/Zj-BinXia/KDSR)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>



<!-- MRDA -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP2022</div><img src='images/MRDA-tip2022.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[Meta-learning based degradation representation for blind super-resolution](https://arxiv.org/pdf/2207.13963.pdf)

**Bin Xia**, Yapeng Tian, Yulun Zhang, Yucheng Hang, Wenming Yang, Qingmin Liao

[**[Paper]**](https://arxiv.org/pdf/2207.13963.pdf)&nbsp;
[**[Code]**](https://github.com/Zj-BinXia/MRDA)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- AMSA -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2022</div><img src='images/amsa-aaai2022.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[Coarse-to-Fine Embedded PatchMatch and Multi-Scale Dynamic Aggregation for Reference-based Super-Resolution](https://arxiv.org/abs/2201.04358)

**Bin Xia**, Yucheng Hang, Yapeng Tian, Wenming Yang, Qingmin Liao, Jie Zhou

[**[Paper]**](https://arxiv.org/abs/2201.04358)&nbsp;
[**[Code]**](https://github.com/Zj-BinXia/AMSA)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- ENLCA -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2022</div><img src='images/enlca-aaai2022.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient Non-Local Contrastive Attention for Image Super-Resolution](https://arxiv.org/pdf/2201.03794)

**Bin Xia**, Yucheng Hang, Yapeng Tian, Wenming Yang, Qingmin Liao, Jie Zhou

[**[Paper]**](https://arxiv.org/pdf/2201.03794.pdf)&nbsp;
[**[Code]**](https://github.com/Zj-BinXia/ENLCA)
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

# Honors and Awards
- **2023.07**,  Excellent Graduate of Tsinghua University
- **2023.07**,  Excellent Master Thesis Award, Tsinghua University
- **2023.05**,  Outstanding Reviewer Award at CVPR
- **2023.05**,  First Prize in Internship Award of Tsinghua University
- **2022.10**,  National Scholarship, Tsinghua University
- **2020.07**,  Excellent Graduate of Xidian University
- **2018.10**,  National Scholarship, Xidian University

<span class='anchor' id='-services'></span>

# Services

**Conference Reviewer**: CVPR, ICLR, ICCV, NeurIPS, AAAI, WACV

**Journal Reviewer**: TIP, IJCV, TNNLS, TMM, TCSVT




