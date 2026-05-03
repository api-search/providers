---
api_count: 3
api_specs:
- filename: xiaomi-open-api-openapi.yml
  format: yaml
  label: Xiaomi Open API
  slug: xiaomi-open-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-open-api-openapi.yml
- filename: xiaomi-galaxy-fds-openapi.yml
  format: yaml
  label: Xiaomi Galaxy FDS API
  slug: xiaomi-galaxy-fds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-galaxy-fds-openapi.yml
- filename: xiaomi-mimo-api-openapi.yml
  format: yaml
  label: Xiaomi MiMo AI API
  slug: xiaomi-mimo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-mimo-api-openapi.yml
apis:
- description: The Xiaomi Open API provides OAuth 2.0 based access to user profile data, contact information, friend lists, and identity verification for Xiaomi account holders. It enables third-party applications t
  name: Xiaomi Open API
  slug: xiaomi-open-api
- description: 'Xiaomi Galaxy File Data Storage (FDS) is a cloud object storage service offering a RESTful API for storing, retrieving, and managing objects and buckets. It supports multipart uploads, access control '
  name: Xiaomi Galaxy FDS API
  slug: xiaomi-galaxy-fds
- description: The Xiaomi MiMo AI API provides OpenAI-compatible access to Xiaomi's MiMo large language models, including reasoning, coding, multimodal, and text-to-speech variants. Developers can use the API for ch
  name: Xiaomi MiMo AI API
  slug: xiaomi-mimo-api
capabilities:
- description: Capability for integrating Xiaomi MiMo large language models into applications. Provides access to reasoning, coding, multimodal, and text-to-speech AI capabilities via an OpenAI-compatible API.
  name: Xiaomi AI Language Models
  slug: ai-language-models
- description: Unified capability for Xiaomi cloud storage workflows combining Galaxy FDS object storage with account authentication. Enables developers to authenticate users and manage files in Xiaomi's cloud infra
  name: Xiaomi Cloud Storage
  slug: cloud-storage
common:
- title: ''
  type: Website
  url: https://www.mi.com
- title: ''
  type: Developer Portal
  url: https://dev.mi.com
- title: ''
  type: GitHub Organization
  url: https://github.com/XiaoMi
- title: ''
  type: SDK
  url: https://github.com/XiaoMi/galaxy-fds-sdk-python
- title: ''
  type: SDK
  url: https://github.com/XiaoMi/cloud-ml-sdk
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-schema/xiaomi-user-profile-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-schema/xiaomi-chat-completion-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-ld/xiaomi-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/vocabulary/xiaomi-vocabulary.yml
created: '2025-02-25'
description: Xiaomi is a multinational technology company headquartered in Beijing, China, that designs, develops, and sells a wide range of consumer electronics and related software services. The company is known for its smartphones, laptops, smart home devices, and other innovative products. Xiaomi offers developer APIs for IoT device control, cloud storage (Galaxy FDS), account/identity (Open API), machine learning (Cloud-ML), and AI language models (MiMo).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Xiaomi Context
  property_count: 2
  slug: xiaomi-context
layout: provider
modified: '2026-05-03'
name: Xiaomi
rules:
- name: Xiaomi API Rules
  rule_count: 8
  severity_counts:
    error: 0
    hint: 0
    info: 3
    warn: 5
  slug: xiaomi-rules
skills: []
slug: xiaomi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: xiaomi\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/apis.yml\nname: Xiaomi\ntags:\n  - Consumer Electronics\n  - IoT\n  - Smart Home\n  - Mobile\n  - Artificial Intelligence\n  - Cloud Storage\n  - Machine Learning\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-25'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Xiaomi is a multinational technology company headquartered in Beijing, China, that\n  designs, develops, and sells a wide range of consumer electronics and related software\n  services. The company is known for its smartphones, laptops, smart home devices,\n  and other innovative products. Xiaomi offers developer APIs for IoT device control,\n  cloud storage (Galaxy FDS), account/identity (Open API), machine learning (Cloud-ML),\n  and AI language models (MiMo).\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  specificationVersion: '0.19'\napis:\n  - aid: xiaomi:xiaomi-open-api\n    name: Xiaomi Open API\n    description: >-\n      The Xiaomi Open API provides OAuth 2.0 based access to user profile data,\n      contact information, friend lists, and identity verification for Xiaomi account\n      holders. It enables third-party applications to integrate Xiaomi account\n      authentication and access authorized user data.\n    humanURL: https://dev.mi.com/docs/passport/en/open-api/\n    baseURL: https://open.account.xiaomi.com\n    tags:\n      - Identity\n      - OAuth\n      - Authentication\n      - User Profile\n    properties:\n      - type: Documentation\n        url: https://dev.mi.com/docs/passport/en/open-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-open-api-openapi.yml\n    contact:\n      - FN: Xiaomi Developer\n        url: https://dev.mi.com/\n\n  - aid: xiaomi:xiaomi-galaxy-fds\n \
  \   name: Xiaomi Galaxy FDS API\n    description: >-\n      Xiaomi Galaxy File Data Storage (FDS) is a cloud object storage service offering\n      a RESTful API for storing, retrieving, and managing objects and buckets. It\n      supports multipart uploads, access control lists, object lifecycle operations,\n      and CDN prefetch/refresh capabilities.\n    humanURL: https://docs.api.xiaomi.com/en/fds/\n    baseURL: https://cnbj0.fds.api.xiaomi.com\n    tags:\n      - Cloud Storage\n      - Object Storage\n      - File Storage\n    properties:\n      - type: Documentation\n        url: https://docs.api.xiaomi.com/en/fds/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-galaxy-fds-openapi.yml\n\n  - aid: xiaomi:xiaomi-mimo-api\n    name: Xiaomi MiMo AI API\n    description: >-\n      The Xiaomi MiMo AI API provides OpenAI-compatible access to Xiaomi's MiMo\n      large language models, including reasoning,\
  \ coding, multimodal, and text-to-speech\n      variants. Developers can use the API for chat completions with models such as\n      mimo-v2.5-pro, mimo-v2.5, mimo-v2-omni, and mimo-v2-flash.\n    humanURL: https://platform.xiaomimimo.com/\n    baseURL: https://api.xiaomimimo.com\n    tags:\n      - Artificial Intelligence\n      - Language Models\n      - Chat Completions\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://platform.xiaomimimo.com/docs/api/chat/openai-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-mimo-api-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.mi.com\n  - type: Developer Portal\n    url: https://dev.mi.com\n  - type: GitHub Organization\n    url: https://github.com/XiaoMi\n  - type: SDK\n    url: https://github.com/XiaoMi/galaxy-fds-sdk-python\n  - type: SDK\n    url: https://github.com/XiaoMi/cloud-ml-sdk\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-schema/xiaomi-user-profile-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-schema/xiaomi-chat-completion-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-ld/xiaomi-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/vocabulary/xiaomi-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/apis.yml
tags:
- Consumer Electronics
- IoT
- Smart Home
- Mobile
- Artificial Intelligence
- Cloud Storage
- Machine Learning
url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/apis.yml
use_cases: []
---
