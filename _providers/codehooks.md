---
api_count: 2
api_specs:
- filename: codehooks-database-rest-api-openapi.yml
  format: yaml
  label: Codehooks Database REST API
  slug: codehooks-database-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/openapi/codehooks-database-rest-api-openapi.yml
- filename: codehooks-events-asyncapi.yml
  format: yaml
  label: Codehooks Events (AsyncAPI)
  slug: codehooks-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/asyncapi/codehooks-events-asyncapi.yml
apis:
- description: Auto-generated, secure REST API for Codehooks NoSQL collections, the built-in key-value store, and queue topics. Supports MongoDB-style query operators ($gt, $lt, $in, $nin, $exists, $regex, $or, $and
  name: Codehooks Database REST API
  slug: codehooks-database-rest-api
- description: 'Asynchronous CRUD lifecycle hooks (onBeforeCreate, onAfterCreate, onBeforeRead, onAfterRead, onBeforeUpdate, onAfterUpdate, onBeforeDelete, onAfterDelete) and queue worker processing (onQueueJob) for '
  name: Codehooks Events (AsyncAPI)
  slug: codehooks-events
asyncapis:
- description: Asynchronous event API for Codehooks serverless backend hooks and queue workers. Covers CRUD lifecycle hooks triggered on collection document operations and asynchronous queue worker processing for na
  name: Codehooks Events API
  slug: codehooks-events-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://codehooks.io/
- title: ''
  type: Documentation
  url: https://codehooks.io/docs/
- title: ''
  type: GettingStarted
  url: https://codehooks.io/docs/quickstart-cli
- title: ''
  type: Blog
  url: https://codehooks.io/blog
- title: ''
  type: Pricing
  url: https://codehooks.io/#pricing
- title: ''
  type: GitHub
  url: https://github.com/RestDB
- title: ''
  type: NPMPackage
  url: https://www.npmjs.com/package/codehooks-js
- title: ''
  type: TermsOfService
  url: https://codehooks.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://codehooks.io/privacy
- title: ''
  type: JSON-LD
  url: json-ld/codehooks-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/codehooks-document-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/codehooks-key-value-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/codehooks-queue-job-schema.json
- title: ''
  type: Spectral
  url: rules/codehooks-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/codehooks-capabilities.yml
created: '2025-02-08'
description: Codehooks is a JavaScript-native serverless backend platform that bundles a NoSQL document database, key-value store, persistent queues with workers, CRON jobs, blob storage, frontend hosting, and an automatic CRUD REST API in a single CLI-deployable runtime. Developers write small Node.js handler files and Codehooks generates a secure REST API, OpenAPI documentation, and event hooks (onBefore/onAfter Create/Read/Update/Delete) without managing servers. The platform targets agent-native and AI backend use cases where simple, fast, MongoDB-style data access and event-driven automation matter.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Codehooks Context
  property_count: 12
  slug: codehooks-context
layout: provider
modified: '2026-04-26'
name: Codehooks
rules:
- name: Codehooks API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 3
    warn: 3
  slug: codehooks-rules
skills: []
slug: codehooks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: codehooks\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/apis.yml\nname: Codehooks\ntags:\n  - Backend\n  - Database\n  - Events\n  - Hooks\n  - JavaScript\n  - NoSQL\n  - Queues\n  - Serverless\n  - Webhooks\n  - Workers\n  - Workflows\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2025-02-08'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  Codehooks is a JavaScript-native serverless backend platform that bundles a\n  NoSQL document database, key-value store, persistent queues with workers,\n  CRON jobs, blob storage, frontend hosting, and an automatic CRUD REST API\n  in a single CLI-deployable runtime. Developers write small Node.js handler\n  files and Codehooks generates a secure REST API, OpenAPI documentation,\n  and event hooks (onBefore/onAfter Create/Read/Update/Delete) without\n  managing servers. The platform\
  \ targets agent-native and AI backend use\n  cases where simple, fast, MongoDB-style data access and event-driven\n  automation matter.\napis:\n  - aid: codehooks:codehooks-database-rest-api\n    name: Codehooks Database REST API\n    tags:\n      - CRUD\n      - Database\n      - Documents\n      - Key-Value\n      - NoSQL\n      - Queues\n      - REST\n    humanURL: https://codehooks.io/docs/\n    baseURL: https://{projectId}.api.codehooks.io/{space}\n    properties:\n      - url: https://codehooks.io/docs/\n        type: Documentation\n      - url: https://codehooks.io/docs/restapi\n        type: APIReference\n      - url: openapi/codehooks-database-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      Auto-generated, secure REST API for Codehooks NoSQL collections, the\n      built-in key-value store, and queue topics. Supports MongoDB-style\n      query operators ($gt, $lt, $in, $nin, $exists, $regex, $or, $and),\n      pagination, sorting, field selection, bulk\
  \ update/delete by query,\n      counts, and increment/decrement on key-value entries. Authenticated\n      via API key.\n    x-features:\n      - Automatic CRUD REST API via app.crudlify()\n      - MongoDB-like query language with $gt/$lt/$in/$exists/$regex/$or/$and\n      - Pagination, sort, field selection\n      - Bulk updateByQuery and deleteByQuery\n      - Key-value cache with TTL plus increment/decrement\n      - Persistent queue API for asynchronous job processing\n      - Auto-generated OpenAPI/Swagger from schema\n      - Sub-5-second deploys via the codehooks CLI\n    x-use-cases:\n      - Internal CRUD apps and admin dashboards\n      - Webhook receivers (Stripe, GitHub, Shopify) with persistent queues\n      - Headless content backends for SPA/PWA hosting\n      - AI agent state and memory backends\n      - Lightweight microservices replacing custom Node.js + MongoDB stacks\n\n  - aid: codehooks:codehooks-events\n    name: Codehooks Events (AsyncAPI)\n    tags:\n      - Async\n\
  \      - Events\n      - Hooks\n      - Lifecycle\n      - Queues\n      - Workers\n    humanURL: https://codehooks.io/docs/hooks-and-workers\n    properties:\n      - url: https://codehooks.io/docs/hooks-and-workers\n        type: Documentation\n      - url: asyncapi/codehooks-events-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Asynchronous CRUD lifecycle hooks (onBeforeCreate, onAfterCreate,\n      onBeforeRead, onAfterRead, onBeforeUpdate, onAfterUpdate,\n      onBeforeDelete, onAfterDelete) and queue worker processing\n      (onQueueJob) for serverless backend operations. AsyncAPI describes\n      these as event-driven channels backed by an internal pub/sub and\n      persistent queue runtime.\n    x-features:\n      - Eight CRUD lifecycle hooks (before/after for each verb)\n      - Queue worker (onQueueJob) for deferred work\n      - Automatic retry and persistent state on workers\n      - CRON-triggered jobs with multi-schedule support\n      - Stateful workflow\
  \ orchestration\n    x-use-cases:\n      - Validation and transformation on writes\n      - Audit logging and outbound webhooks\n      - PDF/email generation deferred to a worker\n      - AI inference pipelines triggered after document creation\n      - Scheduled batch jobs (CRON)\ncommon:\n  - type: Website\n    url: https://codehooks.io/\n  - type: Documentation\n    url: https://codehooks.io/docs/\n  - type: GettingStarted\n    url: https://codehooks.io/docs/quickstart-cli\n  - type: Blog\n    url: https://codehooks.io/blog\n  - type: Pricing\n    url: https://codehooks.io/#pricing\n  - type: GitHub\n    url: https://github.com/RestDB\n  - type: NPMPackage\n    url: https://www.npmjs.com/package/codehooks-js\n  - type: TermsOfService\n    url: https://codehooks.io/terms\n  - type: PrivacyPolicy\n    url: https://codehooks.io/privacy\n  - url: json-ld/codehooks-context.jsonld\n    type: JSON-LD\n  - url: json-schema/codehooks-document-schema.json\n    type: JSONSchema\n  - url: json-schema/codehooks-key-value-schema.json\n\
  \    type: JSONSchema\n  - url: json-schema/codehooks-queue-job-schema.json\n    type: JSONSchema\n  - url: rules/codehooks-rules.yml\n    type: Spectral\n  - url: capabilities/codehooks-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/apis.yml
tags:
- Backend
- Database
- Events
- Hooks
- JavaScript
- NoSQL
- Queues
- Serverless
- Webhooks
- Workers
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/apis.yml
use_cases: []
---
