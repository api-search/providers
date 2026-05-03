---
api_count: 1
api_specs:
- filename: weaviate-openapi.yml
  format: yaml
  label: Weaviate REST API
  slug: weaviate-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/openapi/weaviate-openapi.yml
apis:
- description: The Weaviate REST API provides full programmatic access to vector database operations including object CRUD, schema management, GraphQL vector search, multi-tenancy, backups, authentication, authoriza
  name: Weaviate REST API
  slug: weaviate-rest-api
capabilities:
- description: Unified vector database workflow for managing Weaviate objects, schemas, vector search via GraphQL, backups, and cluster operations. Used by AI engineers, platform operators, and data engineers to bui
  name: Weaviate Vector Database
  slug: vector-database
common:
- title: ''
  type: Documentation
  url: https://weaviate.io/developers/weaviate/api/rest
- title: ''
  type: GitHubRepository
  url: https://github.com/weaviate/weaviate
- title: ''
  type: GitHubOrganization
  url: https://github.com/weaviate
- title: ''
  type: GettingStarted
  url: https://weaviate.io/developers/weaviate/quickstart
- title: ''
  type: Learn
  url: https://weaviate.io/developers/academy
- title: ''
  type: Blog
  url: https://weaviate.io/blog
- title: ''
  type: Community
  url: https://weaviate.io/community
- title: ''
  type: Forum
  url: https://forum.weaviate.io/
- title: ''
  type: Slack
  url: https://weaviate.io/slack
- title: ''
  type: Pricing
  url: https://weaviate.io/pricing
- title: ''
  type: Podcast
  url: https://weaviate.io/podcast
- title: ''
  type: Newsletter
  url: https://newsletter.weaviate.io/
- title: ''
  type: Events
  url: https://weaviate.io/community/events
- title: ''
  type: TermsOfService
  url: https://github.com/weaviate/weaviate/blob/master/LICENSE
- title: ''
  type: Security
  url: https://weaviate.io/security
- title: ''
  type: ChangeLog
  url: https://github.com/weaviate/weaviate/blob/master/CHANGELOG.md
- title: ''
  type: Support
  url: https://github.com/weaviate/weaviate/issues
- title: ''
  type: SpectralRules
  url: rules/weaviate-spectral-rules.yml
- title: Vector Database Capability
  type: NaftikoCapability
  url: capabilities/vector-database.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/weaviate-vocabulary.yml
created: '2024-06-18'
description: Weaviate is an open-source, AI-native vector database that enables developers to build semantic search and AI-powered applications. It stores data as vector embeddings alongside structured properties, enabling lightning-fast similarity search using HNSW or flat indexes. Weaviate supports multi-tenancy, automatic vectorization via configurable modules, GraphQL and REST APIs, and enterprise features including authentication, authorization, backups, and replication.
features:
- description: Stores data objects alongside their vector embeddings for high-performance similarity search using HNSW or flat indexes.
  name: Vector Storage
- description: Powerful GraphQL interface for vector similarity search (nearVector, nearText, nearObject, nearImage), hybrid search, and filtered queries.
  name: GraphQL Search API
- description: Pluggable vectorizer modules (text2vec, img2vec, etc.) automatically generate embeddings from object properties at write time.
  name: Automatic Vectorization
- description: Native multi-tenancy support with tenant isolation, allowing a single Weaviate instance to serve multiple customers with separate data.
  name: Multi-Tenancy
- description: Flexible schema with class and property definitions, cross-references, vector index configuration, and property-level vectorization settings.
  name: Schema Management
- description: Backup data to S3, GCS, Azure Blob Storage, or local filesystem and restore on demand for disaster recovery.
  name: Backup and Restore
- description: Role-based access control with fine-grained permissions for collections, objects, and operations. Supports API key and OIDC/JWT authentication.
  name: Authorization and RBAC
- description: Production-ready Kubernetes Helm chart with support for horizontal scaling, high availability, and major cloud providers.
  name: Kubernetes and Cloud Native
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Weaviate Context
  property_count: 402
  slug: weaviate-context
layout: provider
modified: '2026-05-03'
name: Weaviate
rules:
- name: Weaviate API Rules
  rule_count: 22
  severity_counts:
    error: 8
    hint: 0
    info: 8
    warn: 6
  slug: weaviate-spectral-rules
skills: []
slug: weaviate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: weaviate\nname: Weaviate\ndescription: >-\n  Weaviate is an open-source, AI-native vector database that enables developers\n  to build semantic search and AI-powered applications. It stores data as vector\n  embeddings alongside structured properties, enabling lightning-fast similarity\n  search using HNSW or flat indexes. Weaviate supports multi-tenancy, automatic\n  vectorization via configurable modules, GraphQL and REST APIs, and enterprise\n  features including authentication, authorization, backups, and replication.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Vector Database\n  - AI\n  - Machine Learning\n  - Semantic Search\n  - Open Source\n  - GraphQL\n  - Kubernetes\nurl: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/apis.yml\ncreated: '2024-06-18'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: weaviate:weaviate-rest-api\n\
  \    name: Weaviate REST API\n    description: >-\n      The Weaviate REST API provides full programmatic access to vector database\n      operations including object CRUD, schema management, GraphQL vector search,\n      multi-tenancy, backups, authentication, authorization, and cluster management.\n    humanURL: https://weaviate.io/developers/weaviate/api/rest\n    tags:\n      - Vector Database\n      - Objects\n      - Schema\n      - GraphQL\n      - Search\n      - AI\n    properties:\n      - url: openapi/weaviate-openapi.yml\n        type: OpenAPI\n      - url: https://weaviate.io/developers/weaviate/api/rest\n        type: Documentation\n      - url: https://weaviate.io/developers/weaviate/quickstart\n        type: GettingStarted\ncommon:\n  - url: https://weaviate.io/developers/weaviate/api/rest\n    type: Documentation\n  - url: https://github.com/weaviate/weaviate\n    type: GitHubRepository\n  - url: https://github.com/weaviate\n    type: GitHubOrganization\n  - url: https://weaviate.io/developers/weaviate/quickstart\n\
  \    type: GettingStarted\n  - url: https://weaviate.io/developers/academy\n    type: Learn\n  - url: https://weaviate.io/blog\n    type: Blog\n  - url: https://weaviate.io/community\n    type: Community\n  - url: https://forum.weaviate.io/\n    type: Forum\n  - url: https://weaviate.io/slack\n    type: Slack\n  - url: https://weaviate.io/pricing\n    type: Pricing\n  - url: https://weaviate.io/podcast\n    type: Podcast\n  - url: https://newsletter.weaviate.io/\n    type: Newsletter\n  - url: https://weaviate.io/community/events\n    type: Events\n  - url: https://github.com/weaviate/weaviate/blob/master/LICENSE\n    type: TermsOfService\n  - url: https://weaviate.io/security\n    type: Security\n  - url: https://github.com/weaviate/weaviate/blob/master/CHANGELOG.md\n    type: ChangeLog\n  - url: https://github.com/weaviate/weaviate/issues\n    type: Support\n  - type: SpectralRules\n    url: rules/weaviate-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/vector-database.yaml\n\
  \    title: Vector Database Capability\n  - type: Vocabulary\n    url: vocabulary/weaviate-vocabulary.yml\n  - type: Features\n    data:\n      - name: Vector Storage\n        description: >-\n          Stores data objects alongside their vector embeddings for\n          high-performance similarity search using HNSW or flat indexes.\n      - name: GraphQL Search API\n        description: >-\n          Powerful GraphQL interface for vector similarity search (nearVector,\n          nearText, nearObject, nearImage), hybrid search, and filtered queries.\n      - name: Automatic Vectorization\n        description: >-\n          Pluggable vectorizer modules (text2vec, img2vec, etc.) automatically\n          generate embeddings from object properties at write time.\n      - name: Multi-Tenancy\n        description: >-\n          Native multi-tenancy support with tenant isolation, allowing a single\n          Weaviate instance to serve multiple customers with separate data.\n      - name: Schema\
  \ Management\n        description: >-\n          Flexible schema with class and property definitions, cross-references,\n          vector index configuration, and property-level vectorization settings.\n      - name: Backup and Restore\n        description: >-\n          Backup data to S3, GCS, Azure Blob Storage, or local filesystem and\n          restore on demand for disaster recovery.\n      - name: Authorization and RBAC\n        description: >-\n          Role-based access control with fine-grained permissions for collections,\n          objects, and operations. Supports API key and OIDC/JWT authentication.\n      - name: Kubernetes and Cloud Native\n        description: >-\n          Production-ready Kubernetes Helm chart with support for horizontal\n          scaling, high availability, and major cloud providers.\n  - type: UseCases\n    data:\n      - name: Semantic Search\n        description: >-\n          Build semantic and hybrid search applications using vector similarity\n\
  \          and BM25 keyword search combined.\n      - name: RAG Applications\n        description: >-\n          Power Retrieval Augmented Generation (RAG) pipelines by storing and\n          retrieving relevant context for large language model prompts.\n      - name: Multi-Modal Search\n        description: >-\n          Search across text, images, and other modalities using unified vector\n          representations.\n      - name: AI-Powered Recommendations\n        description: >-\n          Build recommendation engines using object similarity search to find\n          related items based on vector proximity.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/apis.yml
tags:
- Vector Database
- AI
- Machine Learning
- Semantic Search
- Open Source
- GraphQL
- Kubernetes
url: https://raw.githubusercontent.com/api-evangelist/weaviate/refs/heads/main/apis.yml
use_cases:
- description: Build semantic and hybrid search applications using vector similarity and BM25 keyword search combined.
  name: Semantic Search
- description: Power Retrieval Augmented Generation (RAG) pipelines by storing and retrieving relevant context for large language model prompts.
  name: RAG Applications
- description: Search across text, images, and other modalities using unified vector representations.
  name: Multi-Modal Search
- description: Build recommendation engines using object similarity search to find related items based on vector proximity.
  name: AI-Powered Recommendations
---
