---
api_count: 1
apis:
- description: 'The FASHN API is an asynchronous prediction service. Clients POST to /v1/run with a model_name and model-specific inputs, then poll /v1/status/{id} until the prediction completes. Authentication uses '
  name: FASHN
  slug: fashn
common:
- title: ''
  type: Website
  url: https://fashn.ai/
- title: ''
  type: Documentation
  url: https://fashn.ai/products/api
- title: ''
  type: API Documentation
  url: https://docs.fashn.ai/
- title: ''
  type: Developer Portal
  url: https://app.fashn.ai/api
created: '2025-03-01'
description: FASHN AI is an AI-first company specializing in human-centric generative image models tailored for fashion applications. The public API offers an asynchronous prediction workflow against a catalog of models including Try-On Max, Product to Model, Face to Model, Model Create, Model Swap, Edit, Reframe, Image to Video, and Background Remove.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: FASHN AI
skills: []
slug: fashn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fashn\nname: FASHN AI\ndescription: >-\n  FASHN AI is an AI-first company specializing in human-centric generative\n  image models tailored for fashion applications. The public API offers an\n  asynchronous prediction workflow against a catalog of models including\n  Try-On Max, Product to Model, Face to Model, Model Create, Model Swap, Edit,\n  Reframe, Image to Video, and Background Remove.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - AI\n  - Clothing\n  - Fashion\n  - Virtual Try-On\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: fashn:fashn\n    name: FASHN\n    tags:\n      - Clothing\n      - Fashion\n      - AI\n      - Virtual Try-On\n    humanURL: https://fashn.ai/products/api\n    baseURL: https://api.fashn.ai/v1\n    properties:\n\
  \      - url: https://fashn.ai/products/api\n        type: Documentation\n      - url: https://docs.fashn.ai/\n        type: API Documentation\n      - url: https://docs.fashn.ai/api-overview/api-fundamentals\n        type: API Reference\n      - url: https://app.fashn.ai/api\n        type: Developer Portal\n      - url: https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/openapi/fashn-openapi.yml\n        type: OpenAPI\n    description: >-\n      The FASHN API is an asynchronous prediction service. Clients POST to\n      /v1/run with a model_name and model-specific inputs, then poll\n      /v1/status/{id} until the prediction completes. Authentication uses a\n      Bearer token. Rate limits: 50 req/60s on /run, 50 req/10s on /status,\n      6 concurrent predictions. CDN outputs are retained for 72 hours.\ncommon:\n  - type: Website\n    url: https://fashn.ai/\n  - type: Documentation\n    url: https://fashn.ai/products/api\n  - type: API Documentation\n    url: https://docs.fashn.ai/\n\
  \  - type: Developer Portal\n    url: https://app.fashn.ai/api\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/apis.yml
tags:
- AI
- Clothing
- Fashion
- Virtual Try-On
url: https://raw.githubusercontent.com/api-evangelist/fashn/refs/heads/main/apis.yml
use_cases: []
---
