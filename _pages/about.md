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

I am a postdoctoral researcher in [Chang Xu](http://changxu.xyz/)'s group at the School of Computer Science, The University of Sydney.
I obtained a PhD degree from Peking University supervised by [A/Prof Tingting Jiang](http://www.vie.group/ttj) and [Prof Yizhou Wang](https://cfcs.pku.edu.cn/english/people/faculty/yizhouwang/index.htm), and a Bachelor of Engineering from Tongji University. 
My research interests lie in computer vision, artificial intelligence, and related topics in the medical domain, specifically including:
- Generative AI, Diffusion Models
- Surgical AI, Surgical Skill Assessment
- Video Understanding and Action Analysis

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->

<span class='anchor' id='news'></span>

# 🔥 News
- *2023.07*: &nbsp;🎉🎉 Two papers are accepted by ICCV 2023. 
- *2023.07*: I will serve as a reviewer of AAAI 2024.

<span class='anchor' id='publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/ICCV2023-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Diffusion Action Segmentation](https://arxiv.org/abs/2303.17959) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>

**Daochang Liu**, Qiyue Li, Anh-Dung Dinh, Tingting Jiang, Mubarak Shah, Chang Xu

*International Conference on Computer Vision (ICCV), 2023*

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/ICCV2023-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Personalized Image Generation for Color Vision Deficiency Population <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:8k81kl-MbHgC'></span></strong>

Shuyi Jiang, **Daochang Liu**, Dingquan Li, Chang Xu

*International Conference on Computer Vision (ICCV), 2023*

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/ICML2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PixelAsParam: A Gradient View on Diffusion Sampling with Guidance](https://openreview.net/forum?id=2q1Whv1kXL) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:5nxA0vEk-isC'></span></strong>

Anh-Dung Dinh, **Daochang Liu**, Chang Xu

*International Conference on Machine Learning (ICML), 2023*

[[Code]](https://github.com/dungdinhanh/pxpguided-diffusion)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/CVPR2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Private Image Generation with Dual-Purpose Auxiliary Classifier](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_Private_Image_Generation_With_Dual-Purpose_Auxiliary_Classifier_CVPR_2023_paper.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:0EnyYjriUFMC'></span></strong>

Chen Chen, **Daochang Liu**, Siqi Ma, Surya Nepal, Chang Xu

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023*

[[Code]](https://github.com/chenchen-usyd/DP-GAN-DPAC) [[Video]](https://www.youtube.com/watch?v=ZsjYIZ2s0fw)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDM 2022</div><img src='images/ICDM2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Contrastive Code-Comment Pre-training](https://ieeexplore.ieee.org/document/10027715) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:_FxGoFyzp5QC'></span></strong>

Xiaohuan Pei, **Daochang Liu**, Qian Luo, Chang Xu

*IEEE International Conference on Data Mining (ICDM), 2022*

**Best Student Paper Award** 

[[Code]](https://github.com/TerryPei/C3P)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/CVPR21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Unified Surgical Skill Assessment](https://arxiv.org/abs/2106.01035) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:YsMSGLbcyi4C'></span></strong>

**Daochang Liu**, Qiyue Li, Tingting Jiang, Yizhou Wang, Rulin Miao, Fei Shan, Ziyu Li

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021*

[[Code]](https://github.com/Finspire13/Towards-Unified-Surgical-Skill-Assessment) [[Slides]](http://www.vie.group/media/pdf/CVPR2021_SLIDES.pptx) [[Poster]](http://www.vie.group/media/pdf/CVPR2021_POSTER.pdf)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2020</div><img src='images/MICCAI20.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unsupervised Surgical Instrument Segmentation via Anchor Generation and Semantic Diffusion](http://www.vie.group/media/pdf/paper204.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:Y0pCki6q_DkC'></span></strong>

**Daochang Liu\***, Yuhui Wei\*, Tingting Jiang, Yizhou Wang, Rulin Miao, Fei Shan, Ziyu Li

*International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI), 2020*

[[Code]](https://github.com/Finspire13/AGSD-Surgical-Instrument-Segmentation) [[Slides]](http://www.vie.group/media/pdf/MICCAI_2020_Slides.pdf) [[Poster]](http://www.vie.group/media/pdf/Abstract_204.pdf)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCARS 2020</div><img src='images/IJCARS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Clearness of Operating Field: A Surrogate for Surgical Skills on In-Vivo Clinical Data](http://www.vie.group/media/pdf/IJCARS.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:W7OEmFMy1HYC'></span></strong>

**Daochang Liu**, Tingting Jiang, Yizhou Wang, Rulin Miao, Fei Shan, Ziyu Li

*International Journal of Computer Assisted Radiology and Surgery (IJCARS), 2020*

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2019</div><img src='images/CVPR19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Completeness Modeling and Context Separation for Weakly Supervised Temporal Action Localization](http://www.vie.group/media/pdf/1273.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:qjMakFHDy7sC'></span></strong>

**Daochang Liu**, Tingting Jiang, Yizhou Wang

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2019*

[[Code]](https://github.com/Finspire13/CMCS-Temporal-Action-Localization) [[Poster]](http://www.vie.group/media/pdf/CVPR海报_ldc_final.pdf)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2019</div><img src='images/MICCAI19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Surgical Skill Assessment on In-Vivo Clinical Data via the Clearness of Operating Field](http://www.vie.group/media/pdf/paper37.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:zYLM7Y9cAGgC'></span></strong>

**Daochang Liu**, Tingting Jiang, Yizhou Wang, Rulin Miao, Fei Shan, Ziyu Li

*International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI), 2019*

[[Slides]](http://www.vie.group/media/pdf/7_2_Daochang_2sag3xD.pptx) [[Poster]](http://www.vie.group/media/pdf/MICCAI_2019_Poster_QpBvnvQ.pdf)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2018</div><img src='images/MICCAI18.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Reinforcement Learning for Surgical Gesture Segmentation and Classification](http://www.vie.group/media/pdf/paper.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:9yKSN-GCB0IC'></span></strong>

**Daochang Liu**, Tingting Jiang

*International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI), 2018*

[[Code]](https://github.com/Finspire13/RL-Surgical-Gesture-Segmentation) [[Poster]](http://www.vie.group/media/pdf/MICCAI_Poster_v7.pdf)

</div>
</div>

- [Calibrating a Deep Neural Network with Its Predecessors](https://arxiv.org/abs/2302.06245) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:roLk4NBRz8UC'></span></strong>, Linwei Tao, Minjing Dong, **Daochang Liu**, Changming Sun, Chang Xu. *International Joint Conference on Artificial Intelligence (IJCAI), 2023*, [[Code]](https://github.com/Linwei94/PCS)
- [Comparative Validation of Machine Learning Algorithms for Surgical Workflow and Skill Analysis with the HeiChole Benchmark](https://www.sciencedirect.com/science/article/pii/S1361841523000312) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:Se3iqnhoufwC'></span></strong>, Martin Wagner, ..., **Daochang Liu**, ..., Sebastian Bodenstedt. *Medical Image Analysis (MedIA), 2023*, [[Dataset]](https://endovissub-workflowandskill.grand-challenge.org/)
- Surgical Skill Assessment Method and Device, Tingting Jiang, Ziyu Li, **Daochang Liu**, Qiyue Li, Yizhou Wang, Rulin Miao, Fei Shan. *China Patent (ZL202110443748.9)*

<span class='anchor' id='teaching'></span>

# 📖 Teaching
- *2023*, Lecturer for OCMP5329 Deep Learning, The University of Sydney
- *2023*, Guest Lecturer for INFO5993 CS Research methods, The University of Sydney
- *2022*, Guest Lecturer for HTIN5005 Applied Healthcare Data Science, The University of Sydney
- *2019*, Tutor for Computer Vision Algorithms and Techniques, Peking University

<span class='anchor' id='awards'></span>

# 🎖 Awards
- *2022*, ICDM Best Student Paper Award
- *2021*, Peking University Tianchuang Scholarship
- *2020*, Microsoft Research Asia Fellowship Nomination
- *2019*, Peking University Principle's Scholarship
- *2019*, Peking University Academic Innovation Award
- *2017*, Shanghai Outstanding Bachelor Graduate

<span class='anchor' id='talks'></span>

# 💬 Talks
- *2023*, "What Does ChatGPT mean to AI Research", The University of Sydney
- *2023*, "Research in AI", The University of Sydney
- *2022*, "Biomedical Image Analysis", The University of Sydney
- *2021*, "Video-Based Surgical Skill Assessment - Improving Surgical Care by Computer Vision", Baidu Inc.
- *2020*, "Computer-Aided Surgical Skill Assessment", Microsoft Research Asia
- *2019*, "Surgical Skill Assessment on In-Vivo Clinical Data via the Clearness of Operating Field", MICCAI

<span class='anchor' id='grants'></span>

# 🌟 Grants

- *2023 Q1-Q2*, Image Generation for the Colour Vision Impaired (Lead CI), 10000 GPU Hours, The National Computational Infrastructure (NCI) Adapter Scheme, Australia 

<span class='anchor' id='services'></span>

# ♥️ Services

- *2022*, Local Arrangement Chair and Session Chair of The International Conference on Digital Image Computing: Techniques and Applications (DICTA)
- Reviewer of ICCV, CVPR, BMVC, NeurIPS, ICML, ICLR, AAAI, IJCAI, KDD, ICDM, MICCAI, DICTA
- Reviewer of TPAMI, TMI, TMM, CVIU, TMLR, Pattern Recognition, IEEE Access

# -

**Contact:** daochang.liu at sydney.edu.au, finspire13 at gmail.com

**Last Update:** July 15, 2023

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=EPHsmQIJLbnhIay_lL2JI0tJ1EPMrLTnAPwg8zuvHkY&cl=ffffff&w=150"></script>