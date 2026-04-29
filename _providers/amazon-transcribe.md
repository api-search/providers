---
api_count: 1
apis:
- description: RESTful API for Amazon Transcribe speech-to-text operations including transcription jobs, vocabularies, and real-time streaming transcription.
  name: Amazon Transcribe REST API
  slug: ''
capabilities:
- description: ''
  name: Amazon Transcribe Capability
  slug: amazon-transcribe-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/transcribe/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/transcribe/
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
  url: https://aws.amazon.com/blogs/machine-learning/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/transcribe/
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
  url: https://stackoverflow.com/questions/tagged/amazon-transcribe
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/rules/amazon-transcribe-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/vocabulary/amazon-transcribe-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/capabilities/amazon-transcribe-capability.yaml
created: '2024-01-15'
description: Amazon Transcribe is a speech-to-text service that uses machine learning models to convert audio to text, supporting real-time streaming and batch transcription with automatic speech recognition (ASR).
features:
- description: Automate operational tasks with Amazon Transcribe.
  name: Automation
- description: Programmatic access to Amazon Transcribe resources.
  name: API Access
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 7
  name: Amazon Transcribe Context
  property_count: 5
  slug: amazon-transcribe-context
layout: provider
modified: '2026-04-19'
name: Amazon Transcribe
rules:
- name: Amazon Transcribe API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-transcribe-spectral-rules
skills: []
slug: amazon-transcribe
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Transcribe\ndescription: Amazon Transcribe is a speech-to-text service that uses machine learning models to convert audio to text, supporting real-time streaming and batch transcription with automatic speech \n  recognition (ASR).\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/transcribe/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Transcribe REST API\n  description: RESTful API for Amazon Transcribe speech-to-text operations including transcription jobs, vocabularies, and real-time streaming transcription.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/transcribe/\n  baseURL: https://transcribe.amazonaws.com\n  tags:\n  - AWS\n  - Machine Learning\n  - Speech-To-Text\n  - Transcription\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/transcribe/latest/APIReference/\n\
  \  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/openapi/amazon-transcribe-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/transcribe/2017-10-26/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-transcribe-job-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-transcribe-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/transcribe/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/transcribe/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/transcribe/latest/APIReference/CommonParameters.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: FAQ\n    url: https://aws.amazon.com/transcribe/faqs/\n  - type: Service Level Agreement\n    url: https://aws.amazon.com/machine-learning/language/sla/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/transcribe/latest/dg/what-is.html\n\
  \  - type: API Reference\n    url: https://docs.aws.amazon.com/transcribe/latest/APIReference/Welcome.html\n  - type: Code Examples\n    url: https://docs.aws.amazon.com/transcribe/latest/dg/service_code_examples.html\n  - type: Security\n    url: https://docs.aws.amazon.com/transcribe/latest/dg/security.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/transcribe/\n- type: Documentation\n  url: https://docs.aws.amazon.com/transcribe/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/machine-learning/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/transcribe/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n\
  - type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-transcribe\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/rules/amazon-transcribe-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/vocabulary/amazon-transcribe-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/capabilities/amazon-transcribe-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon Transcribe.\n  - name: API Access\n    description:\
  \ Programmatic access to Amazon Transcribe resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Transcribe to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- Audio Processing\n- AWS\n- Machine Learning\n- Speech Recognition\n- Speech-To-Text\n- Transcription\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/apis.yml
tags:
- Audio Processing
- AWS
- Machine Learning
- Speech Recognition
- Speech-To-Text
- Transcription
url: https://aws.amazon.com/transcribe/
use_cases:
- description: Use Amazon Transcribe to manage and automate cloud operations.
  name: Cloud Operations
---
