---
api_count: 1
api_specs:
- filename: amazon-workspaces-openapi-original.yaml
  format: yaml
  label: Amazon WorkSpaces API
  slug: amazon-workspaces-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/openapi/amazon-workspaces-openapi-original.yaml
apis:
- description: The Amazon WorkSpaces API provides programmatic access to manage cloud-based virtual desktops. It enables developers to create, modify, and terminate WorkSpaces, manage workspace bundles and directori
  name: Amazon WorkSpaces API
  slug: amazon-workspaces-api
capabilities:
- description: Unified workflow for IT administrators and end user computing teams to provision, manage, and maintain Amazon WorkSpaces virtual desktops at scale, including workspace lifecycle, bundle management, di
  name: Amazon WorkSpaces Virtual Desktop Management
  slug: virtual-desktop-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/workspaces/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/workspaces/
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
  url: https://console.aws.amazon.com/workspaces/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-workspaces-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-workspaces-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/virtual-desktop-management.yaml
created: '2024-01-15'
description: Amazon WorkSpaces is a managed, secure Desktop-as-a-Service (DaaS) solution that enables you to provision cloud-based virtual desktops for your users. It eliminates the need to procure and deploy hardware or install complex software, providing persistent desktops accessible from various devices with built-in security and management capabilities. The API provides 65 operations for workspace lifecycle management, bundle and directory management, image management, and IP access control groups.
features:
- description: Cloud-based Windows or Linux desktops with persistent storage that users can access from any device or location.
  name: Persistent Virtual Desktops
- description: Configurable compute bundles ranging from Value to Graphics.g4dn to match workload requirements and cost targets.
  name: Desktop Bundle Catalog
- description: Integration with AWS Managed Microsoft AD and AD Connector for user authentication and policy management.
  name: Active Directory Integration
- description: Deploy and manage applications across WorkSpaces using application assignment and streaming capabilities.
  name: Application Management
- description: Restrict workspace access by IP address ranges to enforce network-based access controls.
  name: IP Access Control Groups
- description: AlwaysOn mode for power users and AutoStop mode for cost optimization of occasional-use desktops.
  name: Running Mode Flexibility
- description: Thin client, web browser, iOS, Android, Linux, macOS, and Windows client access for bring-your-own-device scenarios.
  name: BYOD Support
- description: Automated snapshots enable restoring workspaces to previous states for disaster recovery and user error correction.
  name: Workspace Snapshots and Restore
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Managed Microsoft AD and AD Connector for user authentication and group policy management.
  name: AWS Directory Service
- description: IAM-based access control for WorkSpaces API operations and resource-level permissions.
  name: AWS IAM
- description: User storage and workspace image storage backed by Amazon S3.
  name: Amazon S3
- description: Audit logging of all WorkSpaces API calls for compliance and security monitoring.
  name: AWS CloudTrail
- description: Metrics and monitoring for workspace performance, connectivity, and health status.
  name: Amazon CloudWatch
jsonld:
- class_count: 175
  name: Amazon Workspaces Context
  property_count: 173
  slug: amazon-workspaces-context
layout: provider
modified: '2026-04-19'
name: Amazon WorkSpaces
rules:
- name: Amazon WorkSpaces API Rules
  rule_count: 16
  severity_counts:
    error: 8
    hint: 0
    info: 2
    warn: 6
  slug: amazon-workspaces-spectral-rules
skills: []
slug: amazon-workspaces
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-workspaces\nname: Amazon WorkSpaces\ndescription: >-\n  Amazon WorkSpaces is a managed, secure Desktop-as-a-Service (DaaS) solution\n  that enables you to provision cloud-based virtual desktops for your users. It\n  eliminates the need to procure and deploy hardware or install complex software,\n  providing persistent desktops accessible from various devices with built-in\n  security and management capabilities. The API provides 65 operations for\n  workspace lifecycle management, bundle and directory management, image\n  management, and IP access control groups.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - AWS\n  - Desktop\n  - End User Computing\n  - Virtual Desktop\n  - Desktop as a Service\napis:\n  - aid: amazon-workspaces:amazon-workspaces-api\n\
  \    name: Amazon WorkSpaces API\n    description: >-\n      The Amazon WorkSpaces API provides programmatic access to manage cloud-based\n      virtual desktops. It enables developers to create, modify, and terminate\n      WorkSpaces, manage workspace bundles and directories, configure IP access\n      control groups, and automate desktop provisioning and lifecycle management\n      at scale. 65 operations for workspace lifecycle, bundles, directories,\n      images, and access control.\n    humanURL: https://aws.amazon.com/workspaces/\n    baseURL: https://workspaces.amazonaws.com\n    tags:\n      - AWS\n      - Desktop\n      - End User Computing\n      - Virtual Desktop\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/workspaces/\n      - type: OpenAPI\n        url: openapi/amazon-workspaces-openapi-original.yaml\n      - type: Pricing\n        url: https://aws.amazon.com/workspaces/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/workspaces/getting-started/\n\
  \      - type: FAQ\n        url: https://aws.amazon.com/workspaces/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/workspaces/latest/api/welcome.html\n      - type: JSONSchema\n        url: json-schema/workspaces-workspace-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-workspaces-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/workspaces/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/workspaces/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/workspaces/\n  - type: SignUp\n    url: https://signin.aws.amazon.com/signup?request_type=register\n  - type: Login\n    url: https://aws.amazon.com/console/\n\
  \  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-workspaces-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-workspaces-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/virtual-desktop-management.yaml\n  - type: Features\n    data:\n      - name: Persistent Virtual Desktops\n        description: >-\n          Cloud-based Windows or Linux desktops with persistent storage that\n          users can access from any device or location.\n      - name: Desktop Bundle Catalog\n        description: >-\n          Configurable compute bundles ranging from Value to Graphics.g4dn\n          to match workload requirements and cost targets.\n      - name: Active Directory Integration\n        description: >-\n          Integration with AWS Managed Microsoft AD and AD Connector for\n          user authentication and policy management.\n\
  \      - name: Application Management\n        description: >-\n          Deploy and manage applications across WorkSpaces using application\n          assignment and streaming capabilities.\n      - name: IP Access Control Groups\n        description: >-\n          Restrict workspace access by IP address ranges to enforce\n          network-based access controls.\n      - name: Running Mode Flexibility\n        description: >-\n          AlwaysOn mode for power users and AutoStop mode for cost\n          optimization of occasional-use desktops.\n      - name: BYOD Support\n        description: >-\n          Thin client, web browser, iOS, Android, Linux, macOS, and Windows\n          client access for bring-your-own-device scenarios.\n      - name: Workspace Snapshots and Restore\n        description: >-\n          Automated snapshots enable restoring workspaces to previous states\n          for disaster recovery and user error correction.\n  - type: UseCases\n    data:\n      - name:\
  \ Remote Work Enablement\n        description: >-\n          Provide secure cloud desktops to remote and distributed employees\n          without managing physical hardware.\n      - name: Contractor and Temporary Worker Access\n        description: >-\n          Quickly provision and terminate secure desktops for contractors\n          with time-limited access needs.\n      - name: Desktop Refresh and Modernization\n        description: >-\n          Replace aging desktop hardware with cloud-based virtual desktops\n          to reduce capital expenditure.\n      - name: BYOD Security\n        description: >-\n          Enable personal device usage while keeping corporate data and\n          applications in the secure cloud environment.\n      - name: Regulated Industry Compliance\n        description: >-\n          Maintain data residency and security compliance in regulated\n          industries like healthcare and finance.\n  - type: Integrations\n    data:\n      - name: AWS Directory\
  \ Service\n        description: >-\n          Managed Microsoft AD and AD Connector for user authentication\n          and group policy management.\n      - name: AWS IAM\n        description: >-\n          IAM-based access control for WorkSpaces API operations and\n          resource-level permissions.\n      - name: Amazon S3\n        description: >-\n          User storage and workspace image storage backed by Amazon S3.\n      - name: AWS CloudTrail\n        description: >-\n          Audit logging of all WorkSpaces API calls for compliance\n          and security monitoring.\n      - name: Amazon CloudWatch\n        description: >-\n          Metrics and monitoring for workspace performance, connectivity,\n          and health status.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/apis.yml
tags:
- AWS
- Desktop
- End User Computing
- Virtual Desktop
- Desktop as a Service
url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/apis.yml
use_cases:
- description: Provide secure cloud desktops to remote and distributed employees without managing physical hardware.
  name: Remote Work Enablement
- description: Quickly provision and terminate secure desktops for contractors with time-limited access needs.
  name: Contractor and Temporary Worker Access
- description: Replace aging desktop hardware with cloud-based virtual desktops to reduce capital expenditure.
  name: Desktop Refresh and Modernization
- description: Enable personal device usage while keeping corporate data and applications in the secure cloud environment.
  name: BYOD Security
- description: Maintain data residency and security compliance in regulated industries like healthcare and finance.
  name: Regulated Industry Compliance
---
