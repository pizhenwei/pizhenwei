Hi, I'm @pizhenwei

I'm interested in the Linux operating system and various software projects. I've contributed to Linux, QEMU, libvirt, libiscsi, SPDK, tgt, Valkey, Redis, BCC, atop, rdma-core, util-linux, and procps-ng.

- I developed [Valkey over RDMA](https://github.com/valkey-io/valkey/blob/unstable/src/rdma.c), a feature merged into Valkey 8.0 that allows clients to communicate with the Valkey server via RDMA, improving QPS by approximately 250% and reducing latency by about 50%. I also developed Valkey over MPTCP, Valkey LTTNG-based tracing events, and more. I'm a top contributor to Redis/Valkey/libvalkey.
- I contributed the virtio crypto kernel driver, the QEMU backend, and the virtio crypto specification for akcipher support, enabling guests to offload RSA/ECDSA operations to the host. This allows nginx (with OpenSSL) to improve HTTPS performance by up to ~200%. I have been maintaining the cryptodev subsystem of QEMU since March 2023.
- I have also contributed patches to the mm, NVMe, InfiniBand, virtio, and pvpanic subsystems of the Linux kernel. In total, I've contributed over 100 patches to Linux and QEMU.
- I contributed multiple patches to [atop](https://github.com/atoptool/atop)​ and developed [atophttpd](https://github.com/pizhenwei/atophttpd), a web‑based version of atop that provides remote access without requiring login. It also supports batch retrieval of system‑level and process‑level status across multiple servers.
- I authored the `irqtop`, `sirq`, and `blkpr` commands and enhanced `lsblk` in [util-linux](https://github.com/util-linux/util-linux). Suggestions and feedback are welcome!
- I wrote the hugetop command in [procps](https://gitlab.com/procps-ng/procps). Suggestions and feedback are welcome!
- I created the `tcprtt`, `virtiosta`t, and `rdmaucma` commands, and improved `runqslower`, `killsnoop`, `trace`, and `funccount` in [BCC](https://github.com/iovisor/bcc). Suggestions and feedback are welcome!
- I'm familiar with iSCSI, iSER, and NVMe‑oF. I contributed about 100 patches to libiscsi, SPDK, tgt and the kernel NVMe‑oF target, and also developed the userspace NVMe‑oF initiator [libnvmf](https://github.com/bytedance/libnvmf), which enables QEMU block performance of up to ~200K IOPS.
- I worked on the Virtio Over Fabrics specification, Linux driver demonstration code, and the Virtio‑oF target, though this project is currently on hold.

📫 Email: zhenwei.pi@linux.dev
