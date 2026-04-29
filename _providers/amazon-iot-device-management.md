---
api_count: 1
apis:
- description: The AWS IoT Device Management API provides access to thing groups, jobs, bulk registration, fleet indexing, and remote device management capabilities.
  name: AWS IoT Device Management API
  slug: aws-iot-management-api
capabilities:
- description: Unified capability for IoT Engineer, Operations Engineer to manage onboard, organize, and manage iot devices at scale operations.
  name: Amazon IoT Device Management - Iot Fleet Management
  slug: iot-fleet-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iot-device-management/
- title: ''
  type: Website
  url: https://aws.amazon.com/iot-device-management/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/iot/latest/developerguide/iot-thing-management.html
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
  url: rules/amazon-iot-device-management-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iot-device-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/iot-fleet-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iot-device-management-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iot-device-management-context.jsonld
created: '2026-03-16'
description: AWS IoT Device Management makes it easy to securely onboard, organize, monitor, and remotely manage your IoT devices at scale. You can register your connected devices individually or in bulk, and easily manage permissions so your devices remain secure throughout their lifecycle.
features:
- description: Register thousands of devices simultaneously using bulk registration templates.
  name: Bulk Device Registration
- description: Search and query your entire device fleet based on attributes and shadow state.
  name: Fleet Indexing
- description: Deploy firmware updates, configuration changes, and software remotely at scale.
  name: Remote Jobs
- description: Organize devices into hierarchical groups for policies and bulk operations.
  name: Thing Groups
- description: Create secure bidirectional tunnels to devices behind firewalls for remote troubleshooting.
  name: Tunnel Secure
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: All device management operations integrate with IoT Core connectivity.
  name: AWS IoT Core
- description: Trigger automation workflows based on job status changes.
  name: AWS Lambda
- description: Store firmware and configuration files for remote deployment.
  name: Amazon S3
jsonld:
- class_count: 102
  name: Amazon Iot Device Management Context
  property_count: 266
  slug: amazon-iot-device-management-context
layout: provider
modified: '2026-04-19'
name: Amazon IoT Device Management
rules:
- name: Amazon IoT Device Management API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 5
  slug: amazon-iot-device-management-spectral-rules
skills: []
slug: amazon-iot-device-management
solutions: []
source_yaml: "aid: amazon-iot-device-management\nname: Amazon IoT Device Management\ndescription: >-\n  AWS IoT Device Management makes it easy to securely onboard, organize, monitor, and remotely manage your IoT devices at scale. You can register your connected devices individually or in bulk, and easily manage permissions so your devices remain secure throughout their lifecycle.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Device Management\n  - Fleet Management\n  - IoT\n  - OTA Updates\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-management/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iot-device-management:aws-iot-management-api\n    name: AWS IoT Device Management API\n    description: >-\n      The AWS IoT Device Management API provides access to thing groups, jobs, bulk registration, fleet indexing,\
  \ and remote device management capabilities.\n    humanURL: https://aws.amazon.com/iot-device-management/\n    baseURL: https://iot.amazonaws.com\n    tags:\n      - Device Management\n      - Fleet Management\n      - IoT\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/iot/latest/developerguide/iot-jobs.html\n      - type: OpenAPI\n        url: openapi/amazon-iot-device-management-openapi-original.yml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/iot/latest/developerguide/iot-thing-management.html\n      - type: Pricing\n        url: https://aws.amazon.com/iot-device-management/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iot-device-management/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iot-device-management/\n  - type: Website\n    url: https://aws.amazon.com/iot-device-management/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/iot/latest/developerguide/iot-thing-management.html\n\
  \  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/iot/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/iot/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iot-device-management-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iot-device-management.yaml\n  - type: NaftikoCapability\n    url: capabilities/iot-fleet-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iot-device-management-vocabulary.yaml\n\
  \  - type: JSONLD\n    url: json-ld/amazon-iot-device-management-context.jsonld\n  - type: Features\n    data:\n      - name: Bulk Device Registration\n        description: Register thousands of devices simultaneously using bulk registration templates.\n      - name: Fleet Indexing\n        description: Search and query your entire device fleet based on attributes and shadow state.\n      - name: Remote Jobs\n        description: Deploy firmware updates, configuration changes, and software remotely at scale.\n      - name: Thing Groups\n        description: Organize devices into hierarchical groups for policies and bulk operations.\n      - name: Tunnel Secure\n        description: Create secure bidirectional tunnels to devices behind firewalls for remote troubleshooting.\n  - type: UseCases\n    data:\n      - name: OTA Firmware Updates\n        description: Deploy firmware updates to thousands of devices simultaneously with rollback.\n      - name: Device Onboarding\n        description:\
  \ Automate device provisioning and certificate management at manufacturing.\n      - name: Fleet Monitoring\n        description: Monitor device connectivity, metadata, and shadow state across the entire fleet.\n  - type: Integrations\n    data:\n      - name: AWS IoT Core\n        description: All device management operations integrate with IoT Core connectivity.\n      - name: AWS Lambda\n        description: Trigger automation workflows based on job status changes.\n      - name: Amazon S3\n        description: Store firmware and configuration files for remote deployment.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-management/refs/heads/main/apis.yml
tags:
- AWS
- Device Management
- Fleet Management
- IoT
- OTA Updates
url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-management/refs/heads/main/apis.yml
use_cases:
- description: Deploy firmware updates to thousands of devices simultaneously with rollback.
  name: OTA Firmware Updates
- description: Automate device provisioning and certificate management at manufacturing.
  name: Device Onboarding
- description: Monitor device connectivity, metadata, and shadow state across the entire fleet.
  name: Fleet Monitoring
---
