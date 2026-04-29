---
api_count: 1
apis:
- description: The AWS IoT Events API provides access to detector models, inputs, alarms, and event detection configurations for building IoT event-driven workflows.
  name: AWS IoT Events API
  slug: aws-iot-events-api
capabilities:
- description: Unified capability for IoT Developer, Solutions Architect to manage detect and respond to events from iot sensors and applications operations.
  name: Amazon IoT Events - Iot Event Management
  slug: iot-event-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iot-events/
- title: ''
  type: Website
  url: https://aws.amazon.com/iot-events/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/iotevents/
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
  url: https://aws.amazon.com/blogs/iot/tag/aws-iot-events/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/iotevents/
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
  url: rules/amazon-iot-events-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iot-events.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/iot-event-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iot-events-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iot-events-context.jsonld
created: '2026-03-16'
description: AWS IoT Events is a managed service that makes it easy to detect and respond to events from IoT sensors and applications. You can use it to build complex event detection logic, create state machines for IoT workflows, and trigger alerts or actions when specific conditions are met.
features:
- description: Create state machines to detect complex event patterns across IoT data streams.
  name: Detector Models
- description: Built-in alarm management for monitoring IoT sensor thresholds.
  name: Alarm Management
- description: Define structured event inputs and route IoT data to detector models.
  name: Event Inputs
- description: Trigger actions to SNS, SQS, Lambda, and other services when events are detected.
  name: Multi-Trigger Actions
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Receives message data from IoT Core for event detection.
  name: AWS IoT Core
- description: Sends alerts and notifications when events are detected.
  name: Amazon SNS
- description: Triggers Lambda functions to execute response workflows.
  name: AWS Lambda
jsonld:
- class_count: 101
  name: Amazon Iot Events Context
  property_count: 141
  slug: amazon-iot-events-context
layout: provider
modified: '2026-04-19'
name: Amazon IoT Events
rules:
- name: Amazon IoT Events API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 5
  slug: amazon-iot-events-spectral-rules
skills: []
slug: amazon-iot-events
solutions: []
source_yaml: "aid: amazon-iot-events\nname: Amazon IoT Events\ndescription: >-\n  AWS IoT Events is a managed service that makes it easy to detect and respond to events from IoT sensors and applications. You can use it to build complex event detection logic, create state machines for IoT workflows, and trigger alerts or actions when specific conditions are met.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Event Detection\n  - IoT\n  - State Machine\n  - Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iot-events/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iot-events:aws-iot-events-api\n    name: AWS IoT Events API\n    description: >-\n      The AWS IoT Events API provides access to detector models, inputs, alarms, and event detection configurations for building IoT event-driven workflows.\n    humanURL: https://aws.amazon.com/iot-events/\n\
  \    baseURL: https://iotevents.amazonaws.com\n    tags:\n      - Event Detection\n      - IoT\n      - State Machine\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/iotevents/latest/apireference/\n      - type: OpenAPI\n        url: openapi/amazon-iot-events-openapi-original.yml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/iotevents/latest/developerguide/getting-started-iotevents.html\n      - type: Pricing\n        url: https://aws.amazon.com/iot-events/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iot-events/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iot-events/\n  - type: Website\n    url: https://aws.amazon.com/iot-events/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/iotevents/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n\
  \  - type: Blog\n    url: https://aws.amazon.com/blogs/iot/tag/aws-iot-events/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/iotevents/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iot-events-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iot-events.yaml\n  - type: NaftikoCapability\n    url: capabilities/iot-event-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iot-events-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/amazon-iot-events-context.jsonld\n  - type: Features\n    data:\n      - name: Detector Models\n        description: Create state machines to detect complex event patterns\
  \ across IoT data streams.\n      - name: Alarm Management\n        description: Built-in alarm management for monitoring IoT sensor thresholds.\n      - name: Event Inputs\n        description: Define structured event inputs and route IoT data to detector models.\n      - name: Multi-Trigger Actions\n        description: Trigger actions to SNS, SQS, Lambda, and other services when events are detected.\n  - type: UseCases\n    data:\n      - name: Industrial Alarm Management\n        description: Detect equipment failures and trigger maintenance workflows automatically.\n      - name: Complex Event Processing\n        description: Detect patterns across multiple sensor streams over time.\n      - name: Predictive Maintenance\n        description: Alert operations teams when device metrics indicate impending failure.\n  - type: Integrations\n    data:\n      - name: AWS IoT Core\n        description: Receives message data from IoT Core for event detection.\n      - name: Amazon SNS\n  \
  \      description: Sends alerts and notifications when events are detected.\n      - name: AWS Lambda\n        description: Triggers Lambda functions to execute response workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-events/refs/heads/main/apis.yml
tags:
- AWS
- Event Detection
- IoT
- State Machine
- Automation
url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-events/refs/heads/main/apis.yml
use_cases:
- description: Detect equipment failures and trigger maintenance workflows automatically.
  name: Industrial Alarm Management
- description: Detect patterns across multiple sensor streams over time.
  name: Complex Event Processing
- description: Alert operations teams when device metrics indicate impending failure.
  name: Predictive Maintenance
---
