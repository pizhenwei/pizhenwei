Hi, I’m @pizhenwei

👀 I’m interested in the Linux operating system and lots of software. I've contributed to Linux, util-linux, QEMU, libvirt, libiscsi, spdk,tgt, Redis, bcc, atop.
- I developed [Valkey over RDMA](https://github.com/valkey-io/valkey/blob/unstable/src/rdma.c), and the new feature has been merged into Valkey 8.0. This allows clients to communicate with the Valkey server via RDMA, potentially improving the QPS by approximately 250% and reducing latency by around 50%. I am also working on Valkey/Redis for vLLM Splitwise.
- I developed virtio crypto kernel driver and QEMU backend, this allows guest to offload RSA/ECDSA to host. It's possible to let nginx(with openssl) improve the performance of HTTPS to ~200%. I started to maintain the cryptodev subsystem of QEMU since 2023-03.
- I contributed lots of patches to [atop](https://github.com/atoptool/atop), and recently I'm developing [atophttpd](https://github.com/pizhenwei/atophttpd) which is a web style atop, this allows to access atop without login, it's also possible to get system level/process level status of many servers in batch.
- I wrote `irqtop/lsirq/blkpr` commands(from [util-linux](https://github.com/util-linux/util-linux)), any suggestion/feedback is welcome!
- I wrote `hugetop` command(from [procps](https://gitlab.com/procps-ng/procps)), any suggestion/feedback is welcome!
- I wrote `tcprtt/virtiostat/rdmaucma` commands, improved `runqslower/killsnoop/trace/funccount` commands(from [bcc](https://github.com/iovisor/bcc)), any suggestion/feedback is welcome!
- I'm familiar with iSCSI/iSER/NVMe-OF, contributed patches to libiscsi/spdk/tgt/kernel nvme target, I also developed a user space NVMe-oF initiator [libnvmf](https://github.com/bytedance/libnvmf) which makes QEMU block as faster as ~200K IOPS.
- I have worked on the Virtio Over Fabrics specification, Linux driver demonstration code, and the Virtio-oF target. This work has stalled due to a lack of availability from the Virtio-Spec maintainers.
- 📫 Contact me by pizhenwei@bytedance.com

<!---
pizhenwei/pizhenwei is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
