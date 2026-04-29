---
api_count: 1
api_specs:
- filename: amazon-iot-device-defender-openapi-original.yml
  format: yaml
  label: AWS IoT Device Defender API
  slug: aws-iot-defender-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-defender/refs/heads/main/openapi/amazon-iot-device-defender-openapi-original.yml
apis:
- description: The AWS IoT Device Defender API provides programmatic access to security profiles, audit configurations, anomaly detection, and violation management for IoT fleet security.
  name: AWS IoT Device Defender API
  slug: aws-iot-defender-api
capabilities:
- description: Unified capability for Security Engineer, IoT Developer to manage security service for iot fleet auditing and anomaly detection operations.
  name: Amazon IoT Device Defender - Iot Security Monitoring
  slug: iot-security-monitoring
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iot-device-defender/
- title: ''
  type: Website
  url: https://aws.amazon.com/iot-device-defender/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/iot/latest/developerguide/device-defender.html
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
  url: https://aws.amazon.com/blogs/iot/tag/aws-iot-device-defender/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/iot/home#/devicedefender
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
  url: rules/amazon-iot-device-defender-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iot-device-defender.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/iot-security-monitoring.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iot-device-defender-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iot-device-defender-context.jsonld
created: '2026-03-16'
description: AWS IoT Device Defender is a security service that lets you continuously audit your IoT configurations to detect deviations from security best practices. It also lets you detect abnormal device behavior through ML-based anomaly detection and take actions to mitigate security risks.
features:
- description: Continuously audit IoT configurations against security best practices.
  name: Configuration Audit
- description: Detect abnormal device behavior using machine learning models.
  name: ML Anomaly Detection
- description: Define expected behaviors for device metrics and receive alerts on violations.
  name: Security Profiles
- description: Automatically take actions to mitigate security violations.
  name: Automated Mitigation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Monitors all IoT Core device connections and policies.
  name: AWS IoT Core
- description: Sends security metrics and alerts to CloudWatch.
  name: Amazon CloudWatch
- description: Publishes IoT security findings to Security Hub.
  name: AWS Security Hub
jsonld:
- class_count: 102
  name: Amazon Iot Device Defender Context
  property_count: 266
  slug: amazon-iot-device-defender-context
layout: provider
modified: '2026-04-19'
name: Amazon IoT Device Defender
rules:
- name: Amazon IoT Device Defender API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 5
  slug: amazon-iot-device-defender-spectral-rules
skills: []
slug: amazon-iot-device-defender
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-iot-device-defender\nname: Amazon IoT Device Defender\ndescription: >-\n  AWS IoT Device Defender is a security service that lets you continuously audit your IoT configurations to detect deviations from security best practices. It also lets you detect abnormal device behavior through ML-based anomaly detection and take actions to mitigate security risks.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Compliance\n  - IoT\n  - Security\n  - Vulnerability Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-defender/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iot-device-defender:aws-iot-defender-api\n    name: AWS IoT Device Defender API\n    description: >-\n      The AWS IoT Device Defender API provides programmatic access to security profiles, audit configurations, anomaly detection,\
  \ and violation management for IoT fleet security.\n    humanURL: https://aws.amazon.com/iot-device-defender/\n    baseURL: https://iot.amazonaws.com\n    tags:\n      - Compliance\n      - IoT\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/iot/latest/developerguide/device-defender.html\n      - type: OpenAPI\n        url: openapi/amazon-iot-device-defender-openapi-original.yml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/iot/latest/developerguide/device-defender-getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/iot-device-defender/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iot-device-defender/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iot-device-defender/\n  - type: Website\n    url: https://aws.amazon.com/iot-device-defender/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/iot/latest/developerguide/device-defender.html\n\
  \  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/iot/tag/aws-iot-device-defender/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/iot/home#/devicedefender\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iot-device-defender-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iot-device-defender.yaml\n  - type: NaftikoCapability\n    url: capabilities/iot-security-monitoring.yaml\n  - type: Vocabulary\n    url:\
  \ vocabulary/amazon-iot-device-defender-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/amazon-iot-device-defender-context.jsonld\n  - type: Features\n    data:\n      - name: Configuration Audit\n        description: Continuously audit IoT configurations against security best practices.\n      - name: ML Anomaly Detection\n        description: Detect abnormal device behavior using machine learning models.\n      - name: Security Profiles\n        description: Define expected behaviors for device metrics and receive alerts on violations.\n      - name: Automated Mitigation\n        description: Automatically take actions to mitigate security violations.\n  - type: UseCases\n    data:\n      - name: IoT Compliance\n        description: Ensure IoT deployments meet security compliance requirements.\n      - name: Threat Detection\n        description: Detect compromised devices exhibiting abnormal communication patterns.\n      - name: Security Auditing\n        description: Audit IoT\
  \ policies and certificates against security best practices.\n  - type: Integrations\n    data:\n      - name: AWS IoT Core\n        description: Monitors all IoT Core device connections and policies.\n      - name: Amazon CloudWatch\n        description: Sends security metrics and alerts to CloudWatch.\n      - name: AWS Security Hub\n        description: Publishes IoT security findings to Security Hub.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-defender/refs/heads/main/apis.yml
tags:
- AWS
- Compliance
- IoT
- Security
- Vulnerability Management
url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-defender/refs/heads/main/apis.yml
use_cases:
- description: Ensure IoT deployments meet security compliance requirements.
  name: IoT Compliance
- description: Detect compromised devices exhibiting abnormal communication patterns.
  name: Threat Detection
- description: Audit IoT policies and certificates against security best practices.
  name: Security Auditing
---
