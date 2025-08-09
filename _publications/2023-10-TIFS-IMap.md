---
title: "IMap: Toward a Fast, Scalable and Reconfigurable In-Network Scanner With Programmable Switches"
collection: publications
permalink: /publications/2023-10-TIFS-IMap
excerpt: 'This paper proposes the next-generation high-speed network scanner based on the programmable switch.'
date: 2023-10-25
venue: 'IEEE Transactions on Information Forensics and Security (TIFS)'
paperurl: 'https://ieeexplore.ieee.org/document/10295533'

citation: '<i>Menghao Zhang, <b>Guanyu Li</b>, Cheng Guo, Han Bao, Mingwe Xu, Hongxin Hu, Fenghua Li. &quot;IMap: Toward a Fast, Scalable and Reconfigurable In-Network Scanner With Programmable Switches&quot;. In IEEE Transactions on Information Forensics and Security (TIFS), 2023.</i>'

cnrate: 'TIFS：CCF-A/TH-CPL-A，安全领域顶级期刊'

---
**Abstract:**  
Network scanning has been a standard measurement technique to understand a network’s security situations, e.g., revealing security vulnerabilities, monitoring service deployments. However, probing a large-scale scanning space with existing network scanners is both difficult and slow, since they are all implemented on commodity servers and deployed at the network edge. To address this, we introduce IMap, a fast, scalable and reconfigurable in-network scanner based on programmable switches. In designing IMap, we overcome key restrictions posed by computation models and memory resources of programmable switches, and devise numerous techniques and optimizations, including an address-random and rate-adaptive probe packet generation mechanism, and a correct and efficient response packet processing scheme, to turn a switch into a practical runtime-reconfigurable high-speed network scanner. We implement an open-source prototype of IMap, and evaluate it with extensive testbed experiments and real-world deployments in our campus network. Evaluation results show that even with one switch port enabled, IMap can survey all ports of our campus network (i.e., a total of up to 25 billion scanning space) in 8 minutes. This demonstrates a nearly 4 times faster scanning speed and 1.5 times higher scanning accuracy than the state of the art, which shows that IMap has great potentials to be the next-generation terabit network scanner with all switch ports enabled. Besides, our experiments also show that IMap supports the reconfiguration of scanning tasks at runtime, without incurring switch downtime. Leveraging IMap, we also discover several potential security threats in our campus network, and report them to our network administrators responsibly.

**Paper URL:**  
[Read or download the complete paper here](https://ieeexplore.ieee.org/document/10295533){:target="\_blank"}
