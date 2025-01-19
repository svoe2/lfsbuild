# lfsbuild
Linux from scratch

# Structure

`
├── bin
│   └── busybox
├── boot
│   ├── extlinux
│   │   └── extlinux.conf // Startup configuration
│   └── vmlinuz-6.6.72 // Your linux kernel
├── dev
├── Init // My simple init file
├── proc
├── sbin -> /bin
└── sys

`

# Dependency setup
apt-get install qemu-system-x86 util-linux e2fsprogs extlinux
