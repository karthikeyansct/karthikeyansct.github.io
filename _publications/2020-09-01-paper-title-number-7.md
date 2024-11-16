---
title: "Path Aware Transport Layer Solution for Mobile Networks"
collection: publications
permalink: /publication/2020-09-01-paper-title-number-7
excerpt: 'This paper introduces Path Aware Transport (PAT), a client-side solution designed to enhance network reliability by dynamically adapting to path quality variations in 5G environments. PAT enables seamless TCP connection migration across multiple interfaces, improving content download and page loading times, as validated through simulations and real-world implementation.'
date: 2020-09-01
venue: 'Journal, IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/document/9205264'
---

The revolutionary Fifth Generation (5G) network technology has already been deployed in many countries to provide end-to-end quality-of-service for a wide variety of services, applications, and users with extremely diverse requirements. To accomplish the same, 5G architecture has enabled Multi-Connectivity (MC) in mobile devices, which aggregates various radio resources and enables simultaneous connectivity. Moreover, the current mobile devices are equipped with multiple network interfaces (Wi-Fi/Cellular) as well as dual-stack networks (IPv4/IPv6) support. But, their performance degrades significantly due to variation in network path quality. The current design of the Internet protocol suite has not adapted well to utilize these multiple interfaces for providing better network reliability. Hence, we propose a client only software solution called Path Aware Transport (PAT), which explores communication paths between client and server and adapts to the dynamics of the network to migrate from one Transmission Control Protocol (TCP) connection to another without hampering the user experience. PAT is prototyped and evaluated in 5G using the ns3 simulator. Moreover, it is implemented in the Samsung flagship mobile device with Android Pie. PAT significantly improves the content downloading time up to 20% and the page loading time up to 29% consistently.
