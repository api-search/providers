---
api_count: 3
apis:
- description: The Zephyr kernel C API exposes scheduling, threading, synchronization, memory management, and timer services for real-time embedded applications. It is the foundation that device drivers and applicat
  name: Zephyr RTOS Kernel API
  slug: zephyr-kernel-api
- description: The Zephyr device driver subsystem exposes a uniform device model across GPIO, I2C, SPI, UART, ADC, sensors, displays, networking, USB, Bluetooth, and many other peripheral classes, configured through
  name: Zephyr Device Driver API
  slug: zephyr-device-driver-api
- description: The Zephyr networking stack exposes BSD-like sockets, TLS/DTLS, MQTT, CoAP, LWM2M, HTTP, WebSocket, gRPC, and connectivity layers including IPv4/IPv6, Wi-Fi, Thread, OpenThread, Matter, and BLE.
  name: Zephyr Networking API
  slug: zephyr-networking-api
capabilities:
- description: ''
  name: Zephyr Build
  slug: zephyr-build
common:
- title: ''
  type: Portal
  url: https://www.zephyrproject.org/
- title: ''
  type: Documentation
  url: https://docs.zephyrproject.org/latest/
- title: ''
  type: APIReference
  url: https://docs.zephyrproject.org/apidoc/latest/index.html
- title: ''
  type: GettingStarted
  url: https://docs.zephyrproject.org/latest/develop/getting_started/index.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/zephyrproject-rtos
- title: ''
  type: GitHubRepository
  url: https://github.com/zephyrproject-rtos/zephyr
- title: ''
  type: SDK
  url: https://github.com/zephyrproject-rtos/sdk-ng
- title: ''
  type: CLI
  url: https://github.com/zephyrproject-rtos/west
- title: ''
  type: Blog
  url: https://www.zephyrproject.org/blog/
- title: ''
  type: ReleaseNotes
  url: https://docs.zephyrproject.org/latest/releases/index.html
- title: ''
  type: Training
  url: https://www.zephyrproject.org/training-partner-program/
- title: ''
  type: Events
  url: https://www.zephyrproject.org/events/
- title: ''
  type: Compliance
  url: https://docs.zephyrproject.org/latest/security/index.html
- title: ''
  type: TermsOfService
  url: https://www.linuxfoundation.org/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.linuxfoundation.org/privacy-policy/
- title: ''
  type: JSONLD
  url: json-ld/zephyr-context.jsonld
- title: ''
  type: Resources
  url: vocabulary/zephyr-vocabulary.yml
- title: ''
  type: Resources
  url: capabilities/zephyr-build.yaml
created: '2026-03-16'
description: The Zephyr Project is a Linux Foundation project that delivers a small, scalable, secure, and open-source real-time operating system (RTOS) for resource-constrained embedded devices. Zephyr supports 1000+ boards across ARM Cortex, RISC-V, ARC, x86, Xtensa, and other architectures, ships with a C kernel, device drivers, networking stacks (BLE, Wi-Fi, Thread, Matter), security subsystems, and is supported by a meta-tool (west), an SDK (sdk-ng), and a broad ecosystem of training partners and commercial silicon and module vendors.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Zephyr Context
  property_count: 0
  slug: zephyr-context
layout: provider
modified: '2026-05-03'
name: Zephyr Project
skills: []
slug: zephyr
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zephyr\nname: Zephyr Project\ndescription: >-\n  The Zephyr Project is a Linux Foundation project that delivers a small,\n  scalable, secure, and open-source real-time operating system (RTOS) for\n  resource-constrained embedded devices. Zephyr supports 1000+ boards across\n  ARM Cortex, RISC-V, ARC, x86, Xtensa, and other architectures, ships with a\n  C kernel, device drivers, networking stacks (BLE, Wi-Fi, Thread, Matter),\n  security subsystems, and is supported by a meta-tool (west), an SDK\n  (sdk-ng), and a broad ecosystem of training partners and commercial\n  silicon and module vendors.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Embedded\n  - IoT\n  - Linux Foundation\n  - RTOS\n  - Open Source\n  - Edge\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zephyr/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: zephyr:zephyr-kernel-api\n    name: Zephyr RTOS Kernel API\n    description: >-\n      The Zephyr kernel C API exposes scheduling, threading, synchronization,\n      memory management, and timer services for real-time embedded\n      applications. It is the foundation that device drivers and application\n      code build on.\n    humanURL: https://docs.zephyrproject.org/latest/kernel/index.html\n    tags:\n      - RTOS\n      - Embedded\n      - Kernel\n    properties:\n      - type: Documentation\n        url: https://docs.zephyrproject.org/latest/kernel/index.html\n      - type: APIReference\n        url: https://docs.zephyrproject.org/apidoc/latest/index.html\n      - type: GettingStarted\n        url: https://docs.zephyrproject.org/latest/develop/getting_started/index.html\n      - type: GitHubRepository\n        url: https://github.com/zephyrproject-rtos/zephyr\n  - aid: zephyr:zephyr-device-driver-api\n    name: Zephyr Device Driver API\n    description:\
  \ >-\n      The Zephyr device driver subsystem exposes a uniform device model\n      across GPIO, I2C, SPI, UART, ADC, sensors, displays, networking, USB,\n      Bluetooth, and many other peripheral classes, configured through\n      Devicetree and Kconfig.\n    humanURL: https://docs.zephyrproject.org/latest/build/dts/index.html\n    tags:\n      - Drivers\n      - Devicetree\n      - Embedded\n    properties:\n      - type: Documentation\n        url: https://docs.zephyrproject.org/latest/hardware/index.html\n      - type: APIReference\n        url: https://docs.zephyrproject.org/apidoc/latest/group__io__interfaces.html\n  - aid: zephyr:zephyr-networking-api\n    name: Zephyr Networking API\n    description: >-\n      The Zephyr networking stack exposes BSD-like sockets, TLS/DTLS, MQTT,\n      CoAP, LWM2M, HTTP, WebSocket, gRPC, and connectivity layers including\n      IPv4/IPv6, Wi-Fi, Thread, OpenThread, Matter, and BLE.\n    humanURL: https://docs.zephyrproject.org/latest/connectivity/networking/index.html\n\
  \    tags:\n      - Networking\n      - IoT\n      - Connectivity\n    properties:\n      - type: Documentation\n        url: https://docs.zephyrproject.org/latest/connectivity/networking/index.html\ncommon:\n  - type: Portal\n    name: Zephyr Project\n    url: https://www.zephyrproject.org/\n  - type: Documentation\n    name: Zephyr Project Documentation\n    url: https://docs.zephyrproject.org/latest/\n  - type: APIReference\n    name: Zephyr API Reference\n    url: https://docs.zephyrproject.org/apidoc/latest/index.html\n  - type: GettingStarted\n    name: Zephyr Getting Started Guide\n    url: https://docs.zephyrproject.org/latest/develop/getting_started/index.html\n  - type: GitHubOrganization\n    name: Zephyr Project on GitHub\n    url: https://github.com/zephyrproject-rtos\n  - type: GitHubRepository\n    name: Zephyr Primary Git Repository\n    url: https://github.com/zephyrproject-rtos/zephyr\n  - type: SDK\n    name: Zephyr SDK (sdk-ng)\n    url: https://github.com/zephyrproject-rtos/sdk-ng\n\
  \  - type: CLI\n    name: West - Zephyr's Meta-Tool\n    url: https://github.com/zephyrproject-rtos/west\n  - type: Blog\n    name: Zephyr Project Blog\n    url: https://www.zephyrproject.org/blog/\n  - type: ReleaseNotes\n    name: Zephyr Release Notes\n    url: https://docs.zephyrproject.org/latest/releases/index.html\n  - type: Training\n    name: Zephyr Training Partner Program\n    url: https://www.zephyrproject.org/training-partner-program/\n  - type: Events\n    name: Zephyr Events\n    url: https://www.zephyrproject.org/events/\n  - type: Compliance\n    name: Zephyr Security\n    url: https://docs.zephyrproject.org/latest/security/index.html\n  - type: TermsOfService\n    name: Linux Foundation Terms of Use\n    url: https://www.linuxfoundation.org/terms\n  - type: PrivacyPolicy\n    name: Linux Foundation Privacy Policy\n    url: https://www.linuxfoundation.org/privacy-policy/\n  - type: JSONLD\n    name: Zephyr JSON-LD Context\n    url: json-ld/zephyr-context.jsonld\n  - type:\
  \ Resources\n    name: Zephyr Vocabulary\n    url: vocabulary/zephyr-vocabulary.yml\n  - type: Resources\n    name: Zephyr Build Capability\n    url: capabilities/zephyr-build.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zephyr/refs/heads/main/apis.yml
tags:
- Embedded
- IoT
- Linux Foundation
- RTOS
- Open Source
- Edge
url: https://raw.githubusercontent.com/api-evangelist/zephyr/refs/heads/main/apis.yml
use_cases: []
---
