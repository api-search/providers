---
api_count: 10
apis:
- description: Low-level interface between user-space applications and the Linux kernel providing access to process management, file I/O, memory, networking, signals, and IPC primitives.
  name: System Calls API
  slug: system-calls-api
- description: Portable Operating System Interface standards for Unix-like systems, defining a consistent application programming interface across platforms.
  name: POSIX API
  slug: posix-api
- description: Inter-process communication and remote procedure call mechanism widely used on Linux desktop and system services.
  name: D-Bus API
  slug: dbus-api
- description: Socket-based interface for communication between the kernel and user space, particularly for networking and device subsystems.
  name: Netlink API
  slug: netlink-api
- description: Virtual filesystem providing process and system information through a hierarchical file-based interface.
  name: procfs API
  slug: procfs-api
- description: Virtual filesystem for kernel objects and device information presented under /sys.
  name: sysfs API
  slug: sysfs-api
- description: Linux kernel subsystem for monitoring filesystem events such as file creation, deletion, and modification.
  name: inotify API
  slug: inotify-api
- description: I/O event notification facility for scalable monitoring of large numbers of file descriptors.
  name: epoll API
  slug: epoll-api
- description: Device manager for the Linux kernel handling device nodes and hotplug events in /dev.
  name: udev API
  slug: udev-api
- description: System and service manager exposing a D-Bus interface for managing services, sockets, devices, mounts, and timers.
  name: systemd API
  slug: systemd-api
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
created: '2024-01-15'
description: A topic catalog of system-level APIs and interfaces available across Linux/Unix-like operating systems. Includes kernel system calls, POSIX standards, inter-process communication mechanisms (D-Bus, Netlink), virtual filesystems (procfs, sysfs), event-notification facilities (epoll, inotify), device management (udev, systemd), and userspace security interfaces.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Linux/Unix System
skills: []
slug: linuxunix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: linuxunix\nname: Linux/Unix System\ndescription: >-\n  A topic catalog of system-level APIs and interfaces available across\n  Linux/Unix-like operating systems. Includes kernel system calls, POSIX\n  standards, inter-process communication mechanisms (D-Bus, Netlink), virtual\n  filesystems (procfs, sysfs), event-notification facilities (epoll, inotify),\n  device management (udev, systemd), and userspace security interfaces.\ntype: Topic\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Kernel\n  - Linux\n  - Operating System\n  - System\n  - Unix\n  - POSIX\nurl: https://raw.githubusercontent.com/api-evangelist/linuxunix/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: linuxunix:system-calls-api\n    name: System Calls API\n    description: >-\n      Low-level interface between user-space applications and the Linux\
  \ kernel\n      providing access to process management, file I/O, memory, networking,\n      signals, and IPC primitives.\n    humanURL: https://man7.org/linux/man-pages/man2/syscalls.2.html\n    tags:\n      - Kernel\n      - Low-Level\n      - Syscalls\n    properties:\n      - type: Documentation\n        url: https://man7.org/linux/man-pages/dir_section_2.html\n      - type: Reference\n        url: https://www.kernel.org/doc/html/latest/userspace-api/index.html\n  - aid: linuxunix:posix-api\n    name: POSIX API\n    description: >-\n      Portable Operating System Interface standards for Unix-like systems,\n      defining a consistent application programming interface across platforms.\n    humanURL: https://pubs.opengroup.org/onlinepubs/9699919799/\n    tags:\n      - POSIX\n      - Standards\n      - Portability\n    properties:\n      - type: Documentation\n        url: https://pubs.opengroup.org/onlinepubs/9699919799/\n      - type: Specification\n        url: https://standards.ieee.org/ieee/1003.1/7101/\n\
  \  - aid: linuxunix:dbus-api\n    name: D-Bus API\n    description: >-\n      Inter-process communication and remote procedure call mechanism widely\n      used on Linux desktop and system services.\n    humanURL: https://www.freedesktop.org/wiki/Software/dbus/\n    tags:\n      - IPC\n      - Messaging\n      - Desktop\n    properties:\n      - type: Documentation\n        url: https://dbus.freedesktop.org/doc/dbus-specification.html\n      - type: SourceCode\n        url: https://gitlab.freedesktop.org/dbus/dbus\n  - aid: linuxunix:netlink-api\n    name: Netlink API\n    description: >-\n      Socket-based interface for communication between the kernel and user\n      space, particularly for networking and device subsystems.\n    humanURL: https://man7.org/linux/man-pages/man7/netlink.7.html\n    tags:\n      - Networking\n      - Kernel\n      - Sockets\n    properties:\n      - type: Documentation\n        url: https://man7.org/linux/man-pages/man7/netlink.7.html\n      - type: Reference\n\
  \        url: https://www.kernel.org/doc/html/latest/userspace-api/netlink/intro.html\n  - aid: linuxunix:procfs-api\n    name: procfs API\n    description: >-\n      Virtual filesystem providing process and system information through a\n      hierarchical file-based interface.\n    humanURL: https://man7.org/linux/man-pages/man5/proc.5.html\n    tags:\n      - Filesystem\n      - Process\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://man7.org/linux/man-pages/man5/proc.5.html\n      - type: Reference\n        url: https://www.kernel.org/doc/html/latest/filesystems/proc.html\n  - aid: linuxunix:sysfs-api\n    name: sysfs API\n    description: >-\n      Virtual filesystem for kernel objects and device information presented\n      under /sys.\n    humanURL: https://man7.org/linux/man-pages/man5/sysfs.5.html\n    tags:\n      - Filesystem\n      - Kernel\n      - Devices\n    properties:\n      - type: Documentation\n        url: https://man7.org/linux/man-pages/man5/sysfs.5.html\n\
  \      - type: Reference\n        url: https://www.kernel.org/doc/html/latest/filesystems/sysfs.html\n  - aid: linuxunix:inotify-api\n    name: inotify API\n    description: >-\n      Linux kernel subsystem for monitoring filesystem events such as file\n      creation, deletion, and modification.\n    humanURL: https://man7.org/linux/man-pages/man7/inotify.7.html\n    tags:\n      - Filesystem\n      - Monitoring\n      - Events\n    properties:\n      - type: Documentation\n        url: https://man7.org/linux/man-pages/man7/inotify.7.html\n  - aid: linuxunix:epoll-api\n    name: epoll API\n    description: >-\n      I/O event notification facility for scalable monitoring of large numbers\n      of file descriptors.\n    humanURL: https://man7.org/linux/man-pages/man7/epoll.7.html\n    tags:\n      - I/O\n      - Events\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://man7.org/linux/man-pages/man7/epoll.7.html\n  - aid: linuxunix:udev-api\n    name:\
  \ udev API\n    description: >-\n      Device manager for the Linux kernel handling device nodes and hotplug\n      events in /dev.\n    humanURL: https://www.freedesktop.org/software/systemd/man/udev.html\n    tags:\n      - Devices\n      - Hardware\n      - Hotplug\n    properties:\n      - type: Documentation\n        url: https://www.freedesktop.org/software/systemd/man/udev.html\n      - type: SourceCode\n        url: https://github.com/systemd/systemd/tree/main/src/udev\n  - aid: linuxunix:systemd-api\n    name: systemd API\n    description: >-\n      System and service manager exposing a D-Bus interface for managing\n      services, sockets, devices, mounts, and timers.\n    humanURL: https://www.freedesktop.org/wiki/Software/systemd/\n    tags:\n      - Init\n      - Service Management\n      - System\n    properties:\n      - type: Documentation\n        url: https://www.freedesktop.org/software/systemd/man/\n      - type: Reference\n        url: https://www.freedesktop.org/wiki/Software/systemd/dbus/\n\
  \      - type: SourceCode\n        url: https://github.com/systemd/systemd\ncommon:\n  - type: Website\n    name: Kernel.org\n    description: Home of the Linux kernel project.\n    url: https://www.kernel.org/\n  - type: Documentation\n    name: Linux Kernel Documentation\n    description: Official kernel documentation tree.\n    url: https://www.kernel.org/doc/html/latest/\n  - type: Reference\n    name: Linux man-pages\n    description: The Linux man-pages project.\n    url: https://man7.org/linux/man-pages/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/linuxunix/refs/heads/main/apis.yml
tags:
- Kernel
- Linux
- Operating System
- System
- Unix
- POSIX
url: https://raw.githubusercontent.com/api-evangelist/linuxunix/refs/heads/main/apis.yml
use_cases: []
---
