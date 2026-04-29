---
api_count: 1
apis:
- description: RESTful API for Amazon Translate machine translation operations including real-time translation, batch translation jobs, custom terminology, and parallel data management.
  name: Amazon Translate REST API
  slug: ''
capabilities:
- description: ''
  name: Amazon Translate Capability
  slug: amazon-translate-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/translate/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/translate/
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
  url: https://console.aws.amazon.com/translate/
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
  url: https://stackoverflow.com/questions/tagged/amazon-translate
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/rules/amazon-translate-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/vocabulary/amazon-translate-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/capabilities/amazon-translate-capability.yaml
created: '2024-01-15'
description: Amazon Translate is a neural machine translation service that delivers fast, high-quality, affordable, and customizable language translation for applications and content.
features:
- description: Automate operational tasks with Amazon Translate.
  name: Automation
- description: Programmatic access to Amazon Translate resources.
  name: API Access
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 7
  name: Amazon Translate Context
  property_count: 5
  slug: amazon-translate-context
layout: provider
modified: '2026-04-19'
name: Amazon Translate
rules:
- name: Amazon Translate API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-translate-spectral-rules
skills: []
slug: amazon-translate
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Translate\ndescription: Amazon Translate is a neural machine translation service that delivers fast, high-quality, affordable, and customizable language translation for applications and content.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/translate/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Translate REST API\n  description: RESTful API for Amazon Translate machine translation operations including real-time translation, batch translation jobs, custom terminology, and parallel data management.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/translate/\n  baseURL: https://translate.amazonaws.com\n  tags:\n  - AWS\n  - Machine Translation\n  - Natural Language Processing\n  - Translation\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/translate/latest/APIReference/\n\
  \  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/openapi/amazon-translate-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/translate/2017-07-01/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-translate-job-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-translate-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/translate/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/translate/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/translate/latest/APIReference/CommonParameters.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: FAQ\n    url: https://aws.amazon.com/translate/faqs/\n  - type: Service Level Agreement\n    url: https://aws.amazon.com/machine-learning/language/sla/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/translate/latest/dg/what-is.html\n\
  \  - type: API Reference\n    url: https://docs.aws.amazon.com/translate/latest/APIReference/Welcome.html\n  - type: Code Examples\n    url: https://docs.aws.amazon.com/translate/latest/dg/service_code_examples.html\n  - type: Security\n    url: https://docs.aws.amazon.com/translate/latest/dg/security.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/translate/\n- type: Documentation\n  url: https://docs.aws.amazon.com/translate/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/machine-learning/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/translate/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n\
  - type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-translate\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/rules/amazon-translate-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/vocabulary/amazon-translate-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/capabilities/amazon-translate-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon Translate.\n  - name: API Access\n    description: Programmatic\
  \ access to Amazon Translate resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Translate to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Language Processing\n- Localization\n- Machine Translation\n- NLP\n- Translation\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/apis.yml
tags:
- AWS
- Language Processing
- Localization
- Machine Translation
- NLP
- Translation
url: https://aws.amazon.com/translate/
use_cases:
- description: Use Amazon Translate to manage and automate cloud operations.
  name: Cloud Operations
---
