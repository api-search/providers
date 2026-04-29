---
api_count: 1
api_specs:
- filename: amazon-medialive-openapi-original.yml
  format: yaml
  label: Amazon MediaLive API
  slug: medialive-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-medialive/refs/heads/main/openapi/amazon-medialive-openapi-original.yml
apis:
- description: AWS Elemental MediaLive is a broadcast-grade live video processing service that creates high-quality video streams for delivery to broadcast televisions and internet-connected multiscreen devices.
  name: Amazon MediaLive API
  slug: medialive-api
capabilities:
- description: Workflow capability for Amazon MediaLive media processing operations for broadcast engineers and media developers.
  name: Amazon MediaLive Workflow
  slug: amazon-medialive-media-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/medialive/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/medialive/
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
  url: https://console.aws.amazon.com/medialive/
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
  url: rules/amazon-medialive-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-medialive-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-medialive-media-workflow.yaml
created: '2026-03-16'
description: AWS Elemental MediaLive is a broadcast-grade live video processing service that creates high-quality video streams for delivery to broadcast televisions and internet-connected multiscreen devices.
features:
- description: Broadcast-grade live video encoding supporting H.264, H.265, and other professional codecs.
  name: Live Video Encoding
- description: Accept live video from RTP, RTMP, HLS pull, MediaConnect, MP4, and other source types.
  name: Multiple Input Types
- description: Pipeline redundancy for high-availability live events with automatic failover.
  name: Redundant Encoding
- description: Insert SCTE-35 markers for downstream ad replacement in live streams.
  name: Dynamic Ad Insertion Markers
- description: Deliver to HLS, DASH, RTMP, archive, UDP, MediaPackage, and other output destinations simultaneously.
  name: Multiple Output Groups
- description: Dynamically switch between input sources during a live event without interruption.
  name: Input Switching
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Receive high-quality video transport feeds from MediaConnect.
  name: AWS Elemental MediaConnect
- description: Send encoded outputs to MediaPackage for adaptive bitrate packaging.
  name: AWS Elemental MediaPackage
- description: Archive live stream recordings to S3 for storage and later processing.
  name: Amazon S3
- description: Monitor channel health metrics and set alerts for live events.
  name: Amazon CloudWatch
- description: Trigger workflows based on channel state change events.
  name: Amazon EventBridge
jsonld:
- class_count: 622
  name: Amazon Medialive Medialive Api Context
  property_count: 675
  slug: amazon-medialive-medialive-api-context
layout: provider
modified: '2026-04-19'
name: Amazon MediaLive
rules:
- name: Amazon MediaLive API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: amazon-medialive-spectral-rules
skills: []
slug: amazon-medialive
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-medialive\nname: Amazon MediaLive\ndescription: AWS Elemental MediaLive is a broadcast-grade live video processing service that creates high-quality video streams for delivery to broadcast televisions and internet-connected multiscreen\n  devices.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Broadcasting\n- Media Processing\n- Media\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-medialive/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-medialive:medialive-api\n  name: Amazon MediaLive API\n  description: AWS Elemental MediaLive is a broadcast-grade live video processing service that creates high-quality video streams for delivery to broadcast televisions and internet-connected \n    multiscreen devices.\n  humanURL: https://aws.amazon.com/medialive/\n  baseURL: http://medialive.{region}.amazonaws.com\n  tags:\n\
  \  - Broadcasting\n  - Media Processing\n  - Media\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/medialive/\n  - type: OpenAPI\n    url: openapi/amazon-medialive-openapi-original.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/medialive/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/medialive/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/medialive/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/medialive/\n- type: Documentation\n  url: https://docs.aws.amazon.com/medialive/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/media/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/medialive/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n\
  - type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-medialive-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-medialive-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-medialive-media-workflow.yaml\n- type: Features\n  data:\n  - name: Live Video Encoding\n    description: Broadcast-grade live video encoding supporting H.264, H.265, and other professional codecs.\n  - name: Multiple Input Types\n    description: Accept live video from RTP, RTMP, HLS pull, MediaConnect, MP4, and other source types.\n  - name: Redundant Encoding\n    description: Pipeline redundancy for high-availability live events with automatic failover.\n  - name: Dynamic Ad Insertion Markers\n    description: Insert SCTE-35 markers for downstream ad replacement in live streams.\n  - name: Multiple Output Groups\n    description: Deliver to HLS, DASH, RTMP,\
  \ archive, UDP, MediaPackage, and other output destinations simultaneously.\n  - name: Input Switching\n    description: Dynamically switch between input sources during a live event without interruption.\n- type: UseCases\n  data:\n  - name: Live Television Broadcast\n    description: Encode and deliver live TV channels with broadcast-grade quality.\n  - name: Live Sports Streaming\n    description: Handle large-scale live sports events with redundant pipelines.\n  - name: Live News Production\n    description: Create live news channel workflows with multi-source input switching.\n  - name: Virtual Events\n    description: Stream virtual conferences, concerts, and entertainment events.\n- type: Integrations\n  data:\n  - name: AWS Elemental MediaConnect\n    description: Receive high-quality video transport feeds from MediaConnect.\n  - name: AWS Elemental MediaPackage\n    description: Send encoded outputs to MediaPackage for adaptive bitrate packaging.\n  - name: Amazon S3\n    description:\
  \ Archive live stream recordings to S3 for storage and later processing.\n  - name: Amazon CloudWatch\n    description: Monitor channel health metrics and set alerts for live events.\n  - name: Amazon EventBridge\n    description: Trigger workflows based on channel state change events.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-medialive/refs/heads/main/apis.yml
tags:
- AWS
- Broadcasting
- Media Processing
- Media
url: https://raw.githubusercontent.com/api-evangelist/amazon-medialive/refs/heads/main/apis.yml
use_cases:
- description: Encode and deliver live TV channels with broadcast-grade quality.
  name: Live Television Broadcast
- description: Handle large-scale live sports events with redundant pipelines.
  name: Live Sports Streaming
- description: Create live news channel workflows with multi-source input switching.
  name: Live News Production
- description: Stream virtual conferences, concerts, and entertainment events.
  name: Virtual Events
---
