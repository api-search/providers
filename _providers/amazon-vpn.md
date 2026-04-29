---
api_count: 1
apis:
- description: The AWS VPN API (part of the Amazon EC2 API) provides programmatic access to create and manage VPN connections, customer gateways, virtual private gateways, and Client VPN endpoints. It enables config
  name: AWS VPN API
  slug: aws-vpn-api
capabilities:
- description: ''
  name: Amazon Vpn Capability
  slug: amazon-vpn-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/vpn/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/vpn/latest/s2svpn/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/vpc/
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/rules/amazon-vpn-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/vocabulary/amazon-vpn-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/capabilities/amazon-vpn-capability.yaml
created: '2026-03-16'
description: 'AWS VPN solutions establish secure connections between on-premises networks, remote offices, client devices, and the AWS global network. AWS offers two types of private connectivity: AWS Site-to-Site VPN and AWS Client VPN, enabling encrypted tunnels between your network and Amazon Virtual Private Cloud.'
features:
- description: Automate operational tasks with Amazon VPN.
  name: Automation
- description: Programmatic access to Amazon VPN resources.
  name: API Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Vpn Context
  property_count: 0
  slug: amazon-vpn-context
layout: provider
modified: '2026-04-19'
name: Amazon VPN
rules:
- name: Amazon VPN API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-vpn-spectral-rules
skills: []
slug: amazon-vpn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-vpn\nname: Amazon VPN\ndescription: >-\n  AWS VPN solutions establish secure connections between on-premises networks,\n  remote offices, client devices, and the AWS global network. AWS offers two\n  types of private connectivity: AWS Site-to-Site VPN and AWS Client VPN,\n  enabling encrypted tunnels between your network and Amazon Virtual Private Cloud.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Networking\n- Security\n- VPN\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-vpn:aws-vpn-api\n  name: AWS VPN API\n  description: >-\n    The AWS VPN API (part of the Amazon EC2 API) provides programmatic access\n    to create and manage VPN connections, customer gateways, virtual private\n    gateways, and Client VPN endpoints. It enables configuration of\
  \ Site-to-Site\n    VPN and Client VPN for secure hybrid connectivity.\n  humanURL: https://aws.amazon.com/vpn/\n  baseURL: https://ec2.amazonaws.com\n  tags:\n  - AWS\n  - Networking\n  - Security\n  - VPN\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/vpn/latest/s2svpn/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/OperationList-query-vpn.html\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/vpn/latest/s2svpn/SetUpVPNConnections.html\n  - type: Pricing\n    url: https://aws.amazon.com/vpn/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/vpn/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/vpn/\n- type: Documentation\n  url: https://docs.aws.amazon.com/vpn/latest/s2svpn/\n- type: Console\n  url: https://console.aws.amazon.com/vpc/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url:\
  \ https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/rules/amazon-vpn-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/vocabulary/amazon-vpn-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/capabilities/amazon-vpn-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon VPN.\n  - name: API Access\n    description: Programmatic access to Amazon VPN resources.\n\
  - type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon VPN to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/apis.yml
tags:
- AWS
- Networking
- Security
- VPN
url: https://raw.githubusercontent.com/api-evangelist/amazon-vpn/refs/heads/main/apis.yml
use_cases:
- description: Use Amazon VPN to manage and automate cloud operations.
  name: Cloud Operations
---
