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

[Yuxiang Cai](https://person.zju.edu.cn/caiyx) is an assistant professor affiliated with School of Software Technology at Zhejiang University. He obtained the PhD degree in computer science and technology from Zhejiang University in 2023, supervised by Prof. [Jianwei Yin](https://mypage.zju.edu.cn/0001038). His research interests lie in ***Crossover Service***, ***Model Transfer***, ***Embodied AI*** and ***VLM***. In particular, he is actively working on intelligent interpretation of multimodal data (video, 2D/3D image, ...), transfer learning (UDA, TTA, ...), AI+X (remote sensing, medicine, ...)，Embodied AI (VLA, Sim-to-Real, Efficiency, ...) and space–air–ground integrated computing.

***For students who are interested in joining our research group (Master/Intern), please contact me via caiyuxiang AT zju.edu.cn.***
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). --> 


# 🔥 News
- *2026.07*: &nbsp;🎉 One paper is accepted by ***ACMMM 2026***
- *2026.06*: &nbsp; I was Invited to serve as a reviewer for ***IJCV***
- *2026.06*: &nbsp; I was Invited to serve as a reviewer for ***TNNLS***
- *2026.06*: &nbsp;🎉 One paper is accepted by ***IJCV*** (IF=10.3) 
- *2026.06*: &nbsp;🎉 Two papers are accepted by ***ECCV 2026*** 
- *2026.06*: &nbsp; I was Invited to serve as a reviewer for ***AAAI 2027***
- *2026.05*: &nbsp; I was Invited to serve as a reviewer for ***CSUR***
- *2026.05*: &nbsp;🎉 One paper is accepted by ***ICML 2026***
- *2026.04*: &nbsp;🎉 One paper is accepted by ***ISPRS*** (IF=12.9) 
- *2026.02*: &nbsp;🎉 Two papers are accepted by ***CVPR 2026*** (one main, one findings)
- *2026.02*: &nbsp; I was Invited to serve as a reviewer for ***ACMMM 2026***
- *2026.02*: &nbsp; I was Invited to serve as a reviewer for ***ICML 2026***
- *2026.01*: &nbsp;🎉 One paper is accepted by ***ICLR 2026***
- *2026.01*: &nbsp;🎉 One paper is accepted by ***ICASSP 2026***
- *2025.12*: &nbsp; I was Invited to serve as a reviewer for ***IJCAI-ECAI 2026***
- *2025.11*: &nbsp; I was Invited to serve as a reviewer for ***CVPR 2026***
- *2025.09*: &nbsp;🎉 One ***United States Patent*** is granted
- *2025.09*: &nbsp;🎉 One Patent is granted by State Intellectual Property Office of China
- *2025.08*: &nbsp; I was Invited to serve as a reviewer for ***AAAI 2026***
- *2025.05*: &nbsp;🎉 One paper is accepted by ***IEEE GRSM*** (IF=16.4)
- *2025.04*: &nbsp;🎉 One Patent is granted by State Intellectual Property Office of China
- *2025.03*: &nbsp;🎉 One paper is accepted by ***ICME 2025***
- *2025.02*: &nbsp; I was Invited to serve as a reviewer for ***ACMMM 2025***
- *2025.01*: &nbsp; I was Invited to serve as a reviewer for ***IJCAI 2025***
- *2024.07*: &nbsp;🎉 One paper is accepted by ***ACMMM 2024***
- *2024.01*: &nbsp; Join the School of Software Technology at Zhejiang University as an Assistant Professor
- *2023.11*: &nbsp;🎉 One Patent is granted by State Intellectual Property Office of China
- *2023.07*: &nbsp;🎉 One paper is accepted by ***ACMMM 2023***
- *2023.05*: &nbsp; I was Invited to serve as a reviewer for ***IEEE TGRS***
- *2023.02*: &nbsp; I was Invited to serve as a reviewer for ***NPL***
- *2022.12*: &nbsp;🎉 One paper is accepted by ***IEEE TGRS***
- *2022.09*: &nbsp; I was Invited to serve as a reviewer for ***TJSC***
- *2022.08*: &nbsp;🎉 One paper is accepted by ***IEEE TGRS***


# 📝 Selective Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2026</div><img src='images/mm26.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Continual Video-MLLM Adaptation over Evolving Domains](https://2026.acmmm.org/)

Rui Cheng, Meixing Shi, **Yuxiang Cai**\*, Jingcai Guo, Jianwei Yin, Zhi Chen\*

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This paper proposes Distribution-Aware Expert Routing (DAER), a parameter-efficient framework for continual Video-MLLM adaptation over evolving domains.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2026</div><img src='images/IJCV 2026.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Federated Learning Meets Test-Time Adaptation: Methods, Challenges, and Future Directions](https://link.springer.com/journal/11263)

Chen Zhang, Ge Su, Huaxiao Zhou, Lu Hao, Fenglin Zhu, Jintai Chen，**Yuxiang Cai**\*, Jianwei Yin, Hongxia Xu\*.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This paper provides a comprehensive survey of Federated Test-Time Adaptation (FedTTA), formalizing its problem setting and establishing a unified taxonomy encompassing three paradigms.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/ECCV2026S.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spectral Evolution-Guided Token Pruning in Large Multimodal Models](https://eccv.ecva.net/Conferences/2026)

Bin Chen, **Yuxiang Cai**\*, Yadan Luo, Yi Zhang, Jianwei Yin, Zhi Chen\*.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This work proposes a training-free token pruning framework based on Cross-Layer Spectral Evolution (CLSE).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/ECCV2026A.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accelerating Multimodal Large Language Models with Prior-Corrected Token Reduction](https://eccv.ecva.net/Conferences/2026)

Zengjie Chen, **Yuxiang Cai**\*, Jingcai Guo, Taotao Cai, Jianwei Yin, Zhi Chen\*.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This work proposes Prior-Corrected Token Reduction (PriorTR), a training-free token reduction method that explicitly separates task-conditioned attention from the model-induced prior.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/CVPR2026.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[IBISAgent: Reinforcing Pixel-Level Visual Reasoning in MLLMs for Universal Biomedical Object Referring and Segmentation](https://cvpr.thecvf.com/Conferences/2026)

Yankai Jiang, Qiaoru Li, Binlu Xu, Haoran Sun, Chao Ding, Junting Dong, **Yuxiang Cai***, Xuhong Zhang, Jianwei Yin.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This work proposes a novel agentic MLLM, named IBISAgent, that reformulates segmentation as a vision-centric, multi-step decision-making process. IBISAgent enables MLLMs to generate interleaved reasoning and text-based click actions, invoke segmentation tools, and produce high-quality masks without architectural modifications.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2024</div><img src='images/MM24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MultiDAN: Unsupervised, Multistage, Multisource and Multitarget Domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://dl.acm.org/doi/abs/10.1145/3664647.3681494)

**Yuxiang Cai**, Yongheng Shang, Jianwei Yin*

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This work proposes a novel multistage, multisource and multitarget unsupervised domain adaptation network called MultiDAN for remotely sensed semantic segmentation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023</div><img src='images/MM23.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring High-Correlation Source Domain Information for Multi-Source Domain Adaptation in Semantic Segmentation](https://dl.acm.org/doi/10.1145/3581783.3613824)

**Yuxiang Cai**, Meng Xi*, Yongheng Shang, Jianwei Yin

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This work proposes a novel multi-source domain adaptation method for semantic segmentation to maximally exploit the high-correlation source domains and source pixels for target domain.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2023</div><img src='images/DASRSNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DASRSNet: Multitask Domain Adaptation for Super-Resolution-Aided Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3232129)

**Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhengwei Shen, Jianwei Yin*

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This work proposes DASRSNet, a novel multitask domain adaptation network for cross-domain semantic segmentation of low-resolution remote sensing images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2022</div><img src='images/IterDANet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[IterDANet: Iterative Intra-domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3203040)

**Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhenqian Chen, Zhengwei Shen, Jianwei Yin*

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- This work proposes IterDANet, an iterative intra-domain adaptation network for semantic segmentation of remote sensing images.
</div>
</div>

- Rui Cheng, Meixing Shi, **Yuxiang Cai**\*, Jingcai Guo, Jianwei Yin, Zhi Chen\*. [Continual Video-MLLM Adaptation over Evolving Domains](https://2026.acmmm.org/). **ACMMM 2026**. \[CCF-A\]
- Chen Zhang, Ge Su, Huaxiao Zhou, Lu Hao, Fenglin Zhu, Jintai Chen，**Yuxiang Cai**\*, Jianwei Yin, Hongxia Xu\*. [Federated Learning Meets Test-Time Adaptation: Methods, Challenges, and Future Directions](https://link.springer.com/journal/11263). **IJCV**. 2026. \[CCF-A\]
- Bin Chen, **Yuxiang Cai**\*, Yadan Luo, Yi Zhang, Jianwei Yin, Zhi Chen\*. [Spectral Evolution-Guided Token Pruning in Large Multimodal Models](https://eccv.ecva.net/Conferences/2026). **ECCV 2026**. \[TH-CPL A\]
- Zengjie Chen, **Yuxiang Cai**\*, Jingcai Guo, Taotao Cai, Jianwei Yin, Zhi Chen\*. [Accelerating Multimodal Large Language Models with Prior-Corrected Token Reduction](https://eccv.ecva.net/Conferences/2026). **ECCV 2026**. \[TH-CPL A\]
- Yankai Jiang, Qiaoru Li, Binlu Xu, Haoran Sun, Chao Ding, Junting Dong, **Yuxiang Cai***, Xuhong Zhang, Jianwei Yin. [IBISAgent: Reinforcing Pixel-Level Visual Reasoning in MLLMs for Universal Biomedical Object Referring and Segmentation](https://cvpr.thecvf.com/Conferences/2026). **CVPR 2026**. \[CCF-A\]
- **Yuxiang Cai**, Yongheng Shang, Jianwei Yin*. [MultiDAN: Unsupervised, Multistage, Multisource and Multitarget Domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://dl.acm.org/doi/abs/10.1145/3664647.3681494). **ACMMM 2024**. \[CCF-A\]
- **Yuxiang Cai**, Meng Xi*, Yongheng Shang, Jianwei Yin. [Exploring High-Correlation Source Domain Information for Multi-Source Domain Adaptation in Semantic Segmentation](https://dl.acm.org/doi/10.1145/3581783.3613824). **ACMMM 2023**. \[CCF-A\]
- **Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhengwei Shen, Jianwei Yin*. [DASRSNet: Multitask Domain Adaptation for Super-Resolution-Aided Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3232129).
**TGRS 2023**. \[ZJUTOP/CCF-B, IF=8.6\]
- **Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhenqian Chen, Zhengwei Shen, Jianwei Yin*. [IterDANet: Iterative Intra-domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3203040). **TGRS 2022**. \[ZJUTOP/CCF-B, IF=8.6\]
- Xu Jia, Bin Chen, Huaxiao Zhou, Xiaochu Chen, Lingxin Yu, Zilun Zhang, **Yuxiang Cai***. [TSAVD-CLIP: One Visual Encoder Learn Both Temporal and Spatial Feat](https://link.springer.com/article/10.1007/s11761-025-00468-5). **SOCA 2025**. \[CCF-C\]
- **Yuxiang Cai**, Yingchun Yang*, Qiyi Zheng, Zhengwei Shen, Yongheng Shang, Jianwei Yin, Zhongtian Shi. [BiFDANet: Unsupervised Bidirectional Domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://www.mdpi.com/2072-4292/14/1/190). **RS 2022**. \[IF=5.0\]
- Yingxuan Zhuang, Miao Pan, Jingxiao Yang, Jintao Chen, Cheng Tan, **Yuxiang Cai**, Siwei Tan, Chen Zhi, Xuhong Zhang, Jianwei Yin. Mitigating Manifold Departure: Uncertainty-aware Subspace Rectification for Trustworthy MLLM Decoding. **ICML 2026**. \[CCF-A\]
- Yuntai Bao, Xuhong Zhang, Jintao Chen, Ge Su, **Yuxiang Cai**, Hao Peng, Sun Bing, Haiqin Weng, Liu Yan, Jianwei Yin. Faithful Bi-Directional Model Steering via Distribution Matching and Distributed Interchange Interventions. **ICLR 2026**. \[CCF-A\]
- Xingyu Wu, Jintao Chen, Xuanye Zheng, Chenkai pan, **Yuxiang Cai**, Sun Bing, Ge Su, Shengye Pang, Xuhong Zhang. Adaptive Distillation for LM-GNN Alignment in Semi-Supervised Text-Attributed Graph Node Classification. **ICASSP 2026**. \[CCF-B\]
- Zilun Zhang, Zian Guan, Tiancheng Zhao, Haozhan Shen, Tianyu Li, **Yuxiang Cai**, Zhonggen Su, Zhaojun Liu, Jianwei Yin, Xiang Li.Geo-R1: Improving Few-Shot Geospatial Referring Expression Understanding with Reinforcement Fine-Tuning. **ISPRS Journal of Photogrammetry and Remote Sensing 2026**. \[IF=12.9\]
- Zilun Zhang, Haozhan Shen, Tiancheng Zhao, Zian Guan, Bin Chen, Yuhao Wang, Xu Jia, **Yuxiang Cai**, Yongheng Shang, Jianwei Yin. Enhancing Ultra High Resolution Remote Sensing Imagery Analysis with ImageRAG. **IEEE GRSM 2025**. \[IF=16.4\]
- Zhiqiang Shen, Qinfeng Li, Xuhong Zhang, **Yuxiang Cai**, Xiaochu Chen, Ping An, Haiqin Weng, Yan Liu. PatchSegDet: Attack-Agnostic Detection of Physical Adversarial Patches in Face Recognition Systems. **ICME 2025**. \[CCF-B\]
- Zhenqian Chen, Yongheng Shang, Andre Python, **Yuxiang Cai**, Jianwei Yin*. DB-BlendMask: Decomposed Attention and Balanced BlendMask for Instance Segmentation of High-Resolution Remote Sensing Images. **TGRS 2022**. \[ZJUTOP/CCF-B, IF=8.6\]

&nbsp;* denotes Corresponding Author


# 👏 Awards
- 2024年度中国商业联合会科技进步奖特等奖
- 2024年示范性软件学院软件技术创新成果
- 2026年示范性软件学院联盟关键软件技术创新成果


# 📓 Selective Patents 
- US, "SEMANTIC SEGMENTATION METHOD FOR CROSS-DOMAIN REMOTE SENSING IMAGES BASED ON ITERATIVE INTRA-DOMAIN ADAPTATION", US 12423825 B2.
- CN, "基于多级领域相关度的多源领域自适应语义分割方法及装置", ZL 2023 1 1119643.3.
- CN, "基于迭代域内适应和自训练的跨域遥感图像语义分割方法", ZL 2022 1 0402338.4.
- CN, "基于双向无监督域适应融合的跨星遥感图像语义分割方法", ZL 2021 1 1017498.9.
- CN, "基于尺寸平衡FCOS的高分辨率遥感场景目标检测方法", ZL 2021 1 1143539.9.


<!--
# 📓 Patents 
- Jianwei Yin, **Yuxiang Cai**, Yingchun Yang, Shuiguang Deng, Ying Li. SEMANTIC SEGMENTATION METHOD FOR CROSS-SATELLITE REMOTE SENSING IMAGES BASED ON UNSUPERVISED BIDIRECTIONAL DOMAIN ADAPTATION AND FUSION. Chinese Invention Patent. **Grant**. (ZL 2021 1 1017498.9)
- Jianwei Yin, **Yuxiang Cai**, Meng Xi, Yongheng Shang. MULTI-SOURCE DOMAIN ADAPTIVE SEMANTIC SEGMENTATION METHOD AND DEVICE BASED ON MULTI-LEVEL DOMAIN CORRELATION. PCT Patent/Chinese Invention Patent. Accept. (PCT-CN2023-123148/CN202311119643.3)
- Jianwei Yin, **Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhenqian Chen, Zhengwei Shen. SEMANTIC SEGMENTATION METHOD FOR CROSS-DOMAIN REMOTE SENSING IMAGES BASED ON ITERATIVE INTRA-DOMAIN ADAPTATION. PCT Patent/Chinese Invention Patent. Accept. (PCTCN2022-090009/CN202210402338.4)
- Jianwei Yin, **Yuxiang Cai**, Yingchun Yang, Shuiguang Deng, Ying Li. SEMANTIC SEGMENTATION METHOD FOR CROSS-SATELLITE REMOTE SENSING IMAGES BASED ON UNSUPERVISED BIDIRECTIONAL DOMAIN ADAPTATION AND FUSION. PCT Patent. Accept. (PCT-CN2021-119171)
-->

# 📚 Professional Activities
- Reviewer for IEEE/CVF Conference on Computer Vision and Pattern Recognition(CVPR), International Conference on Machine Learning(ICML), ACM International Conference on Multimedia(ACMMM), AAAI Conference on Artificial Intelligence(AAAI), International Joint Conference on Artificial Intelligence(IJCAI), ...
- Reviewer for International Journal of Computer Vision (IJCV), ACM Computing Surveys (CSUR), IEEE Transactions on Geoscience and Remote Sensing (TGRS), IEEE Transactions onNeural Networks andLearning Systems  (TNNLS), ...

# 🎓 Education
- 2018.09 - 2023.12, Ph.D., Computer Science and Technology, Zhejiang University, Hangzhou.
- 2014.09 - 2018.06, B.E., Computer Science and Technology, Lanzhou University, Lanzhou.

# 💬 Contact
- caiyuxiang AT zju dot edu dot cn
- Building 3, School of Software Technology, Zhejiang University, Ningbo, China.

