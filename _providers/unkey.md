---
api_count: 1
api_specs:
- filename: unkey-openapi.yml
  format: yaml
  label: Unkey API
  slug: unkey-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/openapi/unkey-openapi.yml
apis:
- description: 'Unkey''s REST API providing programmatic access to all platform resources: API namespace management, API key lifecycle (create, verify, update, reroll, delete), identity management, permissions and rol'
  name: Unkey API
  slug: unkey-api
capabilities:
- description: Workflow capability for managing the full lifecycle of API keys using the Unkey platform. Covers creating, verifying, updating, rotating, and revoking keys, plus managing permissions and roles for fin
  name: Unkey API Key Management
  slug: api-key-management
- description: 'Workflow capability for managing identities in the Unkey platform. Identities group multiple API keys under a single external user or organization ID, enabling shared rate limits and analytics across '
  name: Unkey Identity Management
  slug: identity-management
- description: Workflow capability for standalone rate limiting using the Unkey platform. Enables platform engineers, backend developers, and API teams to protect any endpoint from abuse with global rate limiting, p
  name: Unkey Rate Limiting
  slug: rate-limiting
common:
- title: ''
  type: Website
  url: https://www.unkey.com
- title: ''
  type: Documentation
  url: https://www.unkey.com/docs
- title: ''
  type: GitHub
  url: https://github.com/unkeyed/unkey
- title: ''
  type: Pricing
  url: https://www.unkey.com/pricing
- title: ''
  type: Blog
  url: https://www.unkey.com/blog
- title: ''
  type: Changelog
  url: https://www.unkey.com/changelog
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/vocabulary/unkey-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/json-ld/unkey-context.jsonld
created: '2026-03-16'
description: Unkey is the developer platform for modern APIs, providing globally distributed API key management, rate limiting, identity management, analytics, and deployment capabilities. The platform enables API providers to issue, verify, and revoke keys with metadata, expiration, usage credits, permissions, and roles — without managing any infrastructure.
features: []
image: ''
integrations: []
jsonld:
- class_count: 10
  name: Unkey Context
  property_count: 33
  slug: unkey-context
layout: provider
modified: '2026-05-03'
name: Unkey
rules:
- name: Unkey API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 7
  slug: unkey-rules
skills: []
slug: unkey
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unkey\nname: Unkey\ndescription: >-\n  Unkey is the developer platform for modern APIs, providing globally distributed API key\n  management, rate limiting, identity management, analytics, and deployment capabilities.\n  The platform enables API providers to issue, verify, and revoke keys with metadata,\n  expiration, usage credits, permissions, and roles — without managing any infrastructure.\nurl: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - API Keys\n  - Rate Limiting\n  - Authentication\n  - Developer Platform\n  - Access Control\n  - Identity\n  - Analytics\napis:\n  - aid: unkey:unkey-api\n    name: Unkey API\n    description: >-\n      Unkey's REST API providing programmatic access to all platform resources: API namespace\n      management, API key lifecycle (create, verify, update, reroll, delete), identity\n      management,\
  \ permissions and roles, standalone rate limiting with namespace overrides,\n      key verification analytics via SQL, and deployment operations. All management operations\n      use Bearer authentication with root keys.\n    humanURL: https://www.unkey.com\n    baseURL: https://api.unkey.com\n    tags:\n      - API Keys\n      - Rate Limiting\n      - Identity\n      - Permissions\n      - Analytics\n      - Deployments\n    properties:\n      - type: Documentation\n        url: https://www.unkey.com/docs\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/openapi/unkey-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/rules/unkey-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/capabilities/api-key-management.yaml\n      - type: NaftikoCapability\n\
  \        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/capabilities/rate-limiting.yaml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/capabilities/identity-management.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/json-schema/unkey-key-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/json-schema/unkey-ratelimit-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/json-schema/unkey-identity-schema.json\n\ncommon:\n  - type: Website\n    url: https://www.unkey.com\n  - type: Documentation\n    url: https://www.unkey.com/docs\n  - type: GitHub\n    url: https://github.com/unkeyed/unkey\n  - type: Pricing\n    url:\
  \ https://www.unkey.com/pricing\n  - type: Blog\n    url: https://www.unkey.com/blog\n  - type: Changelog\n    url: https://www.unkey.com/changelog\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/vocabulary/unkey-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/json-ld/unkey-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/apis.yml
tags:
- API Keys
- Rate Limiting
- Authentication
- Developer Platform
- Access Control
- Identity
- Analytics
url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/apis.yml
use_cases: []
---
