---
api_count: 1
apis:
- description: The AWS License Manager API provides programmatic access to create and manage license configurations, license associations, grants, tokens, and license reports for managing software licenses across AW
  name: AWS License Manager API
  slug: aws-license-manager-api
capabilities:
- description: Unified workflow capability for Amazon License Manager combining resource management and operations.
  name: Amazon License Manager Workflow
  slug: amazon-license-manager-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/license-manager/
- title: ''
  type: Portal
  url: https://aws.amazon.com/license-manager/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/license-manager/
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
  url: https://aws.amazon.com/blogs/mt/tag/aws-license-manager/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/license-manager/
- title: ''
  type: SignUp
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
  url: rules/amazon-license-manager-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-license-manager-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-license-manager-vocabulary.yaml
created: '2026-03-16'
description: AWS License Manager makes it easier to manage licenses in AWS and on-premises servers from software vendors such as Microsoft, SAP, Oracle, and IBM. It helps you control your licensing costs by letting you create rules that emulate the terms of your licensing agreements.
features:
- description: Define licensing rules based on software attributes and enforce them during instance launches.
  name: License Rule Enforcement
- description: Track license usage across AWS and on-premises environments from a central dashboard.
  name: License Tracking
- description: Discover software inventory across multiple AWS accounts in an AWS Organization.
  name: Cross-Account Discovery
- description: Generate license compliance reports for auditors and software vendors.
  name: Automated Compliance Reports
- description: Use existing on-premises software licenses on EC2 with BYOL programs.
  name: Bring Your Own License (BYOL)
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Discover software inventory on EC2 instances using Systems Manager inventory.
  name: AWS Systems Manager
- description: Manage licenses across all accounts in an AWS Organization from a single pane.
  name: AWS Organizations
- description: Access software licenses purchased through AWS Marketplace.
  name: AWS Marketplace
jsonld:
- class_count: 1
  name: Amazon License Manager Context
  property_count: 7
  slug: amazon-license-manager-context
layout: provider
modified: '2026-04-19'
name: Amazon License Manager
rules:
- name: Amazon License Manager API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-license-manager-spectral-rules
skills: []
slug: amazon-license-manager
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-license-manager\nname: Amazon License Manager\ndescription: >-\n  AWS License Manager makes it easier to manage licenses in AWS and on-premises\n  servers from software vendors such as Microsoft, SAP, Oracle, and IBM. It\n  helps you control your licensing costs by letting you create rules that emulate\n  the terms of your licensing agreements.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Compliance\n- Cost Management\n- License Management\n- Software Licensing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-license-manager/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-license-manager:aws-license-manager-api\n  name: AWS License Manager API\n  description: >-\n    The AWS License Manager API provides programmatic access to create and\n    manage license configurations, license associations, grants, tokens,\
  \ and\n    license reports for managing software licenses across AWS.\n  humanURL: https://aws.amazon.com/license-manager/\n  baseURL: https://license-manager.amazonaws.com\n  tags:\n  - Compliance\n  - License Management\n  - Software Licensing\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/license-manager/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/license-manager/2018-08-01/openapi.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/license-manager/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/license-manager/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/license-manager/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-license-manager-license-configuration-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-license-manager-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/license-manager/\n- type: Portal\n  url: https://aws.amazon.com/license-manager/\n\
  - type: Documentation\n  url: https://docs.aws.amazon.com/license-manager/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/mt/tag/aws-license-manager/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/license-manager/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Features\n  data:\n  - name: License Rule Enforcement\n    description: Define licensing rules based on software attributes and enforce them during instance launches.\n  - name: License Tracking\n    description: Track license usage across AWS and on-premises\
  \ environments from a central dashboard.\n  - name: Cross-Account Discovery\n    description: Discover software inventory across multiple AWS accounts in an AWS Organization.\n  - name: Automated Compliance Reports\n    description: Generate license compliance reports for auditors and software vendors.\n  - name: Bring Your Own License (BYOL)\n    description: Use existing on-premises software licenses on EC2 with BYOL programs.\n- type: UseCases\n  data:\n  - name: License Compliance\n    description: Ensure software deployments comply with license agreements across your AWS estate.\n  - name: Cost Optimization\n    description: Track license usage to identify unused licenses and optimize software spend.\n  - name: Vendor Audit Preparation\n    description: Generate detailed license reports for software vendor audits.\n- type: Integrations\n  data:\n  - name: AWS Systems Manager\n    description: Discover software inventory on EC2 instances using Systems Manager inventory.\n  - name:\
  \ AWS Organizations\n    description: Manage licenses across all accounts in an AWS Organization from a single pane.\n  - name: AWS Marketplace\n    description: Access software licenses purchased through AWS Marketplace.\n- type: SpectralRules\n  url: rules/amazon-license-manager-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-license-manager-workflow.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-license-manager-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-license-manager/refs/heads/main/apis.yml
tags:
- AWS
- Compliance
- Cost Management
- License Management
- Software Licensing
url: https://raw.githubusercontent.com/api-evangelist/amazon-license-manager/refs/heads/main/apis.yml
use_cases:
- description: Ensure software deployments comply with license agreements across your AWS estate.
  name: License Compliance
- description: Track license usage to identify unused licenses and optimize software spend.
  name: Cost Optimization
- description: Generate detailed license reports for software vendor audits.
  name: Vendor Audit Preparation
---
