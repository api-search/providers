---
api_count: 3
api_specs:
- filename: jina-ai-embeddings-openapi.yml
  format: yaml
  label: Jina AI Embeddings API
  slug: embeddings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jina-ai/refs/heads/main/openapi/jina-ai-embeddings-openapi.yml
- filename: jina-ai-reader-openapi.yml
  format: yaml
  label: Jina AI Reader API
  slug: reader-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jina-ai/refs/heads/main/openapi/jina-ai-reader-openapi.yml
- filename: jina-ai-reranker-openapi.yml
  format: yaml
  label: Jina AI Reranker API
  slug: reranker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jina-ai/refs/heads/main/openapi/jina-ai-reranker-openapi.yml
apis:
- description: Generate high-quality embeddings from text, images, or code using Jina AI's state-of-the-art embedding models.
  name: Jina AI Embeddings API
  slug: embeddings-api
- description: Convert a URL to LLM-friendly input by simply adding r.jina.ai in front. Also supports search-based reading via s.jina.ai.
  name: Jina AI Reader API
  slug: reader-api
- description: Re-rank search results by relevance using Jina AI's reranker models to improve the quality of retrieved documents.
  name: Jina AI Reranker API
  slug: reranker-api
common:
- title: ''
  type: Website
  url: https://jina.ai
- title: ''
  type: Portal
  url: https://jina.ai/api-dashboard/
- title: ''
  type: Documentation
  url: https://docs.jina.ai/
- title: ''
  type: Getting Started
  url: https://docs.jina.ai/
- title: ''
  type: GitHub Organization
  url: https://github.com/jina-ai
- title: ''
  type: Sign Up
  url: https://jina.ai/api-dashboard/
created: '2025-02-06'
description: Jina AI provides Search Foundation APIs for AI-powered applications, offering embeddings, reranking, and web reading capabilities. Their Reader API converts URLs to LLM-friendly input by simply adding r.jina.ai in front.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Jina AI
skills: []
slug: jina-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jina-ai\nname: Jina AI\ndescription: >-\n  Jina AI provides Search Foundation APIs for AI-powered applications, offering\n  embeddings, reranking, and web reading capabilities. Their Reader API converts\n  URLs to LLM-friendly input by simply adding r.jina.ai in front.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Embeddings\n  - Machine Learning\n  - Reranking\n  - Search\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/jina-ai/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: jina-ai:embeddings-api\n    name: Jina AI Embeddings API\n    description: >-\n      Generate high-quality embeddings from text, images, or code using Jina\n      AI's state-of-the-art embedding models.\n    humanURL: https://jina.ai/embeddings/\n    baseURL: https://api.jina.ai/v1\n    tags:\n      - Embeddings\n\
  \      - Multimodal\n      - Text\n    properties:\n      - type: Documentation\n        url: https://docs.jina.ai/\n      - type: OpenAPI\n        url: openapi/jina-ai-embeddings-openapi.yml\n  - aid: jina-ai:reader-api\n    name: Jina AI Reader API\n    description: >-\n      Convert a URL to LLM-friendly input by simply adding r.jina.ai in front.\n      Also supports search-based reading via s.jina.ai.\n    humanURL: https://jina.ai/reader/\n    baseURL: https://r.jina.ai\n    tags:\n      - Content Extraction\n      - LLM\n      - Web Reading\n    properties:\n      - type: Documentation\n        url: https://jina.ai/reader/\n      - type: OpenAPI\n        url: openapi/jina-ai-reader-openapi.yml\n  - aid: jina-ai:reranker-api\n    name: Jina AI Reranker API\n    description: >-\n      Re-rank search results by relevance using Jina AI's reranker models\n      to improve the quality of retrieved documents.\n    humanURL: https://jina.ai/reranker/\n    baseURL: https://api.jina.ai/v1\n\
  \    tags:\n      - Relevance\n      - Reranking\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.jina.ai/\n      - type: OpenAPI\n        url: openapi/jina-ai-reranker-openapi.yml\ncommon:\n  - type: Website\n    url: https://jina.ai\n  - type: Portal\n    url: https://jina.ai/api-dashboard/\n  - type: Documentation\n    url: https://docs.jina.ai/\n  - type: Getting Started\n    url: https://docs.jina.ai/\n  - type: GitHub Organization\n    url: https://github.com/jina-ai\n  - type: Sign Up\n    url: https://jina.ai/api-dashboard/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jina-ai/refs/heads/main/apis.yml
tags:
- AI
- Embeddings
- Machine Learning
- Reranking
- Search
url: https://raw.githubusercontent.com/api-evangelist/jina-ai/refs/heads/main/apis.yml
use_cases: []
---
