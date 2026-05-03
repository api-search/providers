---
api_count: 5
apis:
- description: OPC-UA (IEC 62541) is the industrial interoperability standard for secure, reliable data exchange in industrial automation and IoT environments. It provides a platform-independent, service-oriented ar
  name: OPC Unified Architecture (OPC-UA)
  slug: opc-ua
- description: MQTT (Message Queuing Telemetry Transport, ISO/IEC 20922) is a lightweight pub/sub messaging protocol widely used in SCADA and IIoT applications for sensor data collection and device control. MQTT bro
  name: MQTT Protocol
  slug: mqtt
- description: Modbus is a serial communication protocol widely used in industrial automation and SCADA systems for connecting electronic devices. Modbus TCP/IP enables integration over standard Ethernet networks, m
  name: Modbus Protocol
  slug: modbus
- description: Inductive Automation's Ignition SCADA platform provides a REST API for reading and writing tag values, managing alarms, retrieving historical data, and controlling system resources. Ignition is one of
  name: Ignition SCADA REST API
  slug: ignition-api
- description: SCADA historians store time-series process data for analysis, reporting, and compliance. Major historian vendors (OSIsoft PI, Aspen InfoPlus.21, GE Proficy Historian) expose REST APIs for querying his
  name: Historian and Alarm Data APIs
  slug: had-api
common:
- title: ''
  type: Website
  url: https://www.isa.org/
- title: ''
  type: Standards Body
  url: https://opcfoundation.org/
- title: ''
  type: Standards Body
  url: https://www.iec.ch/
- title: ''
  type: Documentation
  url: https://www.cisa.gov/topics/industrial-control-systems
- title: ''
  type: GitHub
  url: https://github.com/topics/scada
- title: ''
  type: Vocabulary
  url: vocabulary/scada-vocabulary.yml
- title: ''
  type: JSONLD
  url: json-ld/scada-context.jsonld
created: '2025-01-01'
description: SCADA (Supervisory Control and Data Acquisition) is an industrial control system architecture used to monitor and control industrial processes, infrastructure, and facility-based equipment. It is widely used in manufacturing, energy, water treatment, oil and gas, transportation, and other critical infrastructure sectors to collect real-time data from remote sensors and control equipment. Modern SCADA systems increasingly expose REST APIs, OPC-UA endpoints, and MQTT brokers for integration with enterprise systems, cloud platforms, and AI/ML workloads.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Scada Context
  property_count: 23
  slug: scada-context
layout: provider
modified: '2026-05-02'
name: SCADA
skills: []
slug: scada
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scada\nname: SCADA\ndescription: >-\n  SCADA (Supervisory Control and Data Acquisition) is an industrial control\n  system architecture used to monitor and control industrial processes,\n  infrastructure, and facility-based equipment. It is widely used in\n  manufacturing, energy, water treatment, oil and gas, transportation, and\n  other critical infrastructure sectors to collect real-time data from remote\n  sensors and control equipment. Modern SCADA systems increasingly expose REST\n  APIs, OPC-UA endpoints, and MQTT brokers for integration with enterprise\n  systems, cloud platforms, and AI/ML workloads.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Critical Infrastructure\n  - ICS\n  - Industrial Automation\n  - Industrial IoT\n  - OT Security\n  - SCADA\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scada/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: scada:opc-ua\n    name: OPC Unified Architecture (OPC-UA)\n    description: >-\n      OPC-UA (IEC 62541) is the industrial interoperability standard for secure,\n      reliable data exchange in industrial automation and IoT environments.\n      It provides a platform-independent, service-oriented architecture for\n      accessing real-time and historical data from PLCs, sensors, and SCADA\n      systems. OPC-UA supports both client/server and pub/sub communication\n      models.\n    humanURL: https://opcfoundation.org/about/opc-technologies/opc-ua/\n    tags:\n      - IEC 62541\n      - Industrial Interoperability\n      - OPC-UA\n      - Real-Time Data\n    properties:\n      - type: Documentation\n        url: https://opcfoundation.org/about/opc-technologies/opc-ua/\n      - type: Specification\n        url: https://reference.opcfoundation.org/Core/Part1/v105/docs/\n\n  - aid: scada:mqtt\n    name: MQTT Protocol\n    description: >-\n      MQTT (Message Queuing\
  \ Telemetry Transport, ISO/IEC 20922) is a lightweight\n      pub/sub messaging protocol widely used in SCADA and IIoT applications for\n      sensor data collection and device control. MQTT brokers (Mosquitto,\n      EMQX, HiveMQ) are commonly deployed in SCADA architectures for real-time\n      telemetry streaming.\n    humanURL: https://mqtt.org/\n    tags:\n      - IoT\n      - MQTT\n      - Messaging\n      - Pub/Sub\n      - Telemetry\n    properties:\n      - type: Documentation\n        url: https://mqtt.org/\n      - type: Specification\n        url: https://docs.oasis-open.org/mqtt/mqtt/v5.0/mqtt-v5.0.html\n\n  - aid: scada:modbus\n    name: Modbus Protocol\n    description: >-\n      Modbus is a serial communication protocol widely used in industrial\n      automation and SCADA systems for connecting electronic devices. Modbus\n      TCP/IP enables integration over standard Ethernet networks, making it\n      one of the most common field device protocols in SCADA deployments.\n\
  \    humanURL: https://modbus.org/\n    tags:\n      - Field Protocol\n      - Industrial Automation\n      - Modbus\n      - PLC\n    properties:\n      - type: Documentation\n        url: https://modbus.org/\n      - type: Specification\n        url: https://modbus.org/docs/Modbus_Application_Protocol_V1_1b3.pdf\n\n  - aid: scada:ignition-api\n    name: Ignition SCADA REST API\n    description: >-\n      Inductive Automation's Ignition SCADA platform provides a REST API for\n      reading and writing tag values, managing alarms, retrieving historical\n      data, and controlling system resources. Ignition is one of the most\n      widely deployed SCADA platforms in North America.\n    humanURL: https://docs.inductiveautomation.com/\n    baseURL: https://{ignition-host}/system/webdev\n    tags:\n      - Ignition\n      - Industrial Automation\n      - SCADA Platform\n    properties:\n      - type: Documentation\n        url: https://docs.inductiveautomation.com/\n\n  - aid: scada:had-api\n\
  \    name: Historian and Alarm Data APIs\n    description: >-\n      SCADA historians store time-series process data for analysis, reporting,\n      and compliance. Major historian vendors (OSIsoft PI, Aspen InfoPlus.21,\n      GE Proficy Historian) expose REST APIs for querying historical process\n      data. The OSIsoft PI Web API provides a RESTful interface to PI System\n      data assets.\n    humanURL: https://techsupport.osisoft.com/Documentation/PI-Web-API/\n    tags:\n      - Historian\n      - OSIsoft PI\n      - Time-Series\n    properties:\n      - type: Documentation\n        url: https://techsupport.osisoft.com/Documentation/PI-Web-API/\n\ncommon:\n  - type: Website\n    url: https://www.isa.org/\n  - type: Standards Body\n    url: https://opcfoundation.org/\n  - type: Standards Body\n    url: https://www.iec.ch/\n  - type: Documentation\n    url: https://www.cisa.gov/topics/industrial-control-systems\n  - type: GitHub\n    url: https://github.com/topics/scada\n  - type:\
  \ Vocabulary\n    url: vocabulary/scada-vocabulary.yml\n  - type: JSONLD\n    url: json-ld/scada-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scada/refs/heads/main/apis.yml
tags:
- Critical Infrastructure
- ICS
- Industrial Automation
- Industrial IoT
- OT Security
- SCADA
url: https://raw.githubusercontent.com/api-evangelist/scada/refs/heads/main/apis.yml
use_cases: []
---
