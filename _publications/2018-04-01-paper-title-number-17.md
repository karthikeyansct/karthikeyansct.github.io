---
title: "Layer 4 Optimizer (L4O) for Enhancing Battery Life in Smart Devices"
collection: publications
permalink: /publication/2018-04-01-paper-title-number-17
excerpt: This paper explores how TCP connection flow impacts battery usage in smartphones, especially focusing on TCP delayed closures and prolonged zero window probes. It proposes a solution that reduces unnecessary signaling overhead and radio ON time, resulting in a consistent 10 to 20% reduction in power usage, irrespective of network and traffic conditions.'
date: 2018-04-01
venue: 'IEEE International Conference on Communications (ICC), Kansas City, MO, USA'
paperurl: 'https://ieeexplore.ieee.org/document/8422420'
---

Applications (Apps) in Smart devices make our life connected to Internet all the time. But, the battery capacity is a major setback for Internet connected Smart phones. We know that TCP is the backbone protocol for these Internet data transmissions. In this paper, we studied the impacts of TCP connection flow on Smart phone battery. We have conducted extensive experiments and collected data from various operator networks in different countries. We observe that TCP delayed closures at the client and prolonged TCP zero Window probes (ZWP) from the server lead to increased signaling overhead and radio ON time. These phenomenon cause unwanted battery drain at the smart phones. To address these problems, we propose a solution that prevents unnecessary packet communication due to TCP delayed closures and ZWPs. Our solution has been evaluated for Android devices such as Samsung Galaxy S7 and S8 variants and Tizen device such as Samsung Z3. We have found that, our solution consistently achieves 10 to 20% of power usage reduction irrespective of varying network and traffic conditions.