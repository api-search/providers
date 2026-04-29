---
api_count: 1
apis:
- description: The Amazon Verified Permissions API provides programmatic access to manage policy stores, policies, policy templates, identity sources, and schemas. It enables fine-grained authorization using the Ced
  name: Amazon Verified Permissions API
  slug: amazon-verified-permissions-api
capabilities:
- description: ''
  name: Amazon Verified Permissions Capability
  slug: amazon-verified-permissions-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/verified-permissions/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/verifiedpermissions/latest/userguide/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/verifiedpermissions/
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
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/rules/amazon-verified-permissions-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/vocabulary/amazon-verified-permissions-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/capabilities/amazon-verified-permissions-capability.yaml
created: '2026-03-16'
description: Amazon Verified Permissions is a scalable, fine-grained permissions management and authorization service for the applications you build. Using Cedar, an expressive and analyzable open-source policy language, it helps developers build secure applications faster by externalizing authorization and centralizing policy management.
features:
- description: Automate operational tasks with Amazon Verified Permissions.
  name: Automation
- description: Programmatic access to Amazon Verified Permissions resources.
  name: API Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Verified Permissions Context
  property_count: 0
  slug: amazon-verified-permissions-context
layout: provider
modified: '2026-04-19'
name: Amazon Verified Permissions
rules:
- name: Amazon Verified Permissions API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-verified-permissions-spectral-rules
skills: []
slug: amazon-verified-permissions
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-verified-permissions\nname: Amazon Verified Permissions\ndescription: >-\n  Amazon Verified Permissions is a scalable, fine-grained permissions management\n  and authorization service for the applications you build. Using Cedar, an\n  expressive and analyzable open-source policy language, it helps developers\n  build secure applications faster by externalizing authorization and centralizing\n  policy management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Authorization\n- AWS\n- Permissions\n- Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-verified-permissions:amazon-verified-permissions-api\n  name: Amazon Verified Permissions API\n  description: >-\n    The Amazon Verified Permissions API provides programmatic access to manage\n\
  \    policy stores, policies, policy templates, identity sources, and schemas.\n    It enables fine-grained authorization using the Cedar policy language,\n    supporting real-time authorization decisions for application resources.\n  humanURL: https://aws.amazon.com/verified-permissions/\n  baseURL: https://verifiedpermissions.amazonaws.com\n  tags:\n  - Authorization\n  - AWS\n  - Cedar\n  - Permissions\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/verifiedpermissions/latest/userguide/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/verifiedpermissions/latest/apireference/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/verifiedpermissions/latest/userguide/getting-started.html\n  - type: Pricing\n    url: https://aws.amazon.com/verified-permissions/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/verified-permissions/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/verified-permissions/\n\
  - type: Documentation\n  url: https://docs.aws.amazon.com/verifiedpermissions/latest/userguide/\n- type: Console\n  url: https://console.aws.amazon.com/verifiedpermissions/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/rules/amazon-verified-permissions-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/vocabulary/amazon-verified-permissions-vocabulary.yaml\n- type:\
  \ NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/capabilities/amazon-verified-permissions-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon Verified Permissions.\n  - name: API Access\n    description: Programmatic access to Amazon Verified Permissions resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Verified Permissions to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/apis.yml
tags:
- Authorization
- AWS
- Permissions
- Security
url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-permissions/refs/heads/main/apis.yml
use_cases:
- description: Use Amazon Verified Permissions to manage and automate cloud operations.
  name: Cloud Operations
---
