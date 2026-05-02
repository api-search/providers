---
api_count: 7
apis:
- description: System and service manager for Linux, providing process supervision, socket activation, journaled logging, and a D-Bus management API.
  name: systemd
  slug: systemd
- description: Web-based graphical interface for Linux server administration, providing tools for managing services, storage, networking, and accounts.
  name: Cockpit
  slug: cockpit
- description: The Linux audit subsystem and userspace tools for tracking security-relevant events on a Linux server.
  name: Linux Audit
  slug: linux-audit
- description: The Advanced Package Tool used by Debian, Ubuntu, and derivatives for installing, upgrading, and removing software packages.
  name: APT
  slug: apt
- description: The Dandified YUM package manager used on Fedora, RHEL, CentOS Stream, and related distributions.
  name: DNF
  slug: dnf
- description: The de facto standard suite for secure remote login, command execution, and file transfer on Linux servers.
  name: OpenSSH
  slug: openssh
- description: The systemd journal daemon, providing structured, indexed logs for the Linux server with a query API via journalctl and libsystemd.
  name: systemd-journald
  slug: journald
common:
- title: ''
  type: Website
  url: https://www.linuxfoundation.org/
- title: ''
  type: Documentation
  url: https://www.kernel.org/doc/html/latest/
- title: ''
  type: Reference
  url: https://man7.org/linux/man-pages/
created: '2024-01-15'
description: Linux Server is a topic catalog covering management, administration, and monitoring interfaces used to operate Linux servers in production. It organizes references to systemd, cockpit, the Linux audit framework, package managers (apt, dnf, rpm), configuration management and provisioning tooling, and remote administration protocols commonly used on Linux servers.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Linux Server
skills: []
slug: linux-server
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: linux-server\nname: Linux Server\ndescription: >-\n  Linux Server is a topic catalog covering management, administration, and\n  monitoring interfaces used to operate Linux servers in production. It\n  organizes references to systemd, cockpit, the Linux audit framework, package\n  managers (apt, dnf, rpm), configuration management and provisioning tooling,\n  and remote administration protocols commonly used on Linux servers.\ntype: Topic\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Infrastructure\n  - Linux\n  - Server\n  - System Administration\n  - DevOps\nurl: https://raw.githubusercontent.com/api-evangelist/linux-server/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: linux-server:systemd\n    name: systemd\n    description: >-\n      System and service manager for Linux, providing process supervision,\n   \
  \   socket activation, journaled logging, and a D-Bus management API.\n    humanURL: https://systemd.io/\n    tags:\n      - Service Management\n      - Init\n      - D-Bus\n    properties:\n      - type: Documentation\n        url: https://www.freedesktop.org/software/systemd/man/\n      - type: Reference\n        url: https://www.freedesktop.org/wiki/Software/systemd/dbus/\n      - type: SourceCode\n        url: https://github.com/systemd/systemd\n  - aid: linux-server:cockpit\n    name: Cockpit\n    description: >-\n      Web-based graphical interface for Linux server administration, providing\n      tools for managing services, storage, networking, and accounts.\n    humanURL: https://cockpit-project.org/\n    tags:\n      - Administration\n      - Web UI\n      - Remote\n    properties:\n      - type: Documentation\n        url: https://cockpit-project.org/documentation.html\n      - type: SourceCode\n        url: https://github.com/cockpit-project/cockpit\n  - aid: linux-server:linux-audit\n\
  \    name: Linux Audit\n    description: >-\n      The Linux audit subsystem and userspace tools for tracking\n      security-relevant events on a Linux server.\n    humanURL: https://github.com/linux-audit/audit-documentation\n    tags:\n      - Security\n      - Auditing\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://github.com/linux-audit/audit-documentation/wiki\n      - type: SourceCode\n        url: https://github.com/linux-audit/audit-userspace\n  - aid: linux-server:apt\n    name: APT\n    description: >-\n      The Advanced Package Tool used by Debian, Ubuntu, and derivatives for\n      installing, upgrading, and removing software packages.\n    humanURL: https://wiki.debian.org/Apt\n    tags:\n      - Package Management\n      - Debian\n      - Ubuntu\n    properties:\n      - type: Documentation\n        url: https://manpages.debian.org/bookworm/apt/apt.8.en.html\n  - aid: linux-server:dnf\n    name: DNF\n    description: >-\n      The\
  \ Dandified YUM package manager used on Fedora, RHEL, CentOS Stream,\n      and related distributions.\n    humanURL: https://dnf.readthedocs.io/\n    tags:\n      - Package Management\n      - Fedora\n      - RHEL\n    properties:\n      - type: Documentation\n        url: https://dnf.readthedocs.io/en/latest/\n      - type: SourceCode\n        url: https://github.com/rpm-software-management/dnf\n  - aid: linux-server:openssh\n    name: OpenSSH\n    description: >-\n      The de facto standard suite for secure remote login, command execution,\n      and file transfer on Linux servers.\n    humanURL: https://www.openssh.com/\n    tags:\n      - Remote Access\n      - Security\n      - SSH\n    properties:\n      - type: Documentation\n        url: https://www.openssh.com/manual.html\n      - type: SourceCode\n        url: https://github.com/openssh/openssh-portable\n  - aid: linux-server:journald\n    name: systemd-journald\n    description: >-\n      The systemd journal daemon, providing\
  \ structured, indexed logs for the\n      Linux server with a query API via journalctl and libsystemd.\n    humanURL: https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html\n    tags:\n      - Logging\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html\ncommon:\n  - type: Website\n    name: Linux Foundation\n    description: The Linux Foundation hosts the Linux kernel project.\n    url: https://www.linuxfoundation.org/\n  - type: Documentation\n    name: Linux Kernel Documentation\n    description: Official kernel documentation tree.\n    url: https://www.kernel.org/doc/html/latest/\n  - type: Reference\n    name: Linux man-pages\n    description: The Linux man-pages project.\n    url: https://man7.org/linux/man-pages/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/linux-server/refs/heads/main/apis.yml
tags:
- Infrastructure
- Linux
- Server
- System Administration
- DevOps
url: https://raw.githubusercontent.com/api-evangelist/linux-server/refs/heads/main/apis.yml
use_cases: []
---
