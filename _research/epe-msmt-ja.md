---
title: Measuring the Potential Benefit of Egress Traffic Engineering with Segment Routing
image: /assets/images/epe-msmt.png
alt: Pings sent from our AS out through each eBGP peer to the Internet
links:
  - label: A First Measurement with BGP Egress Peer Engineering
    url: https://link.springer.com/chapter/10.1007/978-3-030-98785-5_9
  - label: Measuring the potential benefit of egress traffic engineering with Segment Routing
    note: (APNIC Blog)
    url: https://blog.apnic.net/2022/03/10/measuring-the-potential-benefit-of-egress-traffic-engineering-with-segment-routing/
---

BGP best paths are not always the lowest in latency, but measuring a non-best path normally means preferring it and shifting all user traffic to that destination. Using Segment Routing based BGP Egress Peer Engineering (RFC 9087), we encapsulated only measurement packets toward a chosen eBGP peer, leaving user traffic untouched. On the ShowNet (AS290) network at Interop Tokyo 2021, 77% of prefixes had a lower-latency alternate path, and about 60% gained up to 10% RTT reduction.
