---
layout: page
title: Research
header_image: /assets/images/shownet.jpg
permalink: /research/
lang: en
---

# Research

### Network Architecture and Routing

Routing is a key mechanism for efficiently delivering packets to their appropriate destinations in a network. Network architectures vary widely, from the entire Internet to carrier networks of Internet service providers, large-scale data center networks, mobile networks like 5G, and campus networks in enterprise environments. Each type has its unique technical requirements and challenges. We are working on addressing challenges and advancing capabilities across these diverse network environments.

* Research on load balancing in data center networks: [Exploiting SRv6 for Stateless and Per-Connection-Consistent Load Balancing](https://ieeexplore.ieee.org/document/10555263)
* Latency measurement of BGP paths across the Internet: [A First Measurement with BGP Egress Peer Engineering](https://link.springer.com/chapter/10.1007/978-3-030-98785-5_9)

<p align="center">
<img src="{{ '/assets/images/research-epe-msmt.png' | relative_url }}" class="responsive-content-img">
</p>
<p align="center">
<a href="https://blog.apnic.net/2022/03/10/measuring-the-potential-benefit-of-egress-traffic-engineering-with-segment-routing/" target="_blank">Measuring the Internet with BGP-EPE over Segment Routing</a>
</p>


### System Software and Network Subsystem

Computers that send and receive packets over networks, more specifically peripheral devices such as Network Interface Cards and packet processing by the Operating System (Network I/O), are also our research targets. We are working on research that improves usability and performance through functionality additions at both OS and application levels.

* Accelerating container network stack: [Grafting Sockets for Fast Container Networking](https://dl.acm.org/doi/10.1145/3230718.3230723)
* Software implementation of PCIe Transaction Layer over IP: [NetTLP: A Development Platform for PCIe devices in Software Interacting with Hardware](https://www.usenix.org/conference/nsdi20/presentation/kuga)
* High-speed file transfer tool using multiple SSH connections: [Multi-threaded scp: Easy and Fast File Transfer over SSH](https://dl.acm.org/doi/10.1145/3569951.3597582)


<p align="center">
<img src="{{ '/assets/images/research-mscp.png' | relative_url }}" class="responsive-content-img">
</p>
<p align="center">
  mscp (<a href="https://github.com/upa/mscp" target="_blank">https://github.com/upa/mscp</a>) copies files over multiple SSH connections.
</p>



### Network Operation

The Internet is supported by the continuous efforts of network operators around the world.

Every day, somewhere, someone investigates and fixes network troubles, plans for the future, expands as needed, and performs daily operations. We are also working on research to make network operations easier. In recent years, we have particularly focused on leveraging LLMs for network operations.

* [Experiment on LLM-assisted Network Construction and Operation Support at Interop Tokyo 2025 ShowNet](https://www.janog.gr.jp/meeting/janog56/shownet/), Japan Network Operators' Group (JANOG) 56th Meeting
* [Segment Routing Deployments and Demonstrations at Interop Tokyo ShowNet](https://2024.apricot.net/assets/files/APIC378/shownet-apricot-sr_1709207447.pdf), Asia Pacific Regional Internet Conference on Operational Technologies (APRICOT) 2024
* [An Experiment of SRv6 Service Chaining at Interop Tokyo 2019 ShowNet](https://datatracker.ietf.org/doc/html/draft-upa-srv6-service-chaining-exp-00), Internet Draft


