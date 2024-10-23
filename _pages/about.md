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

I am a postdoctoral researcher in A/Prof [Arnold Lining Ju](https://prerender.sydney.edu.au/https://www.sydney.edu.au/engineering/about/our-people/academic-staff/arnold-ju.html)'s group at the School of Biomedical Engineering, Faculty of Engineering The University of Sydney.
I obtained my PhD degree from the School of Computer Science, USYD, supervised by Prof [Dacheng Tao](https://scholar.google.com/citations?user=RwlJNLcAAAAJ) 2021-2024. I obtained my Master's degree from Tsinghua University, 2017-2020.

My research interests lie in artificial intelligence, computer vision, autonomous driving, AI for biomedical engineering, and digital healthcare.

<!-- I obtained a PhD degree from Peking University supervised by A/Prof [Tingting Jiang](http://www.vie.group/ttj) and Prof [Yizhou Wang](https://cfcs.pku.edu.cn/english/people/faculty/yizhouwang/index.htm), and a Bachelor of Engineering from Tongji University. 
 -->


<!-- My research interests lie in intelligent surgical skill assessment using computer vision and generative artificial intelligence.
 -->

<!-- My research seeks to answer two principal questions, i.e., “what” is performed and “how well” it is performed, by observing human activities from visual or multi-modal data and using generative learning frameworks. This is pivotal to human-centric machine intelligence to comprehend, collaborate with, and amplify human capabilities in daily and professional lives.  -->

<!-- This stems from the notion that human behavior is inherently a generative act, conditioned on driving goals, environmental contexts, and prior experiences. Such an “understanding-by-generating" paradigm enables unsupervised learning of human activities. I also feel excited about delving into human skill assessment by viewing skills as emergent attributes generated from repeated action operations. My goal is to understand skill acquisition through generative learning, by connecting the generative process of actions and the learning curve of skills from novice to expert.  -->

<!-- My research about generative surgical AI lies in intelligent analysis of surgeries to enhance patient care and surgical education. The short-term goal is to demystify the intricacies of surgical procedures, e.g., tool usage and event patterns, using videos from minimally invasive or robotic surgeries, and establish links with surgical skills and clinical outcomes. My previous works have shown promising results; AI-based skill assessment on in-vivo clinical gastrectomy surgeries demonstrated remarkable correlations with the expert consensus. The long-term vision is to bring intelligence into the multimodal data of surgeries in an enriched context beyond videos, including perioperative imaging, robotic kinematics, textual records, and environmental and physiological metrics, to offer holistic insights into surgical procedures. By utilizing specialized models, foundational models, and specialized-foundational models of machine learning, my research aims to advance surgical data science from concept to translation in the next generation of surgery.
 -->
<!-- My research is rooted in understanding human action and skills with computer vision and generative artificial intelligence, which also involves fundamental problems in generative diffusion models and applications in automatic surgical skill assessment.
 -->
<!-- My research interests lie in computer vision, artificial intelligence, and related topics in the medical domain, specifically including:
- Generative AI, Diffusion Models
- Surgical AI, Surgical Skill Assessment
- Video Understanding and Action Analysis -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->

<span class='anchor' id='news'></span>

# 🔥 News
- *2024.09*: One paper accepted by NeurIPs 2024.
- *2024.07*: One paper accepted by ECCV 2024.
- *2024.02*: One paper accepted by CVPR 2024. 
<!-- *2024.02*: I will serve as an Area Chair for MICCAI 2024.  -->

<span class='anchor' id='publications'></span>





<br>

# 📝 Robust and Efficient AI for Robotics and Autonomous Driving 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR24_mainfigure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UniMix: Towards Domain Adaptive and Generalizable LiDAR Semantic Segmentation in Adverse Weather](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_UniMix_Towards_Domain_Adaptive_and_Generalizable_LiDAR_Semantic_Segmentation_in_CVPR_2024_paper.html) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>

**Haimei Zhao**, Jing Zhang, Zhuo Chen, Shanshan Zhao, Dacheng Tao

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024*



</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/CVPR19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Simdistill: Simulated multi-modal distillation for bev 3d object detection](https://ojs.aaai.org/index.php/AAAI/article/view/28577) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:qjMakFHDy7sC'></span></strong>

**Haimei Zhao**, Qiming Zhang, Shanshan Zhao, Zhe Chen, Jing Zhang, Dacheng Tao

*Proceedings of the AAAI Conference on Artificial Intelligence, 2024*

[[Code]](https://github.com/Finspire13/CMCS-Temporal-Action-Localization) [[Poster]](http://www.vie.group/media/pdf/CVPR海报_ldc_final.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MIR 2022</div><img src='images/ICDM2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[On Robust Cross-View Consistency in Self-Supervised Monocular Depth Estimation]((https://link.springer.com/article/10.1007/s11633-023-1474-0) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:_FxGoFyzp5QC'></span></strong>

**Haimei Zhao**, Jing Zhang, Zhuo Chen, Bo Yuan, Dacheng Tao

*Machine Intelligence Research, 2024*

[[Code]](https://github.com/TerryPei/C3P)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/ICDM2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Jperceiver: Joint perception network for depth, pose and layout estimation in driving scenes](https://link.springer.com/chapter/10.1007/978-3-031-19839-7_41) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:_FxGoFyzp5QC'></span></strong>

**Haimei Zhao**, Jing Zhang, Sen Zhang, Dacheng Tao

*European Conference on Computer Vision, 2022*

[[Code]](https://github.com/TerryPei/C3P)

</div>
</div>

- [Beyond Pretrained Features: Noisy Image Modeling Provides Adversarial Defense](https://neurips.cc/virtual/2023/poster/70490)<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:LkGwnXOMwfcC'></span></strong>, Zunzhi You, **Daochang Liu**, Chang Xu. *Conference on Neural Information Processing Systems (NeurIPS), 2023*, [[Code]](https://github.com/youzunzhi/NIM-AdvDef)

- [Learning Spatiotemporal Frequency-Transformer for Low-Quality Video Super-Resolution](https://arxiv.org/abs/2212.14046)<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:ufrVoPGSRksC'></span></strong>, Zhongwei Qiu, Huan Yang, Jianlong Fu, **Daochang Liu**, Chang Xu, Dongmei Fu. *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023*, [[Code]](https://github.com/researchmm/FTVSR)

- [Calibrating a Deep Neural Network with Its Predecessors](https://arxiv.org/abs/2302.06245)<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:roLk4NBRz8UC'></span></strong>, Linwei Tao, Minjing Dong, **Daochang Liu**, Changming Sun, Chang Xu. *International Joint Conference on Artificial Intelligence (IJCAI), 2023*, [[Code]](https://github.com/Linwei94/PCS) [[Playground]](https://colab.research.google.com/drive/1TjwzG962eyOF51zzqlWLwv3Wq-lgMHZM?usp=sharing)






<br>


# 📝 AI for Biomedical Science, Digital Health 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/ICML2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Strategic reuse of rapid antigen tests for coagulation status assessment: an integrated machine learning approach]([https://openreview.net/pdf?id=PpBs2iL0jv](https://link.springer.com/article/10.1007/s44258-024-00025-3)) 
<!-- <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:_kc_bZDykSQC'></span></strong>
 -->

Allan Sun, Arian Nasser, Chaohao Chen, Yunduo Charles Zhao, **Haimei Zhao**, Zihao Wang, Wenlong Cheng, Pierre Qian, Lining Arnold Ju

*Med-X, 2024*

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR2024-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Memorization-Free Diffusion Models](https://arxiv.org/abs/2404.00922) 
<!-- <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:_kc_bZDykSQC'></span></strong>
 -->

Chen Chen, **Daochang Liu**, Chang Xu

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024*

[[Project]](https://chenchen-usyd.github.io/AMG-Project-Page/) [[Code]](https://github.com/chenchen-usyd/AMG) [[Video]](https://www.youtube.com/watch?v=aS7xfWQTuJk)

</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR2024-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Residual Learning in Diffusion Models](https://openreview.net/pdf?id=EHX9Zg0zW8) 

Junyu Zhang, **Daochang Liu**, Eunbyung Park, Shichao Zhang, Chang Xu

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024*

</div>
</div> -->



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/NeurIPS2023-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rethinking Conditional Diffusion Sampling with Progressive Guidance](https://neurips.cc/virtual/2023/poster/70851) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:_kc_bZDykSQC'></span></strong>

Anh-Dung Dinh, **Daochang Liu**, Chang Xu

*Conference on Neural Information Processing Systems (NeurIPS), 2023*

<!-- [[Code]](https://github.com/dungdinhanh/prog-guided-diffusion) -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/NeurIPS2023-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Contrastive Sampling Chains in Diffusion Models](https://neurips.cc/virtual/2023/poster/71042) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:YOwf2qJgpHMC'></span></strong>

Junyu Zhang,**Daochang Liu**, Shichao Zhang, Chang Xu

*Conference on Neural Information Processing Systems (NeurIPS), 2023*

[[Code]](https://github.com/BestJunYu/Contrastive-Sampling)

</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/ICCV2023-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Personalized Image Generation for Color Vision Deficiency Population](https://openaccess.thecvf.com/content/ICCV2023/html/Jiang_Personalized_Image_Generation_for_Color_Vision_Deficiency_Population_ICCV_2023_paper.html) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:8k81kl-MbHgC'></span></strong>

Shuyi Jiang, **Daochang Liu**, Dingquan Li, Chang Xu

*International Conference on Computer Vision (ICCV), 2023*

[[Code]](https://github.com/Jiangshuyi0V0/CVD-GAN)

</div>
</div> -->



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/ICML2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PixelAsParam: A Gradient View on Diffusion Sampling with Guidance](https://proceedings.mlr.press/v202/dinh23a.html) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:5nxA0vEk-isC'></span></strong>

Anh-Dung Dinh, **Daochang Liu**, Chang Xu

*International Conference on Machine Learning (ICML), 2023*

[[Code]](https://github.com/dungdinhanh/pxpguided-diffusion)

</div>
</div>



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/CVPR2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Private Image Generation with Dual-Purpose Auxiliary Classifier](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_Private_Image_Generation_With_Dual-Purpose_Auxiliary_Classifier_CVPR_2023_paper.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:0EnyYjriUFMC'></span></strong>

Chen Chen, **Daochang Liu**, Siqi Ma, Surya Nepal, Chang Xu

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023*

[[Code]](https://github.com/chenchen-usyd/DP-GAN-DPAC) [[Video]](https://www.youtube.com/watch?v=ZsjYIZ2s0fw)

</div>
</div> -->


- [Residual Learning in Diffusion Models](https://openreview.net/pdf?id=EHX9Zg0zW8), Junyu Zhang, **Daochang Liu**, Eunbyung Park, Shichao Zhang, Chang Xu. *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024*

- [Boosting Diffusion Models with an Adaptive Momentum Sampler](https://arxiv.org/abs/2308.11941) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:MXK_kJrjxJIC'></span></strong>, Xiyu Wang, Anh-Dung Dinh, **Daochang Liu**, Chang Xu. *International Joint Conference on Artificial Intelligence (IJCAI), 2024*

<!-- - [Contrastive Sampling Chains in Diffusion Models](https://neurips.cc/virtual/2023/poster/71042) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:YOwf2qJgpHMC'></span></strong>, Junyu Zhang, **Daochang Liu**, Shichao Zhang, Chang Xu. *Conference on Neural Information Processing Systems (NeurIPS), 2023*, [[Code]](https://github.com/BestJunYu/Contrastive-Sampling) -->

<!-- - [PixelAsParam: A Gradient View on Diffusion Sampling with Guidance](https://openreview.net/forum?id=2q1Whv1kXL) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:5nxA0vEk-isC'></span></strong>, Anh-Dung Dinh, **Daochang Liu**, Chang Xu. *International Conference on Machine Learning (ICML), 2023*, [[Code]](https://github.com/dungdinhanh/pxpguided-diffusion) -->

- [Personalized Image Generation for Color Vision Deficiency Population](https://openaccess.thecvf.com/content/ICCV2023/html/Jiang_Personalized_Image_Generation_for_Color_Vision_Deficiency_Population_ICCV_2023_paper.html) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:8k81kl-MbHgC'></span></strong>, Shuyi Jiang, **Daochang Liu**, Dingquan Li, Chang Xu. *International Conference on Computer Vision (ICCV), 2023*, [[Code]](https://github.com/Jiangshuyi0V0/CVD-GAN)

- [Private Image Generation with Dual-Purpose Auxiliary Classifier](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_Private_Image_Generation_With_Dual-Purpose_Auxiliary_Classifier_CVPR_2023_paper.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:0EnyYjriUFMC'></span></strong>, Chen Chen, **Daochang Liu**, Siqi Ma, Surya Nepal, Chang Xu. *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023* [[Code]](https://github.com/chenchen-usyd/DP-GAN-DPAC) [[Video]](https://www.youtube.com/watch?v=ZsjYIZ2s0fw)



<br>


# 📝 AI for Healthcare and Surgery

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/CVPR21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Unified Surgical Skill Assessment](https://arxiv.org/abs/2106.01035) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:YsMSGLbcyi4C'></span></strong>

**Daochang Liu**, Qiyue Li, Tingting Jiang, Yizhou Wang, Rulin Miao, Fei Shan, Ziyu Li

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021*

[[Project]](https://finspire13.github.io/CVPR21-Project-Page/) [[Code]](https://github.com/Finspire13/Towards-Unified-Surgical-Skill-Assessment) [[Slides]](http://www.vie.group/media/pdf/CVPR2021_SLIDES.pptx) [[Poster]](http://www.vie.group/media/pdf/CVPR2021_POSTER.pdf) [[Video]](https://www.youtube.com/watch?v=xRh9gE0kyjc)

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2020</div><img src='images/MICCAI20.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unsupervised Surgical Instrument Segmentation via Anchor Generation and Semantic Diffusion](http://www.vie.group/media/pdf/paper204.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:Y0pCki6q_DkC'></span></strong>

**Daochang Liu\***, Yuhui Wei\*, Tingting Jiang, Yizhou Wang, Rulin Miao, Fei Shan, Ziyu Li

*Medical Image Computing and Computer Assisted Intervention (MICCAI), 2020*

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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2019</div><img src='images/MICCAI19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Surgical Skill Assessment on In-Vivo Clinical Data via the Clearness of Operating Field](http://www.vie.group/media/pdf/paper37.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:zYLM7Y9cAGgC'></span></strong>

**Daochang Liu**, Tingting Jiang, Yizhou Wang, Rulin Miao, Fei Shan, Ziyu Li

*Medical Image Computing and Computer Assisted Intervention (MICCAI), 2019*

[[Slides]](http://www.vie.group/media/pdf/7_2_Daochang_2sag3xD.pptx) [[Poster]](http://www.vie.group/media/pdf/MICCAI_2019_Poster_QpBvnvQ.pdf)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2018</div><img src='images/MICCAI18.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Reinforcement Learning for Surgical Gesture Segmentation and Classification](http://www.vie.group/media/pdf/paper.pdf) <strong><span class='show_paper_citations' data='ElujT6oAAAAJ:9yKSN-GCB0IC'></span></strong>

**Daochang Liu**, Tingting Jiang

*Medical Image Computing and Computer Assisted Intervention (MICCAI), 2018*

[[Code]](https://github.com/Finspire13/RL-Surgical-Gesture-Segmentation) [[Poster]](http://www.vie.group/media/pdf/MICCAI_Poster_v7.pdf)

</div>
</div>


- [Comparative Validation of Machine Learning Algorithms for Surgical Workflow and Skill Analysis with the HeiChole Benchmark](https://www.sciencedirect.com/science/article/pii/S1361841523000312)<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:Se3iqnhoufwC'></span></strong>, Martin Wagner, ..., **Daochang Liu**, ..., Sebastian Bodenstedt. *Medical Image Analysis (MedIA), 2023*, [[Dataset]](https://endovissub-workflowandskill.grand-challenge.org/)

- Surgical Skill Assessment Method and Device, Tingting Jiang, Ziyu Li, **Daochang Liu**, Qiyue Li, Yizhou Wang, Rulin Miao, Fei Shan. *China Patent (ZL202110443748.9)*




<!-- 
<span class='anchor' id='teaching'></span>

# 📖 Teaching
- *2023-2024*, Lecturer for OCMP5329 Deep Learning, The University of Sydney
- *2022-2023*, Guest Lecturer for HTIN5005 Applied Healthcare Data Science, The University of Sydney
- *2023*, Guest Lecturer for INFO4990/5993 CS Research Methods, The University of Sydney
- *2023-2024*, Supervisor for COMP5702/5704 IT Research Project, The University of Sydney
- *2023-2024*, Supervisor for COMP5709/5703 IT Capstone Project, The University of Sydney
- *2024*, Co-supervisor for INFO2911 IT Special Project, The University of Sydney
 -->

<!-- <span class='anchor' id='awards'></span>

# 🎖 Awards
- *2022*, ICDM Best Student Paper Award, 1 out of 885
- *2021*, Peking University Tianchuang Scholarship, Top 5% PhDs
- *2020*, Microsoft Research Asia Fellowship Nomination, Top 25 PhDs in Asia-Pacific
- *2019*, Peking University Principle's Scholarship, Top 5% PhDs
- *2019*, Peking University Academic Innovation Award, Top 3% PhDs
- *2017*, Shanghai Outstanding Bachelor Graduate, Top 2% Graduates -->

<!-- <span class='anchor' id='talks'></span>

# 💬 Talks
- *2023*, "Human Action and Skill Understanding in Long Videos", Beihang University
- *2023*, "What Does ChatGPT mean to AI Research", The University of Sydney
- *2023*, "Research in AI", The University of Sydney
- *2022*, "Biomedical Image Analysis", The University of Sydney
- *2021*, "Video-Based Surgical Skill Assessment - Improving Surgical Care by Computer Vision", Baidu Inc.
- *2020*, "Computer-Aided Surgical Skill Assessment", Microsoft Research Asia
- *2019*, "Surgical Skill Assessment on In-Vivo Clinical Data via the Clearness of Operating Field", MICCAI -->

<span class='anchor' id='grants'></span>

# 🌟 Grants

<!-- - *2023 - 2024*, Artificial Intelligence Empowered Surgical Skill Assessment (Lead CI), $7840 USD, Google Cloud Research Credits Award 

- *2024 Q1-Q2*, Large Language Models as Training-Free Multimodal Optimizers (Lead CI), 40000 GPU Hours (40K AUD Equivalent), The National Computational Infrastructure (NCI) AI Flagship Scheme, Australia

- *2024 Q1-Q2*, Automatically Assessing Surgical Skills in Enriched Context (Lead CI), 12000 GPU Hours (12K AUD Equivalent), Sydney Informatics Hub (SIH) HPC Allocation Scheme 2024 Round 1, Australia

- *2023 Q1-Q2*, Image Generation for the Colour Vision Impaired (Lead CI), 10000 GPU Hours (10K AUD Equivalent), The National Computational Infrastructure (NCI) Adapter Scheme, Australia 
 -->

<!-- - *2024 - 2025*, Lead CI, $15000 AUD, Digital Sciences Initiative Ignite Award, USYD

- *2023 - 2024*, Lead CI, $7840 USD, Google Cloud Research Credits Award 

- *2024 Q1-Q2*, Lead CI, 40000 GPU Hours (40K AUD Equivalent), The National Computational Infrastructure (NCI) AI Flagship Scheme

- *2024 Q1-Q2*, Lead CI, 12000 GPU Hours (12K AUD Equivalent), Sydney Informatics Hub (SIH) HPC Allocation Scheme 2024 Round 1

- *2023 Q1-Q2*, Lead CI, 10000 GPU Hours (10K AUD Equivalent), The National Computational Infrastructure (NCI) Adapter Scheme 
 -->

- *2024 - 2025*, Digital Sciences Initiative Ignite Award, USYD

- *2023 - 2024*, Google Cloud Research Credits Award 

- *2024 Q1-Q2*, The National Computational Infrastructure (NCI) AI Flagship Scheme

- *2024 Q1-Q2*, Sydney Informatics Hub (SIH) HPC Allocation Scheme 2024 Round 1

- *2023 Q1-Q2*, The National Computational Infrastructure (NCI) Adapter Scheme 


<span class='anchor' id='services'></span>

# ♥️ Services

- *2024*, Diversity, Equity, and Inclusion (DEI) Committee, 2022-2023, Ju Lab, School of Biomedical Engineering, USYD
- *2022-2023*, Higher Degree Research (HDR) Student Committee, 2022-2023, School of Computer Science, USYD
- Program Committee Member of CVPR, ECCV, ACM MM, ICPR
- Reviewer of IEEE Transactions on Multimedia (TMM), IEEE Signal Processing Letters

# -

**Contact:** h.zhao at sydney.edu.au

**Last Update:** Oct 11, 2024

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=EPHsmQIJLbnhIay_lL2JI0tJ1EPMrLTnAPwg8zuvHkY&cl=ffffff&w=300"></script>
