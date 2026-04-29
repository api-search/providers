---
api_count: 1
api_specs:
- filename: amazon-monitron-openapi-original.yml
  format: yaml
  label: Amazon Monitron API
  slug: monitron-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-monitron/refs/heads/main/openapi/amazon-monitron-openapi-original.yml
apis:
- description: Amazon Monitron is an end-to-end system that uses machine learning to detect abnormal behavior in industrial machinery. It includes sensors, a gateway, and the Monitron mobile app to enable predictive
  name: Amazon Monitron API
  slug: monitron-api
capabilities:
- description: Workflow capability for Amazon Monitron media processing operations for broadcast engineers and media developers.
  name: Amazon Monitron Workflow
  slug: amazon-monitron-media-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/monitron/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/monitron/
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
  url: https://aws.amazon.com/blogs/media/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/monitron/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-monitron-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-monitron-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-monitron-media-workflow.yaml
created: '2026-03-16'
description: Amazon Monitron is an end-to-end system that uses machine learning to detect abnormal behavior in industrial machinery. It includes sensors, a gateway, and the Monitron mobile app to enable predictive maintenance and reduce unplanned downtime.
features:
- description: Machine learning models trained on industrial machinery data to detect abnormal behavior automatically.
  name: ML-Based Anomaly Detection
- description: Organize machine monitoring deployments into projects with access control.
  name: Project Management
- description: Integrated hardware sensors, gateway, cloud processing, and mobile app in one solution.
  name: End-to-End System
- description: Identify potential equipment failures before they occur to schedule proactive maintenance.
  name: Predictive Maintenance
- description: Manage project administrators and user associations with fine-grained permissions.
  name: User Access Control
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Monitron gateway connects to the cloud via AWS IoT Core.
  name: AWS IoT Core
- description: Stream Monitron measurement data to Kinesis for real-time analytics.
  name: Amazon Kinesis
- description: Export historical sensor data to S3 for long-term analysis.
  name: Amazon S3
- description: Control API access and project permissions with IAM policies.
  name: AWS IAM
jsonld:
- class_count: 6
  name: Amazon Monitron Monitron Api Context
  property_count: 10
  slug: amazon-monitron-monitron-api-context
layout: provider
modified: '2026-04-19'
name: Amazon Monitron
rules:
- name: Amazon Monitron API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: amazon-monitron-spectral-rules
skills: []
slug: amazon-monitron
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-monitron\nname: Amazon Monitron\ndescription: Amazon Monitron is an end-to-end system that uses machine learning to detect abnormal behavior in industrial machinery. It includes sensors, a gateway, and the Monitron mobile app to \n  enable predictive maintenance and reduce unplanned downtime.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Broadcasting\n- Media Processing\n- Media\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-monitron/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-monitron:monitron-api\n  name: Amazon Monitron API\n  description: Amazon Monitron is an end-to-end system that uses machine learning to detect abnormal behavior in industrial machinery. It includes sensors, a gateway, and the Monitron mobile app to \n    enable predictive maintenance and reduce unplanned downtime.\n  humanURL: https://aws.amazon.com/monitron/\n\
  \  baseURL: https://monitron.us-east-1.amazonaws.com\n  tags:\n  - Broadcasting\n  - Media Processing\n  - Media\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/monitron/\n  - type: OpenAPI\n    url: openapi/amazon-monitron-openapi-original.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/monitron/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/monitron/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/monitron/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/monitron/\n- type: Documentation\n  url: https://docs.aws.amazon.com/monitron/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/media/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/monitron/\n\
  - type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-monitron-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-monitron-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-monitron-media-workflow.yaml\n- type: Features\n  data:\n  - name: ML-Based Anomaly Detection\n    description: Machine learning models trained on industrial machinery data to detect abnormal behavior automatically.\n  - name: Project Management\n    description: Organize machine monitoring deployments into projects with access control.\n  - name: End-to-End System\n    description: Integrated hardware sensors, gateway, cloud processing, and mobile app in one solution.\n  - name: Predictive Maintenance\n    description: Identify potential equipment failures before they occur to schedule proactive\
  \ maintenance.\n  - name: User Access Control\n    description: Manage project administrators and user associations with fine-grained permissions.\n- type: UseCases\n  data:\n  - name: Industrial Equipment Monitoring\n    description: Monitor motors, pumps, fans, and compressors for early signs of failure.\n  - name: Predictive Maintenance Programs\n    description: Build data-driven maintenance schedules based on actual equipment health.\n  - name: Downtime Reduction\n    description: Reduce unplanned production downtime by catching issues before equipment fails.\n  - name: Plant-Wide Monitoring\n    description: Deploy sensors across entire manufacturing facilities for comprehensive asset health.\n- type: Integrations\n  data:\n  - name: AWS IoT Core\n    description: Monitron gateway connects to the cloud via AWS IoT Core.\n  - name: Amazon Kinesis\n    description: Stream Monitron measurement data to Kinesis for real-time analytics.\n  - name: Amazon S3\n    description: Export historical\
  \ sensor data to S3 for long-term analysis.\n  - name: AWS IAM\n    description: Control API access and project permissions with IAM policies.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-monitron/refs/heads/main/apis.yml
tags:
- AWS
- Broadcasting
- Media Processing
- Media
url: https://raw.githubusercontent.com/api-evangelist/amazon-monitron/refs/heads/main/apis.yml
use_cases:
- description: Monitor motors, pumps, fans, and compressors for early signs of failure.
  name: Industrial Equipment Monitoring
- description: Build data-driven maintenance schedules based on actual equipment health.
  name: Predictive Maintenance Programs
- description: Reduce unplanned production downtime by catching issues before equipment fails.
  name: Downtime Reduction
- description: Deploy sensors across entire manufacturing facilities for comprehensive asset health.
  name: Plant-Wide Monitoring
---
