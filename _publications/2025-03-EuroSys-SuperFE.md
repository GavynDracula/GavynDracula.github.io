---
title: "SuperFE: A Scalable and Flexible Feature Extractor for ML-based Traffic Analysis Applications"
collection: publications
permalink: /publications/2025-03-EuroSys-SuperFE
excerpt: 'This paper proposes the next-generation high-speed network featur extractor based on the programmable network.'
date: 2025-03-30
venue: 'European Conference on Computer Systems (EuroSys)'
paperurl: 'https://dl.acm.org/doi/10.1145/3689031.3696081'

citation: '<i>Menghao Zhang*, <b>Guanyu Li*</b>, Cheng Guo, Renyu Yang, Shicheng Wang, Han Bao, Xiao Li, Mingwei Xu, Tianyu Wo, Chunming Hu. &quot;SuperFE: A Scalable and Flexible Feature Extractor for ML-based Traffic Analysis Applications&quot;. In The 20th European Conference on Computer Systems (EuroSys ''25), Rotterdam, Netherlands, March 30-April 3, 2025.</i>'

cnrate: 'EuroSys：CCF-A/TH-CPL-A，系统领域顶级会议'

---
**Abstract:**  
The feature extractor component in today's ML-based traffic analysis applications is becoming a key bottleneck. While mainstream software-based approaches can support flexible feature extraction, they fail to scale to multi-100Gbps network speed easily. Meanwhile, hardware-accelerated solutions can scale to high throughput, but cannot flexibly support generic traffic analysis applications. In this paper, we propose SuperFE, a feature extraction framework that allows users to extract traffic features efficiently and flexibly. SuperFE leverages the capabilities of both new-generation programmable switches and SmartNICs, with three key designs. First, SuperFE presents a user-friendly and extensible interface to support customized feature extraction policies, shielding underlying hardware implementation details and complexities. Second, SuperFE introduces a high-performance multi-granularity key-vector cache system in the programmable switches to batch necessary feature metadata for massive amounts of packets. Third, SuperFE exploits the multi-core parallel and hierarchical memory of SoC-based SmartNICs to achieve efficient feature computation with diverse streaming algorithms. Evaluations using our prototype demonstrate that SuperFE enables various state-of-the-art traffic analysis applications to efficiently extract features from multi-100Gbps raw traffic without compromising detection accuracy, and achieves nearly two orders of magnitude higher throughput than the software-based counterparts.

**Paper URL:**  
[Read or download the complete paper here](https://dl.acm.org/doi/10.1145/3689031.3696081){:target="\_blank"}
