---
title: Host-Driven Flowlet Balancing with Segment Routing over IPv6
image: /assets/images/srflb.png
image_class: height-16em
alt: Host S steers packets of a flow onto Spine 1 or Spine 2 by encapsulating them to SID 1 or SID 2 with SRv6
links:
  - label: Host-Driven Flowlet Balancing with Segment Routing over IPv6
    note: (arXiv)
    url: https://arxiv.org/abs/2606.27697
  - label: Exploiting SRv6 for Stateless and Per-Connection-Consistent Load Balancing
    url: https://ieeexplore.ieee.org/document/10555263
  - label: An Experiment of SRv6 Service Chaining at Interop Tokyo 2019 ShowNet
    note: (Internet Draft)
    url: https://datatracker.ietf.org/doc/html/draft-upa-srv6-service-chaining-exp-00
---

Flowlet balancing splits traffic at a finer granularity than ECMP, but switches must keep per-flow state, which limits deployment. We move the decision to the hosts: each host detects flowlets in its own outgoing traffic and steers them onto specific paths with SRv6, leaving the switches stateless. Paths are chosen from a simple estimate of in-flight bytes on each path. On a testbed with an SRv6-capable router, this cut tail latency by 15% over random flowlet balancing and by 33% over ECMP.

We are also applying SRv6 to other problems: a load balancer for data centers that is stateless yet per-connection-consistent, and service chaining deployed on the ShowNet at Interop Tokyo.
