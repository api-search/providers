---
api_count: 1
apis:
- description: The AWS IoT FleetWise API provides access to vehicle data modeling, fleet management, signal catalogs, campaigns, and data collection for connected vehicle platforms.
  name: AWS IoT FleetWise API
  slug: aws-iot-fleetwise-api
capabilities:
- description: Unified capability for Automotive Engineer, IoT Developer to manage collect, transform, and transfer vehicle data to the cloud operations.
  name: Amazon IoT FleetWise - Vehicle Fleet Management
  slug: vehicle-fleet-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iot-fleetwise/
- title: ''
  type: Website
  url: https://aws.amazon.com/iot-fleetwise/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/iot-fleetwise/
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
  url: https://aws.amazon.com/blogs/iot/tag/aws-iot-fleetwise/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/iotfleetwise/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-iot-fleetwise-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iot-fleetwise.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/vehicle-fleet-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iot-fleetwise-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iot-fleetwise-context.jsonld
created: '2026-03-16'
description: AWS IoT FleetWise is a managed service that makes it easy for automotive manufacturers to collect, transform, and transfer vehicle data to the cloud in near-real time. It provides tools for vehicle data modeling, intelligent data collection, and cloud-based analytics.
features:
- description: Model vehicle signals using VSS and OEM-specific data dictionaries.
  name: Vehicle Signal Catalog
- description: Collect vehicle data conditionally based on events, time windows, or triggers.
  name: Intelligent Data Collection
- description: Deploy data collection campaigns across thousands of vehicles simultaneously.
  name: Fleet-Wide Campaigns
- description: Analyze collected vehicle data using Amazon Timestream and QuickSight.
  name: Cloud Analytics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Stores vehicle time-series telemetry data for analysis.
  name: Amazon Timestream
- description: Stores raw vehicle data files for batch analytics.
  name: Amazon S3
- description: Provides connectivity for vehicle data transmission.
  name: AWS IoT Core
jsonld:
- class_count: 102
  name: Amazon Iot Fleetwise Context
  property_count: 147
  slug: amazon-iot-fleetwise-context
layout: provider
modified: '2026-04-19'
name: Amazon IoT FleetWise
rules:
- name: Amazon IoT FleetWise API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 5
  slug: amazon-iot-fleetwise-spectral-rules
skills: []
slug: amazon-iot-fleetwise
solutions: []
source_yaml: "aid: amazon-iot-fleetwise\nname: Amazon IoT FleetWise\ndescription: >-\n  AWS IoT FleetWise is a managed service that makes it easy for automotive manufacturers to collect, transform, and transfer vehicle data to the cloud in near-real time. It provides tools for vehicle data modeling, intelligent data collection, and cloud-based analytics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automotive\n  - AWS\n  - Connected Vehicles\n  - IoT\n  - Telematics\n  - Vehicle Data\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iot-fleetwise/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iot-fleetwise:aws-iot-fleetwise-api\n    name: AWS IoT FleetWise API\n    description: >-\n      The AWS IoT FleetWise API provides access to vehicle data modeling, fleet management, signal catalogs, campaigns, and data collection for connected\
  \ vehicle platforms.\n    humanURL: https://aws.amazon.com/iot-fleetwise/\n    baseURL: https://iotfleetwise.amazonaws.com\n    tags:\n      - Automotive\n      - IoT\n      - Vehicle Data\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/iot-fleetwise/latest/APIReference/\n      - type: OpenAPI\n        url: openapi/amazon-iot-fleetwise-openapi-original.yml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/iot-fleetwise/latest/developerguide/getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/iot-fleetwise/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iot-fleetwise/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iot-fleetwise/\n  - type: Website\n    url: https://aws.amazon.com/iot-fleetwise/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/iot-fleetwise/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n\
  \    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/iot/tag/aws-iot-fleetwise/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/iotfleetwise/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iot-fleetwise-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iot-fleetwise.yaml\n  - type: NaftikoCapability\n    url: capabilities/vehicle-fleet-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iot-fleetwise-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/amazon-iot-fleetwise-context.jsonld\n  - type:\
  \ Features\n    data:\n      - name: Vehicle Signal Catalog\n        description: Model vehicle signals using VSS and OEM-specific data dictionaries.\n      - name: Intelligent Data Collection\n        description: Collect vehicle data conditionally based on events, time windows, or triggers.\n      - name: Fleet-Wide Campaigns\n        description: Deploy data collection campaigns across thousands of vehicles simultaneously.\n      - name: Cloud Analytics\n        description: Analyze collected vehicle data using Amazon Timestream and QuickSight.\n  - type: UseCases\n    data:\n      - name: OBD Data Collection\n        description: Collect and analyze vehicle diagnostic data from CAN bus.\n      - name: Driver Behavior Analysis\n        description: Analyze driving patterns for safety scoring and insurance.\n      - name: Predictive Maintenance\n        description: Monitor vehicle health and predict maintenance needs.\n  - type: Integrations\n    data:\n      - name: Amazon Timestream\n\
  \        description: Stores vehicle time-series telemetry data for analysis.\n      - name: Amazon S3\n        description: Stores raw vehicle data files for batch analytics.\n      - name: AWS IoT Core\n        description: Provides connectivity for vehicle data transmission.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-fleetwise/refs/heads/main/apis.yml
tags:
- Automotive
- AWS
- Connected Vehicles
- IoT
- Telematics
- Vehicle Data
url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-fleetwise/refs/heads/main/apis.yml
use_cases:
- description: Collect and analyze vehicle diagnostic data from CAN bus.
  name: OBD Data Collection
- description: Analyze driving patterns for safety scoring and insurance.
  name: Driver Behavior Analysis
- description: Monitor vehicle health and predict maintenance needs.
  name: Predictive Maintenance
---
