---
title: "Multa: Enabling Cost-efficient Multi-task Network Traffic Analysis"
collection: publications
permalink: /publications/2023-12-GLOBECOM-MulTA
excerpt: 'This paper designs cost-efficient traffic analysis system with multi-task learning'
date: 2023-12-04
venue: 'IEEE Global Communications Conference (GLOBECOM)'
paperurl: 'https://ieeexplore.ieee.org/document/10437133'

citation: '<i>Cheng Guo, Menghao Zhang, <b>Guanyu Li</b>, Mingwei Xu. &quot;MulTA: Enabling Cost-efficient Multi-task Network Traffic Analysis&quot;. In 2023 IEEE Global Communications Conference (GLOBECOM ''23), Kuala Lumpur, Malaysia, December 4-8, 2023.</i>'

cnrate: 'GLOBECOM：CCF-C/TH-CPL-B，网络领域学术会议'

---
**Abstract:**  
Machine learning based network traffic analysis has been widely used to combat malicious behaviors in various network scenarios. However, most of the applications are specialized for a single task and cannot cover a wide spectrum of security threats. Building a machine learning pipeline from scratch for each traffic analysis task is painstaking and time-consuming. And it is not practical to deploy several traffic analysis tasks together due to the high runtime overhead. In this paper, we propose Multa to enhance the deployability of traffic analysis applications. Multa is a framework that leverages Multi-Task Learning (MTL) - an emerging paradigm in machine learning - to enable the efficient parallel deployment of multiple traffic analysis tasks. Specifically, we devise a sequence-based traffic feature representation that is informative and general enough to serve a diverse range of tasks. Then we use the LSTM-based Multi-gate Mixture-of-Experts (LMMoE) model to learn task characteristics and propose a size tuning algorithm to optimize its performance. Considering different data curating methods, we also present two different training paradigms to construct Multa. Our experiments show that Multa can reduce the space occupancy of the model by up to 50% and accelerate the inference process by more than 100% in multi-task scenarios, which indicates better deployability in real-world networks.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/document/10437133){:target="\_blank"}
