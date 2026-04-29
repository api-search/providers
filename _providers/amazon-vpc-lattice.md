---
api_count: 1
apis:
- description: The Amazon VPC Lattice API provides programmatic access to create and manage service networks, services, target groups, listeners, rules, and access log subscriptions. It enables service-to-service co
  name: Amazon VPC Lattice API
  slug: amazon-vpc-lattice-api
capabilities:
- description: ''
  name: Amazon Vpc Lattice Capability
  slug: amazon-vpc-lattice-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/vpc/lattice/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/vpc-lattice/latest/ug/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/vpc/home#VpcLattice
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/rules/amazon-vpc-lattice-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/vocabulary/amazon-vpc-lattice-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/capabilities/amazon-vpc-lattice-capability.yaml
created: '2026-03-16'
description: Amazon VPC Lattice is an application networking service that consistently connects, monitors, and secures communications between your services, helping you to improve productivity so that your developers can focus on building features that matter to your business. It simplifies service-to-service connectivity and security across VPCs and accounts.
features:
- description: Automate operational tasks with Amazon VPC Lattice.
  name: Automation
- description: Programmatic access to Amazon VPC Lattice resources.
  name: API Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Vpc Lattice Context
  property_count: 0
  slug: amazon-vpc-lattice-context
layout: provider
modified: '2026-04-19'
name: Amazon VPC Lattice
rules:
- name: Amazon VPC Lattice API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-vpc-lattice-spectral-rules
skills: []
slug: amazon-vpc-lattice
solutions: []
source_yaml: "aid: amazon-vpc-lattice\nname: Amazon VPC Lattice\ndescription: >-\n  Amazon VPC Lattice is an application networking service that consistently\n  connects, monitors, and secures communications between your services,\n  helping you to improve productivity so that your developers can focus on\n  building features that matter to your business. It simplifies service-to-service\n  connectivity and security across VPCs and accounts.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Microservices\n- Service Mesh\n- Service Networking\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-vpc-lattice:amazon-vpc-lattice-api\n  name: Amazon VPC Lattice API\n  description: >-\n    The Amazon VPC Lattice API provides programmatic access to create and\n    manage service networks,\
  \ services, target groups, listeners, rules, and\n    access log subscriptions. It enables service-to-service connectivity\n    with built-in authentication and authorization across VPCs and AWS accounts.\n  humanURL: https://aws.amazon.com/vpc/lattice/\n  baseURL: https://vpc-lattice.amazonaws.com\n  tags:\n  - AWS\n  - Microservices\n  - Service Networking\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/vpc-lattice/latest/ug/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/vpc-lattice/latest/APIReference/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/vpc-lattice/latest/ug/getting-started.html\n  - type: Pricing\n    url: https://aws.amazon.com/vpc/lattice/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/vpc/lattice/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/vpc/lattice/\n- type: Documentation\n  url: https://docs.aws.amazon.com/vpc-lattice/latest/ug/\n\
  - type: Console\n  url: https://console.aws.amazon.com/vpc/home#VpcLattice\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/rules/amazon-vpc-lattice-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/vocabulary/amazon-vpc-lattice-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/capabilities/amazon-vpc-lattice-capability.yaml\n\
  - type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon VPC Lattice.\n  - name: API Access\n    description: Programmatic access to Amazon VPC Lattice resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon VPC Lattice to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/apis.yml
tags:
- AWS
- Microservices
- Service Mesh
- Service Networking
url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc-lattice/refs/heads/main/apis.yml
use_cases:
- description: Use Amazon VPC Lattice to manage and automate cloud operations.
  name: Cloud Operations
---
