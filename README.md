# QEMU-NVMe-OC12

This is a copy of QEMU-NVMe from https://github.com/OpenChannelSSD/qemu-nvme/commits/ocssd12 with some error fix.

## Usage example

```
./configure --python=/usr/bin/python2 --enable-kvm --target-list=x86_64-softmmu --enable-linux-aio --prefix=/home/hustsss/qhw/qemu-nvme
make
```

The binary will be in `x86_64-softmmu/qemu-system-x86_64`.
