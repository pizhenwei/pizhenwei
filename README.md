Hi, I’m @pizhenwei

I’m interested in the Linux operating system and lots of software. I've contributed to Linux, util-linux, QEMU, libvirt, libiscsi, spdk, tgt, Valkey, Redis, bcc, atop, rdma-core.
- I developed [Valkey over RDMA](https://github.com/valkey-io/valkey/blob/unstable/src/rdma.c), and the new feature has been merged into Valkey 8.0. This allows clients to communicate with the Valkey server via RDMA, potentially improving the QPS by approximately 250% and reducing latency by around 50%. I also developed Valkey Over MPTCP, Valkey LTTNG based tracing events and so on.
- I developed the virtio crypto kernel driver, the QEMU backend and virtio crypto specification of akcipher support. These developments allow guests to offload RSA/ECDSA to the hosts. It's possible to let nginx (with openssl) improve the performance of HTTPS to ~200%. I have been maintaining the cryptodev subsystem of QEMU since March 2023.
- I contributed lots of patches to [atop](https://github.com/atoptool/atop). I also developed [atophttpd](https://github.com/pizhenwei/atophttpd), which is a web-style atop. This allows users to access atop without logging in. It's also possible to get the system-level/process-level status of many servers in batch.
- I wrote the `irqtop/lsirq/blkpr` commands and improved `lsblk` (from [util-linux](https://github.com/util-linux/util-linux)). Any suggestion/feedback is welcome!
- I wrote the `hugetop` command (from [procps](https://gitlab.com/procps-ng/procps)). Any suggestion/feedback is welcome!
- I wrote the `tcprtt/virtiostat/rdmaucma` commands and improved the `runqslower/killsnoop/trace/funccount` commands (from [bcc](https://github.com/iovisor/bcc)). Any suggestion/feedback is welcome!
- I'm familiar with iSCSI/iSER/NVMe-oF, contributed patches to libiscsi/spdk/tgt/kernel nvme target, and I also developed a user-space NVMe-oF initiator [libnvmf](https://github.com/bytedance/libnvmf) which makes QEMU block as fast as ~200K IOPS.
- I have worked on the Virtio Over Fabrics specification, Linux driver demonstration code, and the Virtio-oF target. This work has stalled.
- 📫 Email: zhenwei.pi@linux.dev
<!---
pizhenwei/pizhenwei is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
