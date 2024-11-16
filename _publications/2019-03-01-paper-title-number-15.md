---
title: "TCP Closure Optimization for Enhanced Battery Life in Smart Devices"
collection: publications
permalink: /publication/2019-03-01-paper-title-number-15
excerpt: 'The paper addresses the issue of battery drain in smartphones caused by background traffic and TCP delayed closures. It proposes an energy-efficient, client-side solution to control unwanted TCP retransmissions, resulting in a 10-20% reduction in power usage across various devices and network conditions.'
date: 2019-03-01
venue: 'Journal, IEEE Transactions on Mobile Computing'
paperurl: 'https://ieeexplore.ieee.org/document/8370648'
---

Applications (Apps) in Smart devices make our life connected to Internet all the time. Many of the Apps like Google Apps, Facebook, and Twitter generate periodic background traffic. Due to this background traffic, battery continuously drains in Smart Phones. In this paper, we identify root causes for the background traffic and evaluate Apps' behavior with respect to impacts of TCP connection flow on Smart phone battery. We have conducted extensive experiments and collected data from various operator networks in different countries. We observe that TCP delayed closures not only extend radio wake up time but also lead to prolonged retransmissions. These prolonged retransmissions lead to severe battery drain problem. We propose a solution for such TCP closures at the client side with the objective of controlling unwanted TCP retransmissions. Our proposed solution is energy efficient, light weight, application agnostic, and a client only solution which makes deployment easier. Our solution has been evaluated for Android devices such as Samsung Galaxy S6, S7 variants, J7, and the Tizen device such as Samsung Z3. We have found that our solution consistently achieves 10 to 20 percent of power usage reduction irrespective of varying network and traffic conditions. We provide detailed experimental results considering various corner cases and also present the implementation architecture of our proposed solution.