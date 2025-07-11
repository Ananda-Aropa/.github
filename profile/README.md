# 🌟 Ānanda Āropa: The Foundation of Blissful Android x86 Experiences 🌟

<p align="center">
  <img src="https://img.shields.io/badge/%C4%80nanda%20%C4%80ropa-RootFS-blueviolet?style=for-the-badge&logo=linux&logoColor=white" alt="Ānanda Āropa RootFS">
  <img src="https://img.shields.io/badge/Maintained%20by-BlissLabs-green?style=for-the-badge&logo=github&logoColor=white" alt="Maintained by BlissLabs">
  <img src="https://img.shields.io/badge/Part%20of-Android%20Generic%20Project-informational?style=for-the-badge&logo=android&logoColor=white" alt="Android Generic Project">
</p>

## ✨ Introduction

**Ānanda Āropa** (`/ɑːˈnʌndə/ /ɑː.ɾɐw.pɐ/`), or simply `aaropa`, represents **[BlissLabs][blisslabs]'** cutting-edge endeavor, originally to revolutionize the installer and initial ramdisk (initrd) for **[BlissOS][blissos]**, offering a suite of enhanced features and improvements over the traditional [Android-x86][androidx86] console installer. As a cornerstone of the **[Android Generic Project][android-generic]**, Ānanda Āropa provides a robust, minimal Linux environment designed to be the bedrock for a variety of purposes, from building comprehensive installer images to serving as a versatile testing ground for [Android-x86][androidx86] distributions.

---

## 💻 Compatibility

`aaropa` is designed for broad compatibility, supporting a range of architectures:

* **x86\_64** *(amd64)*
* **x86** *(i386)*
* **ARM64** *(aarch64)* - (GKI-compliant)

---

## 🛠️ The Ānanda Āropa Ecosystem

Beyond this core repository, the `aaropa` project comprises several integral components and repositories, each contributing to a seamless and feature-rich Android-x86 experience:

### Ānanda Āropa RootFS

Main repository, [aaropa_rootfs_base][aaropa_rootfs_base], is dedicated to producing the core `aaropa rootfs` – a pristine, lightweight Linux base image. This rootfs is meticulously crafted to include essential programs directly within its minimal Linux environment, creating a functional and efficient base for various operations:

* **Desktop Environment:**
    * [JWM][jwm] - A lightweight window manager for a responsive desktop experience.
* **File Management:**
    * [PCManFM-Qt][pcmanfm-qt] - A powerful and user-friendly file manager.
* **Terminal Emulator:**
    * [QTerminal][qterm] - A feature-rich terminal application.
* **Disk & Partition Management:**
    * [GParted][gparted] - The renowned graphical partition editor for effortless disk management.
* **Text Editing:**
    * [L3afpad][leafpad] - A simple yet effective text editor.
* **Image Viewing:**
    * [GPicView][gpicview] - A fast and lightweight image viewer.
* **Drive Health Monitoring:**
    * [GSmartControl][gsmartmon] - A graphical user interface for smartmontools, for monitoring hard drive health.
* **Process Monitoring:**
    * [Htop][htop] - An interactive process viewer.

#### Variants

The `aaropa_rootfs` project offers specialized variants tailored for specific use cases:

* **[aaropa_rootfs_installer][aaropa_rootfs_installer]**: Tailored for creating installer images.
* **[aaropa_rootfs_builder][aaropa_rootfs_builder]**: Designed for building and compiling Android-x86 components and softwares of the ecosystem.
* **[aaropa_rootfs_qemu][aaropa_rootfs_qemu]**: Optimized for QEMU-based development and testing environments for the ecosystem and Android-x86 distributions.

### Dependencies & Related Projects

The following repositories are integral to the broader Ānanda Āropa ecosystem and contribute to its comprehensive functionality:

* **[Ānanda Āropa Calamares Installer][calamares]** [![Build Status][calamares-buildstatus]][calamares]
    * Contains essential patches and modules for Calamares, the popular Linux installer framework, compiled into `.deb` packages for robust installation of BlissOS, Bass OS, and Lineage OS TV x86.
* **[GRUB2 Themes][grub2themes]** ![Build Status][grub2themes-buildstatus]
    * Features custom GRUB2 themes, bundled as `.deb` packages, to provide a polished boot experience for BlissOS, Bass OS, and Lineage OS TV x86.
* **[Ānanda Āropa Busybox][busybox]** [![Build Status][busybox-buildstatus]][busybox]
    * Provides a custom BusyBox build, crucial for the initrd environment, also packaged as a `.deb` file.
* **[EFIFS Extra Modules for rEFInd][efifs]** and **[rEFInd Files i386][refind-i386]**
    * Enhances rEFInd boot manager functionality with additional EFI filesystem drivers.
* **[Debian Quick Packager][packager]**
    * Tools to streamline the creation of Debian packages.
* **[Debian Repo Builder][repobuilder]**
    * Scripts to quickly deploy Debian repositories with no-cost.
* **[GRUB Android Prober][grub-android-prober]**
    * A utility for GRUB to effectively detect and integrate Android-x86 installations.
* **[Linux Zenith Kernel][zenith]**
    * The Android Generic Project's Zenith kernel, targeted Debian-based systems.
* **[Android Tools][android-tools]**
    * A collection of essential Android-related utilities.

---

## 🎯 Provides

Ānanda Āropa is the backbone, providing a versatile and robust foundation for:

* **Comprehensive Installer Environments:** Facilitates the seamless installation of:
    * **[BlissOS][blissos]**
    * **[Bass OS][bassos]**
    * **[Lineage OS TV x86][lineageos]**
* **Testing & Development Environments:** Offers a base multipurpose minimal Linux environment ideal for:
    * Testing Android-x86 builds.
    * Developing new features and components for Android-x86.
    * Serving as a general-purpose Linux sandbox.

---

## 📚 Meaning Behind the Name

The name **Ānanda Āropa** beautifully intertwines two Sanskrit words:

* **"Ananda" (आनन्द):** Signifying "bliss" or "happiness."
* **"Aropa" (आरोप):** Meaning "imposing" or "placing upon."

Together, they form a profound phrase: **"blissful installation"** or **"blissful startup,"** perfectly encapsulating the project's goal of delivering a smooth and enjoyable Android-x86 experience.

---
## 🤝 Maintainers & Contributors

### Active Maintainers:

* **Shadichy** ([@shadichy][shadichy]) - Core Developer
* **Huy Minh** ([@hmtheboy154][hmtheboy154]) - Core Developer
* **Jon West** ([@electricjesus][electricjesus])

### Notable Contributors:

* **XelXen** ([@xelxen][xelxen]) - Artworks
* **Xtr126** ([@xtr126][xtr126])
  
## 🙏 Credits

We extend our sincere gratitude to the following projects and communities whose foundational work and invaluable tools have made Ānanda Āropa possible:

* **[Android-x86][androidx86]**: For the original initrd and installer (`newinstaller`) that served as our initial inspiration.
* **[Devuan][devuan]**: A steadfast Debian-based Linux distribution that champions the absence of systemd. `aaropa` is proudly built atop Devuan, ensuring a lean and focused base.
* **The programs listed above**: Without these exceptional open-source tools, the rich functionality of `aaropa` would not be achievable.

[blisslabs]: https://blisslabs.org
[blissos]: https://blissos.org
[bassos]: https://bliss-bass.blisscolabs.dev
[lineageos]: https://github.com/LineageOS-TV-x86
[android-generic]: https://android-generic.github.io
[androidx86]: https://android-x86.org
[devuan]: https://www.devuan.org

[jwm]: https://github.com/joewing/jwm
[pcmanfm-qt]: https://github.com/lxqt/pcmanfm-qt
[qterm]: https://github.com/lxqt/qterminal
[gparted]: https://gparted.org/
[leafpad]: https://github.com/stevenhoneyman/l3afpad
[gpicview]: https://lxde.sourceforge.net/gpicview/
[gsmartmon]: https://gsmartcontrol.shaduri.dev/
[htop]: https://github.com/htop-dev/htop

[aaropa_rootfs_base]: https://github.com/Ananda-Aropa/aaropa_rootfs_base
[aaropa_rootfs_installer]: https://github.com/Ananda-Aropa/aaropa_rootfs_installer
[aaropa_rootfs_builder]: https://github.com/Ananda-Aropa/aaropa_rootfs_builder
[aaropa_rootfs_qemu]: https://github.com/Ananda-Aropa/aaropa_rootfs_qemu

[calamares]: https://github.com/Ananda-Aropa/aaropa_calamares
[calamares-buildstatus]: https://github.com/Ananda-Aropa/aaropa_calamares/actions/workflows/build-devuan-ceres.yml/badge.svg

[grub2themes]: https://github.com/Ananda-Aropa/grub2-themes
[grub2themes-buildstatus]: https://github.com/Ananda-Aropa/grub2-themes/actions/workflows/build-devuan-ceres.yml/badge.svg

[busybox]: https://github.com/Ananda-Aropa/aaropa_busybox
[busybox-buildstatus]: https://github.com/Ananda-Aropa/aaropa_busybox/actions/workflows/build-linux.yml/badge.svg

[efifs]: https://github.com/Ananda-Aropa/efifs-debian
[refind-i386]: https://github.com/Ananda-Aropa/refind-files-i386
[grub-android-prober]: https://github.com/Ananda-Aropa/grub-android-prober
[android-tools]: https://github.com/Ananda-Aropa/android-tools

[zenith]: https://github.com/Ananda-Aropa/linux-zenith

[packager]: https://github.com/Ananda-Aropa/build-deb
[repobuilder]: https://github.com/Ananda-Aropa/build-deb

[shadichy]: https://github.com/shadichy
[hmtheboy154]: https://github.com/hmtheboy154
[electricjesus]: https://github.com/electrikjesus
[xelxen]: https://github.com/xelxen
[xtr126]: https://github.com/xtr126
