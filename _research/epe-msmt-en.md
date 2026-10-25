---
title: Measuring the Potential Benefit of Egress Traffic Engineering
image: /assets/images/epe-msmt.png
alt: Pings sent from our AS out through each eBGP peer to the Internet
links:
  - label: A First Measurement with BGP Egress Peer Engineering
    note: (PAM 2021)
    url: https://link.springer.com/chapter/10.1007/978-3-030-98785-5_9

  - label: Measuring the potential benefit of egress traffic engineering with Segment Routing
    note: (APNIC Blog)
    url: https://blog.apnic.net/2022/03/10/measuring-the-potential-benefit-of-egress-traffic-engineering-with-segment-routing/
---

The Internet is composed of independent networks called Autonomous
Systems (ASes). ASes exchange their routes (AS paths) with each other
using Border Gateway Protocol (BGP), and each AS selects an AS path
for every destination network.

When there are multiple paths from one AS to another, the path BGP
selects is not always the best in terms of performance, for example
latency or bandwidth. In an experiment conducted on Interop Tokyo
ShowNet (AS290) in 2021, we showed that for 77% of destination
networks have AS paths with lower latency than their BGP best path.
