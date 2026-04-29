---
api_count: 1
api_specs:
- filename: amazon-freertos-openapi.yml
  format: yaml
  label: Amazon FreeRTOS API
  slug: amazon-freertos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/openapi/amazon-freertos-openapi.yml
apis:
- description: The Amazon FreeRTOS API provides programmatic access to manage FreeRTOS software configurations and over-the-air update jobs for IoT devices running FreeRTOS.
  name: Amazon FreeRTOS API
  slug: amazon-freertos-api
capabilities:
- description: Manage FreeRTOS software configurations and OTA firmware updates for microcontroller IoT devices.
  name: Amazon FreeRTOS Device Management
  slug: amazon-freertos-device-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/freertos/
- title: ''
  type: Website
  url: https://aws.amazon.com/freertos/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/freertos/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/iot/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: GitHubRepository
  url: https://github.com/aws/amazon-freertos
- title: ''
  type: Console
  url: https://console.aws.amazon.com/iot/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-freertos
- title: ''
  type: SpectralRules
  url: rules/amazon-freertos-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/freertos.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-freertos-device-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-freertos-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-freertos-context.jsonld
created: '2026-03-16'
description: Amazon FreeRTOS is an open source, real-time operating system for microcontrollers that makes it easy to program, deploy, secure, connect, and manage small, low-power edge devices. It extends the FreeRTOS kernel with libraries for secure connectivity, over-the-air updates, and more.
features:
- description: Open-source real-time operating system kernel with preemptive multitasking for microcontrollers.
  name: FreeRTOS Kernel
- description: Over-the-air firmware update delivery with code signing verification and rollback support.
  name: OTA Update Management
- description: TLS 1.2/1.3 encrypted MQTT and HTTP connectivity using AWS IoT Core.
  name: Secure Connectivity
- description: Zero-touch device provisioning using AWS IoT Fleet Provisioning and Just-In-Time Registration.
  name: Device Provisioning
- description: Cryptographic library for secure key storage and operations on embedded devices.
  name: corePKCS11
- description: IPv4/IPv6 TCP/IP networking stack optimized for embedded systems.
  name: FreeRTOS+TCP
- description: Over 100 partner-qualified hardware platforms from major MCU vendors including Espressif, ST, NXP, Renesas.
  name: Qualified Hardware
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary cloud backend for FreeRTOS device messaging, shadow state, and job management.
  name: AWS IoT Core
- description: Extend cloud intelligence to FreeRTOS edge devices for local compute and ML inference.
  name: AWS IoT Greengrass
- description: Register, organize, monitor, and remotely manage FreeRTOS device fleets.
  name: AWS IoT Device Management
- description: Audit and monitor FreeRTOS device security posture for anomalies and policy violations.
  name: AWS IoT Device Defender
- description: Store firmware binaries for OTA update delivery to FreeRTOS devices.
  name: Amazon S3
- description: Manage code signing keys for secure firmware distribution.
  name: AWS KMS
- description: Automate FreeRTOS fleet infrastructure provisioning with infrastructure-as-code templates.
  name: AWS CloudFormation
jsonld:
- class_count: 5
  name: Amazon Freertos Context
  property_count: 11
  slug: amazon-freertos-context
layout: provider
modified: '2026-04-19'
name: Amazon FreeRTOS
rules:
- name: Amazon FreeRTOS API Rules
  rule_count: 25
  severity_counts:
    error: 7
    hint: 0
    info: 2
    warn: 16
  slug: amazon-freertos-spectral-rules
skills: []
slug: amazon-freertos
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-freertos\nname: Amazon FreeRTOS\ndescription: >-\n  Amazon FreeRTOS is an open source, real-time operating system for\n  microcontrollers that makes it easy to program, deploy, secure, connect, and\n  manage small, low-power edge devices. It extends the FreeRTOS kernel with\n  libraries for secure connectivity, over-the-air updates, and more.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Embedded Systems\n- IoT\n- Microcontrollers\n- RTOS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-freertos:amazon-freertos-api\n  name: Amazon FreeRTOS API\n  description: >-\n    The Amazon FreeRTOS API provides programmatic access to manage FreeRTOS\n    software configurations and over-the-air update jobs for IoT devices\n    running FreeRTOS.\n  humanURL: https://aws.amazon.com/freertos/\n\
  \  baseURL: https://iot.amazonaws.com\n  tags:\n  - Embedded Systems\n  - IoT\n  - RTOS\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/freertos/latest/userguide/what-is-amazon-freertos.html\n  - type: OpenAPI\n    url: openapi/amazon-freertos-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-freertos-software-configuration-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-freertos-ota-update-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-freertos-device-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-freertos-ota-file-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-freertos-tag-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-freertos-software-configuration-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-freertos-ota-update-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-freertos-device-structure.json\n  - type: JSONStructure\n\
  \    url: json-structure/amazon-freertos-ota-file-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-freertos-tag-structure.json\n  - type: Example\n    url: examples/amazon-freertos-software-configuration-example.json\n  - type: Example\n    url: examples/amazon-freertos-ota-update-example.json\n  - type: Example\n    url: examples/amazon-freertos-device-example.json\n  - type: Example\n    url: examples/amazon-freertos-ota-file-example.json\n  - type: Example\n    url: examples/amazon-freertos-tag-example.json\n  - type: GettingStarted\n    url: https://aws.amazon.com/freertos/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/freertos/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/freertos/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/freertos/latest/userguide/freertos-lib-ota-api.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/freertos/\n- type: Website\n  url: https://aws.amazon.com/freertos/\n- type:\
  \ Documentation\n  url: https://docs.aws.amazon.com/freertos/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/iot/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: GitHubRepository\n  url: https://github.com/aws/amazon-freertos\n- type: Console\n  url: https://console.aws.amazon.com/iot/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-freertos\n- type: SpectralRules\n  url: rules/amazon-freertos-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/freertos.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-freertos-device-management.yaml\n\
  - type: Vocabulary\n  url: vocabulary/amazon-freertos-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/amazon-freertos-context.jsonld\n- type: Features\n  data:\n  - name: FreeRTOS Kernel\n    description: Open-source real-time operating system kernel with preemptive multitasking for microcontrollers.\n  - name: OTA Update Management\n    description: Over-the-air firmware update delivery with code signing verification and rollback support.\n  - name: Secure Connectivity\n    description: TLS 1.2/1.3 encrypted MQTT and HTTP connectivity using AWS IoT Core.\n  - name: Device Provisioning\n    description: Zero-touch device provisioning using AWS IoT Fleet Provisioning and Just-In-Time Registration.\n  - name: corePKCS11\n    description: Cryptographic library for secure key storage and operations on embedded devices.\n  - name: FreeRTOS+TCP\n    description: IPv4/IPv6 TCP/IP networking stack optimized for embedded systems.\n  - name: Qualified Hardware\n    description: Over 100 partner-qualified\
  \ hardware platforms from major MCU vendors including Espressif, ST, NXP, Renesas.\n- type: UseCases\n  data:\n  - name: Industrial IoT Sensors\n    description: Deploy FreeRTOS on industrial sensors for secure cloud connectivity and remote firmware updates.\n  - name: Smart Home Devices\n    description: Build connected home devices with low-power FreeRTOS firmware and AWS IoT integration.\n  - name: Asset Tracking\n    description: Develop GPS and location tracking devices with FreeRTOS for fleet and supply chain monitoring.\n  - name: Predictive Maintenance\n    description: Collect vibration, temperature, and current data from FreeRTOS devices for ML-based maintenance prediction.\n  - name: Medical IoT\n    description: Build FDA-validated medical devices with FreeRTOS for remote patient monitoring and diagnostics.\n  - name: Energy Management\n    description: Deploy smart meters and grid sensors running FreeRTOS for utility data collection and OTA updates.\n- type: Integrations\n\
  \  data:\n  - name: AWS IoT Core\n    description: Primary cloud backend for FreeRTOS device messaging, shadow state, and job management.\n  - name: AWS IoT Greengrass\n    description: Extend cloud intelligence to FreeRTOS edge devices for local compute and ML inference.\n  - name: AWS IoT Device Management\n    description: Register, organize, monitor, and remotely manage FreeRTOS device fleets.\n  - name: AWS IoT Device Defender\n    description: Audit and monitor FreeRTOS device security posture for anomalies and policy violations.\n  - name: Amazon S3\n    description: Store firmware binaries for OTA update delivery to FreeRTOS devices.\n  - name: AWS KMS\n    description: Manage code signing keys for secure firmware distribution.\n  - name: AWS CloudFormation\n    description: Automate FreeRTOS fleet infrastructure provisioning with infrastructure-as-code templates.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/apis.yml
tags:
- AWS
- Embedded Systems
- IoT
- Microcontrollers
- RTOS
url: https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/apis.yml
use_cases:
- description: Deploy FreeRTOS on industrial sensors for secure cloud connectivity and remote firmware updates.
  name: Industrial IoT Sensors
- description: Build connected home devices with low-power FreeRTOS firmware and AWS IoT integration.
  name: Smart Home Devices
- description: Develop GPS and location tracking devices with FreeRTOS for fleet and supply chain monitoring.
  name: Asset Tracking
- description: Collect vibration, temperature, and current data from FreeRTOS devices for ML-based maintenance prediction.
  name: Predictive Maintenance
- description: Build FDA-validated medical devices with FreeRTOS for remote patient monitoring and diagnostics.
  name: Medical IoT
- description: Deploy smart meters and grid sensors running FreeRTOS for utility data collection and OTA updates.
  name: Energy Management
---
