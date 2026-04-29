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
source_yaml: "aid: ble\nname: BLE\ndescription: >-\n  Bluetooth Low Energy (BLE), also known as Bluetooth Smart, is a wireless personal\n  area network technology designed and marketed by the Bluetooth Special Interest Group\n  (Bluetooth SIG). Aimed at IoT and embedded applications, BLE provides reduced power\n  consumption while maintaining similar communication range to classic Bluetooth. The\n  specification is managed by the Bluetooth SIG and covers the full protocol stack\n  including the Generic Attribute Profile (GATT), Generic Access Profile (GAP), and\n  the various service and characteristic specifications used for device interoperability.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - BLE\n  - Bluetooth\n  - Embedded\n  - IoT\n  - Protocols\n  - Standards\n  - Wireless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ble/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-21'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: ble:bluetooth-core-specification\n    name: Bluetooth Core Specification\n    description: >-\n      The Bluetooth Core Specification defines the complete Bluetooth wireless\n      communication protocol stack including BLE (LE) and Classic Bluetooth.\n      The current stable version is Bluetooth 6.0. The specification covers the\n      Physical Layer, Link Layer, HCI, L2CAP, SM, GAP, and GATT layers, as well as\n      LE Audio, Isochronous Channels, and Direction Finding extensions.\n    humanURL: https://www.bluetooth.com/specifications/specs/core60/\n    tags:\n      - BLE\n      - Bluetooth\n      - Core Specification\n      - Protocols\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://www.bluetooth.com/specifications/specs/\n      - type: Specification\n        url: https://www.bluetooth.com/specifications/specs/core60/\n      - type: JSONSchema\n        url: json-schema/ble-gatt-service-schema.json\n      - type: JSONSchema\n\
  \        url: json-schema/ble-advertising-packet-schema.json\n      - type: JSONStructure\n        url: json-structure/ble-gatt-service-structure.json\n      - type: JSONStructure\n        url: json-structure/ble-advertising-packet-structure.json\n      - type: JSONLD\n        url: json-ld/ble-context.jsonld\n      - type: Example\n        url: examples/ble-heart-rate-service-example.json\n      - type: Example\n        url: examples/ble-advertising-packet-example.json\n  - aid: ble:gatt-specification\n    name: GATT and Assigned Numbers\n    description: >-\n      The Generic Attribute Profile (GATT) defines the framework for data transfer\n      between Bluetooth LE devices. The Bluetooth SIG maintains assigned numbers for\n      services, characteristics, and descriptors that enable interoperable implementations.\n      GATT services include Battery Service, Heart Rate, Device Information, Health\n      Thermometer, and many other standardized profiles.\n    humanURL: https://www.bluetooth.com/specifications/assigned-numbers/\n\
  \    tags:\n      - BLE\n      - GATT\n      - IoT\n      - Profiles\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://www.bluetooth.com/specifications/assigned-numbers/\n      - type: Specification\n        url: https://www.bluetooth.com/specifications/assigned-numbers/\n  - aid: ble:mesh-networking\n    name: Bluetooth Mesh Networking\n    description: >-\n      Bluetooth Mesh enables many-to-many device communications and is particularly\n      suited for IoT applications that require large-scale device networks, including\n      building automation, industrial IoT, and smart city infrastructure.\n    humanURL: https://www.bluetooth.com/specifications/specs/mesh-profile/\n    tags:\n      - BLE\n      - IoT\n      - Mesh\n      - Networking\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://www.bluetooth.com/specifications/specs/mesh-profile/\n      - type: Specification\n        url: https://www.bluetooth.com/specifications/specs/mesh-profile/\n\
  common:\n  - type: Website\n    url: https://www.bluetooth.com/\n  - type: Documentation\n    url: https://www.bluetooth.com/develop-with-bluetooth/\n  - type: Specification\n    url: https://www.bluetooth.com/specifications/specs/\n  - type: Training\n    url: https://www.bluetooth.com/develop-with-bluetooth/training/\n  - type: Community\n    url: https://www.bluetooth.com/develop-with-bluetooth/\n  - type: SDK\n    url: https://www.bluetooth.com/develop-with-bluetooth/developer-resources/\n    title: Developer Tools and SDKs\n  - type: Conformance\n    url: https://www.bluetooth.com/develop-with-bluetooth/qualification-listing/\n  - type: SpectralRules\n    url: rules/ble-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/ble-gatt-capability.yaml\n  - type: Vocabulary\n    url: vocabulary/ble-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Low Energy Protocol Stack\n        description: >-\n          BLE defines a complete protocol stack from Physical\
  \ Layer through Application,\n          enabling ultra-low-power wireless communication for IoT and wearable devices.\n      - name: Generic Attribute Profile (GATT)\n        description: >-\n          GATT defines a client/server model for data exchange using services and\n          characteristics, enabling standardized device interoperability across vendors.\n      - name: Generic Access Profile (GAP)\n        description: >-\n          GAP controls connections and advertising in BLE, defining how devices discover\n          each other and establish connections.\n      - name: Advertising and Scanning\n        description: >-\n          BLE advertising allows devices to broadcast data without requiring a\n          connection, enabling beacons, proximity sensing, and asset tracking.\n      - name: LE Audio\n        description: >-\n          Bluetooth 5.2+ LE Audio introduces LC3 codec, Auracast broadcast audio,\n          and hearing aid profiles for next-generation wireless audio\
  \ applications.\n      - name: Direction Finding\n        description: >-\n          Bluetooth 5.1+ Direction Finding supports Angle of Arrival (AoA) and\n          Angle of Departure (AoD) for indoor positioning and real-time location.\n      - name: Bluetooth Mesh\n        description: >-\n          The Bluetooth Mesh specification enables many-to-many communications for\n          large-scale IoT deployments in buildings, industry, and infrastructure.\n  - type: UseCases\n    data:\n      - name: Wearable Health Devices\n        description: >-\n          BLE powers fitness trackers, smartwatches, heart rate monitors, and medical\n          wearables using standardized GATT health profiles.\n      - name: Proximity Beacons\n        description: >-\n          BLE beacons broadcast advertising packets for proximity detection, indoor\n          positioning, and contextual notifications in retail and logistics.\n      - name: Smart Home Automation\n        description: >-\n          BLE\
  \ Mesh enables smart lighting, HVAC control, and security systems in\n          residential and commercial building automation.\n      - name: Industrial IoT\n        description: >-\n          BLE provides wireless sensor connectivity for industrial monitoring,\n          predictive maintenance, and asset tracking applications.\n      - name: Healthcare Monitoring\n        description: >-\n          BLE medical devices including glucose meters, blood pressure monitors, and\n          pulse oximeters use standardized health profiles for mobile integration.\n  - type: Integrations\n    data:\n      - name: Apple Core Bluetooth\n        description: >-\n          iOS and macOS Core Bluetooth framework provides native BLE central and\n          peripheral role implementation for Apple platform apps.\n      - name: Android Bluetooth API\n        description: >-\n          Android Bluetooth API provides BLE central and peripheral support for\n          Android application development.\n   \
  \   - name: Zephyr RTOS\n        description: >-\n          The Zephyr Project includes a full BLE stack (Zephyr BT) for embedded\n          and IoT firmware development.\n      - name: NRF Connect SDK\n        description: >-\n          Nordic Semiconductor's nRF Connect SDK provides BLE and Bluetooth mesh\n          implementation for nRF52 and nRF53 series SoCs.\n      - name: Web Bluetooth API\n        description: >-\n          The W3C Web Bluetooth API enables browser-based applications to communicate\n          with BLE devices via JavaScript.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ble/refs/heads/main/apis.yml
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
