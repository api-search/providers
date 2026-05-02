---
api_count: 2
apis:
- description: The LinuxBoot project's build system and tooling for replacing UEFI DXE with a Linux kernel-based boot environment. Includes integrations with coreboot/LinuxBoot and UEFI PEI/LinuxBoot configurations.
  name: LinuxBoot Build System
  slug: linuxboot-build-system
- description: u-root is a Go-based universal root filesystem and ramfs builder used by LinuxBoot to assemble a minimal initramfs containing the userspace tools needed for booting.
  name: u-root
  slug: u-root
common:
- title: ''
  type: Documentation
  url: https://book.linuxboot.org
- title: ''
  type: GitHubOrg
  url: https://github.com/linuxboot
- title: ''
  type: Website
  url: https://www.linuxboot.org/
created: '2026-03-16'
description: LinuxBoot is a Linux Foundation firmware project that uses a Linux kernel and initramfs as a bootloader, replacing specific firmware functionality such as UEFI DXE. It provides faster, more reliable, and more secure boot processes by leveraging the well-tested Linux kernel for hardware initialization. Core components include u-root (the ramfs builder), the LinuxBoot build system, and the NERF (Non-Extensible Reduced Firmware) heritage from Google.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: LinuxBoot
skills: []
slug: linuxboot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: linuxboot\nname: LinuxBoot\ndescription: >-\n  LinuxBoot is a Linux Foundation firmware project that uses a Linux kernel and\n  initramfs as a bootloader, replacing specific firmware functionality such as\n  UEFI DXE. It provides faster, more reliable, and more secure boot processes\n  by leveraging the well-tested Linux kernel for hardware initialization. Core\n  components include u-root (the ramfs builder), the LinuxBoot build system,\n  and the NERF (Non-Extensible Reduced Firmware) heritage from Google.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Boot\n  - Firmware\n  - Hardware\n  - Linux Foundation\n  - u-root\n  - UEFI\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/linuxboot/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: linuxboot:linuxboot-build-system\n    name: LinuxBoot Build\
  \ System\n    description: >-\n      The LinuxBoot project's build system and tooling for replacing UEFI DXE\n      with a Linux kernel-based boot environment. Includes integrations with\n      coreboot/LinuxBoot and UEFI PEI/LinuxBoot configurations.\n    humanURL: https://www.linuxboot.org/\n    tags:\n      - Boot\n      - Firmware\n      - Build\n    properties:\n      - type: Documentation\n        url: https://book.linuxboot.org\n      - type: SourceCode\n        url: https://github.com/linuxboot/linuxboot\n  - aid: linuxboot:u-root\n    name: u-root\n    description: >-\n      u-root is a Go-based universal root filesystem and ramfs builder used by\n      LinuxBoot to assemble a minimal initramfs containing the userspace tools\n      needed for booting.\n    humanURL: https://u-root.org/\n    tags:\n      - Initramfs\n      - Go\n      - Userspace\n    properties:\n      - type: Documentation\n        url: https://u-root.org/\n      - type: SourceCode\n        url: https://github.com/u-root/u-root\n\
  common:\n  - type: Documentation\n    name: LinuxBoot Book\n    description: Official LinuxBoot project documentation and guide.\n    url: https://book.linuxboot.org\n  - type: GitHubOrg\n    name: LinuxBoot GitHub\n    description: Source code and repositories for LinuxBoot.\n    url: https://github.com/linuxboot\n  - type: Website\n    name: LinuxBoot Website\n    description: The main LinuxBoot project website.\n    url: https://www.linuxboot.org/\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/linuxboot/refs/heads/main/apis.yml
tags:
- Boot
- Firmware
- Hardware
- Linux Foundation
- u-root
- UEFI
url: https://raw.githubusercontent.com/api-evangelist/linuxboot/refs/heads/main/apis.yml
use_cases: []
---
