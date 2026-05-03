---
api_count: 1
api_specs:
- filename: replicate-openapi.yml
  format: yaml
  label: Replicate
  slug: replicate
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/openapi/replicate-openapi.yml
apis:
- description: Replicate lets you run machine learning models in the cloud with a simple REST API. Access thousands of open-source models for image generation, language modeling, audio synthesis, video generation, u
  name: Replicate
  slug: replicate
capabilities:
- description: Workflow capability for running AI model inference on Replicate. Covers creating predictions against versioned models and production deployments, monitoring prediction status, and canceling running jo
  name: Replicate Model Inference
  slug: model-inference
- description: Workflow capability for managing ML models, versions, deployments, and training jobs on Replicate. Covers the full model lifecycle from creation through versioning, fine-tuning with training jobs, and
  name: Replicate Model Management
  slug: model-management
common:
- title: ''
  type: Website
  url: https://replicate.com
- title: ''
  type: Documentation
  url: https://replicate.com/docs
- title: ''
  type: Pricing
  url: https://replicate.com/pricing
- title: ''
  type: Blog
  url: https://replicate.com/blog
- title: ''
  type: ChangeLog
  url: https://replicate.com/changelog
- title: ''
  type: TermsOfService
  url: https://replicate.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://replicate.com/privacy
- title: ''
  type: SignUp
  url: https://replicate.com/signin?next=/docs
- title: ''
  type: Login
  url: https://replicate.com/signin
- title: ''
  type: Playground
  url: https://replicate.com/explore
- title: ''
  type: GitHub Organization
  url: https://github.com/replicate
- title: ''
  type: SDKs
  url: https://replicate.com/docs/reference/client-libraries
- title: ''
  type: Python SDK
  url: https://github.com/replicate/replicate-python
- title: ''
  type: Node.js SDK
  url: https://github.com/replicate/replicate-javascript
- title: ''
  type: Go SDK
  url: https://github.com/replicate/replicate-go
- title: ''
  type: Swift SDK
  url: https://github.com/replicate/replicate-swift
- title: ''
  type: Cog
  url: https://github.com/replicate/cog
- title: ''
  type: Status
  url: https://status.replicate.com
created: '2024-11-13'
description: Replicate lets you run machine learning models in the cloud with a simple API. Thousands of open-source models are available, and you can run your own custom models at scale. Run image generation, language models, audio synthesis, video generation, and more with a few lines of code. Replicate makes AI accessible to every software engineer.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Replicate Context
  property_count: 32
  slug: replicate-context
layout: provider
modified: '2026-05-02'
name: Replicate
rules:
- name: Replicate API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 6
  slug: replicate-rules
skills: []
slug: replicate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: replicate\nname: Replicate\ndescription: >-\n  Replicate lets you run machine learning models in the cloud with a simple API.\n  Thousands of open-source models are available, and you can run your own custom\n  models at scale. Run image generation, language models, audio synthesis, video\n  generation, and more with a few lines of code. Replicate makes AI accessible\n  to every software engineer.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artificial Intelligence\n  - Machine Learning\n  - Image Generation\n  - Language Models\n  - Model Deployment\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/apis.yml\ncreated: '2024-11-13'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: replicate:replicate\n    name: Replicate\n    description: >-\n      Replicate lets you run machine learning models in the cloud with a simple\n      REST API. Access thousands\
  \ of open-source models for image generation,\n      language modeling, audio synthesis, video generation, upscaling, and more.\n      Create predictions, manage deployments, fine-tune models, and run training\n      jobs via a clean API with webhooks and streaming support.\n    humanURL: https://replicate.com/\n    tags:\n      - Accounts\n      - Artificial Intelligence\n      - Collections\n      - Deployments\n      - Hardware\n      - Machine Learning\n      - Models\n      - Predictions\n      - Training\n      - Webhooks\n    properties:\n      - url: https://replicate.com/docs\n        type: Documentation\n      - url: https://replicate.com/docs/reference/http\n        type: OpenAPI Documentation\n      - url: openapi/replicate-openapi.yml\n        type: OpenAPI\n      - url: rules/replicate-rules.yml\n        type: SpectralRuleset\n      - url: capabilities/model-inference.yaml\n        type: NaftikoCapability\n      - url: capabilities/model-management.yaml\n        type: NaftikoCapability\n\
  \      - url: vocabulary/replicate-vocabulary.yml\n        type: Vocabulary\ncommon:\n  - type: Website\n    url: https://replicate.com\n  - type: Documentation\n    url: https://replicate.com/docs\n  - type: Pricing\n    url: https://replicate.com/pricing\n  - type: Blog\n    url: https://replicate.com/blog\n  - type: ChangeLog\n    url: https://replicate.com/changelog\n  - type: TermsOfService\n    url: https://replicate.com/terms\n  - type: PrivacyPolicy\n    url: https://replicate.com/privacy\n  - type: SignUp\n    url: https://replicate.com/signin?next=/docs\n  - type: Login\n    url: https://replicate.com/signin\n  - type: Playground\n    url: https://replicate.com/explore\n  - type: GitHub Organization\n    url: https://github.com/replicate\n  - type: SDKs\n    url: https://replicate.com/docs/reference/client-libraries\n  - type: Python SDK\n    url: https://github.com/replicate/replicate-python\n  - type: Node.js SDK\n    url: https://github.com/replicate/replicate-javascript\n\
  \  - type: Go SDK\n    url: https://github.com/replicate/replicate-go\n  - type: Swift SDK\n    url: https://github.com/replicate/replicate-swift\n  - type: Cog\n    url: https://github.com/replicate/cog\n  - type: Status\n    url: https://status.replicate.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Machine Learning
- Image Generation
- Language Models
- Model Deployment
url: https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/apis.yml
use_cases: []
---
