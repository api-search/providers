---
api_count: 1
api_specs:
- filename: amazon-vpc-openapi.yml
  format: yaml
  label: Amazon VPC API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/openapi/amazon-vpc-openapi.yml
apis:
- description: Core API for managing Amazon Virtual Private Cloud resources including VPCs, subnets, internet gateways, NAT gateways, route tables, and network ACLs. VPC operations are part of the Amazon EC2 API.
  name: Amazon VPC API
  slug: ''
capabilities:
- description: ''
  name: Amazon Vpc Capability
  slug: amazon-vpc-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/vpc/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/vpc/
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
  url: https://aws.amazon.com/blogs/networking-and-content-delivery/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/vpc/
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
  type: Knowledge Center
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/amazon-vpc
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/vpc/latest/userguide/security.html
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/rules/amazon-vpc-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/vocabulary/amazon-vpc-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/capabilities/amazon-vpc-capability.yaml
created: '2024-01-15'
description: Amazon Virtual Private Cloud (VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define, with complete control over IP addressing, subnets, routing, and network gateways.
features:
- description: Automate operational tasks with Amazon VPC.
  name: Automation
- description: Programmatic access to Amazon VPC resources.
  name: API Access
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 0
  name: Amazon Vpc Context
  property_count: 6
  slug: amazon-vpc-context
layout: provider
modified: '2026-04-19'
name: Amazon VPC
rules:
- name: Amazon VPC API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-vpc-spectral-rules
skills: []
slug: amazon-vpc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon VPC\ndescription: Amazon Virtual Private Cloud (VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define, with complete \n  control over IP addressing, subnets, routing, and network gateways.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/vpc/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon VPC API\n  description: >-\n    Core API for managing Amazon Virtual Private Cloud resources including VPCs,\n    subnets, internet gateways, NAT gateways, route tables, and network ACLs.\n    VPC operations are part of the Amazon EC2 API.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/vpc/\n  baseURL: https://ec2.amazonaws.com\n  tags:\n  - AWS\n  - Networking\n  - Private Cloud\n  - Security\n  - Subnets\n  - VPC\n  properties:\n\
  \  - type: Documentation\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/OperationList-query-vpc.html\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/openapi/amazon-vpc-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-vpc-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-vpc-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/vpc/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/vpc/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/vpc/faqs/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/vpc/latest/userguide/\n  - type: API Reference\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/\n  - type: CLI Reference\n    url: https://docs.aws.amazon.com/cli/latest/reference/ec2/\n  - type: Security\n    url: https://docs.aws.amazon.com/vpc/latest/userguide/security.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n\
  - type: Website\n  url: https://aws.amazon.com/vpc/\n- type: Documentation\n  url: https://docs.aws.amazon.com/vpc/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/networking-and-content-delivery/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/vpc/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-vpc\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n\
  - type: Security\n  url: https://docs.aws.amazon.com/vpc/latest/userguide/security.html\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/rules/amazon-vpc-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/vocabulary/amazon-vpc-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/capabilities/amazon-vpc-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon VPC.\n  - name: API Access\n    description: Programmatic access to Amazon VPC resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon VPC to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\n\
  tags:\n- AWS\n- Networking\n- Private Cloud\n- Security\n- Subnets\n- VPC\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-vpc/refs/heads/main/apis.yml
tags:
- Networking
- Private Cloud
- Security
- Subnets
- VPC
url: https://aws.amazon.com/vpc/
use_cases:
- description: Use Amazon VPC to manage and automate cloud operations.
  name: Cloud Operations
---
