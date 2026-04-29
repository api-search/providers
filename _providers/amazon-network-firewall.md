---
api_count: 1
api_specs:
- filename: amazon-network-firewall-openapi.yml
  format: yaml
  label: AWS Network Firewall API
  slug: aws-network-firewall-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-network-firewall/refs/heads/main/openapi/amazon-network-firewall-openapi.yml
apis:
- description: The AWS Network Firewall API provides programmatic access to create and manage firewalls, firewall policies, rule groups, and TLS inspection configurations for network traffic filtering in VPCs.
  name: AWS Network Firewall API
  slug: aws-network-firewall-api
capabilities:
- description: Workflow capability composing Amazon Network Firewall APIs for developers and operators.
  name: Amazon Network Firewall API Workflow
  slug: amazon-network-firewall-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/network-firewall/
- title: ''
  type: Website
  url: https://aws.amazon.com/network-firewall/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/network-firewall/
- title: ''
  type: Terms of Service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Privacy Policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/networking-and-content-delivery/tag/aws-network-firewall/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/vpc/network-firewall/
- title: ''
  type: Sign Up
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-network-firewall-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-network-firewall-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-network-firewall-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-network-firewall-openapi-context.jsonld
- title: Openapi Action Definition
  type: JSONSchema
  url: json-schema/openapi-action-definition-schema.json
- title: Openapi Action Name
  type: JSONSchema
  url: json-schema/openapi-action-name-schema.json
- title: Openapi Address Definition
  type: JSONSchema
  url: json-schema/openapi-address-definition-schema.json
- title: Openapi Address
  type: JSONSchema
  url: json-schema/openapi-address-schema.json
- title: Openapi Addresses
  type: JSONSchema
  url: json-schema/openapi-addresses-schema.json
created: '2026-03-16'
description: AWS Network Firewall is a stateful, managed, network firewall and intrusion detection and prevention service for your virtual private cloud (VPC). It enables you to filter traffic at the perimeter of your VPC with a flexible rules engine with support for thousands of custom rules.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 170
  name: Amazon Network Firewall Openapi Context
  property_count: 147
  slug: amazon-network-firewall-openapi-context
layout: provider
modified: '2026-04-19'
name: Amazon Network Firewall
rules:
- name: Amazon Network Firewall API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: amazon-network-firewall-spectral-rules
skills: []
slug: amazon-network-firewall
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-network-firewall\nname: Amazon Network Firewall\ndescription: >-\n  AWS Network Firewall is a stateful, managed, network firewall and intrusion\n  detection and prevention service for your virtual private cloud (VPC). It\n  enables you to filter traffic at the perimeter of your VPC with a flexible\n  rules engine with support for thousands of custom rules.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Firewall\n- Intrusion Detection\n- Network Security\n- VPC\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-network-firewall/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-network-firewall:aws-network-firewall-api\n  name: AWS Network Firewall API\n  description: >-\n    The AWS Network Firewall API provides programmatic access to create and\n    manage firewalls, firewall policies, rule groups, and TLS inspection\n\
  \    configurations for network traffic filtering in VPCs.\n  humanURL: https://aws.amazon.com/network-firewall/\n  baseURL: https://network-firewall.amazonaws.com\n  tags:\n  - Firewall\n  - Network Security\n  - VPC\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/network-firewall/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-network-firewall-openapi.yml\n  - type: Getting Started\n    url: https://aws.amazon.com/network-firewall/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/network-firewall/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/network-firewall/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/network-firewall/\n- type: Website\n  url: https://aws.amazon.com/network-firewall/\n- type: Documentation\n  url: https://docs.aws.amazon.com/network-firewall/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n\
  - type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/networking-and-content-delivery/tag/aws-network-firewall/\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/vpc/network-firewall/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-network-firewall-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-network-firewall-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-network-firewall-workflow.yaml\n- type: JSON-LD\n  url: json-ld/amazon-network-firewall-openapi-context.jsonld\n- type: JSONSchema\n  url: json-schema/openapi-action-definition-schema.json\n  title: Openapi Action Definition\n\
  - type: JSONSchema\n  url: json-schema/openapi-action-name-schema.json\n  title: Openapi Action Name\n- type: JSONSchema\n  url: json-schema/openapi-address-definition-schema.json\n  title: Openapi Address Definition\n- type: JSONSchema\n  url: json-schema/openapi-address-schema.json\n  title: Openapi Address\n- type: JSONSchema\n  url: json-schema/openapi-addresses-schema.json\n  title: Openapi Addresses\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-network-firewall/refs/heads/main/apis.yml
tags:
- AWS
- Firewall
- Intrusion Detection
- Network Security
- VPC
url: https://raw.githubusercontent.com/api-evangelist/amazon-network-firewall/refs/heads/main/apis.yml
use_cases: []
---
