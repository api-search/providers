---
api_count: 4
apis:
- description: The Chroma Server API is a REST API that provides access to the Chroma open-source vector database. It enables developers to create and manage collections of embeddings, add documents with automatic t
  name: Chroma Server API
  slug: server-api
- description: Chroma Cloud is a managed, serverless vector database service that provides fast and scalable vector, full-text, and metadata search across terabytes of data. It is backed by Chroma's Apache 2.0 distr
  name: Chroma Cloud API
  slug: cloud-api
- description: The Chroma Python Client is a first-party SDK for interacting with both self-hosted Chroma servers and Chroma Cloud. It provides a simple, developer-friendly interface with a core API of just four fun
  name: Chroma Python Client
  slug: python-client
- description: The Chroma JavaScript and TypeScript Client is a first-party SDK for interacting with Chroma from JavaScript or TypeScript applications. The v3 rewrite focused on reducing bundle size and improving de
  name: Chroma JavaScript Client
  slug: javascript-client
common:
- title: ''
  type: Website
  url: https://www.trychroma.com/
- title: ''
  type: Documentation
  url: https://docs.trychroma.com/docs/overview/introduction
- title: ''
  type: Portal
  url: https://docs.trychroma.com/
- title: ''
  type: Login
  url: https://cloud.trychroma.com/
- title: ''
  type: Pricing
  url: https://docs.trychroma.com/cloud/pricing
- title: ''
  type: Blog
  url: https://www.trychroma.com/blog
- title: ''
  type: GitHubOrg
  url: https://github.com/chroma-core
- title: ''
  type: SourceCode
  url: https://github.com/chroma-core/chroma
- title: ''
  type: Discord
  url: https://discord.gg/MMeYNTmh3x
- title: ''
  type: Twitter
  url: https://twitter.com/trychroma
- title: ''
  type: License
  url: https://github.com/chroma-core/chroma/blob/main/LICENSE
- title: ''
  type: TermsOfService
  url: https://www.trychroma.com/tos
- title: ''
  type: PrivacyPolicy
  url: https://www.trychroma.com/privacy
- title: ''
  type: JSONLDContext
  url: json-ld/chroma-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/chroma-collection-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/chroma-record-schema.json
- title: ''
  type: Spectral
  url: spectral/chroma-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/chroma-capabilities.yml
- title: ''
  type: EmbeddingProviders
  url: ''
- title: ''
  type: Standards
  url: ''
created: '2025-03-07'
description: Chroma (Chroma DB) is an open-source AI-native embedding database designed to make it easy to build LLM applications by providing storage, retrieval, and management for vector embeddings, full-text search, regex search, and multi-modal retrieval (text, image, audio). Distributed under the Apache 2.0 license, Chroma can be self-hosted (single-node Python or distributed Rust-based deployment) or consumed via Chroma Cloud, a managed serverless vector database service offering usage-based pricing. Chroma is the open-source data infrastructure for AI agents and RAG (Retrieval-Augmented Generation) applications, with first-party SDKs for Python and JavaScript/TypeScript and integrations with leading embedding providers (OpenAI, Cohere, Hugging Face, sentence-transformers).
features:
- name: Document and Metadata Storage
- name: Vector Similarity Search (Dense, Sparse, Hybrid)
- name: Full-Text and Regex Search
- name: Metadata Filtering
- name: Multi-Modal Retrieval (Text, Image, Audio)
- name: Automatic Tokenization and Embedding
- name: Collection Management
- name: Embedding Function Plugins
- name: Self-Hosted and Cloud Deployments
- name: Apache 2.0 Open Source License
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Chroma Context
  property_count: 6
  slug: chroma-context
layout: provider
modified: '2026-04-23'
name: Chroma
skills: []
slug: chroma
solutions: []
source_yaml: "aid: chroma\nname: Chroma\nx-type: company\ndescription: >-\n  Chroma (Chroma DB) is an open-source AI-native embedding database designed\n  to make it easy to build LLM applications by providing storage, retrieval,\n  and management for vector embeddings, full-text search, regex search, and\n  multi-modal retrieval (text, image, audio). Distributed under the Apache\n  2.0 license, Chroma can be self-hosted (single-node Python or distributed\n  Rust-based deployment) or consumed via Chroma Cloud, a managed serverless\n  vector database service offering usage-based pricing. Chroma is the\n  open-source data infrastructure for AI agents and RAG (Retrieval-Augmented\n  Generation) applications, with first-party SDKs for Python and\n  JavaScript/TypeScript and integrations with leading embedding providers\n  (OpenAI, Cohere, Hugging Face, sentence-transformers).\nurl: https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/apis.yml\ntype: Index\nposition: Consumer\n\
  access: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - AI Native\n  - Apache 2.0\n  - Cloud\n  - Embeddings\n  - Hybrid Search\n  - JavaScript\n  - LLM\n  - Machine Learning\n  - Multi-Modal\n  - Open Source\n  - Python\n  - RAG\n  - Retrieval\n  - SDK\n  - Search\n  - Serverless\n  - TypeScript\n  - Vector Database\ncreated: '2025-03-07'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: chroma:server-api\n    name: Chroma Server API\n    description: >-\n      The Chroma Server API is a REST API that provides access to the Chroma\n      open-source vector database. It enables developers to create and manage\n      collections of embeddings, add documents with automatic tokenization and\n      embedding, and perform vector similarity searches. The API supports\n      metadata filtering, full-text search, and collection management\n      operations. An OpenAPI specification is available at the server\
  \ endpoint\n      for client generation in various programming languages.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trychroma.com\n    humanURL: https://docs.trychroma.com/reference/chroma-reference\n    tags:\n      - AI\n      - Embeddings\n      - Machine Learning\n      - Search\n      - Vector Database\n    properties:\n      - type: Documentation\n        url: https://docs.trychroma.com/reference/chroma-reference\n      - type: OpenAPI\n        url: openapi/chroma-server-api-openapi.yml\n  - aid: chroma:cloud-api\n    name: Chroma Cloud API\n    description: >-\n      Chroma Cloud is a managed, serverless vector database service that\n      provides fast and scalable vector, full-text, and metadata search across\n      terabytes of data. It is backed by Chroma's Apache 2.0 distributed\n      database and offers usage-based pricing with starter and team plans.\n      Developers can connect to Chroma Cloud using\
  \ the Python or JavaScript\n      client SDKs without needing to manage infrastructure.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trychroma.com\n    humanURL: https://docs.trychroma.com/cloud/pricing\n    tags:\n      - AI\n      - Cloud\n      - Embeddings\n      - Serverless\n      - Vector Database\n    properties:\n      - type: Documentation\n        url: https://docs.trychroma.com/cloud/sync/overview\n      - type: OpenAPI\n        url: openapi/chroma-cloud-api-openapi.yml\n  - aid: chroma:python-client\n    name: Chroma Python Client\n    description: >-\n      The Chroma Python Client is a first-party SDK for interacting with both\n      self-hosted Chroma servers and Chroma Cloud. It provides a simple,\n      developer-friendly interface with a core API of just four functions for\n      managing collections, adding documents, and querying embeddings. The\n      client handles automatic tokenization, embedding,\
  \ and indexing of\n      documents, making it straightforward to build AI applications that\n      require vector similarity search.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.trychroma.com/reference/python/client\n    tags:\n      - Embeddings\n      - Python\n      - SDK\n      - Vector Database\n    properties:\n      - type: Documentation\n        url: https://docs.trychroma.com/reference/python/client\n      - type: SourceCode\n        url: https://github.com/chroma-core/chroma\n  - aid: chroma:javascript-client\n    name: Chroma JavaScript Client\n    description: >-\n      The Chroma JavaScript and TypeScript Client is a first-party SDK for\n      interacting with Chroma from JavaScript or TypeScript applications. The\n      v3 rewrite focused on reducing bundle size and improving developer\n      experience, making it well-suited for deployment on serverless platforms\n      like Vercel. It supports both self-hosted\
  \ Chroma instances and Chroma\n      Cloud via the CloudClient class, providing collection management,\n      document ingestion, and vector similarity search capabilities.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.trychroma.com/reference/js/client\n    tags:\n      - Embeddings\n      - JavaScript\n      - SDK\n      - TypeScript\n      - Vector Database\n    properties:\n      - type: Documentation\n        url: https://docs.trychroma.com/reference/js/client\n      - type: SourceCode\n        url: https://github.com/chroma-core/chroma-js\ncommon:\n  - type: Website\n    url: https://www.trychroma.com/\n  - type: Documentation\n    url: https://docs.trychroma.com/docs/overview/introduction\n  - type: Portal\n    url: https://docs.trychroma.com/\n  - type: Login\n    url: https://cloud.trychroma.com/\n  - type: Pricing\n    url: https://docs.trychroma.com/cloud/pricing\n  - type: Blog\n    url: https://www.trychroma.com/blog\n\
  \  - type: GitHubOrg\n    url: https://github.com/chroma-core\n  - type: SourceCode\n    url: https://github.com/chroma-core/chroma\n  - type: Discord\n    url: https://discord.gg/MMeYNTmh3x\n  - type: Twitter\n    url: https://twitter.com/trychroma\n  - type: License\n    name: Apache License 2.0\n    url: https://github.com/chroma-core/chroma/blob/main/LICENSE\n  - type: TermsOfService\n    url: https://www.trychroma.com/tos\n  - type: PrivacyPolicy\n    url: https://www.trychroma.com/privacy\n  - type: JSONLDContext\n    url: json-ld/chroma-context.jsonld\n  - type: JSONSchema\n    url: json-schema/chroma-collection-schema.json\n  - type: JSONSchema\n    url: json-schema/chroma-record-schema.json\n  - type: Spectral\n    url: spectral/chroma-spectral.yml\n  - type: NaftikoCapabilities\n    url: naftiko/chroma-capabilities.yml\n  - name: Features\n    type: Features\n    data:\n      - name: Document and Metadata Storage\n      - name: Vector Similarity Search (Dense, Sparse, Hybrid)\n\
  \      - name: Full-Text and Regex Search\n      - name: Metadata Filtering\n      - name: Multi-Modal Retrieval (Text, Image, Audio)\n      - name: Automatic Tokenization and Embedding\n      - name: Collection Management\n      - name: Embedding Function Plugins\n      - name: Self-Hosted and Cloud Deployments\n      - name: Apache 2.0 Open Source License\n  - name: EmbeddingProviders\n    type: EmbeddingProviders\n    data:\n      - name: OpenAI\n      - name: Cohere\n      - name: Hugging Face\n      - name: sentence-transformers\n      - name: Google Vertex AI\n      - name: Ollama\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: RAG (Retrieval Augmented Generation)\n      - name: Semantic Search\n      - name: AI Agent Memory\n      - name: Code Search (AST-Aware Chunking)\n      - name: Recommendation Systems\n      - name: Multi-Modal Search (Text + Images)\n      - name: Question Answering Systems\n      - name: Knowledge Base Querying\n  - name: Standards\n \
  \   type: Standards\n    data:\n      - name: OpenAPI Specification\n      - name: REST/HTTP\n      - name: Apache License 2.0\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/apis.yml
tags:
- AI
- AI Native
- Apache 2.0
- Cloud
- Embeddings
- Hybrid Search
- JavaScript
- LLM
- Machine Learning
- Multi-Modal
- Open Source
- Python
- RAG
- Retrieval
- SDK
- Search
- Serverless
- TypeScript
- Vector Database
url: https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/apis.yml
use_cases:
- name: RAG (Retrieval Augmented Generation)
- name: Semantic Search
- name: AI Agent Memory
- name: Code Search (AST-Aware Chunking)
- name: Recommendation Systems
- name: Multi-Modal Search (Text + Images)
- name: Question Answering Systems
- name: Knowledge Base Querying
---
