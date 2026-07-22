<div align="center">

# OnePlus 📦 KOWX712 📦 SUSFS

### Wild Fork

</div>

This repository provides GitHub Actions workflows to automatically build flashable AnyKernel3 ZIPs for multiple OnePlus devices with integrated **KOWX712** and **SUSFS** support.

## 🌟 Features

- **KOWX712** - Kernel-level root solution
- **SUSFS** - Super User File System support
- **Baseband Guard LSM** - Optional extra security layer
- **WireGuard** - Modern VPN support built into the kernel
- **Magic Mount** - Advanced mounting support
- **TMPFS_XATTR / Mountify** - Extended attribute support for tmpfs
- **BBR & ECN** - TCP/network optimizations
- **sched_ext** - Extensible scheduler framework for supported kernels
- **AnyKernel3 ZIPs** - Flashable kernel packages

## 📱 Supported Devices

OnePlus devices supported by the available configs.

Check:

```text
configs/
```

## 🚀 Installation

1. Download the latest kernel ZIP for your device from **Releases**.
2. Flash the AnyKernel3 ZIP with **Kernel Flasher** or another compatible kernel flashing app.
3. Reboot.
4. Open **KOWX712 Manager** and verify root.

## 🔧 Build Artifacts

Each build can produce:

- Flashable **AnyKernel3 ZIP**
- Build metadata
- Release notes
- Logs and summaries

## 🛠️ Building

Use GitHub Actions:

```text
Actions → Build and Release OnePlus Kernels → Run workflow
```

Use KOWX712 option:

```json
[{"type":"KSU","hash":"main"}]
```

## 📋 Requirements

- Unlocked bootloader
- Compatible OnePlus device
- Matching OS/kernel version
- Basic knowledge of flashing custom kernels

## 🔗 Links

- [KOWX712](https://github.com/KOWX712/KernelSU)
- [SUSFS](https://gitlab.com/simonpunk/susfs4ksu)
- [Kernel Flasher](https://github.com/fatalcoder524/KernelFlasher)
- [Releases](https://github.com/Bouteillepleine/Kowx712_Oneplus-/releases)

## 💝 Donations

Any and all donations are appreciated!

- PayPal: [paypal.me/fatalcoder524](https://paypal.me/fatalcoder524)
- DM on Telegram for UPI donations!

## 🤝 Acknowledgments

Thanks to:

- KOWX712
- susfs4ksu by simonpunk
- AnyKernel3 by osm0sis and contributors
- WildKernels
- OnePlusOSS
- Community testers and contributors
