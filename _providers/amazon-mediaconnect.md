---
api_count: 1
api_specs:
- filename: amazon-mediaconnect-openapi-original.yml
  format: yaml
  label: AWS Elemental MediaConnect API
  slug: aws-elemental-mediaconnect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mediaconnect/refs/heads/main/openapi/amazon-mediaconnect-openapi-original.yml
apis:
- description: The AWS Elemental MediaConnect API provides programmatic access to create and manage flows, sources, outputs, entitlements, VPC interfaces, bridges, gateways, and media streams for reliable live video
  name: AWS Elemental MediaConnect API
  slug: aws-elemental-mediaconnect-api
capabilities:
- description: Workflow capability for live video transport operations including flow management, source configuration, output routing, and entitlement management for broadcast engineers.
  name: Amazon MediaConnect Live Video Transport
  slug: amazon-mediaconnect-live-video-transport
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/mediaconnect/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/mediaconnect/
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
  url: https://aws.amazon.com/blogs/media/tag/aws-elemental-mediaconnect/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/mediaconnect/
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
  url: rules/amazon-mediaconnect-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-mediaconnect-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-mediaconnect-live-video-transport.yaml
created: '2026-03-16'
description: AWS Elemental MediaConnect is a high-quality transport service for live video that provides the reliability, security, and visibility customers expect from traditional satellite and fiber services. It enables broadcasters to build live video workflows in the cloud with reliable transport of broadcast-quality content using protocols including Zixi, RIST, SRT, RTP, and RTP with FEC.
features:
- description: Supports Zixi, RIST, SRT, RTP, and RTP with FEC protocols for reliable live video delivery over IP networks.
  name: Video Transport Protocols
- description: Transmit compressed video between on-premises multicast environments and cloud infrastructure via the MediaConnect Gateway.
  name: Gateway Capability
- description: Handle uncompressed and visually-lossless video through AWS CDI and JPEG XS encoding with low-latency delivery.
  name: Uncompressed Video Support
- description: Built-in AES encryption with AWS Secrets Manager integration for encryption key management.
  name: End-to-End Encryption
- description: Grant partner and customer accounts controlled access to your video streams via entitlements.
  name: Entitlements
- description: Programmatically create and manage flows, sources, outputs, and VPC interfaces.
  name: Flow Management
- description: Visualize relationships between resources in live video workflows across connected AWS services.
  name: Workflow Monitor
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Send video flows to MediaLive for transcoding and processing.
  name: AWS Elemental MediaLive
- description: Monitor MediaConnect performance metrics and set alarms.
  name: Amazon CloudWatch
- description: Trigger event-driven workflows based on MediaConnect source health changes.
  name: Amazon EventBridge
- description: Deliver processed video content at scale using CloudFront.
  name: Amazon CloudFront
- description: Securely manage encryption keys for content protection.
  name: AWS Secrets Manager
jsonld:
- class_count: 246
  name: Amazon Mediaconnect Api Context
  property_count: 170
  slug: amazon-mediaconnect-api-context
layout: provider
modified: '2026-04-19'
name: Amazon MediaConnect
rules:
- name: Amazon MediaConnect API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-mediaconnect-spectral-rules
skills: []
slug: amazon-mediaconnect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-mediaconnect\nname: Amazon MediaConnect\ndescription: >-\n  AWS Elemental MediaConnect is a high-quality transport service for live video\n  that provides the reliability, security, and visibility customers expect from\n  traditional satellite and fiber services. It enables broadcasters to build\n  live video workflows in the cloud with reliable transport of broadcast-quality\n  content using protocols including Zixi, RIST, SRT, RTP, and RTP with FEC.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Broadcasting\n  - Live Video\n  - Media\n  - Media Transport\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-mediaconnect/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-mediaconnect:aws-elemental-mediaconnect-api\n    name: AWS Elemental MediaConnect API\n    description: >-\n      The AWS Elemental MediaConnect\
  \ API provides programmatic access to create\n      and manage flows, sources, outputs, entitlements, VPC interfaces, bridges,\n      gateways, and media streams for reliable live video transport in the cloud.\n    humanURL: https://aws.amazon.com/mediaconnect/\n    baseURL: https://mediaconnect.amazonaws.com\n    tags:\n      - Broadcasting\n      - Live Video\n      - Media Transport\n      - Flows\n      - Bridges\n      - Gateways\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/mediaconnect/latest/api/welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-mediaconnect-openapi-original.yml\n      - type: GettingStarted\n        url: https://aws.amazon.com/mediaconnect/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/mediaconnect/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/mediaconnect/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/mediaconnect/\n  - type: Documentation\n\
  \    url: https://docs.aws.amazon.com/mediaconnect/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/media/tag/aws-elemental-mediaconnect/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/mediaconnect/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-mediaconnect-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-mediaconnect-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/amazon-mediaconnect-live-video-transport.yaml\n  - type: Features\n    data:\n      -\
  \ name: Video Transport Protocols\n        description: Supports Zixi, RIST, SRT, RTP, and RTP with FEC protocols for reliable live video delivery over IP networks.\n      - name: Gateway Capability\n        description: Transmit compressed video between on-premises multicast environments and cloud infrastructure via the MediaConnect Gateway.\n      - name: Uncompressed Video Support\n        description: Handle uncompressed and visually-lossless video through AWS CDI and JPEG XS encoding with low-latency delivery.\n      - name: End-to-End Encryption\n        description: Built-in AES encryption with AWS Secrets Manager integration for encryption key management.\n      - name: Entitlements\n        description: Grant partner and customer accounts controlled access to your video streams via entitlements.\n      - name: Flow Management\n        description: Programmatically create and manage flows, sources, outputs, and VPC interfaces.\n      - name: Workflow Monitor\n        description:\
  \ Visualize relationships between resources in live video workflows across connected AWS services.\n  - type: UseCases\n    data:\n      - name: 24/7 TV Channel Operation\n        description: Transport continuous broadcast streams reliably for round-the-clock television channels.\n      - name: Live Event Streaming\n        description: Manage event-based video distribution for sports, concerts, news, and other live events.\n      - name: Content Sharing\n        description: Share live video feeds with partners and customers through controlled entitlements.\n      - name: Disaster Recovery\n        description: Provide redundant video pathways for business continuity in broadcast workflows.\n  - type: Integrations\n    data:\n      - name: AWS Elemental MediaLive\n        description: Send video flows to MediaLive for transcoding and processing.\n      - name: Amazon CloudWatch\n        description: Monitor MediaConnect performance metrics and set alarms.\n      - name: Amazon EventBridge\n\
  \        description: Trigger event-driven workflows based on MediaConnect source health changes.\n      - name: Amazon CloudFront\n        description: Deliver processed video content at scale using CloudFront.\n      - name: AWS Secrets Manager\n        description: Securely manage encryption keys for content protection.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediaconnect/refs/heads/main/apis.yml
tags:
- Broadcasting
- Live Video
- Media
- Media Transport
url: https://raw.githubusercontent.com/api-evangelist/amazon-mediaconnect/refs/heads/main/apis.yml
use_cases:
- description: Transport continuous broadcast streams reliably for round-the-clock television channels.
  name: 24/7 TV Channel Operation
- description: Manage event-based video distribution for sports, concerts, news, and other live events.
  name: Live Event Streaming
- description: Share live video feeds with partners and customers through controlled entitlements.
  name: Content Sharing
- description: Provide redundant video pathways for business continuity in broadcast workflows.
  name: Disaster Recovery
---
