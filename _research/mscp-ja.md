---
title: "Multi-threaded scp: Easy and Fast File Transfer over SSH"
image: /assets/images/research-mscp.png
figure_position: top
alt: mscp splits source files into chunks and sends them through multiple SSH connections to sshd and sftp on the destination
links:
  - label: "Multi-threaded scp: Easy and Fast File Transfer over SSH"
    note: (PEARC '23)
    url: https://dl.acm.org/doi/10.1145/3569951.3597582
  - label: upa/mscp
    note: (GitHub)
    url: https://github.com/upa/mscp
---

Copying a large dataset over SSH is limited by a single connection: one TCP stream and one thread doing the crypto. mscp splits the transfer across multiple SSH connections and threads, sending chunks of the same file, and multiple files, in parallel. It needs nothing on the remote side beyond a standard sshd with the SFTP subsystem, and it is used like scp. The tool is open source and available for Linux, macOS, and FreeBSD.
