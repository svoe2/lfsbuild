# lfsbuild
Linux from scratch

# Structure

`
├── bin<br>
│   └── busybox<br>
├── boot<br>
│   ├── extlinux<br>
│   │   └── extlinux.conf // Startup configuration<br>
│   └── vmlinuz-6.6.72 // Your linux kernel<br>
├── dev<br>
├── Init // My simple init file<br>
├── proc<br>
├── sbin -> /bin<br>
└── sys<br>

`

# Dependency setup
apt-get install qemu-system-x86 util-linux e2fsprogs extlinux
