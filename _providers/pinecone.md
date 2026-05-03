---
api_count: 6
api_specs:
- filename: pinecone-db-control-openapi.yaml
  format: yaml
  label: Pinecone Database Control API
  slug: pinecone-database-control
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-db-control-openapi.yaml
- filename: pinecone-db-data-openapi.yaml
  format: yaml
  label: Pinecone Database Data API
  slug: pinecone-database-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-db-data-openapi.yaml
- filename: pinecone-inference-openapi.yaml
  format: yaml
  label: Pinecone Inference API
  slug: pinecone-inference
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-inference-openapi.yaml
- filename: pinecone-assistant-control-openapi.yaml
  format: yaml
  label: Pinecone Assistant Control API
  slug: pinecone-assistant-control
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-assistant-control-openapi.yaml
- filename: pinecone-assistant-data-openapi.yaml
  format: yaml
  label: Pinecone Assistant Data API
  slug: pinecone-assistant-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-assistant-data-openapi.yaml
- filename: pinecone-admin-openapi.yaml
  format: yaml
  label: Pinecone Admin API
  slug: pinecone-admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-admin-openapi.yaml
apis:
- description: Use the Database Control API to manage indexes, collections, and backups in Pinecone Database. The control plane handles lifecycle and configuration of vector storage resources.
  name: Pinecone Database Control API
  slug: pinecone-database-control
- description: Use the Database Data API to upsert, query, fetch, update, and delete vector records in Pinecone indexes. The data plane is the high-throughput interface for real-time vector search.
  name: Pinecone Database Data API
  slug: pinecone-database-data
- description: Use the Inference API to generate vector embeddings and rerank results using models hosted on Pinecone's infrastructure.
  name: Pinecone Inference API
  slug: pinecone-inference
- description: Use the Assistant Control API to create and manage Pinecone Assistants for retrieval-augmented generation (RAG) over your documents.
  name: Pinecone Assistant Control API
  slug: pinecone-assistant-control
- description: Use the Assistant Data API to upload documents to a Pinecone Assistant, ask questions, and receive responses grounded in those documents.
  name: Pinecone Assistant Data API
  slug: pinecone-assistant-data
- description: Use the Admin API to manage Pinecone organizations, projects, API keys, and service accounts at the platform level.
  name: Pinecone Admin API
  slug: pinecone-admin
common:
- title: ''
  type: Website
  url: https://www.pinecone.io/
- title: ''
  type: Pricing
  url: https://www.pinecone.io/pricing/
- title: ''
  type: Blog
  url: https://www.pinecone.io/blog/
- title: ''
  type: Newsroom
  url: https://www.pinecone.io/newsroom/news/
- title: ''
  type: Documentation
  url: https://docs.pinecone.io/guides/get-started/overview
- title: ''
  type: GettingStarted
  url: https://docs.pinecone.io/guides/get-started/overview
- title: ''
  type: Glossary
  url: https://docs.pinecone.io/guides/get-started/glossary
- title: ''
  type: Examples
  url: https://docs.pinecone.io/examples/notebooks
- title: ''
  type: ChangeLog
  url: https://docs.pinecone.io/release-notes/2024
- title: ''
  type: Status
  url: https://status.pinecone.io/
- title: ''
  type: Login
  url: https://app.pinecone.io
- title: ''
  type: Security
  url: https://www.pinecone.io/security/
- title: ''
  type: TermsOfService
  url: https://www.pinecone.io/legal/
- title: ''
  type: PrivacyPolicy
  url: https://www.pinecone.io/privacy/
- title: ''
  type: SDKs
  url: https://docs.pinecone.io/reference/pinecone-sdks
- title: ''
  type: Repository
  url: https://github.com/pinecone-io/pinecone-api
created: '2024-07-02'
description: With its vector database at the core, Pinecone is the leading knowledge platform for building accurate, secure, and scalable AI applications. The Pinecone APIs cover Database (vector storage and search), Inference (embeddings and reranking), Assistant (RAG over documents), and Admin (organization and project management).
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/introduction-pinecone-docs.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Pinecone
skills: []
slug: pinecone
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: pinecone\nname: Pinecone\ndescription: >-\n  With its vector database at the core, Pinecone is the leading knowledge platform\n  for building accurate, secure, and scalable AI applications. The Pinecone APIs\n  cover Database (vector storage and search), Inference (embeddings and reranking),\n  Assistant (RAG over documents), and Admin (organization and project management).\ntype: Contract\nposition: Consumer\naccess: 3rd-Party\nimage: >-\n  https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/introduction-pinecone-docs.png\ntags:\n  - Vector Databases\n  - AI\n  - Embeddings\n  - RAG\ncreated: '2024-07-02'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: pinecone:pinecone-database-control\n    name: Pinecone Database Control API\n    description: >-\n      Use the Database Control API to manage indexes, collections, and backups in\n      Pinecone\
  \ Database. The control plane handles lifecycle and configuration of\n      vector storage resources.\n    humanURL: https://docs.pinecone.io/reference/api/introduction\n    baseURL: https://api.pinecone.io\n    tags:\n      - Vector Databases\n      - Indexes\n      - Control Plane\n    properties:\n      - type: Documentation\n        url: https://docs.pinecone.io/reference/api/introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-db-control-openapi.yaml\n  - aid: pinecone:pinecone-database-data\n    name: Pinecone Database Data API\n    description: >-\n      Use the Database Data API to upsert, query, fetch, update, and delete vector\n      records in Pinecone indexes. The data plane is the high-throughput interface\n      for real-time vector search.\n    humanURL: https://docs.pinecone.io/reference/api/introduction\n    baseURL: https://{index_host}\n    tags:\n      - Vector Databases\n\
  \      - Vectors\n      - Data Plane\n    properties:\n      - type: Documentation\n        url: https://docs.pinecone.io/reference/api/introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-db-data-openapi.yaml\n  - aid: pinecone:pinecone-inference\n    name: Pinecone Inference API\n    description: >-\n      Use the Inference API to generate vector embeddings and rerank results using\n      models hosted on Pinecone's infrastructure.\n    humanURL: https://docs.pinecone.io/reference/api/introduction#inference-api\n    baseURL: https://api.pinecone.io\n    tags:\n      - Embeddings\n      - Reranking\n      - AI\n    properties:\n      - type: Documentation\n        url: https://docs.pinecone.io/reference/api/introduction#inference-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-inference-openapi.yaml\n\
  \  - aid: pinecone:pinecone-assistant-control\n    name: Pinecone Assistant Control API\n    description: >-\n      Use the Assistant Control API to create and manage Pinecone Assistants for\n      retrieval-augmented generation (RAG) over your documents.\n    humanURL: https://docs.pinecone.io/reference/api/introduction#assistant-api\n    baseURL: https://api.pinecone.io\n    tags:\n      - Assistants\n      - RAG\n      - Control Plane\n    properties:\n      - type: Documentation\n        url: https://docs.pinecone.io/reference/api/introduction#assistant-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-assistant-control-openapi.yaml\n  - aid: pinecone:pinecone-assistant-data\n    name: Pinecone Assistant Data API\n    description: >-\n      Use the Assistant Data API to upload documents to a Pinecone Assistant, ask\n      questions, and receive responses grounded in those documents.\n  \
  \  humanURL: https://docs.pinecone.io/reference/api/introduction#assistant-api\n    baseURL: https://prod-1-data.ke.pinecone.io\n    tags:\n      - Assistants\n      - RAG\n      - Data Plane\n    properties:\n      - type: Documentation\n        url: https://docs.pinecone.io/reference/api/introduction#assistant-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-assistant-data-openapi.yaml\n  - aid: pinecone:pinecone-admin\n    name: Pinecone Admin API\n    description: >-\n      Use the Admin API to manage Pinecone organizations, projects, API keys, and\n      service accounts at the platform level.\n    humanURL: https://docs.pinecone.io/reference/api/introduction\n    baseURL: https://api.pinecone.io\n    tags:\n      - Admin\n      - Organizations\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://docs.pinecone.io/reference/api/introduction\n      - type:\
  \ OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/openapi/pinecone-admin-openapi.yaml\ncommon:\n  - type: Website\n    url: https://www.pinecone.io/\n  - type: Pricing\n    url: https://www.pinecone.io/pricing/\n  - type: Blog\n    url: https://www.pinecone.io/blog/\n  - type: Newsroom\n    url: https://www.pinecone.io/newsroom/news/\n  - type: Documentation\n    url: https://docs.pinecone.io/guides/get-started/overview\n  - type: GettingStarted\n    url: https://docs.pinecone.io/guides/get-started/overview\n  - type: Features\n    url: https://docs.pinecone.io/guides/get-started/key-features\n  - type: Glossary\n    url: https://docs.pinecone.io/guides/get-started/glossary\n  - type: Examples\n    url: https://docs.pinecone.io/examples/notebooks\n  - type: Integrations\n    url: https://docs.pinecone.io/integrations/overview\n  - type: ChangeLog\n    url: https://docs.pinecone.io/release-notes/2024\n  - type: Status\n    url:\
  \ https://status.pinecone.io/\n  - type: Login\n    url: https://app.pinecone.io\n  - type: Security\n    url: https://www.pinecone.io/security/\n  - type: TermsOfService\n    url: https://www.pinecone.io/legal/\n  - type: PrivacyPolicy\n    url: https://www.pinecone.io/privacy/\n  - type: SDKs\n    url: https://docs.pinecone.io/reference/pinecone-sdks\n  - type: Repository\n    url: https://github.com/pinecone-io/pinecone-api\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/apis.yml
tags:
- Vector Databases
- AI
- Embeddings
- RAG
url: https://raw.githubusercontent.com/api-evangelist/pinecone/refs/heads/main/apis.yml
use_cases: []
---
