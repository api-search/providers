---
api_count: 1
api_specs:
- filename: amazon-direct-connect-openapi.yaml
  format: yaml
  label: Amazon Direct Connect API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-direct-connect/refs/heads/main/openapi/amazon-direct-connect-openapi.yaml
apis:
- description: The AWS Direct Connect API provides programmatic access to create and manage dedicated network connections between your on-premises network and AWS, including connections, virtual interfaces, gateways
  name: Amazon Direct Connect API
  slug: ''
capabilities:
- description: Workflow capability for network engineers and cloud architects to manage dedicated private connections between on-premises networks and AWS using Amazon Direct Connect. Covers connection provisioning,
  name: Amazon Direct Connect Hybrid Network Connectivity
  slug: hybrid-network-connectivity
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/directconnect/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/directconnect/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/networking-and-content-delivery/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/directconnect/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-direct-connect
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-direct-connect-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-direct-connect-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/hybrid-network-connectivity.yaml
created: '2024-01-15'
description: AWS Direct Connect links your internal network to an AWS Direct Connect location over a standard Ethernet fiber-optic cable. With this connection, you can create virtual interfaces directly to public AWS services or to Amazon VPC, bypassing internet service providers in your network path. An AWS Direct Connect location provides access to AWS in the region with which it is associated, providing reduced network costs, increased bandwidth throughput, and a more consistent network experience.
features:
- description: Provides dedicated private connectivity with consistent bandwidth from 50 Mbps to 100 Gbps directly to AWS data centers.
  name: Dedicated Physical Connections
- description: Create private virtual interfaces for direct access to Amazon VPC without traversing the public internet.
  name: Private Virtual Interfaces
- description: Create public virtual interfaces to access all AWS public services using private bandwidth.
  name: Public Virtual Interfaces
- description: Create transit virtual interfaces to connect to AWS Transit Gateway for centralized hub-and-spoke connectivity.
  name: Transit Virtual Interfaces
- description: Use gateways to connect to multiple VPCs across different regions through a single Direct Connect connection.
  name: Direct Connect Gateways
- description: Bundle multiple connections into a LAG to increase bandwidth and improve redundancy with active-active failover.
  name: Link Aggregation Groups
- description: Purchase sub-1G and 1G connections through Direct Connect partners for flexible capacity options.
  name: Hosted Connections
- description: Secure point-to-point Ethernet connections with 802.1AE MACsec encryption for data-in-transit security.
  name: MACsec Encryption
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Connect directly to private VPC subnets using private virtual interfaces without internet exposure.
  name: Amazon VPC
- description: Use transit virtual interfaces to connect multiple VPCs and VPNs through a single gateway hub.
  name: AWS Transit Gateway
- description: Purchase hosted connections and virtual interfaces through AWS Direct Connect delivery partners worldwide.
  name: AWS Direct Connect Partners
- description: Automate Direct Connect resource provisioning using CloudFormation templates for infrastructure as code.
  name: AWS CloudFormation
- description: Use Direct Connect for private DNS resolution between on-premises and AWS environments.
  name: Amazon Route 53 Resolver
jsonld:
- class_count: 19
  name: Amazon Direct Connect Context
  property_count: 85
  slug: amazon-direct-connect-context
layout: provider
modified: '2026-04-19'
name: Amazon Direct Connect
rules:
- name: Amazon Direct Connect API Rules
  rule_count: 18
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 4
  slug: amazon-direct-connect-spectral-rules
skills: []
slug: amazon-direct-connect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Direct Connect\ndescription: >-\n  AWS Direct Connect links your internal network to an AWS Direct Connect\n  location over a standard Ethernet fiber-optic cable. With this connection,\n  you can create virtual interfaces directly to public AWS services or to\n  Amazon VPC, bypassing internet service providers in your network path. An\n  AWS Direct Connect location provides access to AWS in the region with which\n  it is associated, providing reduced network costs, increased bandwidth\n  throughput, and a more consistent network experience.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/directconnect/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n  - name: Amazon Direct Connect API\n    description: >-\n      The AWS Direct Connect API provides programmatic access to create and\n      manage dedicated network connections between your on-premises network\n      and AWS, including connections,\
  \ virtual interfaces, gateways, and\n      link aggregation groups. Covers 63 operations for full lifecycle management\n      of hybrid network connectivity.\n    humanURL: https://aws.amazon.com/directconnect/\n    baseURL: https://directconnect.amazonaws.com\n    tags:\n      - AWS\n      - Dedicated Connection\n      - Direct Connect\n      - Hybrid Cloud\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/directconnect/latest/APIReference/\n      - type: OpenAPI\n        url: openapi/amazon-direct-connect-openapi.yaml\n      - type: Pricing\n        url: https://aws.amazon.com/directconnect/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/directconnect/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/directconnect/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-direct-connect-connection-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-direct-connect-virtual-interface-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/amazon-direct-connect-direct-connect-gateway-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-direct-connect-lag-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-direct-connect-connection-structure.json\n      - type: JSONStructure\n        url: json-structure/amazon-direct-connect-virtual-interface-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-direct-connect-context.jsonld\n      - type: Example\n        url: examples/amazon-direct-connect-connection-example.json\n      - type: Example\n        url: examples/amazon-direct-connect-virtual-interface-example.json\n      - type: Example\n        url: examples/amazon-direct-connect-lag-example.json\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/directconnect/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/directconnect/\n  - type: TermsOfService\n\
  \    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/support/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/networking-and-content-delivery/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/directconnect/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/aws-direct-connect\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-direct-connect-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-direct-connect-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/hybrid-network-connectivity.yaml\n\
  \  - type: Features\n    data:\n      - name: Dedicated Physical Connections\n        description: Provides dedicated private connectivity with consistent bandwidth from 50 Mbps to 100 Gbps directly to AWS data centers.\n      - name: Private Virtual Interfaces\n        description: Create private virtual interfaces for direct access to Amazon VPC without traversing the public internet.\n      - name: Public Virtual Interfaces\n        description: Create public virtual interfaces to access all AWS public services using private bandwidth.\n      - name: Transit Virtual Interfaces\n        description: Create transit virtual interfaces to connect to AWS Transit Gateway for centralized hub-and-spoke connectivity.\n      - name: Direct Connect Gateways\n        description: Use gateways to connect to multiple VPCs across different regions through a single Direct Connect connection.\n      - name: Link Aggregation Groups\n        description: Bundle multiple connections into a LAG to increase\
  \ bandwidth and improve redundancy with active-active failover.\n      - name: Hosted Connections\n        description: Purchase sub-1G and 1G connections through Direct Connect partners for flexible capacity options.\n      - name: MACsec Encryption\n        description: Secure point-to-point Ethernet connections with 802.1AE MACsec encryption for data-in-transit security.\n  - type: UseCases\n    data:\n      - name: Hybrid Cloud Connectivity\n        description: Establish private, high-bandwidth connections between on-premises data centers and AWS for consistent hybrid workloads.\n      - name: Data Migration\n        description: Transfer large datasets to AWS efficiently using dedicated connections that offer higher throughput than internet-based transfers.\n      - name: Latency-Sensitive Applications\n        description: Run latency-sensitive applications that require consistent, predictable network performance to AWS services.\n      - name: Compliance and Security\n        description:\
  \ Meet regulatory requirements that mandate private network connections rather than internet-based access to cloud resources.\n      - name: Backup and Disaster Recovery\n        description: Create reliable backup and DR connections to AWS for on-premises infrastructure with predictable bandwidth for replication.\n  - type: Integrations\n    data:\n      - name: Amazon VPC\n        description: Connect directly to private VPC subnets using private virtual interfaces without internet exposure.\n      - name: AWS Transit Gateway\n        description: Use transit virtual interfaces to connect multiple VPCs and VPNs through a single gateway hub.\n      - name: AWS Direct Connect Partners\n        description: Purchase hosted connections and virtual interfaces through AWS Direct Connect delivery partners worldwide.\n      - name: AWS CloudFormation\n        description: Automate Direct Connect resource provisioning using CloudFormation templates for infrastructure as code.\n      - name: Amazon\
  \ Route 53 Resolver\n        description: Use Direct Connect for private DNS resolution between on-premises and AWS environments.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - AWS\n  - Dedicated Connection\n  - Direct Connect\n  - Hybrid Cloud\n  - Networking\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-direct-connect/refs/heads/main/apis.yml
tags:
- Dedicated Connection
- Direct Connect
- Hybrid Cloud
- Networking
url: https://aws.amazon.com/directconnect/
use_cases:
- description: Establish private, high-bandwidth connections between on-premises data centers and AWS for consistent hybrid workloads.
  name: Hybrid Cloud Connectivity
- description: Transfer large datasets to AWS efficiently using dedicated connections that offer higher throughput than internet-based transfers.
  name: Data Migration
- description: Run latency-sensitive applications that require consistent, predictable network performance to AWS services.
  name: Latency-Sensitive Applications
- description: Meet regulatory requirements that mandate private network connections rather than internet-based access to cloud resources.
  name: Compliance and Security
- description: Create reliable backup and DR connections to AWS for on-premises infrastructure with predictable bandwidth for replication.
  name: Backup and Disaster Recovery
---
