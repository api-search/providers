---
api_count: 1
api_specs:
- filename: amazon-global-accelerator-openapi.yml
  format: yaml
  label: Amazon Global Accelerator API
  slug: amazon-global-accelerator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-global-accelerator/refs/heads/main/openapi/amazon-global-accelerator-openapi.yml
apis:
- description: The Amazon Global Accelerator API enables programmatic access to create and manage accelerators, listeners, and endpoint groups. You can configure traffic routing, health checks, and client IP address
  name: Amazon Global Accelerator API
  slug: amazon-global-accelerator-api
capabilities:
- description: Workflow capability for network engineers and DevOps teams managing Amazon Global Accelerator infrastructure. Covers accelerator lifecycle, listener configuration, endpoint group management, and traff
  name: Amazon Global Accelerator Network Operations
  slug: amazon-global-accelerator-network-operations
common:
- title: ''
  type: Portal
  url: https://console.aws.amazon.com/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/global-accelerator/
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
  url: https://console.aws.amazon.com/globalaccelerator
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-global-accelerator-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-global-accelerator-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-global-accelerator-network-operations.yaml
created: '2024-01-15'
description: Amazon Global Accelerator is a networking service that improves the performance and availability of applications with local or global users. It provides static IP addresses that act as a fixed entry point to your applications and uses the AWS global network to optimize the path from users to applications, improving performance by up to 60%.
features:
- description: Provides two static IP addresses as fixed entry points to applications, simplifying DNS management and whitelisting.
  name: Static Anycast IP Addresses
- description: Routes user traffic through the AWS global network backbone for up to 60% performance improvement over public internet.
  name: AWS Global Network Routing
- description: Automatically routes traffic to the closest healthy endpoint based on geography, health, and routing policies.
  name: Intelligent Traffic Distribution
- description: Continuously monitors endpoint health and instantly reroutes traffic away from unhealthy endpoints.
  name: Health Checking
- description: Preserves the original client IP address for application endpoints that need it.
  name: Client IP Preservation
- description: Enables deterministic routing of connections to specific EC2 instances using port mappings.
  name: Custom Routing
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Route traffic to Application, Network, or Classic Load Balancers as endpoints.
  name: AWS Elastic Load Balancing
- description: Use EC2 instances directly as Global Accelerator endpoints.
  name: Amazon EC2
- description: Monitor accelerator metrics and set alarms for traffic and health status.
  name: Amazon CloudWatch
- description: Provision Global Accelerator resources using infrastructure templates.
  name: AWS CloudFormation
jsonld:
- class_count: 0
  name: Amazon Global Accelerator Context
  property_count: 2
  slug: amazon-global-accelerator-context
layout: provider
modified: '2026-04-19'
name: Amazon Global Accelerator
rules:
- name: Amazon Global Accelerator API Rules
  rule_count: 14
  severity_counts:
    error: 7
    hint: 0
    info: 2
    warn: 5
  slug: amazon-global-accelerator-spectral-rules
skills: []
slug: amazon-global-accelerator
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-global-accelerator\nname: Amazon Global Accelerator\ndescription: >-\n  Amazon Global Accelerator is a networking service that improves the\n  performance and availability of applications with local or global users.\n  It provides static IP addresses that act as a fixed entry point to your\n  applications and uses the AWS global network to optimize the path from\n  users to applications, improving performance by up to 60%.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-global-accelerator/refs/heads/main/apis.yml\ntype: Index\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n  - Availability\n  - AWS\n  - CDN\n  - Global\n  - Load Balancing\n  - Networking\n  - Performance\napis:\n  - aid: amazon-global-accelerator:amazon-global-accelerator-api\n    name: Amazon Global Accelerator API\n    description: >-\n      The Amazon Global Accelerator\
  \ API enables programmatic access to create\n      and manage accelerators, listeners, and endpoint groups. You can\n      configure traffic routing, health checks, and client IP address\n      preservation to optimize application performance across AWS Regions.\n    humanURL: https://aws.amazon.com/global-accelerator/\n    baseURL: https://globalaccelerator.amazonaws.com\n    tags:\n      - Global\n      - Networking\n      - Performance\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html\n      - type: OpenAPI\n        url: openapi/amazon-global-accelerator-openapi.yml\n      - type: Pricing\n        url: https://aws.amazon.com/global-accelerator/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/global-accelerator/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/global-accelerator/faqs/\n      - type: APIReference\n\
  \        url: https://docs.aws.amazon.com/global-accelerator/latest/api/Welcome.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html\n      - type: JSONSchema\n        url: json-schema/global-accelerator-accelerator-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-global-accelerator-context.jsonld\ncommon:\n  - type: Portal\n    url: https://console.aws.amazon.com/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/global-accelerator/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/networking-and-content-delivery/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/globalaccelerator\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n\
  \  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-global-accelerator-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-global-accelerator-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/amazon-global-accelerator-network-operations.yaml\n  - type: Features\n    data:\n      - name: Static Anycast IP Addresses\n        description: Provides two static IP addresses as fixed entry points to applications, simplifying DNS management and whitelisting.\n      - name: AWS Global Network Routing\n        description: Routes user traffic through the AWS global network backbone for up to 60% performance improvement over public internet.\n      - name: Intelligent Traffic Distribution\n        description: Automatically routes traffic to the closest healthy endpoint based on geography, health, and routing policies.\n      -\
  \ name: Health Checking\n        description: Continuously monitors endpoint health and instantly reroutes traffic away from unhealthy endpoints.\n      - name: Client IP Preservation\n        description: Preserves the original client IP address for application endpoints that need it.\n      - name: Custom Routing\n        description: Enables deterministic routing of connections to specific EC2 instances using port mappings.\n  - type: UseCases\n    data:\n      - name: Global Application Performance\n        description: Improve latency and throughput for globally distributed users by routing through AWS edge locations.\n      - name: Multi-Region Failover\n        description: Automatically failover traffic to healthy endpoints across regions without DNS changes.\n      - name: Gaming Applications\n        description: Reduce latency for real-time gaming applications using the AWS global network.\n  - type: Integrations\n    data:\n      - name: AWS Elastic Load Balancing\n       \
  \ description: Route traffic to Application, Network, or Classic Load Balancers as endpoints.\n      - name: Amazon EC2\n        description: Use EC2 instances directly as Global Accelerator endpoints.\n      - name: Amazon CloudWatch\n        description: Monitor accelerator metrics and set alarms for traffic and health status.\n      - name: AWS CloudFormation\n        description: Provision Global Accelerator resources using infrastructure templates.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-global-accelerator/refs/heads/main/apis.yml
tags:
- Availability
- AWS
- CDN
- Global
- Load Balancing
- Networking
- Performance
url: https://raw.githubusercontent.com/api-evangelist/amazon-global-accelerator/refs/heads/main/apis.yml
use_cases:
- description: Improve latency and throughput for globally distributed users by routing through AWS edge locations.
  name: Global Application Performance
- description: Automatically failover traffic to healthy endpoints across regions without DNS changes.
  name: Multi-Region Failover
- description: Reduce latency for real-time gaming applications using the AWS global network.
  name: Gaming Applications
---
