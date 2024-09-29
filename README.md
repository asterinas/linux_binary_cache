# linux_binary_cache

## Overview

This repository contains Linux kernels and modules for benchmarks which need Linux VMs as baselines.

`vmlinuz-5.15.0-105-generic` is a specific version of the Linux kernel designed for Ubuntu 20.04 LTS (Focal Fossa). This kernel version belongs to the 5.15.0-105 series and includes updates for performance, stability, and security enhancements.

`vmlinuz-6.11-98f7e32-x86_64-defconfig` is a x86-64 Linux kernel with the default config built from unmodified Linux kernel tree commit `98f7e32` in Sept. 29 2024.

[kernel](kernel/) contains additional kernel modules that can be loaded into the Linux kernel. The `virtio_blk.ko` module, for instance, provides support for the VirtIO block driver.
