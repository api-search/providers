---
api_count: 10
apis:
- description: The set of stable userspace-facing interfaces exposed by the Linux kernel, including system calls, ioctls, eBPF, futex2, and the netlink protocol.
  name: Linux Kernel Userspace API
  slug: linux-kernel-userspace-api
- description: Extended Berkeley Packet Filter (eBPF) userspace API for loading and interacting with sandboxed programs running in the kernel.
  name: eBPF Userspace API
  slug: ebpf-userspace-api
- description: Socket-based interface for communication between the kernel and userspace, used widely for networking, routing, and device configuration.
  name: Netlink API
  slug: netlink-api
- description: SECure COMPuting mode with BPF filters, used to restrict which system calls a process can make for sandboxing and hardening.
  name: Seccomp BPF
  slug: seccomp-bpf
- description: Unprivileged access-control framework allowing processes to restrict themselves and their descendants from filesystem and network operations.
  name: Landlock
  slug: landlock
- description: Virtual filesystem mounted at /proc that exposes process and kernel information through a file-based interface.
  name: procfs
  slug: procfs
- description: Virtual filesystem mounted at /sys that exports kernel object and device information to userspace.
  name: sysfs
  slug: sysfs
- description: The system and service manager API exposed by systemd over D-Bus for managing units, services, and the boot process.
  name: systemd D-Bus API
  slug: systemd-dbus
- description: Pluggable Authentication Modules providing flexible, configurable authentication mechanisms for Linux applications.
  name: Linux PAM
  slug: linux-pam
- description: Device manager for the Linux kernel handling device nodes and hotplug events under /dev.
  name: udev
  slug: udev
common:
- title: ''
  type: Website
  url: https://www.kernel.org/
- title: ''
  type: Documentation
  url: https://www.kernel.org/doc/html/latest/
- title: ''
  type: Reference
  url: https://man7.org/linux/man-pages/
- title: ''
  type: Website
  url: https://www.linuxfoundation.org/
created: '2024-01-15'
description: Linux is an open-source Unix-like operating system kernel originally created by Linus Torvalds. This index catalogs the userspace and kernel programming interfaces exposed by Linux, including system calls, eBPF, ioctl, netlink, procfs, sysfs, GPIO, and security interfaces such as Seccomp, Landlock, and Linux Security Modules. It also covers ecosystem APIs for systemd and PAM.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Linux
skills: []
slug: linux
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: linux\nname: Linux\ndescription: >-\n  Linux is an open-source Unix-like operating system kernel originally created\n  by Linus Torvalds. This index catalogs the userspace and kernel programming\n  interfaces exposed by Linux, including system calls, eBPF, ioctl, netlink,\n  procfs, sysfs, GPIO, and security interfaces such as Seccomp, Landlock, and\n  Linux Security Modules. It also covers ecosystem APIs for systemd and PAM.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Kernel\n  - Linux\n  - Open Source\n  - Operating System\n  - Unix\n  - Userspace API\nurl: https://raw.githubusercontent.com/api-evangelist/linux/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: linux:linux-kernel-userspace-api\n    name: Linux Kernel Userspace API\n    description: >-\n      The set of stable userspace-facing interfaces\
  \ exposed by the Linux kernel,\n      including system calls, ioctls, eBPF, futex2, and the netlink protocol.\n    humanURL: https://www.kernel.org/doc/html/latest/userspace-api/index.html\n    tags:\n      - Kernel\n      - Userspace\n      - System Calls\n    properties:\n      - type: Documentation\n        url: https://www.kernel.org/doc/html/latest/userspace-api/index.html\n      - type: Reference\n        url: https://man7.org/linux/man-pages/man2/syscalls.2.html\n  - aid: linux:ebpf-userspace-api\n    name: eBPF Userspace API\n    description: >-\n      Extended Berkeley Packet Filter (eBPF) userspace API for loading and\n      interacting with sandboxed programs running in the kernel.\n    humanURL: https://www.kernel.org/doc/html/latest/userspace-api/ebpf/index.html\n    tags:\n      - eBPF\n      - Kernel\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://www.kernel.org/doc/html/latest/userspace-api/ebpf/index.html\n  - aid: linux:netlink-api\n\
  \    name: Netlink API\n    description: >-\n      Socket-based interface for communication between the kernel and userspace,\n      used widely for networking, routing, and device configuration.\n    humanURL: https://man7.org/linux/man-pages/man7/netlink.7.html\n    tags:\n      - Networking\n      - IPC\n      - Kernel\n    properties:\n      - type: Documentation\n        url: https://www.kernel.org/doc/html/latest/userspace-api/netlink/index.html\n  - aid: linux:seccomp-bpf\n    name: Seccomp BPF\n    description: >-\n      SECure COMPuting mode with BPF filters, used to restrict which system\n      calls a process can make for sandboxing and hardening.\n    humanURL: https://www.kernel.org/doc/html/latest/userspace-api/seccomp_filter.html\n    tags:\n      - Security\n      - Sandboxing\n      - Syscalls\n    properties:\n      - type: Documentation\n        url: https://www.kernel.org/doc/html/latest/userspace-api/seccomp_filter.html\n  - aid: linux:landlock\n    name: Landlock\n\
  \    description: >-\n      Unprivileged access-control framework allowing processes to restrict\n      themselves and their descendants from filesystem and network operations.\n    humanURL: https://www.kernel.org/doc/html/latest/userspace-api/landlock.html\n    tags:\n      - Security\n      - Access Control\n    properties:\n      - type: Documentation\n        url: https://www.kernel.org/doc/html/latest/userspace-api/landlock.html\n  - aid: linux:procfs\n    name: procfs\n    description: >-\n      Virtual filesystem mounted at /proc that exposes process and kernel\n      information through a file-based interface.\n    humanURL: https://man7.org/linux/man-pages/man5/proc.5.html\n    tags:\n      - Filesystem\n      - Process\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://www.kernel.org/doc/html/latest/filesystems/proc.html\n  - aid: linux:sysfs\n    name: sysfs\n    description: >-\n      Virtual filesystem mounted at /sys that exports kernel\
  \ object and device\n      information to userspace.\n    humanURL: https://man7.org/linux/man-pages/man5/sysfs.5.html\n    tags:\n      - Filesystem\n      - Devices\n      - Kernel\n    properties:\n      - type: Documentation\n        url: https://www.kernel.org/doc/html/latest/filesystems/sysfs.html\n  - aid: linux:systemd-dbus\n    name: systemd D-Bus API\n    description: >-\n      The system and service manager API exposed by systemd over D-Bus for\n      managing units, services, and the boot process.\n    humanURL: https://www.freedesktop.org/wiki/Software/systemd/dbus/\n    tags:\n      - systemd\n      - D-Bus\n      - Service Management\n    properties:\n      - type: Documentation\n        url: https://www.freedesktop.org/software/systemd/man/\n      - type: Reference\n        url: https://www.freedesktop.org/wiki/Software/systemd/dbus/\n  - aid: linux:linux-pam\n    name: Linux PAM\n    description: >-\n      Pluggable Authentication Modules providing flexible, configurable\n\
  \      authentication mechanisms for Linux applications.\n    humanURL: http://www.linux-pam.org/\n    tags:\n      - Authentication\n      - Security\n    properties:\n      - type: Documentation\n        url: http://www.linux-pam.org/Linux-PAM-html/\n  - aid: linux:udev\n    name: udev\n    description: >-\n      Device manager for the Linux kernel handling device nodes and hotplug\n      events under /dev.\n    humanURL: https://www.freedesktop.org/software/systemd/man/udev.html\n    tags:\n      - Devices\n      - Hardware\n      - Hotplug\n    properties:\n      - type: Documentation\n        url: https://www.freedesktop.org/software/systemd/man/udev.html\ncommon:\n  - type: Website\n    name: Kernel.org\n    description: Home of the Linux kernel project.\n    url: https://www.kernel.org/\n  - type: Documentation\n    name: Linux Kernel Documentation\n    description: Official kernel documentation tree.\n    url: https://www.kernel.org/doc/html/latest/\n  - type: Reference\n    name:\
  \ Linux man-pages\n    description: The Linux man-pages project.\n    url: https://man7.org/linux/man-pages/\n  - type: Website\n    name: Linux Foundation\n    description: The Linux Foundation hosts the Linux kernel project.\n    url: https://www.linuxfoundation.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/linux/refs/heads/main/apis.yml
tags:
- Kernel
- Linux
- Open Source
- Operating System
- Unix
- Userspace API
url: https://raw.githubusercontent.com/api-evangelist/linux/refs/heads/main/apis.yml
use_cases: []
---
