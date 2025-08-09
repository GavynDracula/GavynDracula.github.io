---
title: "Paraleon: Automatic and Adaptive Tuning for DCQCN Parameters in RDMA Networks"
collection: publications
permalink: /publications/2024-10-ICNP-Paraleon
excerpt: 'This paper is about automatic and adaptive RDMA congestion control parameters setting.'
date: 2024-10-28
venue: 'IEEE International Conference on Network Protocols (ICNP)'
paperurl: 'https://ieeexplore.ieee.org/document/10858517'

citation: '<i>Ziteng Chen, Menghao Zhang, <b>Guanyu Li</b>, Jiahao Cao, Yang Jing, Mingwei Xu, Renjie Xie, He Liu, Fangzheng Jiao, Xiaohe Hu. &quot;Paraleon: Automatic and Adaptive Tuning for DCQCN Parameters in RDMA Networks&quot;. In The 32nd IEEE International Conference on Network Protocols  (ICNP ''24), Charleroi, Belgium, October 28-31, 2024.</i>'

cnrate: 'ICNP：CCF-B/TH-CPL-A，网络领域重要会议'

---
**Abstract:**  
RDMA is a kernel-bypass and transport-offload technology that provides high throughput and low delay for datacenter networks, and DCQCN is the default and most widely used congestion control algorithm in large-scale RDMA networks. DCQCN involves over 10 parameters at RNICs and switches, and their settings significantly affect network performance, currently relying heavily on exhaustive manual tuning. Although some automatic methods are proposed to tune a subset of DCQCN parameters, none of them comprehensively address all parameters at both RNICs and switches, resulting in compromised network performance. In this paper, we propose Paraleon, an automatic and adaptive system to tune DCQCN parameters comprehensively. We design a millisecond-level sketch-based monitoring mechanism for accurate network-wide measurement, which collects runtime metrics as feedback to guide the tuning process. We also analyze the complicated parameter impacts on network performance, and leverage an improved heuristic searching algorithm for timely performance optimization with better efficiency and convergence. We implement Paraleon and conduct extensive experiments in both NS3 simulations and a real-world testbed. The results show that Paraleon achieves 3.8%∼61.4% higher performance than existing tuning schemes.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/document/10858517){:target="\_blank"}
