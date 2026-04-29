---
api_count: 1
apis:
- description: The AWS Verified Access API provides programmatic access to create and manage Verified Access instances, groups, endpoints, and trust providers. It enables configuring zero-trust network access polici
  name: AWS Verified Access API
  slug: amazon-verified-access-api
capabilities:
- description: ''
  name: Amazon Verified Access Capability
  slug: amazon-verified-access-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/verified-access/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/verified-access/latest/ug/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/verified-access/
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/rules/amazon-verified-access-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/vocabulary/amazon-verified-access-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/capabilities/amazon-verified-access-capability.yaml
created: '2026-03-16'
description: AWS Verified Access provides secure access to corporate applications without requiring a VPN. It evaluates each application request in real time using security signals like identity, device posture, and contextual data to grant granular access only to users who meet the specified requirements.
features:
- description: Automate operational tasks with Amazon Verified Access.
  name: Automation
- description: Programmatic access to Amazon Verified Access resources.
  name: API Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Verified Access Context
  property_count: 0
  slug: amazon-verified-access-context
layout: provider
modified: '2026-04-19'
name: Amazon Verified Access
rules:
- name: Amazon Verified Access API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-verified-access-spectral-rules
skills: []
slug: amazon-verified-access
solutions: []
source_yaml: "aid: amazon-verified-access\nname: Amazon Verified Access\ndescription: >-\n  AWS Verified Access provides secure access to corporate applications without\n  requiring a VPN. It evaluates each application request in real time using\n  security signals like identity, device posture, and contextual data to grant\n  granular access only to users who meet the specified requirements.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Access Management\n- AWS\n- Security\n- Zero Trust\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-verified-access:amazon-verified-access-api\n  name: AWS Verified Access API\n  description: >-\n    The AWS Verified Access API provides programmatic access to create and\n    manage Verified Access instances, groups, endpoints, and trust providers.\n\
  \    It enables configuring zero-trust network access policies that evaluate\n    user identity and device security posture for each application request.\n  humanURL: https://aws.amazon.com/verified-access/\n  baseURL: https://ec2.amazonaws.com\n  tags:\n  - Access Management\n  - AWS\n  - Security\n  - Zero Trust\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/verified-access/latest/ug/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/OperationList-query-verified-access.html\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/verified-access/latest/ug/getting-started.html\n  - type: Pricing\n    url: https://aws.amazon.com/verified-access/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/verified-access/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/verified-access/\n- type: Documentation\n  url: https://docs.aws.amazon.com/verified-access/latest/ug/\n\
  - type: Console\n  url: https://console.aws.amazon.com/verified-access/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/rules/amazon-verified-access-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/vocabulary/amazon-verified-access-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/capabilities/amazon-verified-access-capability.yaml\n\
  - type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon Verified Access.\n  - name: API Access\n    description: Programmatic access to Amazon Verified Access resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Verified Access to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/apis.yml
tags:
- Access Management
- AWS
- Security
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/amazon-verified-access/refs/heads/main/apis.yml
use_cases:
- description: Use Amazon Verified Access to manage and automate cloud operations.
  name: Cloud Operations
---
