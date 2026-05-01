---
api_count: 1
api_specs:
- filename: amazon-mediastore-openapi-original.yml
  format: yaml
  label: Amazon MediaStore API
  slug: mediastore-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/openapi/amazon-mediastore-openapi-original.yml
apis:
- description: AWS Elemental MediaStore is an AWS storage service optimized for media, providing the performance, consistency, and low latency required to deliver live streaming video content at scale.
  name: Amazon MediaStore API
  slug: mediastore-api
capabilities:
- description: Workflow capability for Amazon MediaStore media processing operations for broadcast engineers and media developers.
  name: Amazon MediaStore Workflow
  slug: amazon-mediastore-media-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/mediastore/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/mediastore/
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
  url: https://aws.amazon.com/blogs/media/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/mediastore/
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
  url: rules/amazon-mediastore-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-mediastore-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-mediastore-media-workflow.yaml
created: '2026-03-16'
description: AWS Elemental MediaStore is an AWS storage service optimized for media, providing the performance, consistency, and low latency required to deliver live streaming video content at scale.
features:
- description: Optimized object storage for live video with consistent low-latency performance.
  name: High-Performance Media Storage
- description: Organize media assets in containers with fine-grained access control policies.
  name: Container and Object Management
- description: Cross-origin resource sharing configuration for browser-based media players.
  name: CORS Support
- description: Automatically expire and delete media objects based on age or other criteria.
  name: Lifecycle Policies
- description: Detailed access logs for auditing and monitoring media storage activity.
  name: Access Logging
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use MediaStore as an output destination for live encoded streams.
  name: AWS Elemental MediaLive
- description: Serve MediaStore content via CloudFront for global distribution.
  name: Amazon CloudFront
- description: Control access to MediaStore containers using IAM policies.
  name: AWS IAM
- description: Monitor MediaStore request metrics and latency.
  name: Amazon CloudWatch
jsonld:
- class_count: 83
  name: Amazon Mediastore Mediastore Api Context
  property_count: 27
  slug: amazon-mediastore-mediastore-api-context
layout: provider
modified: '2026-04-19'
name: Amazon MediaStore
rules:
- name: Amazon MediaStore API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: amazon-mediastore-spectral-rules
skills: []
slug: amazon-mediastore
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-mediastore\nname: Amazon MediaStore\ndescription: AWS Elemental MediaStore is an AWS storage service optimized for media, providing the performance, consistency, and low latency required to deliver live streaming video content at scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Broadcasting\n- Media Processing\n- Media\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-mediastore:mediastore-api\n  name: Amazon MediaStore API\n  description: AWS Elemental MediaStore is an AWS storage service optimized for media, providing the performance, consistency, and low latency required to deliver live streaming video content at \n    scale.\n  humanURL: https://aws.amazon.com/mediastore/\n  baseURL: http://mediastore.{region}.amazonaws.com\n  tags:\n  - Broadcasting\n\
  \  - Media Processing\n  - Media\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/mediastore/\n  - type: OpenAPI\n    url: openapi/amazon-mediastore-openapi-original.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/mediastore/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/mediastore/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/mediastore/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/mediastore/\n- type: Documentation\n  url: https://docs.aws.amazon.com/mediastore/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/media/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/mediastore/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n\
  - type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-mediastore-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-mediastore-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-mediastore-media-workflow.yaml\n- type: Features\n  data:\n  - name: High-Performance Media Storage\n    description: Optimized object storage for live video with consistent low-latency performance.\n  - name: Container and Object Management\n    description: Organize media assets in containers with fine-grained access control policies.\n  - name: CORS Support\n    description: Cross-origin resource sharing configuration for browser-based media players.\n  - name: Lifecycle Policies\n    description: Automatically expire and delete media objects based on age or other criteria.\n  - name: Access Logging\n    description: Detailed access logs for auditing and monitoring\
  \ media storage activity.\n- type: UseCases\n  data:\n  - name: Live Video Origin Storage\n    description: Use as a high-performance origin for live video workflows.\n  - name: Media Asset Management\n    description: Store and manage media files with low-latency access.\n  - name: Streaming Video Delivery\n    description: Serve HLS and DASH segments with consistent performance for video streaming.\n- type: Integrations\n  data:\n  - name: AWS Elemental MediaLive\n    description: Use MediaStore as an output destination for live encoded streams.\n  - name: Amazon CloudFront\n    description: Serve MediaStore content via CloudFront for global distribution.\n  - name: AWS IAM\n    description: Control access to MediaStore containers using IAM policies.\n  - name: Amazon CloudWatch\n    description: Monitor MediaStore request metrics and latency.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/apis.yml
tags:
- Broadcasting
- Media Processing
- Media
url: https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/apis.yml
use_cases:
- description: Use as a high-performance origin for live video workflows.
  name: Live Video Origin Storage
- description: Store and manage media files with low-latency access.
  name: Media Asset Management
- description: Serve HLS and DASH segments with consistent performance for video streaming.
  name: Streaming Video Delivery
---
