---
api_count: 5
api_specs:
- filename: typesense-search-api-openapi.yml
  format: yaml
  label: Typesense Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-search-api-openapi.yml
- filename: typesense-vector-search-api-openapi.yml
  format: yaml
  label: Typesense Vector Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-vector-search-api-openapi.yml
- filename: typesense-conversational-search-api-openapi.yml
  format: yaml
  label: Typesense Conversational Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-conversational-search-api-openapi.yml
- filename: typesense-analytics-api-openapi.yml
  format: yaml
  label: Typesense Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-analytics-api-openapi.yml
- filename: typesense-cloud-management-api-openapi.yml
  format: yaml
  label: Typesense Cloud Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/openapi/typesense-cloud-management-api-openapi.yml
apis:
- description: The core Typesense REST API for managing collections, indexing documents, and performing full-text, faceted, filtered, sorted, geo-based, and multi-search queries. Supports synonym sets, curation sets
  name: Typesense Search API
  slug: ''
- description: The Typesense Vector Search API extends the core search capabilities with vector and hybrid search. It supports indexing embedding fields, querying by vector proximity, and combining semantic vector s
  name: Typesense Vector Search API
  slug: ''
- description: The Typesense Conversational Search API enables AI-powered question answering over your search index. It supports conversation models (OpenAI, Cloudflare Workers AI), NL search models, and stateful mu
  name: Typesense Conversational Search API
  slug: ''
- description: The Typesense Analytics API tracks search events and provides insights into search behavior, popular queries, no-result queries, and click analytics. Supports rule-based aggregation and analytics data
  name: Typesense Analytics API
  slug: ''
- description: The Typesense Cloud Management API enables provisioning and managing Typesense Cloud clusters programmatically. Supports creating, updating, terminating clusters, scheduling configuration changes, man
  name: Typesense Cloud Management API
  slug: ''
capabilities:
- description: Unified search and discovery workflow combining Typesense full-text search, vector search, and conversational AI search. Used by application developers to deliver instant, relevant, and AI-powered sea
  name: Typesense Search and Discovery
  slug: search-and-discovery
common:
- title: ''
  type: Website
  url: https://typesense.org
- title: ''
  type: Documentation
  url: https://typesense.org/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/typesense
- title: ''
  type: Blog
  url: https://typesense.org/blog/
- title: ''
  type: Slack Community
  url: https://join.slack.com/t/typesense-community/shared_invite/zt-2fetvh0pw-ft5y2YQlq4FS3fVDFTfWJA
- title: ''
  type: Docker Hub
  url: https://hub.docker.com/r/typesense/typesense
- title: ''
  type: npm
  url: https://www.npmjs.com/package/typesense
- title: ''
  type: Pricing
  url: https://typesense.org/pricing/
- title: ''
  type: Terms of Service
  url: https://typesense.org/terms/
- title: ''
  type: Privacy Policy
  url: https://typesense.org/privacy/
- title: ''
  type: JSON-LD
  url: json-ld/typesense-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/typesense-collection-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/typesense-search-result-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/typesense-analytics-event-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/typesense-collection-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/typesense-search-result-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/typesense-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/typesense-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/search-and-discovery.yaml
created: '2026-05-03'
description: Typesense is a fast, typo-tolerant, open-source search engine designed for developer productivity. It provides instant search experiences with support for full-text search, faceting, filtering, sorting, geo-based search, vector search, and conversational AI search. Typesense is available as an open-source self-hosted solution or as a managed cloud service via Typesense Cloud.
features: []
image: https://typesense.org/favicon-32x32.png
integrations: []
jsonld:
- class_count: 0
  name: Typesense Context
  property_count: 12
  slug: typesense-context
layout: provider
modified: '2026-05-03'
name: Typesense
skills: []
slug: typesense
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Typesense\ndescription: >-\n  Typesense is a fast, typo-tolerant, open-source search engine designed for\n  developer productivity. It provides instant search experiences with support\n  for full-text search, faceting, filtering, sorting, geo-based search,\n  vector search, and conversational AI search. Typesense is available as an\n  open-source self-hosted solution or as a managed cloud service via\n  Typesense Cloud.\nimage: https://typesense.org/favicon-32x32.png\nurl: https://typesense.org\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Full-Text Search\n  - Open Source\n  - Search Engine\n  - Typo Tolerance\n  - Vector Search\napis:\n  - name: Typesense Search API\n    description: >-\n      The core Typesense REST API for managing collections, indexing documents,\n      and performing full-text, faceted, filtered, sorted, geo-based, and\n      multi-search queries. Supports synonym sets, curation sets, collection\n     \
  \ aliases, stopwords, presets, stemming dictionaries, API keys, and\n      cluster operations.\n    image: https://typesense.org/favicon-32x32.png\n    humanURL: https://typesense.org/docs/\n    baseURL: http://localhost:8108\n    tags:\n      - Collections\n      - Documents\n      - Full-Text Search\n      - Search\n    properties:\n      - type: Documentation\n        url: https://typesense.org/docs/\n      - type: OpenAPI\n        url: openapi/typesense-search-api-openapi.yml\n      - type: Getting Started\n        url: https://typesense.org/docs/guide/\n      - type: API Reference\n        url: https://typesense.org/docs/latest/api/\n\n  - name: Typesense Vector Search API\n    description: >-\n      The Typesense Vector Search API extends the core search capabilities\n      with vector and hybrid search. It supports indexing embedding fields,\n      querying by vector proximity, and combining semantic vector search\n      with keyword search for superior relevance.\n    image: https://typesense.org/favicon-32x32.png\n\
  \    humanURL: https://typesense.org/docs/guide/vector-search.html\n    baseURL: http://localhost:8108\n    tags:\n      - Embeddings\n      - Hybrid Search\n      - Semantic Search\n      - Vector Search\n    properties:\n      - type: Documentation\n        url: https://typesense.org/docs/guide/vector-search.html\n      - type: OpenAPI\n        url: openapi/typesense-vector-search-api-openapi.yml\n\n  - name: Typesense Conversational Search API\n    description: >-\n      The Typesense Conversational Search API enables AI-powered question\n      answering over your search index. It supports conversation models\n      (OpenAI, Cloudflare Workers AI), NL search models, and stateful\n      multi-turn conversations over indexed data.\n    image: https://typesense.org/favicon-32x32.png\n    humanURL: https://typesense.org/docs/guide/conversational-search-rag.html\n    baseURL: http://localhost:8108\n    tags:\n      - AI\n      - Conversational Search\n      - LLM\n      - RAG\n    properties:\n\
  \      - type: Documentation\n        url: https://typesense.org/docs/guide/conversational-search-rag.html\n      - type: OpenAPI\n        url: openapi/typesense-conversational-search-api-openapi.yml\n\n  - name: Typesense Analytics API\n    description: >-\n      The Typesense Analytics API tracks search events and provides insights\n      into search behavior, popular queries, no-result queries, and click\n      analytics. Supports rule-based aggregation and analytics data exports.\n    image: https://typesense.org/favicon-32x32.png\n    humanURL: https://typesense.org/docs/guide/analytics-query-suggestions.html\n    baseURL: http://localhost:8108\n    tags:\n      - Analytics\n      - Events\n      - Query Insights\n      - Search Analytics\n    properties:\n      - type: Documentation\n        url: https://typesense.org/docs/guide/analytics-query-suggestions.html\n      - type: OpenAPI\n        url: openapi/typesense-analytics-api-openapi.yml\n\n  - name: Typesense Cloud Management\
  \ API\n    description: >-\n      The Typesense Cloud Management API enables provisioning and managing\n      Typesense Cloud clusters programmatically. Supports creating, updating,\n      terminating clusters, scheduling configuration changes, managing server\n      configuration parameters, and generating API keys.\n    image: https://typesense.org/favicon-32x32.png\n    humanURL: https://typesense.org/docs/cloud-management-api/v1/cluster-management.html\n    baseURL: https://cloud.typesense.org/api/v1\n    tags:\n      - Cluster Management\n      - Cloud\n      - Infrastructure\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://typesense.org/docs/cloud-management-api/v1/cluster-management.html\n      - type: OpenAPI\n        url: openapi/typesense-cloud-management-api-openapi.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Website\n    url: https://typesense.org\n  - type: Documentation\n    url: https://typesense.org/docs/\n\
  \  - type: GitHub Organization\n    url: https://github.com/typesense\n  - type: Blog\n    url: https://typesense.org/blog/\n  - type: Slack Community\n    url: https://join.slack.com/t/typesense-community/shared_invite/zt-2fetvh0pw-ft5y2YQlq4FS3fVDFTfWJA\n  - type: Docker Hub\n    url: https://hub.docker.com/r/typesense/typesense\n  - type: npm\n    url: https://www.npmjs.com/package/typesense\n  - type: Pricing\n    url: https://typesense.org/pricing/\n  - type: Terms of Service\n    url: https://typesense.org/terms/\n  - type: Privacy Policy\n    url: https://typesense.org/privacy/\n  - type: JSON-LD\n    url: json-ld/typesense-context.jsonld\n  - type: JSONSchema\n    url: json-schema/typesense-collection-schema.json\n  - type: JSONSchema\n    url: json-schema/typesense-search-result-schema.json\n  - type: JSONSchema\n    url: json-schema/typesense-analytics-event-schema.json\n  - type: JSONStructure\n    url: json-structure/typesense-collection-structure.json\n  - type: JSONStructure\n\
  \    url: json-structure/typesense-search-result-structure.json\n  - type: Vocabulary\n    url: vocabulary/typesense-vocabulary.yml\n  - type: SpectralRules\n    url: rules/typesense-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/search-and-discovery.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/typesense/refs/heads/main/apis.yml
tags:
- Full-Text Search
- Open Source
- Search Engine
- Typo Tolerance
- Vector Search
url: https://typesense.org
use_cases: []
---
