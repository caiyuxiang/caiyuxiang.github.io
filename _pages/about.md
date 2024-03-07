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

Yuxiang Cai is a Researcher (特聘研究员) affiliated with School of Software Technology at Zhejiang University. He obtained the PhD degree in computer science and technology from Zhejiang University in 2023. His research interests lie in ***Edge Intelligence*** and ***AI for Remote Sensing***. In particular, he is actively working on intelligent interpretation of remote sensing image, transfer learning/unsupervised domain adaptation, distributed edge intelligence and space–air–ground integrated integrated computing.

***For students who are interested in joining our lab (Mater/Intern), please contact me via caiyuxiang AT zju.edu.cn.***
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). --> 


# 🔥 News
- *2023.11*: &nbsp;🎉 One Patent is granted by State Intellectual Property Office of China
- *2023.07*: &nbsp;🎉 One paper is accepted by ***ACMMM 2023***
- *2023.05*: &nbsp;🎉 Invited to serve as a reviewer for ***TGRS***
- *2023.02*: &nbsp;🎉 Invited to serve as a reviewer for ***NPL***
- *2022.12*: &nbsp;🎉 One paper is accepted by ***TGRS 2023***
- *2022.09*: &nbsp;🎉 Invited to serve as a reviewer for ***TJSC***
- *2022.08*: &nbsp;🎉 One paper is accepted by ***TGRS 2022***



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023</div><img src='images/MM23.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring High-Correlation Source Domain Information for Multi-Source Domain Adaptation in Semantic Segmentation](https://dl.acm.org/doi/10.1145/3581783.3613824)

**Yuxiang Cai**, Meng Xi*, Yongheng Shang, Jianwei Yin

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- We reveal a crucial discovery that existing multi-source domain adaptation (MSDA) methods neglect the significance of both domain-level source-target correlation (DSC) and pixel-level source-target correlation (PSC). Hence we propose a novel MSDA method for semantic segmentation to maximally exploit the high-correlation source domains and source pixels for target domain.
- We propose a novel correlation measurement mechanism to quantitatively estimate domain-level and pixel-level sourcetarget correlations for MSDA problems. On the basis of DSC and PSC, reweighted source segmentation loss and attentive prototype alignment loss are proposed to align target domain with its similar source domains as well as degrading the negative effects of disturbed source pixels.
- We propose a novel high-correlation source domain pixel cross-domain mixing strategy (HSCM) to construct highcorrelation source-target mixed images, so as to degrade the negative effects of disturbed source pixels and enhance the feature learning of target domain.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2023</div><img src='images/DASRSNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DASRSNet: Multitask Domain Adaptation for Super-Resolution-Aided Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3232129)

**Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhengwei Shen and Jianwei Yin*

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- We propose a novel multitask UDA network called DASRSNet for cross-domain SS (SS) of LR remotely sensed images. Our DASRSNet includes three modules, with DASS branch to perform SS and UDA in the output level, DASR branch to conduct SR and UDA in the image space, and FA module to boost the correlation between DASS and DASR branches. To the best of our knowledge, DASRSNet is the first work on multitask DASR-aided SS of LR remote sensing images.
- We propose to integrate SR into the popular UDA method, which enables the existing UDA model to better segment LR target remote sensing images and small objects. Extensive experimental results validate the effectiveness and robustness of this SR-aided architecture.
- We propose a novel FA loss for the SR-aided SS tasks of cross-domain remotely sensed images. The proposed FA loss is designed to strengthen the affinity of SS features and SR features on both source and target domains.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2022</div><img src='images/IterDANet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[IterDANet: Iterative Intra-domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://doi.org/10.1109/TGRS.2022.3203040)

**Yuxiang Cai**, Yingchun Yang, Yongheng Shang, Zhenqian Chen, Zhengwei Shen and Jianwei Yin*

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> --> 
- We propose a novel IterDANet for cross-domain semantic segmentation of remote sensing images. IterDANet clusters the diverse target domain into multiple subdomains on the basis of InterDA and ER and iteratively reduces the intra-domain gap in remote sensing images. For all we know, IterDANet is the first study on unsupervised iterative IntraDA for remotely sensed semantic segmentation.
- We propose a new GSS, which is a practical assessment approach, to reduce the impact of the instability issue of the GAN-based I2I translation and enhance the performance of InterDA, which is the basis of IntraDA. The proposed GSS can assess all intermediate image generators during the training phase and select a well-trained generator for I2I-based InterDA.
- We propose a new PLGS to further improve the performance of IntraDA module and SSL methods. The proposed PLGS takes advantages of the combination of softmax probability and entropy as the confidence assessment and removes both high-entropy and low-confident predictions to produce more accurate pseudolabels.
</div>
</div>

- **Yuxiang Cai**, Yingchun Yang*, Qiyi Zheng, Zhengwei Shen, Yongheng Shang, Jianwei Yin, Zhongtian Shi. [BiFDANet: Unsupervised Bidirectional Domain Adaptation for Semantic Segmentation of Remote Sensing Images](https://www.mdpi.com/2072-4292/14/1/190). **RS 2022**
- Zhenqian Chen, Yongheng Shang, Andre Python, **Yuxiang Cai**, Jianwei Yin*. [DB-BlendMask: Decomposed Attention and Balanced BlendMask for Instance Segmentation of High-Resolution Remote Sensing Images](https://doi.org/10.1109/TGRS.2021.3138913). **TGRS 2022**

*Corresponding Author

# 📝 Patents 
- Jianwei Yin, **Yuxiang Cai**, Yingchun Yang, Shuiguang Deng, Ying Li. SEMANTIC SEGMENTATION METHOD FOR CROSS-SATELLITE REMOTE SENSING IMAGES BASED ON UNSUPERVISED BIDIRECTIONAL DOMAIN ADAPTATION AND FUSION. Chinese invention patent. **Grant**.

# 📚 Professional Activities
- Reviewer for IEEE Transactions on Geoscience and Remote Sensing (TGRS).
- Reviewer for Neural Processing Letters (NPL)、The Journal of SuperComputing (TJSC).

# 💬 Contact
- caiyuxiang AT zju dot edu dot cn
- E307 Teaching Building, School of Software Technology, Zhejiang University, Ningbo, China.

<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
--> 
