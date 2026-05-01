---
api_count: 1
api_specs:
- filename: amazon-data-lifecycle-manager-openapi.yml
  format: yaml
  label: Amazon Data Lifecycle Manager API
  slug: amazon-dlm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-data-lifecycle-manager/refs/heads/main/openapi/amazon-data-lifecycle-manager-openapi.yml
apis:
- description: The Amazon Data Lifecycle Manager API enables programmatic management of lifecycle policies for automating the creation, retention, and deletion of EBS snapshots and AMIs to meet backup and compliance
  name: Amazon Data Lifecycle Manager API
  slug: amazon-dlm-api
capabilities:
- description: ''
  name: Backup Automation Operations
  slug: backup-automation-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/ebs/data-lifecycle-manager/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/ebs/data-lifecycle-manager/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/dlm/
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
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/ec2/v2/home#Lifecycle
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
  url: rules/amazon-data-lifecycle-manager-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-data-lifecycle-manager-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/backup-automation-operations.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/data-lifecycle-manager.yaml
created: '2026-03-16'
description: Amazon Data Lifecycle Manager provides an automated way to manage the lifecycle of your AWS resources. Using lifecycle policies, you can automate the creation, retention, and deletion of Amazon EBS snapshots and EBS-backed AMIs, reducing storage costs and simplifying backup management. Policies target EBS volumes and EC2 instances using tags, execute on configurable schedules, and apply flexible retention rules based on count or age.
features:
- description: Automatically create, copy, and delete EBS snapshots on configurable schedules using tag-based targeting of volumes across AWS accounts.
  name: EBS Snapshot Automation
- description: Automate the creation and deregistration of Amazon Machine Images from EC2 instances on schedules to maintain a library of AMIs.
  name: AMI Lifecycle Management
- description: Retain snapshots by count (keep the last N) or by age (keep for N days/weeks/months/years), automatically deleting older snapshots.
  name: Flexible Retention Rules
- description: Target EBS volumes or EC2 instances using resource tags for policy scope, enabling granular backup control without managing resource lists.
  name: Tag-Based Targeting
- description: Configure schedules to copy snapshots to other AWS regions for disaster recovery and geographic redundancy automatically.
  name: Cross-Region Copy
- description: Enable fast snapshot restore on snapshots created by DLM policies to dramatically reduce EBS volume initialization time.
  name: Fast Snapshot Restore
- description: Trigger snapshot sharing and copying workflows in response to CloudWatch Events for cross-account snapshot automation.
  name: Event-Based Policies
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Amazon EBS for snapshot creation, retention, and deletion of volumes across the AWS account.
  name: Amazon EBS
- description: Target EC2 instances with IMAGE_MANAGEMENT policies to automate AMI creation from running or stopped instances.
  name: Amazon EC2
- description: Event-based DLM policies are triggered by Amazon CloudWatch Events for cross-account snapshot sharing scenarios.
  name: Amazon CloudWatch
- description: Complementary to DLM, AWS Backup provides centralized backup management across multiple AWS services including EBS, RDS, and DynamoDB.
  name: AWS Backup
- description: DLM uses IAM execution roles to assume permissions for creating and deleting snapshots on behalf of the lifecycle policy.
  name: AWS IAM
- description: Cross-account snapshot sharing policies use AWS Organizations to share EBS snapshots with member accounts automatically.
  name: AWS Organizations
jsonld:
- class_count: 0
  name: Amazon Data Lifecycle Manager Context
  property_count: 34
  slug: amazon-data-lifecycle-manager-context
layout: provider
modified: '2026-04-19'
name: Amazon Data Lifecycle Manager
rules:
- name: Amazon Data Lifecycle Manager API Rules
  rule_count: 21
  severity_counts:
    error: 13
    hint: 0
    info: 3
    warn: 5
  slug: amazon-data-lifecycle-manager-spectral-rules
skills: []
slug: amazon-data-lifecycle-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-data-lifecycle-manager\nname: Amazon Data Lifecycle Manager\ndescription: >-\n  Amazon Data Lifecycle Manager provides an automated way to manage the\n  lifecycle of your AWS resources. Using lifecycle policies, you can automate\n  the creation, retention, and deletion of Amazon EBS snapshots and EBS-backed\n  AMIs, reducing storage costs and simplifying backup management. Policies target\n  EBS volumes and EC2 instances using tags, execute on configurable schedules,\n  and apply flexible retention rules based on count or age.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Backup\n  - EBS Snapshots\n  - Lifecycle Management\n  - Storage\n  - Automation\n  - Compliance\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-data-lifecycle-manager/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-data-lifecycle-manager:amazon-dlm-api\n\
  \    name: Amazon Data Lifecycle Manager API\n    description: >-\n      The Amazon Data Lifecycle Manager API enables programmatic management of\n      lifecycle policies for automating the creation, retention, and deletion\n      of EBS snapshots and AMIs to meet backup and compliance requirements.\n      Supports EBS snapshot management, AMI lifecycle management, and\n      event-based snapshot policies.\n    humanURL: https://aws.amazon.com/ebs/data-lifecycle-manager/\n    baseURL: https://dlm.amazonaws.com\n    tags:\n      - Automation\n      - EBS Snapshots\n      - Lifecycle Management\n      - Backup\n      - AMI Management\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/dlm/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-data-lifecycle-manager-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/dlm/2018-01-12/openapi.yaml\n      - type: GettingStarted\n     \
  \   url: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/snapshot-lifecycle.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/dlm/latest/APIReference/\n      - type: JSONSchema\n        url: json-schema/lifecycle-policy-schema.json\n      - type: JSONSchema\n        url: json-schema/policy-details-schema.json\n      - type: JSONSchema\n        url: json-schema/schedule-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-data-lifecycle-manager-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/ebs/data-lifecycle-manager/\n  - type: DeveloperPortal\n    url: https://aws.amazon.com/ebs/data-lifecycle-manager/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/dlm/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n\
  \  - type: Console\n    url: https://console.aws.amazon.com/ec2/v2/home#Lifecycle\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-data-lifecycle-manager-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-data-lifecycle-manager-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/backup-automation-operations.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/data-lifecycle-manager.yaml\n  - type: Features\n    data:\n      - name: EBS Snapshot Automation\n        description: >-\n          Automatically create, copy, and delete EBS snapshots on configurable\n          schedules using tag-based targeting of volumes across AWS accounts.\n      - name: AMI Lifecycle Management\n\
  \        description: >-\n          Automate the creation and deregistration of Amazon Machine Images\n          from EC2 instances on schedules to maintain a library of AMIs.\n      - name: Flexible Retention Rules\n        description: >-\n          Retain snapshots by count (keep the last N) or by age (keep for N\n          days/weeks/months/years), automatically deleting older snapshots.\n      - name: Tag-Based Targeting\n        description: >-\n          Target EBS volumes or EC2 instances using resource tags for policy\n          scope, enabling granular backup control without managing resource lists.\n      - name: Cross-Region Copy\n        description: >-\n          Configure schedules to copy snapshots to other AWS regions for\n          disaster recovery and geographic redundancy automatically.\n      - name: Fast Snapshot Restore\n        description: >-\n          Enable fast snapshot restore on snapshots created by DLM policies\n          to dramatically reduce EBS volume\
  \ initialization time.\n      - name: Event-Based Policies\n        description: >-\n          Trigger snapshot sharing and copying workflows in response to\n          CloudWatch Events for cross-account snapshot automation.\n  - type: UseCases\n    data:\n      - name: Automated Daily Backups\n        description: >-\n          Schedule daily EBS volume snapshots with automated retention of the\n          last 7 or 30 days of backups without manual intervention.\n      - name: Compliance and Audit Retention\n        description: >-\n          Meet regulatory backup retention requirements by defining long-term\n          retention policies (monthly/yearly) for compliance snapshots.\n      - name: Disaster Recovery\n        description: >-\n          Automatically copy EBS snapshots to secondary AWS regions to enable\n          cross-region disaster recovery with minimal RTO and RPO.\n      - name: Golden AMI Pipeline\n        description: >-\n          Automate the creation of hardened\
  \ EC2 AMI images from approved\n          instances and manage their lifecycle for deployment fleets.\n      - name: Storage Cost Optimization\n        description: >-\n          Reduce EBS snapshot storage costs by automatically deleting outdated\n          snapshots based on configurable age or count retention rules.\n  - type: Integrations\n    data:\n      - name: Amazon EBS\n        description: >-\n          Native integration with Amazon EBS for snapshot creation, retention,\n          and deletion of volumes across the AWS account.\n      - name: Amazon EC2\n        description: >-\n          Target EC2 instances with IMAGE_MANAGEMENT policies to automate\n          AMI creation from running or stopped instances.\n      - name: Amazon CloudWatch\n        description: >-\n          Event-based DLM policies are triggered by Amazon CloudWatch Events\n          for cross-account snapshot sharing scenarios.\n      - name: AWS Backup\n        description: >-\n          Complementary\
  \ to DLM, AWS Backup provides centralized backup management\n          across multiple AWS services including EBS, RDS, and DynamoDB.\n      - name: AWS IAM\n        description: >-\n          DLM uses IAM execution roles to assume permissions for creating and\n          deleting snapshots on behalf of the lifecycle policy.\n      - name: AWS Organizations\n        description: >-\n          Cross-account snapshot sharing policies use AWS Organizations to\n          share EBS snapshots with member accounts automatically.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-lifecycle-manager/refs/heads/main/apis.yml
tags:
- Backup
- EBS Snapshots
- Lifecycle Management
- Storage
- Automation
- Compliance
url: https://raw.githubusercontent.com/api-evangelist/amazon-data-lifecycle-manager/refs/heads/main/apis.yml
use_cases:
- description: Schedule daily EBS volume snapshots with automated retention of the last 7 or 30 days of backups without manual intervention.
  name: Automated Daily Backups
- description: Meet regulatory backup retention requirements by defining long-term retention policies (monthly/yearly) for compliance snapshots.
  name: Compliance and Audit Retention
- description: Automatically copy EBS snapshots to secondary AWS regions to enable cross-region disaster recovery with minimal RTO and RPO.
  name: Disaster Recovery
- description: Automate the creation of hardened EC2 AMI images from approved instances and manage their lifecycle for deployment fleets.
  name: Golden AMI Pipeline
- description: Reduce EBS snapshot storage costs by automatically deleting outdated snapshots based on configurable age or count retention rules.
  name: Storage Cost Optimization
---
