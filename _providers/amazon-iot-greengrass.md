---
api_count: 1
api_specs:
- filename: amazon-iot-greengrass-openapi-original.yml
  format: yaml
  label: AWS IoT Greengrass API
  slug: aws-iot-greengrass-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-greengrass/refs/heads/main/openapi/amazon-iot-greengrass-openapi-original.yml
apis:
- description: The AWS IoT Greengrass V2 API provides access to component management, core device management, and deployment orchestration for edge computing workloads.
  name: AWS IoT Greengrass API
  slug: aws-iot-greengrass-api
capabilities:
- description: Unified capability for IoT Developer, Edge Computing Engineer to manage extend aws compute and services to edge devices operations.
  name: Amazon IoT Greengrass - Edge Device Management
  slug: edge-device-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/greengrass/
- title: ''
  type: Website
  url: https://aws.amazon.com/greengrass/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/greengrass/v2/developerguide/
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
  url: https://aws.amazon.com/blogs/iot/tag/aws-iot-greengrass/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/greengrass/
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
  url: rules/amazon-iot-greengrass-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iot-greengrass.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/edge-device-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iot-greengrass-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iot-greengrass-context.jsonld
created: '2026-03-16'
description: AWS IoT Greengrass extends AWS compute, messaging, data management, sync, and ML inference capabilities to edge devices so they can act locally on the data they generate, while still using the cloud for management, analytics, and durable storage.
features:
- description: Run Lambda functions and containers on edge devices with local compute.
  name: Edge Computing
- description: Deploy reusable software components to edge devices from a component catalog.
  name: Component System
- description: Run machine learning inference locally with SageMaker model deployment.
  name: Local ML Inference
- description: Deploy and update software components to thousands of edge devices.
  name: Deployment Management
- description: Enable MQTT messaging between local IoT devices without cloud round-trips.
  name: Local Messaging
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Run Lambda functions on edge devices for local processing.
  name: AWS Lambda
- description: Deploy trained ML models to edge devices for local inference.
  name: Amazon SageMaker
- description: Syncs device state and routes messages between edge and cloud.
  name: AWS IoT Core
jsonld:
- class_count: 102
  name: Amazon Iot Greengrass Context
  property_count: 133
  slug: amazon-iot-greengrass-context
layout: provider
modified: '2026-04-19'
name: Amazon IoT Greengrass
rules:
- name: Amazon IoT Greengrass API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 5
  slug: amazon-iot-greengrass-spectral-rules
skills: []
slug: amazon-iot-greengrass
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-iot-greengrass\nname: Amazon IoT Greengrass\ndescription: >-\n  AWS IoT Greengrass extends AWS compute, messaging, data management, sync, and ML inference capabilities to edge devices so they can act locally on the data they generate, while still using the cloud for management, analytics, and durable storage.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Edge Computing\n  - IoT\n  - Lambda\n  - Machine Learning\n  - Real-Time Processing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iot-greengrass/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iot-greengrass:aws-iot-greengrass-api\n    name: AWS IoT Greengrass API\n    description: >-\n      The AWS IoT Greengrass V2 API provides access to component management, core device management, and deployment orchestration for edge computing workloads.\n\
  \    humanURL: https://aws.amazon.com/greengrass/\n    baseURL: https://greengrass.amazonaws.com\n    tags:\n      - Edge Computing\n      - IoT\n      - Lambda\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/greengrass/v2/APIReference/\n      - type: OpenAPI\n        url: openapi/amazon-iot-greengrass-openapi-original.yml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/greengrass/v2/developerguide/getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/greengrass/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/greengrass/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/greengrass/\n  - type: Website\n    url: https://aws.amazon.com/greengrass/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/greengrass/v2/developerguide/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n\
  \  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/iot/tag/aws-iot-greengrass/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/greengrass/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iot-greengrass-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iot-greengrass.yaml\n  - type: NaftikoCapability\n    url: capabilities/edge-device-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iot-greengrass-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/amazon-iot-greengrass-context.jsonld\n  - type: Features\n    data:\n      - name: Edge\
  \ Computing\n        description: Run Lambda functions and containers on edge devices with local compute.\n      - name: Component System\n        description: Deploy reusable software components to edge devices from a component catalog.\n      - name: Local ML Inference\n        description: Run machine learning inference locally with SageMaker model deployment.\n      - name: Deployment Management\n        description: Deploy and update software components to thousands of edge devices.\n      - name: Local Messaging\n        description: Enable MQTT messaging between local IoT devices without cloud round-trips.\n  - type: UseCases\n    data:\n      - name: Industrial Edge Processing\n        description: Process sensor data locally to reduce latency and bandwidth.\n      - name: Edge ML Inference\n        description: Run computer vision and anomaly detection models at the edge.\n      - name: Offline Operation\n        description: Continue processing and storing data when disconnected\
  \ from the cloud.\n  - type: Integrations\n    data:\n      - name: AWS Lambda\n        description: Run Lambda functions on edge devices for local processing.\n      - name: Amazon SageMaker\n        description: Deploy trained ML models to edge devices for local inference.\n      - name: AWS IoT Core\n        description: Syncs device state and routes messages between edge and cloud.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-greengrass/refs/heads/main/apis.yml
tags:
- Edge Computing
- IoT
- Lambda
- Machine Learning
- Real-Time Processing
url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-greengrass/refs/heads/main/apis.yml
use_cases:
- description: Process sensor data locally to reduce latency and bandwidth.
  name: Industrial Edge Processing
- description: Run computer vision and anomaly detection models at the edge.
  name: Edge ML Inference
- description: Continue processing and storing data when disconnected from the cloud.
  name: Offline Operation
---
