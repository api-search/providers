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
