---
api_count: 1
api_specs:
- filename: amazon-mediatailor-openapi-original.yml
  format: yaml
  label: Amazon MediaTailor API
  slug: mediatailor-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/openapi/amazon-mediatailor-openapi-original.yml
apis:
- description: AWS Elemental MediaTailor is a channel assembly and personalized ad-insertion service that enables you to monetize your video content with server-side targeted advertising while maintaining broadcast-
  name: Amazon MediaTailor API
  slug: mediatailor-api
capabilities:
- description: Workflow capability for Amazon MediaTailor media processing operations for broadcast engineers and media developers.
  name: Amazon MediaTailor Workflow
  slug: amazon-mediatailor-media-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/mediatailor/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/mediatailor/
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
  url: https://console.aws.amazon.com/mediatailor/
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
  url: rules/amazon-mediatailor-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-mediatailor-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-mediatailor-media-workflow.yaml
created: '2026-03-16'
description: AWS Elemental MediaTailor is a channel assembly and personalized ad-insertion service that enables you to monetize your video content with server-side targeted advertising while maintaining broadcast-quality.
features:
- description: Seamless ad replacement at the server side for consistent viewer experience across devices.
  name: Server-Side Ad Insertion
- description: Insert targeted ads based on viewer demographics, geography, and behavioral data.
  name: Personalized Ad Targeting
- description: Create linear channels from VOD assets and live streams with automated ad scheduling.
  name: Channel Assembly
- description: Connect to any VAST/VPAID-compliant ad decision server for programmatic advertising.
  name: Ad Decision Server Integration
- description: Configure ad insertion parameters, slate, and CDN settings per playback session.
  name: Playback Configuration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Ingest packaged live streams for ad insertion.
  name: AWS Elemental MediaPackage
- description: Deliver ad-inserted content via CloudFront with low latency.
  name: Amazon CloudFront
- description: Store VOD source content and slate media assets in S3.
  name: Amazon S3
- description: Monitor ad insertion metrics and playback session data.
  name: Amazon CloudWatch
jsonld:
- class_count: 154
  name: Amazon Mediatailor Mediatailor Api Context
  property_count: 116
  slug: amazon-mediatailor-mediatailor-api-context
layout: provider
modified: '2026-04-19'
name: Amazon MediaTailor
rules:
- name: Amazon MediaTailor API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: amazon-mediatailor-spectral-rules
skills: []
slug: amazon-mediatailor
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-mediatailor\nname: Amazon MediaTailor\ndescription: AWS Elemental MediaTailor is a channel assembly and personalized ad-insertion service that enables you to monetize your video content with server-side targeted advertising while \n  maintaining broadcast-quality.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Broadcasting\n- Media Processing\n- Media\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-mediatailor:mediatailor-api\n  name: Amazon MediaTailor API\n  description: AWS Elemental MediaTailor is a channel assembly and personalized ad-insertion service that enables you to monetize your video content with server-side targeted advertising while \n    maintaining broadcast-quality.\n  humanURL: https://aws.amazon.com/mediatailor/\n  baseURL: http://api.mediatailor.{region}.amazonaws.com\n\
  \  tags:\n  - Broadcasting\n  - Media Processing\n  - Media\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/mediatailor/\n  - type: OpenAPI\n    url: openapi/amazon-mediatailor-openapi-original.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/mediatailor/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/mediatailor/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/mediatailor/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/mediatailor/\n- type: Documentation\n  url: https://docs.aws.amazon.com/mediatailor/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/media/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/mediatailor/\n- type: SignUp\n  url:\
  \ https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-mediatailor-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-mediatailor-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-mediatailor-media-workflow.yaml\n- type: Features\n  data:\n  - name: Server-Side Ad Insertion\n    description: Seamless ad replacement at the server side for consistent viewer experience across devices.\n  - name: Personalized Ad Targeting\n    description: Insert targeted ads based on viewer demographics, geography, and behavioral data.\n  - name: Channel Assembly\n    description: Create linear channels from VOD assets and live streams with automated ad scheduling.\n  - name: Ad Decision Server Integration\n    description: Connect to any VAST/VPAID-compliant ad decision server for programmatic advertising.\n\
  \  - name: Playback Configuration\n    description: Configure ad insertion parameters, slate, and CDN settings per playback session.\n- type: UseCases\n  data:\n  - name: VOD Monetization\n    description: Insert targeted ads into video-on-demand content for revenue generation.\n  - name: Live Stream Advertising\n    description: Replace live ad markers with personalized ads during live events.\n  - name: FAST Channel Creation\n    description: Build free ad-supported streaming TV channels from VOD libraries.\n  - name: Addressable Advertising\n    description: Deliver personalized ad experiences to individual viewers at scale.\n- type: Integrations\n  data:\n  - name: AWS Elemental MediaPackage\n    description: Ingest packaged live streams for ad insertion.\n  - name: Amazon CloudFront\n    description: Deliver ad-inserted content via CloudFront with low latency.\n  - name: Amazon S3\n    description: Store VOD source content and slate media assets in S3.\n  - name: Amazon CloudWatch\n\
  \    description: Monitor ad insertion metrics and playback session data.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/apis.yml
tags:
- AWS
- Broadcasting
- Media Processing
- Media
url: https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/apis.yml
use_cases:
- description: Insert targeted ads into video-on-demand content for revenue generation.
  name: VOD Monetization
- description: Replace live ad markers with personalized ads during live events.
  name: Live Stream Advertising
- description: Build free ad-supported streaming TV channels from VOD libraries.
  name: FAST Channel Creation
- description: Deliver personalized ad experiences to individual viewers at scale.
  name: Addressable Advertising
---
