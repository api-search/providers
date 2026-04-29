---
api_count: 1
api_specs:
- filename: amazon-snow-family.yaml
  format: yaml
  label: AWS Snow Device Management API
  slug: aws-snow-device-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-snow-family/refs/heads/main/openapi/amazon-snow-family.yaml
apis:
- description: The AWS Snow Device Management API provides programmatic access to manage Snow device jobs, tasks, device resources, and network configurations for edge computing and data transfer operations.
  name: AWS Snow Device Management API
  slug: aws-snow-device-management-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/snowball/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/snowball/latest/developer-guide/api-reference.html
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
  url: https://aws.amazon.com/blogs/storage/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/snowball/
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
  url: rules/amazon-snow-family-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-snow-family-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-snow-family.yaml
created: '2026-03-16'
description: AWS Snow Family is a collection of physical devices and capacity points that help customers with data transfers in and out of AWS when network capacity is limited or unavailable. It includes Snowcone, Snowball, and Snowmobile devices for edge computing and offline data migration.
features:
- description: Transfer large datasets to AWS using physical devices.
  name: Petabyte-scale Data Transfer
- description: Run compute workloads at the edge with Snowball Edge and Snowcone.
  name: Edge Computing
- description: Use multiple Snow Family devices as a cluster for more storage and compute.
  name: Cluster Mode
- description: All data is automatically encrypted with 256-bit encryption.
  name: Encryption
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Transfer data directly to S3 buckets using Snow devices.
  name: Amazon S3
- description: Run IoT Greengrass on Snowball Edge for edge IoT workloads.
  name: AWS IoT Greengrass
- description: Run EC2 compute instances on Snowball Edge devices.
  name: Amazon EC2
- description: Use DataSync with Snow Family for accelerated data transfer.
  name: AWS DataSync
jsonld:
- class_count: 77
  name: Amazon Snow Family Context
  property_count: 122
  slug: amazon-snow-family-context
layout: provider
modified: '2026-04-19'
name: Amazon Snow Family
rules:
- name: Amazon Snow Family API Rules
  rule_count: 19
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 7
  slug: amazon-snow-family-spectral-rules
skills: []
slug: amazon-snow-family
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-snow-family\nname: Amazon Snow Family\ndescription: >-\n  AWS Snow Family is a collection of physical devices and capacity points that\n  help customers with data transfers in and out of AWS when network capacity is\n  limited or unavailable. It includes Snowcone, Snowball, and Snowmobile\n  devices for edge computing and offline data migration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Data Migration\n- Edge Computing\n- Offline Transfer\n- Physical Appliance\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-snow-family/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-snow-family:aws-snow-device-management-api\n  name: AWS Snow Device Management API\n  description: >-\n    The AWS Snow Device Management API provides programmatic access to manage\n    Snow device jobs, tasks, device resources, and network\
  \ configurations\n    for edge computing and data transfer operations.\n  humanURL: https://aws.amazon.com/snow/\n  baseURL: https://snow-device-management.amazonaws.com\n  tags:\n  - Data Migration\n  - Edge Computing\n  - Physical Appliance\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/snowball/latest/developer-guide/api-reference.html\n  - type: OpenAPI\n    url: openapi/amazon-snow-family.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/snowball/\n  - type: Pricing\n    url: https://aws.amazon.com/snowball/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/snowball/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/snowball/\n- type: Documentation\n  url: https://docs.aws.amazon.com/snowball/latest/developer-guide/api-reference.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n\
  - type: Blog\n  url: https://aws.amazon.com/blogs/storage/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/snowball/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-snow-family-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-snow-family-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-snow-family.yaml\n- type: Features\n  data:\n  - name: Petabyte-scale Data Transfer\n    description: Transfer large datasets to AWS using physical devices.\n  - name: Edge Computing\n    description: Run compute workloads at the edge with Snowball Edge and Snowcone.\n  - name: Cluster Mode\n    description: Use multiple Snow Family devices as a cluster\
  \ for more storage and compute.\n  - name: Encryption\n    description: All data is automatically encrypted with 256-bit encryption.\n- type: UseCases\n  data:\n  - name: Large Data Migration\n    description: Migrate terabytes to petabytes of data to AWS.\n  - name: Disconnected Edge Computing\n    description: Run AWS compute in environments with no internet connectivity.\n  - name: Disaster Recovery\n    description: Collect and transfer disaster recovery data to AWS.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Transfer data directly to S3 buckets using Snow devices.\n  - name: AWS IoT Greengrass\n    description: Run IoT Greengrass on Snowball Edge for edge IoT workloads.\n  - name: Amazon EC2\n    description: Run EC2 compute instances on Snowball Edge devices.\n  - name: AWS DataSync\n    description: Use DataSync with Snow Family for accelerated data transfer.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nx-type: company\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-snow-family/refs/heads/main/apis.yml
tags:
- AWS
- Data Migration
- Edge Computing
- Offline Transfer
- Physical Appliance
url: https://raw.githubusercontent.com/api-evangelist/amazon-snow-family/refs/heads/main/apis.yml
use_cases:
- description: Migrate terabytes to petabytes of data to AWS.
  name: Large Data Migration
- description: Run AWS compute in environments with no internet connectivity.
  name: Disconnected Edge Computing
- description: Collect and transfer disaster recovery data to AWS.
  name: Disaster Recovery
---
