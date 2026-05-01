---
api_count: 1
api_specs:
- filename: amazon-iot-core-openapi-original.yml
  format: yaml
  label: AWS IoT Core API
  slug: aws-iot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-core/refs/heads/main/openapi/amazon-iot-core-openapi-original.yml
apis:
- description: The AWS IoT Core API provides programmatic access to manage things, policies, certificates, rules, and MQTT messaging for IoT device connectivity.
  name: AWS IoT Core API
  slug: aws-iot-api
capabilities:
- description: Unified capability for IoT Developer, Solutions Architect to manage managed cloud service for iot device connectivity and message routing operations.
  name: Amazon IoT Core - Iot Device Connectivity
  slug: iot-device-connectivity
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iot-core/
- title: ''
  type: Website
  url: https://aws.amazon.com/iot-core/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/iot/
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
  type: Console
  url: https://console.aws.amazon.com/iot/
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
  url: rules/amazon-iot-core-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iot-core.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/iot-device-connectivity.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iot-core-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iot-core-context.jsonld
created: '2026-03-16'
description: AWS IoT Core is a managed cloud service that lets connected devices easily and securely interact with cloud applications and other devices. It can support billions of devices and trillions of messages, routing those messages to AWS endpoints and other devices reliably and securely.
features:
- description: Connects IoT devices to AWS using MQTT, HTTPS, and WebSocket protocols with mutual TLS authentication.
  name: Secure Device Connectivity
- description: Scales to billions of messages per day with a fully managed MQTT message broker.
  name: Message Broker
- description: Routes device messages to 15+ AWS services based on SQL-like rules.
  name: Rules Engine
- description: Maintains a persistent virtual representation of each device for state management.
  name: Device Shadow
- description: Index and search all IoT things and their attributes at scale.
  name: Fleet Indexing
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Trigger serverless functions from IoT device messages with Rules Engine.
  name: AWS Lambda
- description: Stream IoT telemetry data to Kinesis for real-time analytics.
  name: Amazon Kinesis
- description: Store device messages and data in S3 using IoT Rules.
  name: Amazon S3
- description: Write device state data to DynamoDB tables with IoT Rules.
  name: Amazon DynamoDB
jsonld:
- class_count: 102
  name: Amazon Iot Core Context
  property_count: 267
  slug: amazon-iot-core-context
layout: provider
modified: '2026-04-19'
name: Amazon IoT Core
rules:
- name: Amazon IoT Core API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 5
  slug: amazon-iot-core-spectral-rules
skills: []
slug: amazon-iot-core
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-iot-core\nname: Amazon IoT Core\ndescription: >-\n  AWS IoT Core is a managed cloud service that lets connected devices easily and securely interact with cloud applications and other devices. It can support billions of devices and trillions of messages, routing those messages to AWS endpoints and other devices reliably and securely.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Device Management\n  - IoT\n  - MQTT\n  - Message Routing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iot-core/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iot-core:aws-iot-api\n    name: AWS IoT Core API\n    description: >-\n      The AWS IoT Core API provides programmatic access to manage things, policies, certificates, rules, and MQTT messaging for IoT device connectivity.\n    humanURL: https://aws.amazon.com/iot-core/\n\
  \    baseURL: https://iot.amazonaws.com\n    tags:\n      - Device Management\n      - IoT\n      - MQTT\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/iot/latest/apireference/\n      - type: OpenAPI\n        url: openapi/amazon-iot-core-openapi-original.yml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/iot/latest/developerguide/iot-gs.html\n      - type: Pricing\n        url: https://aws.amazon.com/iot-core/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iot-core/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iot-core/\n  - type: Website\n    url: https://aws.amazon.com/iot-core/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/iot/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/iot/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/iot/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iot-core-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iot-core.yaml\n  - type: NaftikoCapability\n    url: capabilities/iot-device-connectivity.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iot-core-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/amazon-iot-core-context.jsonld\n  - type: Features\n    data:\n      - name: Secure Device Connectivity\n        description: Connects IoT devices to AWS using MQTT, HTTPS, and WebSocket protocols with mutual TLS authentication.\n      - name: Message Broker\n\
  \        description: Scales to billions of messages per day with a fully managed MQTT message broker.\n      - name: Rules Engine\n        description: Routes device messages to 15+ AWS services based on SQL-like rules.\n      - name: Device Shadow\n        description: Maintains a persistent virtual representation of each device for state management.\n      - name: Fleet Indexing\n        description: Index and search all IoT things and their attributes at scale.\n  - type: UseCases\n    data:\n      - name: Industrial IoT\n        description: Connect factory equipment to AWS for real-time monitoring and predictive maintenance.\n      - name: Smart Home\n        description: Build connected home devices with secure two-way communication.\n      - name: Asset Tracking\n        description: Track vehicles, equipment, and assets with GPS and sensor data.\n  - type: Integrations\n    data:\n      - name: AWS Lambda\n        description: Trigger serverless functions from IoT device messages\
  \ with Rules Engine.\n      - name: Amazon Kinesis\n        description: Stream IoT telemetry data to Kinesis for real-time analytics.\n      - name: Amazon S3\n        description: Store device messages and data in S3 using IoT Rules.\n      - name: Amazon DynamoDB\n        description: Write device state data to DynamoDB tables with IoT Rules.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-core/refs/heads/main/apis.yml
tags:
- Device Management
- IoT
- MQTT
- Message Routing
url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-core/refs/heads/main/apis.yml
use_cases:
- description: Connect factory equipment to AWS for real-time monitoring and predictive maintenance.
  name: Industrial IoT
- description: Build connected home devices with secure two-way communication.
  name: Smart Home
- description: Track vehicles, equipment, and assets with GPS and sensor data.
  name: Asset Tracking
---
