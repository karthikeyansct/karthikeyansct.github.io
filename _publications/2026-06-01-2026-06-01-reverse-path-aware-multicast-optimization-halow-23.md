---
title: "Reverse-Path-Aware Multicast Optimization in BATMAN-adv for HaLow Mesh Networks"
collection: publications
permalink: /publication/2026-06-01-reverse-path-aware-multicast-optimization-halow-23
excerpt: 'Designed a scalable multicast forwarding enhancement for BATMAN-adv mesh networks that leverages reverse-path routing awareness to reduce broadcast overhead by up to 90% while preserving reliable multicast delivery in low-bandwidth IEEE 802.11ah environments.'
date: 2026-06-01
venue: 'WCNC 2026 - IEEE Wireless Communications and Networking Conference (WCNC), Kuala Lumpur, Malaysia'
paperurl: 'https://ieeexplore.ieee.org/document/11555529'
doi: '10.1109/WCNC65185.2026.11555529'
---

Multicast forwarding in wireless mesh networks is often bandwidth-inefficient and unreliable over low-rate links such as IEEE 802.11ah (HaLow). BATMAN-adv, a Layer-2 Mesh Routing Protocol, handles multicast by either flooding packets or converting them into multiple unicasts. While effective in high-rate networks, these approaches create severe redundancy and congestion in constrained environments. We propose a reverse-path-aware multicast optimization for BATMAN-adv that transmits multicast packets as broadcasts and selectively rebroadcasts them only when a node lies on the reverse routing path. This design leverages BATMAN-adv's Originator Message (OGM) based routing state for forwarding decisions without adding control overhead. Testbed experiments over HaLow network show up to 90% reduction in broadcast overhead in dense topologies while maintaining high delivery ratios. To enhance performance under loss-prone links, we also include an optional lightweight redundancy mechanism that duplicates multicast packets at the source, improving reliability for real-time traffic without retransmissions or protocol modifications.

## Links

- IEEE Xplore: [https://ieeexplore.ieee.org/document/11555529](https://ieeexplore.ieee.org/document/11555529)
