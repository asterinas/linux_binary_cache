# linux_binary_cache

## Overview

This repository contains Linux kernels and modules for benchmarks which need Linux VMs as baselines.

`vmlinuz-5.15.0-105-generic` is a specific version of the Linux kernel designed for Ubuntu 20.04 LTS (Focal Fossa). This kernel version belongs to the 5.15.0-105 series and includes updates for performance, stability, and security enhancements.

[kernel](kernel/) contains additional kernel modules that can be loaded into the Linux kernel. The `virtio_blk.ko` module, for instance, provides support for the VirtIO block driver.
