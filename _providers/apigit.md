---
api_count: 1
api_specs:
- filename: apigit-api.yaml
  format: yaml
  label: APIGit
  slug: apigit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apigit/refs/heads/main/openapi/apigit-api.yaml
apis:
- description: APIGit is a Git-native API lifecycle platform providing native Git repositories, visual API design, documentation generation, governance policies, automated testing, and dynamic mock servers for API d
  name: APIGit
  slug: apigit
capabilities:
- description: Workflow for Git-native API lifecycle development using APIGit - managing API repositories, designing APIs with visual tools, running mock servers for development, and executing automated tests.
  name: APIGit API Lifecycle Development
  slug: api-lifecycle-development
common:
- title: ''
  type: Website
  url: https://apigit.com/
- title: ''
  type: Documentation
  url: https://apigit.com/doc
- title: ''
  type: Pricing
  url: https://apigit.com/pricing
- title: ''
  type: Blog
  url: https://apigit.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/apigitlabs
- title: ''
  type: YouTube
  url: https://www.youtube.com/@apigit
created: '2025-01-08'
description: APIGit is a Git-native platform for full lifecycle API development that combines version control, API design, documentation generation, governance, testing, and dynamic mock servers in a single integrated environment. Teams can build, publish, share, and secure APIs through Git-based workflows.
features:
- description: Version-controlled API repositories with Git-native workflows for teams.
  name: Native Git Repository
- description: Visual OpenAPI designer for designing APIs without writing YAML manually.
  name: API Design
- description: Automatic documentation generation and publishing with custom domains.
  name: API Documentation
- description: Policy management and compliance controls for API standards enforcement.
  name: API Governance
- description: Built-in automated API testing with test case management.
  name: API Testing
- description: Zero-configuration dynamic mock servers generated from API definitions.
  name: Dynamic Mock Server
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native OpenAPI specification support for API design and documentation.
  name: OpenAPI
- description: Native Git version control for all API definitions and changes.
  name: Git
jsonld:
- class_count: 4
  name: Apigit Context
  property_count: 3
  slug: apigit-context
layout: provider
modified: '2026-04-19'
name: APIGit
rules:
- name: APIGit API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apigit-spectral-rules
skills: []
slug: apigit
solutions:
- description: 1 API repository, mock server, and document publication with up to 1,000 mock calls/month.
  name: Free Plan
- description: $8/user/month with 5 seats, 5 organizations, and 2,000 mock calls/month/seat.
  name: Team Plan
- description: $18/user/month with 20 organizations, custom domains, SSO, webhooks, and 4,000 mock calls/month/seat.
  name: Enterprise Plan
source_filename: apis.yml
source_yaml: "aid: apigit\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apigit/refs/heads/main/apis.yml\nname: APIGit\ndescription: >-\n  APIGit is a Git-native platform for full lifecycle API development that\n  combines version control, API design, documentation generation, governance,\n  testing, and dynamic mock servers in a single integrated environment.\n  Teams can build, publish, share, and secure APIs through Git-based workflows.\ntags:\n  - API Design\n  - API Lifecycle\n  - Documentation\n  - Git\n  - Governance\n  - Mocking\n  - Platform\n  - Testing\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  - aid: apigit:apigit\n    name: APIGit\n    tags:\n      - API Design\n      - API Lifecycle\n      - Git\n      - Mocking\n    humanURL: https://apigit.com/\n    baseURL: https://api.apigit.com/v1\n\
  \    properties:\n      - url: https://apigit.com/\n        type: Documentation\n      - url: https://apigit.com/pricing\n        type: Pricing\n      - url: openapi/apigit-api.yaml\n        type: OpenAPI\n      - url: json-schema/apigit-repository-schema.json\n        type: JSONSchema\n      - url: json-schema/apigit-mock-server-schema.json\n        type: JSONSchema\n      - url: json-ld/apigit-context.jsonld\n        type: JSON-LD\n    description: >-\n      APIGit is a Git-native API lifecycle platform providing native Git\n      repositories, visual API design, documentation generation, governance\n      policies, automated testing, and dynamic mock servers for API development.\ncommon:\n  - url: https://apigit.com/\n    type: Website\n  - url: https://apigit.com/doc\n    type: Documentation\n  - url: https://apigit.com/pricing\n    type: Pricing\n  - url: https://apigit.com/blog\n    type: Blog\n  - url: https://github.com/apigitlabs\n    type: GitHubOrganization\n  - url: https://www.youtube.com/@apigit\n\
  \    type: YouTube\n  - type: Features\n    data:\n      - name: Native Git Repository\n        description: Version-controlled API repositories with Git-native workflows for teams.\n      - name: API Design\n        description: Visual OpenAPI designer for designing APIs without writing YAML manually.\n      - name: API Documentation\n        description: Automatic documentation generation and publishing with custom domains.\n      - name: API Governance\n        description: Policy management and compliance controls for API standards enforcement.\n      - name: API Testing\n        description: Built-in automated API testing with test case management.\n      - name: Dynamic Mock Server\n        description: Zero-configuration dynamic mock servers generated from API definitions.\n  - type: UseCases\n    data:\n      - name: Design-First API Development\n        description: Design APIs visually before implementation using Git-tracked OpenAPI definitions.\n      - name: Parallel Frontend-Backend\
  \ Development\n        description: Enable frontend teams to develop against mock servers while backends are being built.\n      - name: Team API Governance\n        description: Enforce API standards and policies across teams with built-in governance tools.\n  - type: Integrations\n    data:\n      - name: OpenAPI\n        description: Native OpenAPI specification support for API design and documentation.\n      - name: Git\n        description: Native Git version control for all API definitions and changes.\n  - type: Solutions\n    data:\n      - name: Free Plan\n        description: 1 API repository, mock server, and document publication with up to 1,000 mock calls/month.\n      - name: Team Plan\n        description: $8/user/month with 5 seats, 5 organizations, and 2,000 mock calls/month/seat.\n      - name: Enterprise Plan\n        description: $18/user/month with 20 organizations, custom domains, SSO, webhooks, and 4,000 mock calls/month/seat.\nmaintainers:\n  - FN: Kin Lane\n \
  \   email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apigit/refs/heads/main/apis.yml
tags:
- API Design
- API Lifecycle
- Documentation
- Git
- Governance
- Mocking
- Platform
- Testing
url: https://raw.githubusercontent.com/api-evangelist/apigit/refs/heads/main/apis.yml
use_cases:
- description: Design APIs visually before implementation using Git-tracked OpenAPI definitions.
  name: Design-First API Development
- description: Enable frontend teams to develop against mock servers while backends are being built.
  name: Parallel Frontend-Backend Development
- description: Enforce API standards and policies across teams with built-in governance tools.
  name: Team API Governance
---
