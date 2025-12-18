---
layout: page
title: Research
header_image: /assets/images/shownet.jpg
permalink: /research/
---


# Network Architecture and Routing

ネットワークにおいて、パケットを適切な宛先へより効率的に運ぶための仕組みが経路制御(Routing)です。ネットワークのあり方は、インターネット全体から、通信事業者のキャリアネットワーク、大規模なデータセンターネットワーク、5Gなどのモバイルネットワーク、エンタープライズ環境のようなキャンパスネットワークなど多種多様であり、それぞれに異なる技術的な要件と課題があります。そうした様々なネットワークにおける課題や機能の高度化に取り組んでいます。

* データセンターネットワークにおけるロードバランサの研究: [Exploiting SRv6 for Stateless and Per-Connection-Consistent Load Balancing](https://ieeexplore.ieee.org/document/10555263)
* インターネット全体のBGP Pathのレイテンシ計測: [A First Measurement with BGP Egress Peer Engineering](https://link.springer.com/chapter/10.1007/978-3-030-98785-5_9)

<p align="center">
<img src="{{ '/assets/images/research-epe-msmt.png' | relative_url }}" class="responsive-content-img">
</p>
<p align="center">
<a href="https://blog.apnic.net/2022/03/10/measuring-the-potential-benefit-of-egress-traffic-engineering-with-segment-routing/" target="_blank">Measuring the Internet with BGP-EPE over Segment Routing</a>
</p>


# System Software and Network Subsystem

ネットワークごしにパケットを送受信するコンピュータ、より具体的に言えばNetwork Interface CardといったPeripheralデバイスや、Operating Systemによるパケット処理そのもの(Network I/O)も研究対象です。OSのデバイスドライバのレイヤにおける機能追加や、アプリケーション側の工夫のによって使い勝手や性能向上を実現する研究にも取り組んでいます。

* コンテナネットワークスタックの高速化: [Grafting Sockets for Fast Container Networking](https://dl.acm.org/doi/10.1145/3230718.3230723)
* PCIe Transaction Layerをover-IPでSoftwareで実装: [NetTLP: A Development Platform for PCIe devices in Software Interacting with Hardware](https://www.usenix.org/conference/nsdi20/presentation/kuga)
* 複数SSHコネクションを用いる高速ファイル転送ツール: [Multi-threaded scp: Easy and Fast File Transfer over SSH](https://dl.acm.org/doi/10.1145/3569951.3597582)


<p align="center">
<img src="{{ '/assets/images/research-mscp.png' | relative_url }}" class="responsive-content-img">
</p>
<p align="center">
  mscp (<a href="https://github.com/upa/mscp" target="_blank">https://github.com/upa/mscp</a>) copies files over multiple SSH connections.
</p>



# Network Operation

インターネットは世界中のネットワークオペレータの不断の努力によって維持されています。

今日もどこかで誰かが、ネットワークに問題があればその原因を特定して修正し、将来に向けた設計を行い、必要に応じて拡張したりと、日々の運用を行っています。こうしたネットワークの運用を楽にするための研究にも取り組んでいます。とくに近年は生成AIのネットワーク運用への利用について積極的に研究を行っています。

* [LLMでネットワーク構築運用支援実験@Interop Tokyo 2025 ShowNet](https://www.janog.gr.jp/meeting/janog56/shownet/), JANOG56
* [An Experiment of SRv6 Service Chaining at Interop Tokyo 2019 ShowNet](https://datatracker.ietf.org/doc/html/draft-upa-srv6-service-chaining-exp-00), Internet Draft


