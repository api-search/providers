---
api_count: 1
api_specs:
- filename: amazon-mediapackage-openapi-original.yml
  format: yaml
  label: Amazon MediaPackage API
  slug: mediapackage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mediapackage/refs/heads/main/openapi/amazon-mediapackage-openapi-original.yml
apis:
- description: AWS Elemental MediaPackage is a video origination and just-in-time packaging service that reliably prepares and protects video for delivery over the internet, creating multiple output formats from a s
  name: Amazon MediaPackage API
  slug: mediapackage-api
capabilities:
- description: Workflow capability for Amazon MediaPackage media processing operations for broadcast engineers and media developers.
  name: Amazon MediaPackage Workflow
  slug: amazon-mediapackage-media-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/mediapackage/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/mediapackage/
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
  url: https://console.aws.amazon.com/mediapackage/
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
  url: rules/amazon-mediapackage-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-mediapackage-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-mediapackage-media-workflow.yaml
created: '2026-03-16'
description: AWS Elemental MediaPackage is a video origination and just-in-time packaging service that reliably prepares and protects video for delivery over the internet, creating multiple output formats from a single video input.
features:
- description: Package live video into HLS, DASH, CMAF, and Microsoft Smooth Streaming formats on demand.
  name: Just-in-Time Packaging
- description: Integrated DRM support with PlayReady, Widevine, FairPlay, and SPEKE standard.
  name: Content Protection
- description: Enable start-over, catch-up TV, and pause live TV with configurable time windows.
  name: Time-Shifted Viewing
- description: Direct integration with CloudFront for scalable content delivery.
  name: CDN Integration
- description: Clip and archive live stream segments to S3 for VOD asset creation.
  name: Harvest Jobs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Receive live encoded streams from MediaLive for packaging.
  name: AWS Elemental MediaLive
- description: Distribute packaged content globally via CloudFront CDN.
  name: Amazon CloudFront
- description: Store harvested clips and VOD assets in S3.
  name: Amazon S3
- description: Manage DRM encryption keys with AWS KMS integration.
  name: AWS Key Management Service
jsonld:
- class_count: 79
  name: Amazon Mediapackage Mediapackage Api Context
  property_count: 73
  slug: amazon-mediapackage-mediapackage-api-context
layout: provider
modified: '2026-04-19'
name: Amazon MediaPackage
rules:
- name: Amazon MediaPackage API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: amazon-mediapackage-spectral-rules
skills: []
slug: amazon-mediapackage
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-mediapackage\nname: Amazon MediaPackage\ndescription: AWS Elemental MediaPackage is a video origination and just-in-time packaging service that reliably prepares and protects video for delivery over the internet, creating multiple output \n  formats from a single video input.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Broadcasting\n- Media Processing\n- Media\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-mediapackage/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-mediapackage:mediapackage-api\n  name: Amazon MediaPackage API\n  description: AWS Elemental MediaPackage is a video origination and just-in-time packaging service that reliably prepares and protects video for delivery over the internet, creating multiple output \n    formats from a single video input.\n  humanURL: https://aws.amazon.com/mediapackage/\n\
  \  baseURL: http://mediapackage.{region}.amazonaws.com\n  tags:\n  - Broadcasting\n  - Media Processing\n  - Media\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/mediapackage/\n  - type: OpenAPI\n    url: openapi/amazon-mediapackage-openapi-original.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/mediapackage/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/mediapackage/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/mediapackage/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/mediapackage/\n- type: Documentation\n  url: https://docs.aws.amazon.com/mediapackage/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/media/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/mediapackage/\n\
  - type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-mediapackage-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-mediapackage-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-mediapackage-media-workflow.yaml\n- type: Features\n  data:\n  - name: Just-in-Time Packaging\n    description: Package live video into HLS, DASH, CMAF, and Microsoft Smooth Streaming formats on demand.\n  - name: Content Protection\n    description: Integrated DRM support with PlayReady, Widevine, FairPlay, and SPEKE standard.\n  - name: Time-Shifted Viewing\n    description: Enable start-over, catch-up TV, and pause live TV with configurable time windows.\n  - name: CDN Integration\n    description: Direct integration with CloudFront for scalable content delivery.\n  - name: Harvest Jobs\n\
  \    description: Clip and archive live stream segments to S3 for VOD asset creation.\n- type: UseCases\n  data:\n  - name: Live OTT Streaming\n    description: Package live video for over-the-top delivery to mobile and connected devices.\n  - name: Time-Shifted Television\n    description: Enable catch-up TV and start-over viewing experiences.\n  - name: Multi-DRM Content Protection\n    description: Protect premium content with multiple DRM systems simultaneously.\n  - name: Live Clipping\n    description: Create VOD clips from live streams for highlights and replays.\n- type: Integrations\n  data:\n  - name: AWS Elemental MediaLive\n    description: Receive live encoded streams from MediaLive for packaging.\n  - name: Amazon CloudFront\n    description: Distribute packaged content globally via CloudFront CDN.\n  - name: Amazon S3\n    description: Store harvested clips and VOD assets in S3.\n  - name: AWS Key Management Service\n    description: Manage DRM encryption keys with AWS KMS\
  \ integration.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediapackage/refs/heads/main/apis.yml
tags:
- AWS
- Broadcasting
- Media Processing
- Media
url: https://raw.githubusercontent.com/api-evangelist/amazon-mediapackage/refs/heads/main/apis.yml
use_cases:
- description: Package live video for over-the-top delivery to mobile and connected devices.
  name: Live OTT Streaming
- description: Enable catch-up TV and start-over viewing experiences.
  name: Time-Shifted Television
- description: Protect premium content with multiple DRM systems simultaneously.
  name: Multi-DRM Content Protection
- description: Create VOD clips from live streams for highlights and replays.
  name: Live Clipping
---
