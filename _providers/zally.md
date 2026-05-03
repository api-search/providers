---
api_count: 1
api_specs:
- filename: zally-api.yml
  format: yaml
  label: Zally API
  slug: zally-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/openapi/zally-api.yml
apis:
- description: The Zally REST API performs linting of OpenAPI specifications against configurable rule sets. It returns violations grouped by rule severity (MUST, SHOULD, COULD, MAY, HINT), tracks linting statistics
  name: Zally API
  slug: zally-api
capabilities:
- description: Unified workflow capability composing Zally APIs.
  name: Zally Workflow
  slug: zally-workflow
common:
- title: ''
  type: Website
  url: https://opensource.zalando.com/zally/
- title: ''
  type: Documentation
  url: https://github.com/zalando/zally#readme
- title: ''
  type: GitHubRepository
  url: https://github.com/zalando/zally
- title: ''
  type: GitHubOrganization
  url: https://github.com/zalando
- title: ''
  type: License
  url: https://github.com/zalando/zally/blob/main/LICENSE
- title: ''
  type: Issues
  url: https://github.com/zalando/zally/issues
- title: ''
  type: ChangeLog
  url: https://github.com/zalando/zally/releases
- title: ''
  type: CLI
  url: https://github.com/zalando/zally/tree/main/cli
- title: ''
  type: SDK
  url: https://github.com/zalando/zally/tree/main/web-ui
- title: ''
  type: Specification
  url: https://opensource.zalando.com/restful-api-guidelines/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/rules/zally-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/vocabulary/zally-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/capabilities/zally-workflow.yaml
created: '2026-03-25'
description: Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3 specifications against configurable rule sets for API design consistency. It exposes a REST API, command-line interface, and web UI for checking API designs against Zalando's RESTful API Guidelines or custom rule sets.
features:
- description: Validate OpenAPI 2/3 specifications against rule sets to enforce design consistency.
  name: API Linting
- description: Customize default Zalando RESTful API Guidelines rules or define custom rule sets.
  name: Configurable Rules
- description: REST API for programmatic access, CLI for local checking, and Web UI for visual review.
  name: Multiple Interfaces
- description: Use x-zally-ignore extension in specs to selectively bypass rules.
  name: Ignore Extension
- description: Rules categorized as MUST, SHOULD, COULD, MAY, and HINT for graduated enforcement.
  name: Rule Severity Levels
- description: Track linting requests and aggregate review statistics over time.
  name: Linting Statistics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Run Zally linting in GitHub Actions workflows on PRs.
  name: GitHub Actions
- description: Translate Zally rule sets to Spectral rulesets for OpenAPI 3 alignment.
  name: Spectral
- description: Default rule set ships with rules from Zalando's public API guidelines.
  name: Zalando RESTful API Guidelines
jsonld:
- class_count: 10
  name: Zally Context
  property_count: 29
  slug: zally-context
layout: provider
modified: '2026-05-03'
name: Zally
rules:
- name: Zally API Rules
  rule_count: 18
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 13
  slug: zally-rules
skills: []
slug: zally
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zally\nname: Zally\ndescription: >-\n  Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3\n  specifications against configurable rule sets for API design consistency.\n  It exposes a REST API, command-line interface, and web UI for checking API\n  designs against Zalando's RESTful API Guidelines or custom rule sets.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Design\n  - API Linting\n  - API Quality\n  - Open Source\n  - OpenAPI\n  - Zalando\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zally:zally-api\n    name: Zally API\n    description: >-\n      The Zally REST API performs linting of OpenAPI specifications against\n      configurable rule sets. It returns violations grouped by rule severity\n      (MUST, SHOULD, COULD, MAY, HINT), tracks\
  \ linting statistics, and lists\n      supported rules. Authentication is via Bearer JWT.\n    humanURL: https://opensource.zalando.com/zally/\n    baseURL: https://zally.on.inter.net\n    tags:\n      - API Linting\n      - API Quality\n      - OpenAPI\n    properties:\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/openapi/zally-api.yml\n      - type: Documentation\n        url: https://opensource.zalando.com/zally/\n      - type: APIReference\n        url: https://github.com/zalando/zally/blob/main/server/zally-server/src/main/resources/api/zally-api.yaml\n      - type: Authentication\n        url: https://github.com/zalando/zally/tree/main/server#authentication\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-schema/\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-structure/\n      - type:\
  \ JSON-LD\n        url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-ld/zally-context.jsonld\n      - type: Example\n        url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/examples/\ncommon:\n  - type: Website\n    url: https://opensource.zalando.com/zally/\n    name: Zally Project Website\n  - type: Documentation\n    url: https://github.com/zalando/zally#readme\n    name: Zally README\n  - type: GitHubRepository\n    url: https://github.com/zalando/zally\n    name: Zalando Zally Repository\n  - type: GitHubOrganization\n    url: https://github.com/zalando\n    name: Zalando GitHub Organization\n  - type: License\n    url: https://github.com/zalando/zally/blob/main/LICENSE\n    name: MIT License\n  - type: Issues\n    url: https://github.com/zalando/zally/issues\n    name: GitHub Issues\n  - type: ChangeLog\n    url: https://github.com/zalando/zally/releases\n    name: Releases\n  - type: CLI\n    url: https://github.com/zalando/zally/tree/main/cli\n\
  \    name: Zally CLI\n  - type: SDK\n    url: https://github.com/zalando/zally/tree/main/web-ui\n    name: Zally Web UI\n  - type: Specification\n    url: https://opensource.zalando.com/restful-api-guidelines/\n    name: Zalando RESTful API Guidelines\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/rules/zally-rules.yml\n    name: Zally Spectral Ruleset\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/vocabulary/zally-vocabulary.yml\n    name: Zally Vocabulary\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/capabilities/zally-workflow.yaml\n    name: Zally Workflow Capability\n  - data:\n      - name: API Linting\n        description: Validate OpenAPI 2/3 specifications against rule sets to enforce design consistency.\n      - name: Configurable Rules\n        description: Customize default Zalando RESTful API Guidelines\
  \ rules or define custom rule sets.\n      - name: Multiple Interfaces\n        description: REST API for programmatic access, CLI for local checking, and Web UI for visual review.\n      - name: Ignore Extension\n        description: Use x-zally-ignore extension in specs to selectively bypass rules.\n      - name: Rule Severity Levels\n        description: Rules categorized as MUST, SHOULD, COULD, MAY, and HINT for graduated enforcement.\n      - name: Linting Statistics\n        description: Track linting requests and aggregate review statistics over time.\n    name: Features\n    type: Features\n  - data:\n      - name: API Design Review\n        description: Review OpenAPI specs in pull requests to enforce design standards before merge.\n      - name: API Governance\n        description: Enforce organizational API guidelines across teams via shared rule sets.\n      - name: API Quality Gate\n        description: Block API releases that violate critical MUST rules in CI/CD pipelines.\n\
  \      - name: Style Guide Enforcement\n        description: Encode an API style guide as executable rules and apply consistently.\n    name: UseCases\n    type: UseCases\n  - data:\n      - name: GitHub Actions\n        description: Run Zally linting in GitHub Actions workflows on PRs.\n      - name: Spectral\n        description: Translate Zally rule sets to Spectral rulesets for OpenAPI 3 alignment.\n      - name: Zalando RESTful API Guidelines\n        description: Default rule set ships with rules from Zalando's public API guidelines.\n    name: Integrations\n    type: Integrations\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/apis.yml
tags:
- API Design
- API Linting
- API Quality
- Open Source
- OpenAPI
- Zalando
url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/apis.yml
use_cases:
- description: Review OpenAPI specs in pull requests to enforce design standards before merge.
  name: API Design Review
- description: Enforce organizational API guidelines across teams via shared rule sets.
  name: API Governance
- description: Block API releases that violate critical MUST rules in CI/CD pipelines.
  name: API Quality Gate
- description: Encode an API style guide as executable rules and apply consistently.
  name: Style Guide Enforcement
---
