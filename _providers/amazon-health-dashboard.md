---
api_count: 1
apis:
- description: The AWS Health API provides programmatic access to AWS Health information about events that can affect your AWS infrastructure, including service outages, planned maintenance, and account-specific not
  name: AWS Health API
  slug: aws-health-api
capabilities:
- description: Workflow capability for operations teams using AWS Health Dashboard to monitor AWS service health, track events affecting resources, and coordinate incident response to AWS infrastructure events.
  name: Amazon Health Dashboard Operations Monitoring
  slug: amazon-health-dashboard-operations-monitoring
common:
- title: ''
  type: Portal
  url: https://health.aws.amazon.com/health/home
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/health/
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
  url: https://aws.amazon.com/blogs/mt/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/health/
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
  url: rules/amazon-health-dashboard-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-health-dashboard-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-health-dashboard-operations-monitoring.yaml
created: '2026-03-16'
description: AWS Health Dashboard provides ongoing visibility into the status of your AWS services, and alerts and remediation guidance when AWS is experiencing events that may affect your operations. It delivers personalized information about events that might affect your specific AWS resources and accounts.
features:
- description: Receive alerts specifically tailored to the AWS services and resources you use in your accounts.
  name: Personalized Health Notifications
- description: Get advance notice of AWS planned maintenance, deprecations, and service changes before they occur.
  name: Proactive Event Notifications
- description: Each health event includes specific guidance on what actions to take to minimize impact.
  name: Remediation Guidance
- description: View health events across all accounts in an AWS Organization from a single management account.
  name: Organization-Wide Visibility
- description: Identify exactly which of your specific EC2 instances, RDS databases, or other resources are impacted.
  name: Affected Resource Identification
- description: Access up to 90 days of event history for your account.
  name: Event History
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Receive health events as EventBridge events and trigger automated Lambda responses.
  name: Amazon EventBridge
- description: View health events across all member accounts in an organization.
  name: AWS Organizations
- description: Health events link directly to AWS Support cases for faster resolution.
  name: AWS Support
- description: Create CloudWatch alarms based on health event metrics.
  name: Amazon CloudWatch
- description: Receive health notifications in Slack or Chime via AWS Chatbot.
  name: AWS Chatbot
jsonld:
- class_count: 39
  name: Amazon Health Dashboard Context
  property_count: 57
  slug: amazon-health-dashboard-context
layout: provider
modified: '2026-04-19'
name: Amazon Health Dashboard
rules:
- name: Amazon Health Dashboard API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 2
  slug: amazon-health-dashboard-spectral-rules
skills: []
slug: amazon-health-dashboard
solutions: []
source_yaml: "aid: amazon-health-dashboard\nname: Amazon Health Dashboard\ndescription: >-\n  AWS Health Dashboard provides ongoing visibility into the status of your AWS\n  services, and alerts and remediation guidance when AWS is experiencing events\n  that may affect your operations. It delivers personalized information about\n  events that might affect your specific AWS resources and accounts.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Health Monitoring\n  - Notifications\n  - Operations\n  - Service Status\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-health-dashboard/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-health-dashboard:aws-health-api\n    name: AWS Health API\n    description: >-\n      The AWS Health API provides programmatic access to AWS Health information\n      about events that can affect your\
  \ AWS infrastructure, including service\n      outages, planned maintenance, and account-specific notifications.\n    humanURL: https://aws.amazon.com/health/\n    baseURL: https://health.us-east-1.amazonaws.com\n    tags:\n      - Health Monitoring\n      - Notifications\n      - Operations\n      - Service Status\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/health/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-health-dashboard-openapi.yaml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/health/latest/ug/getting-started-api.html\n      - type: Pricing\n        url: https://aws.amazon.com/premiumsupport/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/health/latest/APIReference/Welcome.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html\n      - type: JSONSchema\n        url: json-schema/health-event-schema.json\n\
  \      - type: JSONLD\n        url: json-ld/amazon-health-dashboard-context.jsonld\ncommon:\n  - type: Portal\n    url: https://health.aws.amazon.com/health/home\n  - type: Documentation\n    url: https://docs.aws.amazon.com/health/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/mt/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/health/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-health-dashboard-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-health-dashboard-vocabulary.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/amazon-health-dashboard-operations-monitoring.yaml\n  - type: Features\n    data:\n      - name: Personalized Health Notifications\n        description: Receive alerts specifically tailored to the AWS services and resources you use in your accounts.\n      - name: Proactive Event Notifications\n        description: Get advance notice of AWS planned maintenance, deprecations, and service changes before they occur.\n      - name: Remediation Guidance\n        description: Each health event includes specific guidance on what actions to take to minimize impact.\n      - name: Organization-Wide Visibility\n        description: View health events across all accounts in an AWS Organization from a single management account.\n      - name: Affected Resource Identification\n        description: Identify exactly which of your specific EC2 instances, RDS databases, or other resources are impacted.\n      - name: Event History\n        description:\
  \ Access up to 90 days of event history for your account.\n  - type: UseCases\n    data:\n      - name: Operations Monitoring\n        description: Monitor AWS service health in real-time to detect and respond to events affecting workloads.\n      - name: Automated Incident Response\n        description: Trigger automated runbooks when health events affect specific resources using EventBridge.\n      - name: Change Management\n        description: Track planned maintenance and scheduled changes to coordinate deployments.\n      - name: Compliance Reporting\n        description: Maintain records of AWS service events for compliance and audit purposes.\n  - type: Integrations\n    data:\n      - name: Amazon EventBridge\n        description: Receive health events as EventBridge events and trigger automated Lambda responses.\n      - name: AWS Organizations\n        description: View health events across all member accounts in an organization.\n      - name: AWS Support\n        description:\
  \ Health events link directly to AWS Support cases for faster resolution.\n      - name: Amazon CloudWatch\n        description: Create CloudWatch alarms based on health event metrics.\n      - name: AWS Chatbot\n        description: Receive health notifications in Slack or Chime via AWS Chatbot.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-health-dashboard/refs/heads/main/apis.yml
tags:
- AWS
- Health Monitoring
- Notifications
- Operations
- Service Status
url: https://raw.githubusercontent.com/api-evangelist/amazon-health-dashboard/refs/heads/main/apis.yml
use_cases:
- description: Monitor AWS service health in real-time to detect and respond to events affecting workloads.
  name: Operations Monitoring
- description: Trigger automated runbooks when health events affect specific resources using EventBridge.
  name: Automated Incident Response
- description: Track planned maintenance and scheduled changes to coordinate deployments.
  name: Change Management
- description: Maintain records of AWS service events for compliance and audit purposes.
  name: Compliance Reporting
---
