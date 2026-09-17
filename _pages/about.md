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

I am currently a second-year Ph.D. student at [Sun Yat-sen University](https://www.sysu.edu.cn/), advised by Prof. [Jian-Fang Hu](https://www.isee-ai.cn/~hujianfang/). Before this, I obtained my M.S. and B.S degrees from [Sun Yat-sen University](https://www.sysu.edu.cn/).

Currently, my research interests lie in Human Motion Prediction and Trajectory Prediction.

# 🔥 News

- *2026.09*: &nbsp;🎉🎉 1 paper is accepted by IJCV 2026.
- *2026.02*: &nbsp;🎉🎉 1 paper is accepted by CVPR 2026.

<details>
  <summary><b>Earlier News</b></summary>
  <ul>
    <li><i>2024.12</i>: 🎉🎉 1 paper is accepted by AAAI 2025.</li>
    <li><i>2024.07</i>: 🎉🎉 1 paper is accepted by TCSVT 2024.</li>
    <li><i>2024.07</i>: 🎉🎉 1 paper is accepted by ECCV 2024.</li>
    <li><i>2023.09</i>: 🎉🎉 1 paper is accepted by NeurIPS 2023.</li>
  </ul>
</details>




# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2026</div><img src='images/PICI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Controllable Human-Object Interaction Synthesis via Progressive and Invertible Condition Injection**

**Xiaotong Lin**, [Tianming Liang](https://tmliang.github.io/), [Heng Li](https://ai-lh.github.io/), [Jiangxin Sun](https://sunjiangxin.github.io/website), [Jianguo Zhang](https://faculty.sustech.edu.cn/?tagid=zhangjg&iscss=1&snapid=1&orderby=date&go=2&lang=en), [Jian-Fang Hu](https://www.isee-ai.cn/~hujianfang/)\*

*International Journal of Computer Vision, 2026.*



</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/MotionHiFlow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MotionHiFlow: Text-to-motion via hierarchical flow matching**

[Heng Li](https://ai-lh.github.io/), **Xiaotong Lin**, [Ling-An Zeng](https://www.lingan.art/), Yulei Kang, Shuai Li, [Jian-Fang Hu](https://www.isee-ai.cn/~hujianfang/)\*

*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2026.*

[**[Paper]**](https://openaccess.thecvf.com/content/CVPR2026/papers/Li_MotionHiFlow_Text-to-Motion_via_Hierarchical_Flow_Matching_CVPR_2026_paper.pdf) / [**[Code]**](https://github.com/ai-lh/MotionHiFlow).

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/SAUGE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SAUGE: Taming SAM for Uncertainty-Aligned Multi-Granularity Edge Detection**

Xing Liufu, [Chaolei Tan](https://chaoleitan.github.io/), **Xiaotong Lin**, Yonggang Qi, Jinxuan Li, [Jian-Fang Hu](https://www.isee-ai.cn/~hujianfang/)\*

*AAAI Conference on Artificial Intelligence, 2025.*

[**[Arxiv]**](https://arxiv.org/abs/2412.12892) / [**[Code]**](https://github.com/Star-xing1/SAUGE)

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/PPT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Progressive Pretext Task Learning for Human Trajectory Prediction**

**Xiaotong Lin**, [Tianming Liang](https://tmliang.github.io/), [Jianhuang Lai](https://scholar.google.com/citations?user=w3GjGqoAAAAJ), [Jian-Fang Hu](https://www.isee-ai.cn/~hujianfang/)\*

*European Conference on Computer Vision, 2024.*

[**[Paper]**](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04345.pdf) / [**[Code]**](https://github.com/iSEE-Laboratory/PPT).

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2024</div><img src='images/KE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Beyond Minimum-of-N: Rethinking the Evaluation and Methods of Pedestrian Trajectory Prediction**

Linhui Li, **Xiaotong Lin**, Yejia Huang, Zizhen Zhang\*, [Jian-Fang Hu](https://www.isee-ai.cn/~hujianfang/)\*

*IEEE Transactions on Circuits and Systems for Video Technology, 2024.*

[**[Paper]**](https://ieeexplore.ieee.org/document/10623470)

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/TCL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Temporal Continual Learning with Prior Compensation for Human Motion Prediction**

Jianwei Tang, [Jiangxin Sun](https://sunjiangxin.github.io/website), **Xiaotong Lin**, Lifang Zhang, [Wei-Shi Zheng](https://isee-ai.cn/~zhwshi/), [Jian-Fang Hu](https://www.isee-ai.cn/~hujianfang/)\*

*Advances in Neural Information Processing Systems, 2023*

[**[Paper]**](https://papers.nips.cc/paper_files/paper/2023/hash/cf7a83a5342befd11d3d65beba1be5b0-Abstract-Conference.html) / [**[Code]**](https://github.com/hyqlat/TCL).

</div>
</div>

<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

