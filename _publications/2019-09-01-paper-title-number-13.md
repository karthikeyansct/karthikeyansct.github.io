---
title: "Low Power TCP for Enhanced Battery Life in Mobile Devices"
collection: publications
permalink: /publication/2019-09-01-paper-title-number-13
excerpt: 'The paper presents Low Power TCP (LPTCP), a client-side solution that proactively closes idle TCP connections to reduce mobile network signaling and power consumption. LPTCP improves battery life by optimizing connection management, achieving significant power gains and reduced signaling overhead in real-world smartphone testing.'
date: 2019-09-01
venue: 'ICC 2019 - IEEE International Conference on Communications (ICC)), Shanghai, China'
paperurl: 'https://ieeexplore.ieee.org/document/8761824'
---

As the daily usage time of smart phone increases, battery life time becomes increasingly important. Recently, a complaint is raised for frequent battery drain in smart phones due to applications running in the background. In most of the mobile applications, after end of the data transfer, longer idle time occurs in a Transmission Control Protocol (TCP) connection for connection closure. Usually such idle TCP connections are terminated by servers based on a static timeout value configured at the server side. This results in frequent transition from idle Radio Frequency (RF) state to active RF state thereby increasing mobile network signalling and device battery power consumption. To address this problem, we propose a novel TCP connection control mechanism in view of power saving, called Low Power TCP (LPTCP). Our solution is lightweight, application agnostic, a client deployed solution. LPTCP identifies inactive TCP connections that cause the delayed server close and pro-actively closes those TCP connections. We evaluated LPTCP with the latest Samsung smart phones such as Galaxy S8 and S9. LPTCP achieved up to 18% of power gain and significantly reduced 24% of mobile network signalling overhead.