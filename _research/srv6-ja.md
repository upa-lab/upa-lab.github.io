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

多数のサーバ、多数のネットワークスイッチで構成されるデータセンターネッ
トワークでは、負荷をいかに分散するかが重要な課題です。負荷とは、例えば
トラフィックであったり、処理のリクエストであったり、計算処理などです。

Segment Routing over IPv6を応用した負荷分散手法の開発に取り組んできました。
例えばハードウェアルータを使ったステートレスなL4ロードバランサの開発や、
多数のスイッチで構成される複数のパスに、いかに均等にトラフィックを分散するか、といった課題です。
いずれも、パケットの経路を送信側が指定でき、ネットワーク側に状態を持たずに済む、
というSRv6の性質を活かしたアプローチをとっています。
