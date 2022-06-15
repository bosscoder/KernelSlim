# KernelSlim
### What is this?
It's a pre-built kernel with minimal modules loaded.

### Why this?
I had a 64mb KVM server, running the latest Debian 7. Not very secure, so I decided to upgrade to Debian 11 (latest at the time of writing this). System won't boot due to OOM, so I've decided to find ways to build a kernel with just enough modules to run in this VM (SolusVM KVM).

### How to use?
Create a VM with latest Debian 11 (you'll need at least 1GB of RAM to run the installer successfully, or other versions of Debian), complete the installation and enable swap (you'll need swap in most cases, otherwise you won't be needing this). Download the kernel, install it. Edit grub and reboot.
