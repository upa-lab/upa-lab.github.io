---
title: "Multi-threaded scp: Easy and Fast File Transfer over SSH"
image: /assets/images/research-mscp.png
figure_position: top
alt: mscp splits source files into chunks and sends them through multiple SSH connections to sshd and sftp on the destination
links:
  - label: "Multi-threaded scp: Easy and Fast File Transfer over SSH"
    note: 
    url: https://dl.acm.org/doi/10.1145/3569951.3597582
  - label: github.com/upa/mscp
    url: https://github.com/upa/mscp
---

大量のデータをより高速にネットワーク越しに転送することは、コンピュータサイエンスをはじめ様々な分野で不可欠な、基本的な操作です。高速なデータ転送を手軽に実現するツールとして、mscpというツールを開発しています。mscpは複数のSSHコネクションを使って並列にデータを転送することで、通常のscpコマンドと同じ使い勝手で高速なファイル転送を実現します。mscpはオープンソースソフトウェアとして保守されており、LinuxとmacOSで利用できます。

