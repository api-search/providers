---
api_count: 1
api_specs:
- filename: amazon-transit-gateway-openapi.yml
  format: yaml
  label: Amazon Transit Gateway REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/openapi/amazon-transit-gateway-openapi.yml
apis:
- description: RESTful API for Amazon Transit Gateway operations including creating and managing transit gateways, VPC attachments, route tables, peering connections, and multicast domains.
  name: Amazon Transit Gateway REST API
  slug: ''
capabilities:
- description: ''
  name: Amazon Transit Gateway Capability
  slug: amazon-transit-gateway-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/transit-gateway/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/vpc/latest/tgw/
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
  url: https://stackoverflow.com/questions/tagged/aws-transit-gateway
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/rules/amazon-transit-gateway-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/vocabulary/amazon-transit-gateway-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/capabilities/amazon-transit-gateway-capability.yaml
created: '2024-01-15'
description: Amazon Transit Gateway connects VPCs and on-premises networks through a central hub, simplifying network architecture and reducing operational complexity for large-scale cloud deployments.
features:
- description: Automate operational tasks with Amazon Transit Gateway.
  name: Automation
- description: Programmatic access to Amazon Transit Gateway resources.
  name: API Access
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 7
  name: Amazon Transit Gateway Context
  property_count: 5
  slug: amazon-transit-gateway-context
layout: provider
modified: '2026-04-19'
name: Amazon Transit Gateway
rules:
- name: Amazon Transit Gateway API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-transit-gateway-spectral-rules
skills: []
slug: amazon-transit-gateway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Transit Gateway\ndescription: Amazon Transit Gateway connects VPCs and on-premises networks through a central hub, simplifying network architecture and reducing operational complexity for large-scale cloud \n  deployments.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/transit-gateway/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Transit Gateway REST API\n  description: RESTful API for Amazon Transit Gateway operations including creating and managing transit gateways, VPC attachments, route tables, peering connections, and multicast domains.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/transit-gateway/\n  baseURL: https://ec2.amazonaws.com\n  tags:\n  - AWS\n  - Networking\n  - Transit Gateway\n  - VPC\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/OperationList-query-tgw.html\n\
  \  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/openapi/amazon-transit-gateway-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/ec2/2016-11-15/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-transit-gateway-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-transit-gateway-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/transit-gateway/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/transit-gateway/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/Query-Requests.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: FAQ\n    url: https://aws.amazon.com/transit-gateway/faqs/\n  - type: Service Level Agreement\n    url: https://aws.amazon.com/ec2/sla/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/vpc/latest/tgw/what-is-transit-gateway.html\n\
  \  - type: API Reference\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/OperationList-query-tgw.html\n  - type: Code Examples\n    url: https://docs.aws.amazon.com/vpc/latest/tgw/TGW_Scenarios.html\n  - type: Security\n    url: https://docs.aws.amazon.com/vpc/latest/tgw/tgw-security.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/transit-gateway/\n- type: Documentation\n  url: https://docs.aws.amazon.com/vpc/latest/tgw/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/networking-and-content-delivery/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/vpc/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n\
  \  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/aws-transit-gateway\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/rules/amazon-transit-gateway-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/vocabulary/amazon-transit-gateway-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/capabilities/amazon-transit-gateway-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational\
  \ tasks with Amazon Transit Gateway.\n  - name: API Access\n    description: Programmatic access to Amazon Transit Gateway resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Transit Gateway to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Cloud Networking\n- Network Hub\n- Networking\n- Transit Gateway\n- VPC\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-transit-gateway/refs/heads/main/apis.yml
tags:
- Cloud Networking
- Network Hub
- Networking
- Transit Gateway
- VPC
url: https://aws.amazon.com/transit-gateway/
use_cases:
- description: Use Amazon Transit Gateway to manage and automate cloud operations.
  name: Cloud Operations
---
