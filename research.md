---
title: ""
feature_text: ""
feature_image: "https://unsplash.it/1300/400?image=885&gravity=north"
excerpt: ""
aside: true
---
### Research Areas
* Mobile data offloading
* Next-generation Internet
* Adaptive video streaming
* TCP latency measurement and solution 

### Mobile data offloading

![amuse](assets/amuse.png)

* To cope with recent exponential increases in demand for mobile data, wireless Internet service providers (ISPs) are increasingly changing their pricing plans and deploying Wi-Fi hotspots to offload their mobile traffic. However, these ISP-centric approaches for traffic management do not always match the interests of mobile users. Users face a complex, multi-dimensional tradeoff between cost, throughput, and delay in making their offloading decisions: while they may save money and receive a higher throughput by waiting for Wi-Fi access, they may not wait for Wi-Fi if they are sensitive to delay. To navigate this tradeoff, we develop Adaptive bandwidth Management through USer-Empowerment (AMUSE), a functional prototype of a practical, cost-aware Wi-Fi offloading system that takes into account a user's throughput-delay tradeoffs and cellular budget constraint. Based on predicted future usage and Wi-Fi availability, AMUSE decides which applications to offload to what times of the day. Since nearly all traffic flows from mobile devices are TCP flows, we introduce a new receiver-side bandwidth allocation mechanism to practically enforce the assigned rate of each TCP application. Thus, AMUSE users can optimize their bandwidth rates according to their own cost-throughput-delay tradeoff without relying on support from different apps' content servers. Through a measurement study of 20 smartphone users' traffic usage traces, we observe that though users already offload a large amount of some application types, our framework can offload a significant additional portion of users' cellular traffic. We implement AMUSE on Windows 7 tablets and evaluate its effectiveness with 3G and Wi-Fi usage data obtained from a trial with 37 mobile users. Our results show that AMUSE improves user utility; when compared with AMUSE, other offloading algorithms yield 14 and 27 percent lower user utilities for light and heavy users, respectively. Intelligently managing users' competing interests for cost, throughput, and delay can therefore improve their offloading decisions.

### Adaptive video streaming

![flare](assets/flare.png)

* Fog computing is an emerging architecture that aims to run applications on multiple devices that lie on a continuum from cloud servers to personal user smartphones. These architectures allow applications to optimize over the information stored at and functionalities run on each device, based on individual device capabilities. We demonstrate the benefits of this approach for mobile video streaming. Existing HAS (HTTP adaptive streaming) techniques often suffer from problems like unstable video quality and suboptimal resource utilization. We find that a lack of coordination prevents both clientand network-side HAS techniques from solving them. However, our fog approach can exploit existing telecommunication APIs, which expose network capabilities to applications, in order to coordinate between clients and the network. Our coordinated HAS solution, FLARE, optimizes the total utility of all clients in a cell while maintaining stable video quality and supporting user- and device-specific needs. We implement FLARE on a commodity LTE femtocell and use the implementation to conduct the first comparison of HAS players on an LTE femtocell. By conducting extensive experiments using the ns-3 simulator, we also demonstrate that FLARE (i) enhances the average video bitrate, (ii) achieves stable video quality, and (iii) balances the throughput of simultaneous video and data flows, compared to other representative HAS solutions.
