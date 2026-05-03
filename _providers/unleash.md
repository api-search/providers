---
api_count: 3
api_specs:
- filename: unleash-admin-api-openapi.yml
  format: yaml
  label: Unleash Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-admin-api-openapi.yml
- filename: unleash-client-api-openapi.yml
  format: yaml
  label: Unleash Client API
  slug: client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-client-api-openapi.yml
- filename: unleash-frontend-api-openapi.yml
  format: yaml
  label: Unleash Frontend API
  slug: frontend-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-frontend-api-openapi.yml
apis:
- description: Comprehensive REST API providing full programmatic control over Unleash resources including feature flags, projects, environments, users, API tokens, strategies, segments, integrations (addons), event
  name: Unleash Admin API
  slug: admin-api
- description: API endpoint consumed by backend Unleash SDKs to fetch complete feature flag configurations including all activation strategies. Supports server-side flag evaluation with zero additional latency after
  name: Unleash Client API
  slug: client-api
- description: 'API endpoint consumed by frontend/client-side SDKs. Returns only the evaluated state (enabled/disabled) of feature flags for a given Unleash Context, without exposing strategy configuration. Safe for '
  name: Unleash Frontend API
  slug: frontend-api
capabilities:
- description: 'Workflow capability for managing access control in Unleash, including user management, API token lifecycle, service accounts, and personal access tokens. Used by platform admins and security teams to '
  name: Unleash Access Management
  slug: access-management
- description: Workflow capability for managing the complete lifecycle of feature flags using Unleash. Covers creating and configuring flags, toggling environments, managing strategies and segments, tracking events,
  name: Unleash Feature Flag Management
  slug: feature-flag-management
common:
- title: ''
  type: Website
  url: https://www.getunleash.io
- title: ''
  type: Documentation
  url: https://docs.getunleash.io
- title: ''
  type: GitHub
  url: https://github.com/Unleash/unleash
- title: ''
  type: Pricing
  url: https://www.getunleash.io/pricing
- title: ''
  type: Blog
  url: https://www.getunleash.io/blog
- title: ''
  type: Changelog
  url: https://github.com/Unleash/unleash/releases
- title: ''
  type: SDK
  url: https://docs.getunleash.io/reference/sdks
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/vocabulary/unleash-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/json-ld/unleash-context.jsonld
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/json-schema/unleash-feature-flag-schema.json
created: '2026-03-16'
description: Unleash is the open-source feature management platform enabling progressive delivery, A/B testing, and canary releases through feature flags (feature toggles). Teams use Unleash to decouple code deployments from feature releases, control rollouts by user segment, run experiments with variants, and maintain kill switches for rapid incident response. Available as open-source (self-hosted) and as Unleash Cloud (managed).
features: []
image: ''
integrations: []
jsonld:
- class_count: 11
  name: Unleash Context
  property_count: 27
  slug: unleash-context
layout: provider
modified: '2026-05-03'
name: Unleash
rules:
- name: Unleash API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 4
  slug: unleash-rules
skills: []
slug: unleash
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unleash\nname: Unleash\ndescription: >-\n  Unleash is the open-source feature management platform enabling progressive delivery,\n  A/B testing, and canary releases through feature flags (feature toggles). Teams use\n  Unleash to decouple code deployments from feature releases, control rollouts by user\n  segment, run experiments with variants, and maintain kill switches for rapid incident\n  response. Available as open-source (self-hosted) and as Unleash Cloud (managed).\nurl: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Feature Flags\n  - Feature Management\n  - Progressive Delivery\n  - A/B Testing\n  - Open Source\n  - Developer Tools\napis:\n  - aid: unleash:admin-api\n    name: Unleash Admin API\n    description: >-\n      Comprehensive REST API providing full programmatic control over Unleash resources\n      including feature\
  \ flags, projects, environments, users, API tokens, strategies,\n      segments, integrations (addons), events, change requests, and instance administration.\n      Powers the Unleash Admin UI and enables CI/CD and GitOps automation workflows.\n      Base URL: https://{your-unleash-instance}/api/admin\n    humanURL: https://docs.getunleash.io/api\n    baseURL: https://app.unleash-instance.example.com\n    tags:\n      - Admin\n      - Feature Flags\n      - Projects\n      - Environments\n      - Users\n      - Events\n    properties:\n      - type: Documentation\n        url: https://docs.getunleash.io/api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-admin-api-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/rules/unleash-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/capabilities/feature-flag-management.yaml\n\
  \      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/capabilities/access-management.yaml\n\n  - aid: unleash:client-api\n    name: Unleash Client API\n    description: >-\n      API endpoint consumed by backend Unleash SDKs to fetch complete feature flag\n      configurations including all activation strategies. Supports server-side flag\n      evaluation with zero additional latency after initial bootstrap. Requires a\n      backend API token scoped to a project and environment.\n    humanURL: https://docs.getunleash.io/api#client-api\n    baseURL: https://app.unleash-instance.example.com\n    tags:\n      - Client\n      - SDK\n      - Feature Flags\n    properties:\n      - type: Documentation\n        url: https://docs.getunleash.io/api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-client-api-openapi.yml\n\n \
  \ - aid: unleash:frontend-api\n    name: Unleash Frontend API\n    description: >-\n      API endpoint consumed by frontend/client-side SDKs. Returns only the evaluated\n      state (enabled/disabled) of feature flags for a given Unleash Context, without\n      exposing strategy configuration. Safe for use in browser and mobile apps.\n    humanURL: https://docs.getunleash.io/api#frontend-api\n    baseURL: https://app.unleash-instance.example.com\n    tags:\n      - Frontend\n      - SDK\n      - Feature Flags\n    properties:\n      - type: Documentation\n        url: https://docs.getunleash.io/api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-frontend-api-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.getunleash.io\n  - type: Documentation\n    url: https://docs.getunleash.io\n  - type: GitHub\n    url: https://github.com/Unleash/unleash\n  - type: Pricing\n    url: https://www.getunleash.io/pricing\n\
  \  - type: Blog\n    url: https://www.getunleash.io/blog\n  - type: Changelog\n    url: https://github.com/Unleash/unleash/releases\n  - type: SDK\n    url: https://docs.getunleash.io/reference/sdks\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/vocabulary/unleash-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/json-ld/unleash-context.jsonld\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/json-schema/unleash-feature-flag-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/apis.yml
tags:
- Feature Flags
- Feature Management
- Progressive Delivery
- A/B Testing
- Open Source
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/apis.yml
use_cases: []
---
