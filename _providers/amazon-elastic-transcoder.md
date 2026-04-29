---
api_count: 1
api_specs:
- filename: amazon-elastic-transcoder-openapi.yml
  format: yaml
  label: Amazon Elastic Transcoder API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-transcoder/refs/heads/main/openapi/amazon-elastic-transcoder-openapi.yml
apis:
- description: API for creating and managing media transcoding pipelines, presets, and jobs to convert media files for playback on various devices.
  name: Amazon Elastic Transcoder API
  slug: ''
capabilities:
- description: Unified capability for managing Amazon Elastic Transcoder resources. Combines Amazon Elastic Transcoder APIs for Media Engineer workflows in Media Processing.
  name: Amazon Elastic Transcoder Management
  slug: amazon-elastic-transcoder-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/elastictranscoder/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/elastictranscoder/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/elastictranscoder/
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
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/elastictranscoder/faqs/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/elastictranscoder
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-elastic-transcoder-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-elastic-transcoder-capability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-elastic-transcoder-vocabulary.yaml
created: '2024-01-15'
description: Amazon Elastic Transcoder is media transcoding in the cloud. It is designed to be a highly scalable, easy-to-use, and cost-effective way for developers and businesses to convert or transcode media files from their source format into versions that will play back on devices like smartphones, tablets, and PCs.
features:
- description: Create pipelines that manage media transcoding jobs with configurable input/output settings
  name: Managed Transcoding Pipelines
- description: Use built-in presets optimized for popular devices and formats
  name: Preset Library
- description: Create custom presets for specific output requirements
  name: Custom Presets
- description: Automatically generate thumbnails from video files during transcoding
  name: Thumbnail Generation
- description: Apply HLS content protection and digital rights management
  name: Content Protection
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Use S3 for input and output media file storage
  name: Amazon S3
- description: Receive notifications when transcoding jobs complete
  name: Amazon SNS
- description: Distribute transcoded content via CDN
  name: Amazon CloudFront
- description: Trigger transcoding workflows from Lambda functions
  name: AWS Lambda
jsonld:
- class_count: 67
  name: Amazon Elastic Transcoder Context
  property_count: 108
  slug: amazon-elastic-transcoder-context
layout: provider
modified: '2026-04-19'
name: Amazon Elastic Transcoder
rules:
- name: Amazon Elastic Transcoder API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-elastic-transcoder-spectral-rules
skills: []
slug: amazon-elastic-transcoder
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Elastic Transcoder\ndescription: Amazon Elastic Transcoder is media transcoding in the cloud. It is designed to be a highly scalable, easy-to-use, and cost-effective way for developers and businesses to convert or \n  transcode media files from their source format into versions that will play back on devices like smartphones, tablets, and PCs.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/elastictranscoder/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Amazon Web Services\n- AWS\n- Media\n- Transcoding\n- Video\napis:\n- name: Amazon Elastic Transcoder API\n  description: API for creating and managing media transcoding pipelines, presets, and jobs to convert media files for playback on various devices.\n  humanURL: https://aws.amazon.com/elastictranscoder/\n  baseURL: https://elastictranscoder.amazonaws.com\n  tags:\n  - Media\n  - Transcoding\n  - Video\n\
  \  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/elastictranscoder/latest/developerguide/\n  - type: OpenAPI\n    url: openapi/amazon-elastic-transcoder-openapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/elastictranscoder/latest/developerguide/api-reference.html\n  - type: GettingStarted\n    url: https://aws.amazon.com/elastictranscoder/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/elastictranscoder/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/elastictranscoder/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-elastic-transcoder-access-control-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-elastic-transcoder-access-controls-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-elastic-transcoder-access-denied-exception-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-elastic-transcoder-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type:\
  \ DeveloperPortal\n  url: https://aws.amazon.com/elastictranscoder/\n- type: Documentation\n  url: https://docs.aws.amazon.com/elastictranscoder/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/elastictranscoder/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: FAQ\n  url: https://aws.amazon.com/elastictranscoder/faqs/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n\
  \  url: https://stackoverflow.com/questions/tagged/elastictranscoder\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-elastic-transcoder-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-elastic-transcoder-capability.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/api.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-elastic-transcoder-vocabulary.yaml\n- type: Features\n  data:\n  - name: Managed Transcoding Pipelines\n    description: Create pipelines that manage media transcoding jobs with configurable input/output settings\n  - name: Preset Library\n    description: Use built-in presets optimized for popular devices and formats\n  - name: Custom Presets\n    description: Create custom presets for specific output requirements\n  - name: Thumbnail Generation\n    description: Automatically generate thumbnails from video files\
  \ during transcoding\n  - name: Content Protection\n    description: Apply HLS content protection and digital rights management\n- type: UseCases\n  data:\n  - name: Video-on-Demand Transcoding\n    description: Convert video files for streaming across different devices and bandwidths\n  - name: Mobile Video Delivery\n    description: Transcode content optimized for smartphone and tablet playback\n  - name: HLS Streaming\n    description: Create adaptive bitrate HLS streams for seamless playback\n  - name: Audio File Conversion\n    description: Convert audio files between different formats and bitrates\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Use S3 for input and output media file storage\n  - name: Amazon SNS\n    description: Receive notifications when transcoding jobs complete\n  - name: Amazon CloudFront\n    description: Distribute transcoded content via CDN\n  - name: AWS Lambda\n    description: Trigger transcoding workflows from Lambda functions\n\
  maintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-transcoder/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- AWS
- Media
- Transcoding
- Video
url: https://aws.amazon.com/elastictranscoder/
use_cases:
- description: Convert video files for streaming across different devices and bandwidths
  name: Video-on-Demand Transcoding
- description: Transcode content optimized for smartphone and tablet playback
  name: Mobile Video Delivery
- description: Create adaptive bitrate HLS streams for seamless playback
  name: HLS Streaming
- description: Convert audio files between different formats and bitrates
  name: Audio File Conversion
---
