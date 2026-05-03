---
api_count: 6
api_specs:
- filename: rubygems-gems-api-openapi.yml
  format: yaml
  label: RubyGems Gems API
  slug: gems-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-gems-api-openapi.yml
- filename: rubygems-api-v2-openapi.yml
  format: yaml
  label: RubyGems API V2
  slug: api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-api-v2-openapi.yml
- filename: rubygems-downloads-api-openapi.yml
  format: yaml
  label: RubyGems Downloads API
  slug: downloads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-downloads-api-openapi.yml
- filename: rubygems-search-api-openapi.yml
  format: yaml
  label: RubyGems Search API
  slug: search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-search-api-openapi.yml
- filename: rubygems-activity-api-openapi.yml
  format: yaml
  label: RubyGems Activity API
  slug: activity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-activity-api-openapi.yml
- filename: rubygems-webhooks-api-openapi.yml
  format: yaml
  label: RubyGems Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-webhooks-api-openapi.yml
apis:
- description: The RubyGems Gems API (v1) provides endpoints for retrieving gem metadata, listing owned gems, submitting new gems, yanking gem versions, managing gem ownership, retrieving user profiles, querying gem
  name: RubyGems Gems API
  slug: gems-api
- description: The RubyGems API V2 provides improved endpoints for querying detailed gem version information including metadata, dependencies, checksums, and platform-specific builds. Designed to better support mode
  name: RubyGems API V2
  slug: api-v2
- description: The RubyGems Downloads API provides download count statistics for gems and individual gem versions hosted on RubyGems.org.
  name: RubyGems Downloads API
  slug: downloads-api
- description: The RubyGems Search API allows developers to search for gems by matching a query string against gem names and descriptions. Returns paginated results of active gems.
  name: RubyGems Search API
  slug: search-api
- description: The RubyGems Activity API provides activity feeds of the most recently added and most recently updated gems on RubyGems.org, useful for monitoring new releases and tracking ecosystem changes.
  name: RubyGems Activity API
  slug: activity-api
- description: The RubyGems Webhooks API enables webhook subscriptions that fire when gems are pushed to RubyGems.org. Webhooks can be scoped to a specific gem or applied globally using a wildcard. Includes test-fir
  name: RubyGems Webhooks API
  slug: webhooks-api
asyncapis:
- description: The RubyGems webhook event system delivers HTTP POST notifications when gems are pushed to RubyGems.org. Webhook subscribers receive a JSON payload containing the full gem metadata whenever a new vers
  name: RubyGems Webhook Events
  slug: rubygems-webhooks-asyncapi
capabilities:
- description: Workflow capability for discovering and evaluating Ruby gems using the RubyGems.org APIs. Combines search, gem metadata retrieval, version history, download statistics, and dependency analysis for dev
  name: RubyGems Gem Discovery
  slug: gem-discovery
- description: Workflow capability for publishing and managing Ruby gems on RubyGems.org. Combines gem publishing, yanking, ownership management, and webhook notification setup. Serves gem maintainers and CI/CD pipe
  name: RubyGems Gem Publishing
  slug: gem-publishing
common:
- title: ''
  type: Portal
  url: https://rubygems.org/
- title: ''
  type: Documentation
  url: https://guides.rubygems.org/
- title: ''
  type: Authentication
  url: https://guides.rubygems.org/api-key-scopes/
- title: ''
  type: GitHub
  url: https://github.com/rubygems/rubygems.org
- title: ''
  type: Status
  url: https://status.rubygems.org/
- title: ''
  type: Blog
  url: https://blog.rubygems.org/
created: '2025-01-01'
description: RubyGems.org is the Ruby community's primary gem hosting service, providing the infrastructure for publishing, discovering, and installing Ruby gems. The RubyGems API enables programmatic access to gem metadata, version information, download statistics, search, owner management, webhooks, and the compact index used by Bundler for dependency resolution. RubyGems.org hosts over 160,000 gems with billions of total downloads.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Rubygems Context
  property_count: 5
  slug: rubygems-context
layout: provider
modified: '2026-05-02'
name: RubyGems
rules:
- name: RubyGems API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 6
  slug: rubygems-spectral-rules
skills: []
slug: rubygems
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rubygems\nname: RubyGems\ndescription: >-\n  RubyGems.org is the Ruby community's primary gem hosting service, providing\n  the infrastructure for publishing, discovering, and installing Ruby gems.\n  The RubyGems API enables programmatic access to gem metadata, version\n  information, download statistics, search, owner management, webhooks, and\n  the compact index used by Bundler for dependency resolution. RubyGems.org\n  hosts over 160,000 gems with billions of total downloads.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Ruby\n  - Package Manager\n  - Open Source\n  - Developer Tools\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: rubygems:gems-api\n    name: RubyGems Gems API\n    description: >-\n      The RubyGems Gems API (v1) provides\
  \ endpoints for retrieving gem metadata,\n      listing owned gems, submitting new gems, yanking gem versions, managing\n      gem ownership, retrieving user profiles, querying gem dependencies, and\n      exchanging OIDC tokens for API keys for trusted publishing workflows.\n    humanURL: https://guides.rubygems.org/rubygems-org-api/\n    baseURL: https://rubygems.org/api/v1\n    tags:\n      - Ruby\n      - Gems\n      - Package Manager\n    properties:\n      - type: Documentation\n        url: https://guides.rubygems.org/rubygems-org-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-gems-api-openapi.yml\n  - aid: rubygems:api-v2\n    name: RubyGems API V2\n    description: >-\n      The RubyGems API V2 provides improved endpoints for querying detailed\n      gem version information including metadata, dependencies, checksums, and\n      platform-specific builds. Designed to better support modern tooling\
  \ and\n      dependency resolution workflows.\n    humanURL: https://guides.rubygems.org/rubygems-org-api-v2/\n    baseURL: https://rubygems.org/api/v2\n    tags:\n      - Ruby\n      - Gems\n      - Versions\n      - Package Manager\n    properties:\n      - type: Documentation\n        url: https://guides.rubygems.org/rubygems-org-api-v2/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-api-v2-openapi.yml\n  - aid: rubygems:downloads-api\n    name: RubyGems Downloads API\n    description: >-\n      The RubyGems Downloads API provides download count statistics for gems\n      and individual gem versions hosted on RubyGems.org.\n    humanURL: https://guides.rubygems.org/rubygems-org-api/\n    baseURL: https://rubygems.org/api/v1\n    tags:\n      - Ruby\n      - Downloads\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://guides.rubygems.org/rubygems-org-api/\n      - type:\
  \ OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-downloads-api-openapi.yml\n  - aid: rubygems:search-api\n    name: RubyGems Search API\n    description: >-\n      The RubyGems Search API allows developers to search for gems by matching\n      a query string against gem names and descriptions. Returns paginated\n      results of active gems.\n    humanURL: https://guides.rubygems.org/rubygems-org-api/\n    baseURL: https://rubygems.org/api/v1\n    tags:\n      - Ruby\n      - Search\n      - Discovery\n    properties:\n      - type: Documentation\n        url: https://guides.rubygems.org/rubygems-org-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-search-api-openapi.yml\n  - aid: rubygems:activity-api\n    name: RubyGems Activity API\n    description: >-\n      The RubyGems Activity API provides activity feeds of the most recently\n    \
  \  added and most recently updated gems on RubyGems.org, useful for\n      monitoring new releases and tracking ecosystem changes.\n    humanURL: https://guides.rubygems.org/rubygems-org-api/\n    baseURL: https://rubygems.org/api/v1\n    tags:\n      - Ruby\n      - Activity\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://guides.rubygems.org/rubygems-org-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-activity-api-openapi.yml\n  - aid: rubygems:webhooks-api\n    name: RubyGems Webhooks API\n    description: >-\n      The RubyGems Webhooks API enables webhook subscriptions that fire when\n      gems are pushed to RubyGems.org. Webhooks can be scoped to a specific\n      gem or applied globally using a wildcard. Includes test-fire functionality\n      and HMAC signature verification.\n    humanURL: https://guides.rubygems.org/rubygems-org-api/\n    baseURL: https://rubygems.org/api/v1\n\
  \    tags:\n      - Ruby\n      - Webhooks\n      - Events\n    properties:\n      - type: Documentation\n        url: https://guides.rubygems.org/rubygems-org-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-webhooks-api-openapi.yml\n      - type: AsyncAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/asyncapi/rubygems-webhooks-asyncapi.yml\ncommon:\n  - type: Portal\n    url: https://rubygems.org/\n  - type: Documentation\n    url: https://guides.rubygems.org/\n  - type: Authentication\n    url: https://guides.rubygems.org/api-key-scopes/\n  - type: GitHub\n    url: https://github.com/rubygems/rubygems.org\n  - type: Status\n    url: https://status.rubygems.org/\n  - type: Blog\n    url: https://blog.rubygems.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/apis.yml
tags:
- Ruby
- Package Manager
- Open Source
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/apis.yml
use_cases: []
---
