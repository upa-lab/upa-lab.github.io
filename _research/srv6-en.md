---
title: Data Center Load Balancing with Segment Routing over IPv6
image: /assets/images/srflb.png
image_class: height-16em
alt: Host S steers packets of a flow onto Spine 1 or Spine 2 by encapsulating them to SID 1 or SID 2 with SRv6
links:
  - label: Host-Driven Flowlet Balancing with Segment Routing over IPv6
    note: (IEEE HPSR 2026)
    url: https://arxiv.org/abs/2606.27697

  - label: Exploiting SRv6 for Stateless and Per-Connection-Consistent Load Balancing
    url: https://ieeexplore.ieee.org/document/10555263
---

In a data center network built from a large number of servers and
network switches, how to distribute load is an important issue. The
load here can be traffic, requests to be processed, or computation.

We have developed load balancing methods that apply Segment Routing
over IPv6. Examples are a stateless L4 load balancer built with
hardware routers, and how to spread traffic as evenly as possible over
the multiple paths that a large number of switches provide. Both take
the same approach: exploiting the property of SRv6 that the sender can
specify the path a packet takes, so that the network side does not
have to keep state.
