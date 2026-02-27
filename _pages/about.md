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

[Yuxiang Cai](https://person.zju.edu.cn/caiyx) is an assistant professor affiliated with School of Software Technology at Zhejiang University. He obtained the PhD degree in computer science and technology from Zhejiang University in 2023, supervised by Prof. [Jianwei Yin](https://mypage.zju.edu.cn/0001038). His research interests lie in ***Crossover Service***, ***Model Transfer*** and ***VLM***. In particular, he is actively working on intelligent interpretation of multimodal data(video, 2D/3D image, ...), transfer learning(UDA, TTA, ...), AI+X(remote sensing, medicine, ...) and space–air–ground integrated computing.

***For students who are interested in joining our research group (Master/Intern), please contact me via caiyuxiang AT zju.edu.cn.***
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). --> 


# 🔥 News
- *2026.02*: &nbsp;🎉 One paper is accepted by ***CVPR 2026***
- *2026.02*: &nbsp; I was Invited to serve as a reviewer for ***ACMMM 2026***
- *2026.02*: &nbsp; I was Invited to serve as a reviewer for ***ICML 2026***
- *2026.01*: &nbsp;🎉 One paper is accepted by ***ICLR 2026***
- *2026.01*: &nbsp;🎉 One paper is accepted by ***ICASSP 2026***
- *2025.12*: &nbsp; I was Invited to serve as a reviewer for ***IJCAI-ECAI 2026***
- *2025.11*: &nbsp; I was Invited to serve as a reviewer for ***CVPR 2026***
- *2025.09*: &nbsp;🎉 One ***United States Patent*** is granted
- *2025.09*: &nbsp;🎉 One Patent is granted by State Intellectual Property Office of China
- *2025.08*: &nbsp; I was Invited to serve as a reviewer for ***AAAI 2026***
- *2025.05*: &nbsp;🎉 One paper is accepted by ***IEEE GRSM***(IF=16.4)
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

[MultiDAN: Unsupervised, Multistage, Multisource and Multitarget Domain Adaptation for Semantic Segmentation of Remote Sensing Images]([https://2024.acmmm.org/](https://dl.acm.org/doi/abs/10.1145/3664647.3681494))

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

- **Yuxiang Cai**, Yongheng Shang, Jianwei Yin*. [MultiDAN: Unsupervised, Multistage, Multisource and Multitarget Domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://2024.acmmm.org/). **ACMMM 2024**. \[CCF-A\]
- **Yuxiang Cai**, Meng Xi*, Yongheng Shang, Jianwei Yin. [Exploring High-Correlation Source Domain Information for Multi-Source Domain Adaptation in Semantic Segmentation](https://dl.acm.org/doi/10.1145/3581783.3613824). **ACMMM 2023**. \[CCF-A\]
- **Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhengwei Shen, Jianwei Yin*. [DASRSNet: Multitask Domain Adaptation for Super-Resolution-Aided Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3232129).
**TGRS 2023**. \[CCF-B, IF=8.2\]
- **Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhenqian Chen, Zhengwei Shen, Jianwei Yin*. [IterDANet: Iterative Intra-domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3203040). **TGRS 2022**. \[CCF-B, IF=8.2\]
- **Yuxiang Cai**, Yingchun Yang*, Qiyi Zheng, Zhengwei Shen, Yongheng Shang, Jianwei Yin, Zhongtian Shi. [BiFDANet: Unsupervised Bidirectional Domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://www.mdpi.com/2072-4292/14/1/190). **RS 2022**. \[IF=5.0\]
- Zhenqian Chen, Yongheng Shang, Andre Python, **Yuxiang Cai**, Jianwei Yin*. [DB-BlendMask: Decomposed Attention and Balanced BlendMask for Instance Segmentation of High-Resolution Remote Sensing Images](https://doi.org/10.1109/TGRS.2021.3138913). **TGRS 2022**. \[CCF-B, IF=8.2\]

&nbsp;* denotes Corresponding Author

# 📓 Patents 
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
- Reviewer for IEEE Transactions on Geoscience and Remote Sensing (TGRS), Neural Processing Letters (NPL), The Journal of SuperComputing (TJSC), ...

# 🎓 Education
- 2018.09 - 2023.12, Ph.D., Computer Science and Technology, Zhejiang University, Hangzhou.
- 2014.09 - 2018.06, B.E., Computer Science and Technology, Lanzhou University, Lanzhou.

# 💬 Contact
- caiyuxiang AT zju dot edu dot cn
- E307 Teaching Building, School of Software Technology, Zhejiang University, Ningbo, China.

