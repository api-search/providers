---
api_count: 7
api_specs:
- filename: lucidworks-ai-platform-openapi.yml
  format: yaml
  label: Lucidworks AI Platform API
  slug: ai-platform
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/openapi/lucidworks-ai-platform-openapi.yml
- filename: lucidworks-embeddings-openapi.yml
  format: yaml
  label: Lucidworks Embeddings and Classification API
  slug: embeddings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/openapi/lucidworks-embeddings-openapi.yml
- filename: lucidworks-signals-openapi.yml
  format: yaml
  label: Lucidworks Signals API
  slug: signals
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/openapi/lucidworks-signals-openapi.yml
- filename: lucidworks-rules-openapi.yml
  format: yaml
  label: Lucidworks Rules and Query Rewrites API
  slug: rules
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/openapi/lucidworks-rules-openapi.yml
- filename: lucidworks-chunking-openapi.yml
  format: yaml
  label: Lucidworks Content Chunking API
  slug: chunking
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/openapi/lucidworks-chunking-openapi.yml
- filename: lucidworks-models-openapi.yml
  format: yaml
  label: Lucidworks Model Management API
  slug: models
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/openapi/lucidworks-models-openapi.yml
apis:
- description: The Lucidworks AI Platform API exposes prediction endpoints for FAQ enrichment, keyword extraction, named entity recognition, retrieval augmented generation (RAG), summarization, passthrough LLM calls
  name: Lucidworks AI Platform API
  slug: ai-platform
- description: 'The Embeddings and Classification API generates 768-dimensional vector encodings using the English Language Model text encoder, returns ranked classification labels, exposes custom model predictions, '
  name: Lucidworks Embeddings and Classification API
  slug: embeddings
- description: The Signals API captures and retrieves user behavior signals for click, query, cart-add, and purchase-complete events. Signals power relevance tuning, recommendations, and analytics across Commerce St
  name: Lucidworks Signals API
  slug: signals
- description: The Rules and Query Rewrites API allows commerce and search teams to create, read, update, and delete custom business rules and query rewrites. Rules drive boost, bury, pin, redirect, and synonym beha
  name: Lucidworks Rules and Query Rewrites API
  slug: rules
- description: The Content Chunking API splits long-form content into retrieval-ready passages using dynamic-sentence chunkers, semantic chunkers, and regex splitters. Chunked output feeds vector indexing and RAG pi
  name: Lucidworks Content Chunking API
  slug: chunking
- description: The Model Management API lets teams create, get, list, deploy, and delete models used by Lucidworks AI. Custom models can be registered and deployed alongside the default catalog for inference at quer
  name: Lucidworks Model Management API
  slug: models
- description: Fusion REST APIs administer collections, indexing pipelines, query pipelines, connectors, and search apps inside the Lucidworks Fusion platform. The legacy Custom Rules API for Fusion 5.7 is part of t
  name: Lucidworks Fusion REST API
  slug: fusion
common:
- title: ''
  type: Website
  url: https://lucidworks.com
- title: ''
  type: Documentation
  url: https://doc.lucidworks.com
- title: ''
  type: APIReference
  url: https://doc.lucidworks.com/api-reference
- title: ''
  type: Authentication
  url: https://doc.lucidworks.com/api-reference/request-access-token/request-access-token
- title: ''
  type: SDK
  url: https://doc.lucidworks.com/docs/5/fusion/dev-portal/connectors-sdk/overview
- title: ''
  type: Blog
  url: https://lucidworks.com/blog
created: '2025-01-07'
description: Lucidworks builds AI-powered search, discovery, and agent platforms used by enterprise commerce, support, and workplace teams. The Lucidworks AI Platform, Fusion, Neural Hybrid Search, Agent Studio, Commerce Studio, and Analytics Studio expose REST APIs for prediction, embedding, classification, signals capture, query rewriting, custom rule management, content chunking, and model deployment.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Lucidworks
skills: []
slug: lucidworks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: lucidworks\nname: Lucidworks\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ntags:\n  - Search\n  - Artificial Intelligence\n  - Enterprise Search\n  - Vector Search\n  - RAG\n  - Commerce\ncreated: '2025-01-07'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ndescription: >-\n  Lucidworks builds AI-powered search, discovery, and agent platforms used by\n  enterprise commerce, support, and workplace teams. The Lucidworks AI\n  Platform, Fusion, Neural Hybrid Search, Agent Studio, Commerce Studio, and\n  Analytics Studio expose REST APIs for prediction, embedding, classification,\n  signals capture, query rewriting, custom rule management, content chunking,\n  and model deployment.\napis:\n  - aid: lucidworks:ai-platform\n    name: Lucidworks AI Platform API\n    description: >-\n \
  \     The Lucidworks AI Platform API exposes prediction endpoints for FAQ\n      enrichment, keyword extraction, named entity recognition, retrieval\n      augmented generation (RAG), summarization, passthrough LLM calls, and\n      query rewriting. Developers can invoke pre-built use cases or chain\n      custom predictions, then fetch results asynchronously by prediction ID.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://doc.lucidworks.com/api-reference\n    baseURL: https://api.lucidworks.ai\n    tags:\n      - Artificial Intelligence\n      - Predictions\n      - RAG\n      - Summarization\n      - NER\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://doc.lucidworks.com/api-reference\n      - type: Authentication\n        url: https://doc.lucidworks.com/api-reference/request-access-token/request-access-token\n      - type: OpenAPI\n        url: openapi/lucidworks-ai-platform-openapi.yml\n\
  \  - aid: lucidworks:embeddings\n    name: Lucidworks Embeddings and Classification API\n    description: >-\n      The Embeddings and Classification API generates 768-dimensional vector\n      encodings using the English Language Model text encoder, returns ranked\n      classification labels, exposes custom model predictions, and tokenizes\n      inputs by model ID for use in vector search and downstream ML pipelines.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://doc.lucidworks.com/api-reference\n    baseURL: https://api.lucidworks.ai\n    tags:\n      - Embeddings\n      - Vector Search\n      - Classification\n      - Tokenization\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://doc.lucidworks.com/api-reference/get-predictions/english-language-model-text-encoder\n      - type: OpenAPI\n        url: openapi/lucidworks-embeddings-openapi.yml\n  - aid: lucidworks:signals\n    name:\
  \ Lucidworks Signals API\n    description: >-\n      The Signals API captures and retrieves user behavior signals for click,\n      query, cart-add, and purchase-complete events. Signals power relevance\n      tuning, recommendations, and analytics across Commerce Studio and the\n      Analytics Studio.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://doc.lucidworks.com/api-reference\n    baseURL: https://api.lucidworks.ai\n    tags:\n      - Signals\n      - Analytics\n      - Click Tracking\n      - Commerce\n    properties:\n      - type: Documentation\n        url: https://doc.lucidworks.com/api-reference/get-signals/click-signals\n      - type: OpenAPI\n        url: openapi/lucidworks-signals-openapi.yml\n  - aid: lucidworks:rules\n    name: Lucidworks Rules and Query Rewrites API\n    description: >-\n      The Rules and Query Rewrites API allows commerce and search teams to\n      create, read, update, and delete custom\
  \ business rules and query\n      rewrites. Rules drive boost, bury, pin, redirect, and synonym behaviors\n      that personalize search results without code changes.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://doc.lucidworks.com/api-reference/rule-management/list-rules\n    baseURL: https://api.lucidworks.ai\n    tags:\n      - Business Rules\n      - Query Rewrites\n      - Search Tuning\n      - Commerce\n    properties:\n      - type: Documentation\n        url: https://doc.lucidworks.com/api-reference/rule-management/list-rules\n      - type: Documentation\n        url: https://doc.lucidworks.com/api-reference/query-rewrite-management/list-query-rewrites\n      - type: OpenAPI\n        url: openapi/lucidworks-rules-openapi.yml\n  - aid: lucidworks:chunking\n    name: Lucidworks Content Chunking API\n    description: >-\n      The Content Chunking API splits long-form content into retrieval-ready\n      passages using\
  \ dynamic-sentence chunkers, semantic chunkers, and regex\n      splitters. Chunked output feeds vector indexing and RAG pipelines.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker\n    baseURL: https://api.lucidworks.ai\n    tags:\n      - Chunking\n      - Content Processing\n      - RAG\n      - Indexing\n    properties:\n      - type: Documentation\n        url: https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker\n      - type: OpenAPI\n        url: openapi/lucidworks-chunking-openapi.yml\n  - aid: lucidworks:models\n    name: Lucidworks Model Management API\n    description: >-\n      The Model Management API lets teams create, get, list, deploy, and\n      delete models used by Lucidworks AI. Custom models can be registered\n      and deployed alongside the default catalog\
  \ for inference at query and\n      indexing time.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://doc.lucidworks.com/api-reference/manage-models/list-all-models\n    baseURL: https://api.lucidworks.ai\n    tags:\n      - Model Management\n      - MLOps\n      - Deployment\n    properties:\n      - type: Documentation\n        url: https://doc.lucidworks.com/api-reference/manage-models/list-all-models\n      - type: OpenAPI\n        url: openapi/lucidworks-models-openapi.yml\n  - aid: lucidworks:fusion\n    name: Lucidworks Fusion REST API\n    description: >-\n      Fusion REST APIs administer collections, indexing pipelines, query\n      pipelines, connectors, and search apps inside the Lucidworks Fusion\n      platform. The legacy Custom Rules API for Fusion 5.7 is part of this\n      family of administrative endpoints.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis\n\
  \    tags:\n      - Fusion\n      - Enterprise Search\n      - Indexing\n      - Pipelines\n      - Connectors\n    properties:\n      - type: Documentation\n        url: https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis\n      - type: Documentation\n        url: https://legacydoc.lucidworks.com/fusion/5.7/331/custom-rules-api\ncommon:\n  - type: Website\n    url: https://lucidworks.com\n  - type: Documentation\n    url: https://doc.lucidworks.com\n  - type: APIReference\n    url: https://doc.lucidworks.com/api-reference\n  - type: Authentication\n    url: https://doc.lucidworks.com/api-reference/request-access-token/request-access-token\n  - type: SDK\n    url: https://doc.lucidworks.com/docs/5/fusion/dev-portal/connectors-sdk/overview\n  - type: Blog\n    url: https://lucidworks.com/blog\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/apis.yml
tags:
- Search
- Artificial Intelligence
- Enterprise Search
- Vector Search
- RAG
- Commerce
url: https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/apis.yml
use_cases: []
---
