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

  - label: SR-MPLS Egress Peer Engineeringを使って測るインターネットレイテンシー
    note: (JANOG48)
    url: https://www.janog.gr.jp/meeting/janog48/epe/
---

インターネットは複数の独立したネットワーク(Autonomous System、AS)の集合体です。AS同士はBorder Gateway Protocol (BGP)を使ってお互いの経路(ASパス)を交換し、各ASは宛先ネットワークごとに、そのネットワークへ到達するASパスを選択します。

あるASからあるASへのパスが複数あるとき、BGPが選択するパスが常に性能上、例えば遅延や帯域の観点からベストであるとは限りません。2021年にInterop Tokyo ShowNet (AS290)で実施した実験では、77%の宛先ネットワークについて、BGPベストパスよりも遅延が短いASパスがあることを示しました。


