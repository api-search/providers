---
api_count: 9
api_specs:
- filename: sanity-openapi.yml
  format: yaml
  label: Sanity Query API
  slug: sanity-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/openapi/sanity-openapi.yml
apis:
- description: The Sanity Query API enables querying Content Lake documents using GROQ (Graph-Relational Object Queries). Supports GET for queries under 11 KB and POST for larger queries. Available at both the stand
  name: Sanity Query API
  slug: sanity-query-api
- description: The Sanity Mutation API enables creating, updating, patching, and deleting documents in Content Lake. Mutations are submitted as arrays of operations (create, createOrReplace, createIfNotExists, patch
  name: Sanity Mutation API
  slug: sanity-mutation-api
- description: The Sanity Assets API handles uploading, retrieving, and managing file and image assets in Content Lake. Assets are stored as documents and referenced from content documents.
  name: Sanity Assets API
  slug: sanity-assets-api
- description: The Sanity Projects API enables programmatic management of Sanity projects including creating projects, managing datasets, configuring CORS origins, managing access tokens, and checking user permissio
  name: Sanity Projects API
  slug: sanity-projects-api
- description: 'The Sanity Webhooks API enables configuring event-driven notifications for content changes. Webhooks can be created to trigger on document create, update, delete, and publish events with customizable '
  name: Sanity Webhooks API
  slug: sanity-webhooks-api
- description: The Sanity Listen API provides real-time event streaming via Server-Sent Events (SSE) for content changes in a dataset. Clients can subscribe to a GROQ query and receive real-time notifications when m
  name: Sanity Listen API
  slug: sanity-listen-api
- description: The Sanity Roles API provides endpoints for managing user roles and permissions within Sanity projects. Supports predefined roles (Administrator, Read+Write, Read, Viewer) and custom role management.
  name: Sanity Roles API
  slug: sanity-roles-api
- description: The Sanity Scheduling API enables scheduling content for future publication or unpublication at specific times, supporting editorial workflows and content calendars.
  name: Sanity Scheduling API
  slug: sanity-scheduling-api
- description: The Sanity Embeddings Index API enables creating and managing vector embedding indexes for Content Lake documents, supporting semantic search and AI-powered content retrieval workflows.
  name: Sanity Embeddings Index API
  slug: sanity-embeddings-index-api
capabilities:
- description: Unified capability combining Sanity's Content API and Projects API for full content lifecycle management. Used by developers, content engineers, and editorial teams to query, create, update, and manag
  name: Sanity Content Management
  slug: content-management
common:
- title: ''
  type: Website
  url: https://www.sanity.io
- title: ''
  type: Documentation
  url: https://www.sanity.io/docs
- title: ''
  type: HTTP API Reference
  url: https://www.sanity.io/docs/http-reference
- title: ''
  type: Developer Portal
  url: https://www.sanity.io/docs
- title: ''
  type: GitHub Organization
  url: https://github.com/sanity-io
- title: ''
  type: Getting Started
  url: https://www.sanity.io/docs/getting-started-with-sanity
- title: ''
  type: JavaScript SDK
  url: https://www.npmjs.com/package/@sanity/client
- title: ''
  type: Pricing
  url: https://www.sanity.io/pricing
- title: ''
  type: Community
  url: https://slack.sanity.io
- title: ''
  type: Blog
  url: https://www.sanity.io/blog
- title: ''
  type: Status
  url: https://status.sanity.io
- title: ''
  type: Vocabulary
  url: vocabulary/sanity-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/sanity-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/content-management.yaml
- title: ''
  type: JSONLD
  url: json-ld/sanity-context.jsonld
created: '2026-05-02'
description: Sanity is a composable content platform providing a headless CMS with a real-time collaborative editor (Sanity Studio) and a powerful HTTP API for managing structured content. The Sanity Content Lake stores content as flexible documents queryable via GROQ (Graph-Relational Object Queries). Key API capabilities include document querying, mutations, real-time listening, asset management, project management, webhooks, scheduling, roles and permissions, vector embeddings, and AI-powered content agents.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sanity Context
  property_count: 12
  slug: sanity-context
layout: provider
modified: '2026-05-02'
name: Sanity
rules:
- name: Sanity API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: sanity-rules
skills: []
slug: sanity
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sanity\nname: Sanity\ndescription: >-\n  Sanity is a composable content platform providing a headless CMS with a\n  real-time collaborative editor (Sanity Studio) and a powerful HTTP API for\n  managing structured content. The Sanity Content Lake stores content as\n  flexible documents queryable via GROQ (Graph-Relational Object Queries).\n  Key API capabilities include document querying, mutations, real-time\n  listening, asset management, project management, webhooks, scheduling,\n  roles and permissions, vector embeddings, and AI-powered content agents.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Headless CMS\n  - Content Management\n  - GROQ\n  - Real-Time\n  - Structured Content\n  - Developer Platform\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nx-profiled: '2026-05'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n \
  \ - aid: sanity:sanity-query-api\n    name: Sanity Query API\n    description: >-\n      The Sanity Query API enables querying Content Lake documents using GROQ\n      (Graph-Relational Object Queries). Supports GET for queries under 11 KB\n      and POST for larger queries. Available at both the standard API endpoint\n      and a CDN endpoint for edge-cached results. Supports perspectives\n      (drafts, published), result source maps, and query explain functionality.\n    humanURL: https://www.sanity.io/docs/http-query\n    tags:\n      - GROQ\n      - Query\n      - Content Lake\n      - CDN\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/http-query\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/openapi/sanity-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sanity-document-schema.json\n      - type: JSONSchema\n        url: json-schema/sanity-webhook-schema.json\n\
  \n  - aid: sanity:sanity-mutation-api\n    name: Sanity Mutation API\n    description: >-\n      The Sanity Mutation API enables creating, updating, patching, and\n      deleting documents in Content Lake. Mutations are submitted as arrays\n      of operations (create, createOrReplace, createIfNotExists, patch,\n      delete) against a dataset endpoint.\n    humanURL: https://www.sanity.io/docs/http-reference\n    tags:\n      - Mutation\n      - Documents\n      - CRUD\n      - Content Lake\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/http-reference\n\n  - aid: sanity:sanity-assets-api\n    name: Sanity Assets API\n    description: >-\n      The Sanity Assets API handles uploading, retrieving, and managing\n      file and image assets in Content Lake. Assets are stored as\n      documents and referenced from content documents.\n    humanURL: https://www.sanity.io/docs/http-reference\n    tags:\n      - Assets\n      - Images\n      - Files\n \
  \     - Upload\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/http-reference\n\n  - aid: sanity:sanity-projects-api\n    name: Sanity Projects API\n    description: >-\n      The Sanity Projects API enables programmatic management of Sanity\n      projects including creating projects, managing datasets, configuring\n      CORS origins, managing access tokens, and checking user permissions.\n      Authentication uses Bearer tokens.\n    humanURL: https://www.sanity.io/docs/projects-api\n    tags:\n      - Projects\n      - Datasets\n      - Access Control\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/projects-api\n\n  - aid: sanity:sanity-webhooks-api\n    name: Sanity Webhooks API\n    description: >-\n      The Sanity Webhooks API enables configuring event-driven notifications\n      for content changes. Webhooks can be created to trigger on document\n      create, update, delete, and publish\
  \ events with customizable filter\n      expressions.\n    humanURL: https://www.sanity.io/docs/http-reference\n    tags:\n      - Webhooks\n      - Events\n      - Notifications\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/http-reference\n\n  - aid: sanity:sanity-listen-api\n    name: Sanity Listen API\n    description: >-\n      The Sanity Listen API provides real-time event streaming via\n      Server-Sent Events (SSE) for content changes in a dataset.\n      Clients can subscribe to a GROQ query and receive real-time\n      notifications when matching documents change.\n    humanURL: https://www.sanity.io/docs/http-reference\n    tags:\n      - Real-Time\n      - SSE\n      - Events\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/http-reference\n\n  - aid: sanity:sanity-roles-api\n    name: Sanity Roles API\n    description: >-\n      The Sanity Roles API provides\
  \ endpoints for managing user roles and\n      permissions within Sanity projects. Supports predefined roles\n      (Administrator, Read+Write, Read, Viewer) and custom role management.\n    humanURL: https://www.sanity.io/docs/roles-reference\n    tags:\n      - Roles\n      - Permissions\n      - Access Control\n      - Security\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/roles-reference\n\n  - aid: sanity:sanity-scheduling-api\n    name: Sanity Scheduling API\n    description: >-\n      The Sanity Scheduling API enables scheduling content for future\n      publication or unpublication at specific times, supporting\n      editorial workflows and content calendars.\n    humanURL: https://www.sanity.io/docs/http-reference\n    tags:\n      - Scheduling\n      - Publishing\n      - Content Calendar\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/http-reference\n\n  - aid: sanity:sanity-embeddings-index-api\n\
  \    name: Sanity Embeddings Index API\n    description: >-\n      The Sanity Embeddings Index API enables creating and managing vector\n      embedding indexes for Content Lake documents, supporting semantic\n      search and AI-powered content retrieval workflows.\n    humanURL: https://www.sanity.io/docs/http-reference\n    tags:\n      - Embeddings\n      - Vector Search\n      - AI\n      - Semantic Search\n    properties:\n      - type: Documentation\n        url: https://www.sanity.io/docs/http-reference\n\ncommon:\n  - type: Website\n    url: https://www.sanity.io\n  - type: Documentation\n    url: https://www.sanity.io/docs\n  - type: HTTP API Reference\n    url: https://www.sanity.io/docs/http-reference\n  - type: Developer Portal\n    url: https://www.sanity.io/docs\n  - type: GitHub Organization\n    url: https://github.com/sanity-io\n  - type: Getting Started\n    url: https://www.sanity.io/docs/getting-started-with-sanity\n  - type: JavaScript SDK\n    url: https://www.npmjs.com/package/@sanity/client\n\
  \  - type: Pricing\n    url: https://www.sanity.io/pricing\n  - type: Community\n    url: https://slack.sanity.io\n  - type: Blog\n    url: https://www.sanity.io/blog\n  - type: Status\n    url: https://status.sanity.io\n  - type: Vocabulary\n    url: vocabulary/sanity-vocabulary.yml\n  - type: SpectralRules\n    url: rules/sanity-rules.yml\n  - type: Capabilities\n    url: capabilities/content-management.yaml\n  - type: JSONLD\n    url: json-ld/sanity-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/apis.yml
tags:
- Headless CMS
- Content Management
- GROQ
- Real-Time
- Structured Content
- Developer Platform
url: https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/apis.yml
use_cases: []
---
