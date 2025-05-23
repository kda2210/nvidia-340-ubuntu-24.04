✅ NVIDIA 340.108 Legacy Driver — Ubuntu 24.04 + Linux 6.11

Fully working DKMS-based legacy driver for old NVIDIA GPUs — now on Ubuntu 24.04 (Noble) with kernel 6.11

📦 What it includes:

✅ Kernel 6.11 compatibility via patched DKMS module

✅ Brightness control restored via GRUB patcher

✅ Full packaging: nvidia-support, nvidia-installer-cleanup

✅ nvidia-settings UI app

✅ Meta-package (nvidia340) for one-command install

🧪 Tested on:

Ubuntu 24.04 LTS

Kubuntu 24.04

Linux Mint 22.1

Linux kernel: 6.8 ✅ & 6.11 ✅

> ⚠️ **NVIDIA driver 340.108 does not support Wayland!**

🔗 PPA

Add my PPA with:

sudo add-apt-repository ppa:kda2210/nvidia340

sudo apt-get update

sudo apt-get install nvidia340

More info here: [Launchpad PPA](https://launchpad.net/~kda2210/+archive/ubuntu/nvidia340)

🙏 A note from the author

I’m a Linux user from Russia, living modestly — but I was determined not to give up on my old GPU.

This was my first real experience in maintaining and publishing a complete PPA, with DKMS, postinst scripts, and meta-packages.

💡 Without Andreas Beckmann’s prior packaging work, this would’ve never happened.

Huge thanks to him for continuing Debian support even in 2025.

P.S. This was my first full-fledged PPA.

P.P.S. And damn, I’m proud of it.

📸 Screenshots
![Screenshot_20250517_225624](https://github.com/user-attachments/assets/7e52c997-5a2c-4a79-bc61-0cc8ed119a38)

---

## ⚖️ License and Legal Notice

This repository contains NO proprietary NVIDIA driver binaries or reverse-engineered code.

All driver components are retrieved through Debian's `non-free` section and are subject to the NVIDIA Software License Agreement:  
🔗 https://www.nvidia.com/content/DriverDownload-March2009/licence.php?lang=us

Included here:

- Debian packaging metadata and build structure (free software)
- Helper scripts and DKMS patches for Linux 6.8–6.11
- A meta-package for simple installation via Launchpad PPA

This project is intended to assist with integration and usability only.
