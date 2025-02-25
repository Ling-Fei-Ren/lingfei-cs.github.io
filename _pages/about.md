---
permalink: /
title: "" 
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

**Yuan Sun (孙元)** is a Ph.D. candidate at the College of Computer Science, Sichuan University, advised by Prof. [Dezhong Peng](https://cs.scu.edu.cn/info/1182/7307.htm) and Prof. [Peng Hu](https://penghu-cs.github.io/). My research interests mainly focus on  [Hashing Learning](https://github.com/caoyuan57/Hashing) and [Noisy Correspondence](https://github.com/QinYang79/Awesome-Noisy-Correspondence). Recently, I’ve been conducting research related to Multi-modal Learning and [AI for PDEs](https://github.com/WillDreamer/Awesome-AI4CFD).
- **Image Set Classification**: it constructs an image set consisting of multiple images, and then measures the distance between two sets.
- **Cross-modal Retrieval**: it uses the information of one modal to retrieve the relevant content of another modal (such as text, image, audio, video, etc.).
- **Multi-modal Learning**: it integrates the supplementary and consistent information of multiple modalities for clustering or classification tasks.
- **AI for PDEs**: it utilizes Physics-Informed Neural Networks (PINNs) for solving forward and inverse PDE problems as well as their applications (such as nuclear reactor thermal hydraulics).
  
If you are interested in collaborating with me or want to have a chat, always feel free to contact me through <font color="red"> e-mail (sunyuan_work@163.com)</font> 


# 🔥 News
- \[**Services**\]: Feb. 5, 2025, I have been invited to be an Area Chair（AC) for the ACL 2025. 🎉
- \[**Publications**\]: Jan. 3, 2025, one paper was accepted by IEEE Transactions on Image Processing (TIP)! Congrats to Honglin (Master)! 🎉
- \[**Publications**\]: Dec. 10, 2024, four papers were accepted by AAAI 2025! Congrats to Ruitao (Master), Shilin (Master), and coauthors! 🎉
- \[**Services**\]: Nov. 29, 2024, I have been invited to be a Senior Program Committee（SPC) for the IJCAI 2025. 🎉
- \[**Publications**\]: Jul. 16, 2024, three papers were accepted by ACM Multimedia (ACM MM 2024)! Congrats to Honglin (Master), Longan (Undergrad), and coauthors! 🎉
- \[**Publications**\]: Jun. 23, 2024, one paper was accepted by IEEE Transactions on Knowledge and Data Engineering (TKDE)! 🎉
- \[**Publications**\]: Apr. 20, 2024, one paper was accepted by IEEE Transactions on Multimedia (TMM)! 🎉
- \[**Publications**\]: Apr. 17, 2024, one paper was accepted by IJCAI 2024. Congrats to Kaiming (Master) and coauthors! 🎉
- \[**Publications**\]: Jan. 3, 2024, one paper was accepted by IEEE Transactions on Intelligent Transportation Systems (TITS). 🎉
- \[**Publications**\]: Sep. 22, 2023, one paper was accepted by AAAI 2024. 🎉
- \[**Publications**\]: Sep. 12, 2023, one paper was accepted by Expert Systems With Applications (ESWA)! 🎉
- \[**Publications**\]: Jul. 26, 2023, one paper was accepted by ACM Multimedia (ACM MM 2023)! 🎉
- \[**Services**\]: Jul. 28, 2023, I have been invited to be a PC member for AAAI 2024. 🎉
- \[**Publications**\]: Apr. 26, 2023, one paper was accepted by IEEE Transactions on Multimedia (TMM)! 🎉
- \[**Publications**\]: Feb. 14, 2023, one paper was accepted by IEEE Transactions on Image Processing (TIP)! 🎉
- \[**Publications**\]: Dec. 24, 2022, two papers were accepted by ACM Multimedia (ACM MM 2022)!  🎉


# 📝 Publications 
(# denotes the corresponding author)
# 2025
- [30] Dongliang Wang, Chuang Huang, Hao Pan, **Yuan Sun**, Jian Dai, Yanan Li, Zhenwen Ren, AMLCA: Additive Multi-layer Convolution-guided Cross-attention Network for Visible and Infrared Image Fusion, **Pattern Recognition (PR) (中科院一区)**. [Code](https://github.com/Wangdl2000/AMLCA-code)
- [29] Yongxiang Li, **Yuan Sun**, Yang Qin, Dezhong Peng, Xi Peng, Peng Hu, Robust Duality Learning for Unsupervised Visible-Infrared Person Re-Identification, **IEEE Transactions on Information Forensics and Security (TIFS) (CCF-A类)**.
- [28] Honglin Yuan, **Yuan Sun#**, Fei Zhou, Jing Wen, Shihua Yuan, Xiaojian You, Zhenwen Ren#, Prototype Matching Learning for Incomplete Multi-view Clustering, **IEEE Transactions on Image Processing (TIP) (CCF-A类)**. [Code](https://github.com/hl-yuan/PMIMC)
- [27] Yuan Li, Liangli Zhen, **Yuan Sun**, Dezhong Peng, Xi Peng, Peng Hu, Deep Evidential Hashing for Trustworthy Cross-Modal Retrieval, **AAAI 2025 (CCF-A类)**. [Code](https://github.com/blackant-dev/DECH)
- [26] Ruitao Pu, **Yuan Sun#**, Yang Qin, Zhenwen Ren, Xiaomin Song, Huiming Zheng, Dezhong Peng, Robust Self-paced Hashing for Cross-Modal Retrieval with Noisy Labels, **AAAI 2025 (CCF-A类)**. [Code](https://github.com/perquisite/RSHNL)
- [25] Shilin Xu, **Yuan Sun#**, Xingfeng Li, Siyuan Duan, Zhenwen Ren, Zheng Liu, Dezhong Peng#, Noisy Label Calibration for Multi-view Classification, **AAAI 2025 (CCF-A类)**. [Code](https://github.com/sstaree/NLC)
- [24] Zhongwen Wang, Xingfeng Li, Yinghui Sun, Quansen Sun, **Yuan Sun**, Han Ling, Jian Dai, Zhenwen Ren, TPCH: Tensor-interacted Projection and Cooperative Hashing for Multi-view Clustering], **AAAI 2025 (CCF-A类)**. [Code](https://github.com/jankin-wang/TPCH)
# 2024
- [23] Xingfeng Li, Yuangang Pan, **Yuan Sun**, Yinghui Sun, Quansen Sun, Zhenwen Ren, Ivor W. Tsang, [Scalable Unpaired Multi-view Clustering with Bipartite Graph Matching](https://www.sciencedirect.com/science/article/pii/S1566253524005645?dgcid=coauthor), **Information Fusion (中科院一区)**.
- [22] Wenyuan Wu, Siyuan Duan, **Yuan Sun**, Yang Yu, Dong Liu, Dezhong Peng, [Deep Fuzzy Physics-Informed Neural Networks for Forward and Inverse PDE Problems](https://www.sciencedirect.com/science/article/pii/S0893608024006749), **Neural Networks (中科院一区)**. [Code](https://github.com/siyuancncd/FPINNs)
- [21] Xingfeng Li, Yuangang Pan, **Yuan Sun**, Quansen Sun, Yinghui Sun, Ivor W. Tsang, Zhenwen Ren, [Incomplete Multi-view Clustering with Paired and Balanced Dynamic Anchor Learning](https://ieeexplore.ieee.org/document/10812848), **IEEE Transactions on Multimedia (中科院一区)**. [Code](https://github.com/lee-xingfeng/PBDAL)
- [20] Longan Wang, Yang Qin, **Yuan Sun**, Dezhong Peng, Xi Peng, Peng Hu, [Robust Contrastive Cross-modal Hashing with Noisy Labels](https://dl.acm.org/doi/abs/10.1145/3664647.3680564), **ACM MM 2024 (CCF-A类)**. [Code](https://github.com/LonganWANG-cs/NRCH)
- [19] Honglin Yuan, Shiyun Lai, Xingfeng Li, Jian Dai, **Yuan Sun#**, Zhenwen Ren#, [Robust Prototype Completion for Incomplete Multi-view Clustering](https://dl.acm.org/doi/abs/10.1145/3664647.3681397), **ACM MM 2024 (CCF-A类)**. [Code](https://github.com/hl-yuan/RPCIC)
- [18] **Yuan Sun**, Kaiming Liu, Yongxiang Li, Zhenwen Ren, Jian Dai, Dezhong Peng, [Distribution Consistency Guided Hashing for Cross-Modal Retrieval](https://dl.acm.org/doi/abs/10.1145/3664647.3680633), **ACM MM 2024 (CCF-A类)**. [Code](https://github.com/sunyuan-cs/2024-MM-DCGH)
- [17] Yongxiang Li, Yang Qin, **Yuan Sun**, Dezhong Peng, Xi Peng, Peng Hu, [RoMo: Robust Unsupervised Multimodal Learning with Noisy Pseudo Labels](https://ieeexplore.ieee.org/abstract/document/10653726), **IEEE Transactions on Image Processing (TIP) (CCF-A类)**. [Code](https://github.com/LYXRhythm/RoMo)
- [16] **Yuan Sun**, Yang Qin, Yongxiang Li, Dezhong Peng, Xi Peng, Peng Hu, [Robust Multi-View Clustering with Noisy Correspondence](https://ieeexplore.ieee.org/document/10595464), **IEEE Transactions on Knowledge and Data Engineering (TKDE) (CCF-A类)**. [Code](https://github.com/sunyuan-cs/2024-TKDE-RMCNC)
- [15] **Yuan Sun**, Yang Qin, Dezhong Peng, Zhenwen Ren, Chao Yang, Peng Hu, [Dual Self-Paced Hashing for Image Retrieval](https://ieeexplore.ieee.org/abstract/document/10517459), **IEEE Transactions on Multimedia (TMM) (中科院一区)**. [Code](https://github.com/sunyuan-cs/DSPH)
- [14] Kaiming Liu, Yunhong Gong, Yu Cao, Zhenwen Ren, Dezhong Peng, **Yuan Sun#**, [Dual Semantic Fusion Hashing for Multi-Label Cross-Modal Retrieval](https://www.ijcai.org/proceedings/2024/505), **IJCAI 2024 (CCF-A类)**. [Code](https://github.com/sunyuan-cs/24-IJCAI-DSFH)
- [13] **Yuan Sun**, Jian Dai, Zhenwen Ren, Qilin Li, Dezhong Peng, [Relaxed Energy Preserving Hashing for Image Retrieval](https://ieeexplore.ieee.org/abstract/document/10414409), **IEEE Transactions on Intelligent Transportation Systems (TITS) (中科院一区)**. [Code](https://github.com/sunyuan-cs/REPH_main)
- [12] **Yuan Sun**, Jian Dai, Zhenwen Ren, Yingke Chen, Dezhong Peng, Peng Hu, [Dual Self-Paced Cross-Modal Hashing](https://ojs.aaai.org/index.php/AAAI/article/view/29441), **AAAI 2024 (CCF-A类)**.
  
# 2023
- [11] Yang Qin, **Yuan Sun**, Dezhong Peng, Joey Tianyi Zhou, Xi Peng, Peng Hu, [Cross-modal Active Complementary Learning with Self-refining Correspondence](https://proceedings.neurips.cc/paper_files/paper/2023/file/4e580cdd54fe38ca9a5b8ea6fe99bb44-Paper-Conference.pdf), **NeurIPS 2023 (CCF-A类)**. [Code](https://github.com/QinYang79/CRCL)
- [10] **Yuan Sun**, Dezhong Peng, Zhenwen Ren, [Discrete Aggregation Hashing for Image Set Classification](https://www.sciencedirect.com/science/article/pii/S0957417423021176), **Expert Systems With Applications (中科院一区)**.
- [9] **Yuan Sun**, Dezhong Peng, Jian Dai, Zhenwen Ren, [Stepwise Refinement Short Hashing for Image Retrieval](https://openreview.net/pdf?id=9ol1HoBfir), **ACM MM 2023 (CCF-A类)**.
- [8] Xingfeng Li, Yinghui Sun, Quansen Sun, Zhenwen Ren, **Yuan Sun**, [Cross-view Graph Matching Guided Anchor Alignment for Incomplete Multi-view Clustering](https://www.sciencedirect.com/science/article/pii/S1566253523002579), **Information Fusion (中科院一区)**.
- [7] **Yuan Sun**, Zhenwen Ren, Peng Hu, Dezhong Peng, Xu Wang, [Hierarchical Consensus Hashing for Cross-Modal Retrieval](https://ieeexplore.ieee.org/document/10119165), **IEEE Transactions on Multimedia (TMM) (中科院一区)**. **(ESI Highly Cited Paper)**. [Code](https://github.com/sunyuan-cs/HCCH)  
- [6] **Yuan Sun**, Xu Wang, Dezhong Peng, Zhenwen Ren, Xiaobo Shen, [Hierarchical Hashing Learning for Image Set Classification](https://ieeexplore.ieee.org/document/10061433), **IEEE Transactions on Image Processing (TIP) (CCF-A类)**.

# 2022
- [5] **Yuan Sun**, Dezhong, Haixiao Huang, Zhenwen Ren, [Feature and Semantic Views Consensus Hashing for Image Set Classification](https://dl.acm.org/doi/abs/10.1145/3503161.3547876), **ACM MM 2022 (CCF-A类)**.
- [4] Jiali You, Zhenwen Ren, Quansen Sun, **Yuan Sun**, Xingfeng Li, [Approximate Shifted Laplacian Reconstruction for Multiple Kernel Clustering](https://github.com/sunyuan-cs/sunyuan-cs.github.io/blob/main/docs/4.pdf), **ACM MM 2022 (CCF-A类)**.

# Before 2021
- [3] **Yuan Sun**, Zhenwen Ren, Chao Yang, Quansen Sun, Liwan Chen, Yanglong Ou, [Face Image Set Classification with Self-weighted Latent Sparse Discriminative Learning](https://link.springer.com/article/10.1007/s00521-020-05479-1), **Neural Computing and Applications (中科院二区)**.
- [2] Chao Yang, Zhenwen Ren, Quansen Sun, Mingna Wu, Maowei Yin, **Yuan Sun**, [Joint Correntropy Metric Weighting and Block Diagonal Rgularizer for Robust Multiple Kernel Subspace Clustering](https://www.sciencedirect.com/science/article/pii/S0020025519304803), **Information Sciences (中科院一区)**.
- [1] **Yuan Sun**, Zhenwen Ren, Chao Yang, Haoyun Lei, [Latent Sparse Discriminative Learning for Face Image Set Classification](https://link.springer.com/chapter/10.1007/978-981-15-7670-6_13), **International Conference on Neural Computing for Advanced Applications (EI)**.

# 🎖 Honors and Awards
- 四川大学“十佳学术之星”，2024.12.
- 国家奖学金，2024.11.
- 四川大学优秀研究生，2024.10.
- 四川省计算机学会年度优秀学生论文，2024.01.
- 中国自动化学会科技进步奖二等奖，2023.11.
- 国家奖学金，2023.09.
- 四川大学优秀研究生，2023.09.
- 博士一等学业奖学金，2023.09-2025.06.
- 博士创新奖学金，2023.03.
- 校级优秀硕士毕业论文，2021.06.
- NCAA 2020最佳论文提名奖.
- 成都市技术能手（成都市人力资源与保障局颁发），2018.12.
- 互联网+、挑战杯等20余项国家级、省级竞赛获奖.

# 🙋 Services 
- Conferences:
  - AC/SPC:
    - ACL 2025, IJCAI 2025.
  - Reviewer: 
    - ICML 2025, AAAI 2025, ICLR 2025, AISTATS 2025, ICASSP 2025, IJCNN 2025, KDD 2025, NeurIPS 2025.
    - ICML 2024, NeurIPS 2024, CVPR 2024, ECCV 2024, AAAI 2024, IJCAI 2024, ACM MM 2024, PRCV 2024, EMNLP 2024.
    - ACM MM 2023, PRCV 2023.
  - Associate Editor:
    - ICARM 2024
  - Workshop Chair:
    - CVDL 2024.

- Journals:
    - IEEE Transactions on Image Processing.
    - IEEE Transactions on Knowledge and Data Engineering.
    - IEEE Transactions on Neural Networks and Learning Systems.
    - IEEE Transactions on Circuits and Systems for Video Technology.
    - IEEE Transactions on Big Data.
    - IEEE Transactions on Computational Social Systems.
    - ACM Transactions on Multimedia Computing, Communications and Applications.
    - ACM Transactions on Information Systems.
    - IEEE Signal Processing Letters.
    - Neural Networks.
    - Information Fusion.
    - Expert Systems With Applications.
    - Neurocomputing.
    - Neural Computing and Applications.
    - CAAI Transactions on Intelligence Technology.
    - Data Science and Management.
    - The Visual Computer.


