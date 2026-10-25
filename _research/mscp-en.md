---
title: "Multi-threaded scp: Easy and Fast File Transfer over SSH"
image: /assets/images/research-mscp.png
figure_position: top
alt: mscp splits source files into chunks and sends them through multiple SSH connections to sshd and sftp on the destination
links:
  - label: "Multi-threaded scp: Easy and Fast File Transfer over SSH"
    note: (ACM PEARC 2023)
    url: https://dl.acm.org/doi/10.1145/3569951.3597582
  - label: github.com/upa/mscp
    url: https://github.com/upa/mscp
---

Transferring a large amount of data over a network, and doing so
faster, is an indispensable operation in computer science and in many
other fields. We develop mscp, a tool that makes fast data transfer
easy. By transferring data in parallel over multiple SSH connections,
mscp achieves high-speed file transfer with the same usability as the
ordinary scp command. mscp is maintained as open source software and
runs on Linux and macOS.
