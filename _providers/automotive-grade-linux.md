---
api_count: 3
apis:
- description: The AGL Application Framework provides APIs for managing applications on the AGL platform including installation, lifecycle management, permission enforcement, and inter-application communication. App
  name: AGL Application Framework API
  slug: agl-application-framework-api
- description: 'AGL uses SOME/IP (Scalable service-Oriented MiddlewarE over IP) via the vSomeIP library for vehicle service communication. This enables microservice communication between ECUs over Ethernet using the '
  name: AGL VSOMEIP Service API
  slug: vsomeip-service-api
- description: The AGL SoDeV (Software Defined Vehicle) reference platform provides APIs for software-defined vehicle architectures that decouple software from hardware. SoDeV builds on Zephyr RTOS and meta-AGL laye
  name: AGL SoDeV Software Defined Vehicle API
  slug: sodev-api
common:
- title: ''
  type: Website
  url: https://www.automotivelinux.org
- title: ''
  type: Documentation
  url: https://docs.automotivelinux.org
- title: ''
  type: GitHubOrganization
  url: https://github.com/automotive-grade-linux
- title: ''
  type: GitHubRepository
  url: https://github.com/automotive-grade-linux/meta-agl-monorepo
created: '2026-03-16'
description: Automotive Grade Linux (AGL) is a collaborative open source project under the Linux Foundation that develops a unified software platform for connected vehicles. AGL brings together automakers (Toyota, Honda, Mercedes-Benz), suppliers, and technology companies to build an open Linux-based software stack for in-vehicle infotainment, instrument clusters, telematics, and software-defined vehicle (SoDeV) architectures. The platform decouples software from hardware enabling rapid automotive application development.
features:
- description: AGL uses the Yocto Project and OpenEmbedded build framework with meta-AGL layers for creating customized embedded Linux distributions targeting automotive hardware platforms including Renesas R-Car and Raspberry Pi.
  name: Yocto-Based Build System
- description: Service-oriented in-vehicle communication using the SOME/IP protocol via vSomeIP for microservice architectures across ECUs over automotive Ethernet networks.
  name: SOME/IP Vehicle Services
- description: AGL SoDeV reference platform for decoupling software from hardware, enabling flexible, updatable in-vehicle software architectures using Zephyr RTOS and container-based application isolation.
  name: Software Defined Vehicle (SoDeV)
- description: OTA update framework for delivering software updates to AGL-based in-vehicle systems without physical access, supporting fleet-wide update management.
  name: Over-The-Air Updates
- description: Wayland/Weston-based display framework for in-vehicle infotainment and digital instrument cluster applications with automotive-grade display requirements.
  name: IVI and Instrument Cluster Support
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with the COVESA Vehicle Signal Specification (VSS) for standardized access to vehicle sensor and actuator data.
  name: COVESA Vehicle Signal Specification
- description: Integration with Eclipse KUKSA for vehicle signal API abstraction enabling portable in-vehicle application development.
  name: Eclipse KUKSA
- description: AGL SoDeV integrates Zephyr RTOS for safety-critical microcontroller domains within software-defined vehicle architectures.
  name: Zephyr RTOS
- description: Primary hardware reference platform support for Renesas R-Car SoCs used in production automotive IVI and cluster systems.
  name: Renesas R-Car Platforms
layout: provider
modified: '2026-04-19'
name: Automotive Grade Linux
skills: []
slug: automotive-grade-linux
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: automotive-grade-linux\nname: Automotive Grade Linux\ndescription: >-\n  Automotive Grade Linux (AGL) is a collaborative open source project under the Linux\n  Foundation that develops a unified software platform for connected vehicles. AGL brings\n  together automakers (Toyota, Honda, Mercedes-Benz), suppliers, and technology companies\n  to build an open Linux-based software stack for in-vehicle infotainment, instrument\n  clusters, telematics, and software-defined vehicle (SoDeV) architectures. The platform\n  decouples software from hardware enabling rapid automotive application development.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automotive\n  - Connected Vehicles\n  - Embedded Linux\n  - In-Vehicle Infotainment\n  - IoT\n  - Linux Foundation\n  - Open Source\n  - Software Defined Vehicles\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/automotive-grade-linux/refs/heads/main/apis.yml\n\
  created: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: automotive-grade-linux:agl-application-framework-api\n    name: AGL Application Framework API\n    description: >-\n      The AGL Application Framework provides APIs for managing applications on\n      the AGL platform including installation, lifecycle management, permission\n      enforcement, and inter-application communication. Applications interact\n      with vehicle services through the Application Framework using D-Bus and\n      WebSocket-based APIs.\n    humanURL: https://docs.automotivelinux.org/en/master/#0_Getting_Started/2_Developing_an_AGL_Application/\n    tags:\n      - Application Framework\n      - Lifecycle Management\n      - IVI\n      - D-Bus\n    properties:\n      - type: Documentation\n        url: https://docs.automotivelinux.org/en/master/#0_Getting_Started/2_Developing_an_AGL_Application/\n\n  - aid: automotive-grade-linux:vsomeip-service-api\n    name: AGL VSOMEIP Service\
  \ API\n    description: >-\n      AGL uses SOME/IP (Scalable service-Oriented MiddlewarE over IP) via the\n      vSomeIP library for vehicle service communication. This enables microservice\n      communication between ECUs over Ethernet using the SOME/IP protocol,\n      supporting service discovery, request-response, and event notification\n      patterns for in-vehicle networks.\n    humanURL: https://github.com/COVESA/vsomeip\n    tags:\n      - SOME/IP\n      - Vehicle Services\n      - ECU Communication\n      - Ethernet\n      - Microservices\n    properties:\n      - type: Documentation\n        url: https://github.com/COVESA/vsomeip\n      - type: GitHubRepository\n        url: https://github.com/COVESA/vsomeip\n\n  - aid: automotive-grade-linux:sodev-api\n    name: AGL SoDeV Software Defined Vehicle API\n    description: >-\n      The AGL SoDeV (Software Defined Vehicle) reference platform provides APIs\n      for software-defined vehicle architectures that decouple software\
  \ from\n      hardware. SoDeV builds on Zephyr RTOS and meta-AGL layers to provide\n      a foundation for developing modern in-vehicle computing architectures\n      with over-the-air update capabilities and service-oriented interfaces.\n    humanURL: https://www.automotivelinux.org\n    tags:\n      - Software Defined Vehicles\n      - Zephyr\n      - OTA Updates\n      - Vehicle Computing\n    properties:\n      - type: Documentation\n        url: https://docs.automotivelinux.org\n      - type: GitHubRepository\n        url: https://github.com/automotive-grade-linux/meta-agl-monorepo\n\ncommon:\n  - type: Website\n    url: https://www.automotivelinux.org\n  - type: Documentation\n    url: https://docs.automotivelinux.org\n  - type: GitHubOrganization\n    url: https://github.com/automotive-grade-linux\n  - type: GitHubRepository\n    url: https://github.com/automotive-grade-linux/meta-agl-monorepo\n  - type: Features\n    data:\n      - name: Yocto-Based Build System\n        description:\
  \ >-\n          AGL uses the Yocto Project and OpenEmbedded build framework with\n          meta-AGL layers for creating customized embedded Linux distributions\n          targeting automotive hardware platforms including Renesas R-Car and Raspberry Pi.\n      - name: SOME/IP Vehicle Services\n        description: >-\n          Service-oriented in-vehicle communication using the SOME/IP protocol\n          via vSomeIP for microservice architectures across ECUs over automotive\n          Ethernet networks.\n      - name: Software Defined Vehicle (SoDeV)\n        description: >-\n          AGL SoDeV reference platform for decoupling software from hardware,\n          enabling flexible, updatable in-vehicle software architectures using\n          Zephyr RTOS and container-based application isolation.\n      - name: Over-The-Air Updates\n        description: >-\n          OTA update framework for delivering software updates to AGL-based\n          in-vehicle systems without physical access,\
  \ supporting fleet-wide\n          update management.\n      - name: IVI and Instrument Cluster Support\n        description: >-\n          Wayland/Weston-based display framework for in-vehicle infotainment\n          and digital instrument cluster applications with automotive-grade\n          display requirements.\n  - type: UseCases\n    data:\n      - name: In-Vehicle Infotainment Development\n        description: >-\n          Develop navigation, media, and connectivity applications for\n          automotive head units using AGL application framework APIs and\n          the Wayland display system.\n      - name: Connected Car Platform\n        description: >-\n          Build telematics, V2X communication, and cloud connectivity\n          capabilities on AGL-based vehicle computing platforms.\n      - name: Software Defined Vehicle Architecture\n        description: >-\n          Design vehicle software architectures that decouple application\n          software from hardware using\
  \ AGL SoDeV as the foundation platform.\n      - name: Instrument Cluster Applications\n        description: >-\n          Create digital instrument cluster applications for speedometers,\n          tachometers, and ADAS status displays using AGL display APIs.\n  - type: Integrations\n    data:\n      - name: COVESA Vehicle Signal Specification\n        description: >-\n          Integration with the COVESA Vehicle Signal Specification (VSS)\n          for standardized access to vehicle sensor and actuator data.\n      - name: Eclipse KUKSA\n        description: >-\n          Integration with Eclipse KUKSA for vehicle signal API abstraction\n          enabling portable in-vehicle application development.\n      - name: Zephyr RTOS\n        description: >-\n          AGL SoDeV integrates Zephyr RTOS for safety-critical microcontroller\n          domains within software-defined vehicle architectures.\n      - name: Renesas R-Car Platforms\n        description: >-\n          Primary hardware\
  \ reference platform support for Renesas R-Car SoCs\n          used in production automotive IVI and cluster systems.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/automotive-grade-linux/refs/heads/main/apis.yml
tags:
- Automotive
- Connected Vehicles
- Embedded Linux
- In-Vehicle Infotainment
- IoT
- Linux Foundation
- Open Source
- Software Defined Vehicles
url: https://raw.githubusercontent.com/api-evangelist/automotive-grade-linux/refs/heads/main/apis.yml
use_cases:
- description: Develop navigation, media, and connectivity applications for automotive head units using AGL application framework APIs and the Wayland display system.
  name: In-Vehicle Infotainment Development
- description: Build telematics, V2X communication, and cloud connectivity capabilities on AGL-based vehicle computing platforms.
  name: Connected Car Platform
- description: Design vehicle software architectures that decouple application software from hardware using AGL SoDeV as the foundation platform.
  name: Software Defined Vehicle Architecture
- description: Create digital instrument cluster applications for speedometers, tachometers, and ADAS status displays using AGL display APIs.
  name: Instrument Cluster Applications
---
