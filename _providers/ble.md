---
api_count: 3
apis:
- description: The Bluetooth Core Specification defines the complete Bluetooth wireless communication protocol stack including BLE (LE) and Classic Bluetooth. The current stable version is Bluetooth 6.0. The specifi
  name: Bluetooth Core Specification
  slug: bluetooth-core-specification
- description: The Generic Attribute Profile (GATT) defines the framework for data transfer between Bluetooth LE devices. The Bluetooth SIG maintains assigned numbers for services, characteristics, and descriptors t
  name: GATT and Assigned Numbers
  slug: gatt-specification
- description: Bluetooth Mesh enables many-to-many device communications and is particularly suited for IoT applications that require large-scale device networks, including building automation, industrial IoT, and s
  name: Bluetooth Mesh Networking
  slug: mesh-networking
capabilities:
- description: ''
  name: Ble Gatt Capability
  slug: ble-gatt-capability
common:
- title: ''
  type: Website
  url: https://www.bluetooth.com/
- title: ''
  type: Documentation
  url: https://www.bluetooth.com/develop-with-bluetooth/
- title: ''
  type: Specification
  url: https://www.bluetooth.com/specifications/specs/
- title: ''
  type: Training
  url: https://www.bluetooth.com/develop-with-bluetooth/training/
- title: ''
  type: Community
  url: https://www.bluetooth.com/develop-with-bluetooth/
- title: Developer Tools and SDKs
  type: SDK
  url: https://www.bluetooth.com/develop-with-bluetooth/developer-resources/
- title: ''
  type: Conformance
  url: https://www.bluetooth.com/develop-with-bluetooth/qualification-listing/
- title: ''
  type: SpectralRules
  url: rules/ble-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/ble-gatt-capability.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/ble-vocabulary.yaml
created: '2025-01-01'
description: Bluetooth Low Energy (BLE), also known as Bluetooth Smart, is a wireless personal area network technology designed and marketed by the Bluetooth Special Interest Group (Bluetooth SIG). Aimed at IoT and embedded applications, BLE provides reduced power consumption while maintaining similar communication range to classic Bluetooth. The specification is managed by the Bluetooth SIG and covers the full protocol stack including the Generic Attribute Profile (GATT), Generic Access Profile (GAP), and the various service and characteristic specifications used for device interoperability.
features:
- description: BLE defines a complete protocol stack from Physical Layer through Application, enabling ultra-low-power wireless communication for IoT and wearable devices.
  name: Low Energy Protocol Stack
- description: GATT defines a client/server model for data exchange using services and characteristics, enabling standardized device interoperability across vendors.
  name: Generic Attribute Profile (GATT)
- description: GAP controls connections and advertising in BLE, defining how devices discover each other and establish connections.
  name: Generic Access Profile (GAP)
- description: BLE advertising allows devices to broadcast data without requiring a connection, enabling beacons, proximity sensing, and asset tracking.
  name: Advertising and Scanning
- description: Bluetooth 5.2+ LE Audio introduces LC3 codec, Auracast broadcast audio, and hearing aid profiles for next-generation wireless audio applications.
  name: LE Audio
- description: Bluetooth 5.1+ Direction Finding supports Angle of Arrival (AoA) and Angle of Departure (AoD) for indoor positioning and real-time location.
  name: Direction Finding
- description: The Bluetooth Mesh specification enables many-to-many communications for large-scale IoT deployments in buildings, industry, and infrastructure.
  name: Bluetooth Mesh
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: iOS and macOS Core Bluetooth framework provides native BLE central and peripheral role implementation for Apple platform apps.
  name: Apple Core Bluetooth
- description: Android Bluetooth API provides BLE central and peripheral support for Android application development.
  name: Android Bluetooth API
- description: The Zephyr Project includes a full BLE stack (Zephyr BT) for embedded and IoT firmware development.
  name: Zephyr RTOS
- description: Nordic Semiconductor's nRF Connect SDK provides BLE and Bluetooth mesh implementation for nRF52 and nRF53 series SoCs.
  name: NRF Connect SDK
- description: The W3C Web Bluetooth API enables browser-based applications to communicate with BLE devices via JavaScript.
  name: Web Bluetooth API
jsonld:
- class_count: 11
  name: Ble Context
  property_count: 0
  slug: ble-context
layout: provider
modified: '2026-04-21'
name: BLE
rules:
- name: BLE API Rules
  rule_count: 5
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 5
  slug: ble-spectral-rules
skills: []
slug: ble
solutions: []
tags:
- BLE
- Bluetooth
- Embedded
- IoT
- Protocols
- Standards
- Wireless
url: https://raw.githubusercontent.com/api-evangelist/ble/refs/heads/main/apis.yml
use_cases:
- description: BLE powers fitness trackers, smartwatches, heart rate monitors, and medical wearables using standardized GATT health profiles.
  name: Wearable Health Devices
- description: BLE beacons broadcast advertising packets for proximity detection, indoor positioning, and contextual notifications in retail and logistics.
  name: Proximity Beacons
- description: BLE Mesh enables smart lighting, HVAC control, and security systems in residential and commercial building automation.
  name: Smart Home Automation
- description: BLE provides wireless sensor connectivity for industrial monitoring, predictive maintenance, and asset tracking applications.
  name: Industrial IoT
- description: BLE medical devices including glucose meters, blood pressure monitors, and pulse oximeters use standardized health profiles for mobile integration.
  name: Healthcare Monitoring
---
