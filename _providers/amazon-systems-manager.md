---
api_count: 1
apis:
- description: The AWS Systems Manager API provides programmatic access to manage and automate operational tasks across your AWS and on-premises infrastructure. It enables developers to run commands on managed insta
  name: AWS Systems Manager API
  slug: ''
capabilities:
- description: ''
  name: Amazon Systems Manager Capability
  slug: amazon-systems-manager-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/systems-manager/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/systems-manager/
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
  url: https://console.aws.amazon.com/systems-manager/
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/rules/amazon-systems-manager-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/vocabulary/amazon-systems-manager-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/capabilities/amazon-systems-manager-capability.yaml
created: '2024-01-15'
description: AWS Systems Manager is an operational management service that provides a unified interface for managing AWS resources and on-premises infrastructure. It enables automation of operational tasks, configuration management, patch management, parameter storage, and run command execution across your hybrid cloud environment at scale.
features:
- description: Automate operational tasks with Amazon Systems Manager.
  name: Automation
- description: Programmatic access to Amazon Systems Manager resources.
  name: API Access
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 0
  name: Amazon Systems Manager Context
  property_count: 5
  slug: amazon-systems-manager-context
layout: provider
modified: '2026-04-19'
name: Amazon Systems Manager
rules:
- name: Amazon Systems Manager API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-systems-manager-spectral-rules
skills: []
slug: amazon-systems-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Systems Manager\ndescription: AWS Systems Manager is an operational management service that provides a unified interface for managing AWS resources and on-premises infrastructure. It enables automation of operational \n  tasks, configuration management, patch management, parameter storage, and run command execution across your hybrid cloud environment at scale.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/systems-manager/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: AWS Systems Manager API\n  description: >-\n    The AWS Systems Manager API provides programmatic access to manage and\n    automate operational tasks across your AWS and on-premises infrastructure.\n    It enables developers to run commands on managed instances, manage\n    parameters and secrets, create automation documents, configure patch\n    baselines, manage inventory, and set up maintenance windows.\n  image:\
  \ https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/systems-manager/\n  baseURL: https://ssm.amazonaws.com\n  tags:\n  - Automation\n  - AWS\n  - Management\n  - Operations\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/systems-manager/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/openapi/amazon-systems-manager-openapi.yml\n  - type: Pricing\n    url: https://aws.amazon.com/systems-manager/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/systems-manager/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/systems-manager/faq/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/systems-manager/\n- type: Documentation\n  url: https://docs.aws.amazon.com/systems-manager/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type:\
  \ PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/systems-manager/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/rules/amazon-systems-manager-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/vocabulary/amazon-systems-manager-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/capabilities/amazon-systems-manager-capability.yaml\n\
  - type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon Systems Manager.\n  - name: API Access\n    description: Programmatic access to Amazon Systems Manager resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Systems Manager to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- Automation\n- AWS\n- Management\n- Operations\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-systems-manager/refs/heads/main/apis.yml
tags:
- Automation
- AWS
- Management
- Operations
url: https://aws.amazon.com/systems-manager/
use_cases:
- description: Use Amazon Systems Manager to manage and automate cloud operations.
  name: Cloud Operations
---
