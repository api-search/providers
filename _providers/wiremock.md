---
api_count: 1
api_specs:
- filename: wiremock-admin-api-openapi.yml
  format: yaml
  label: WireMock Admin API
  slug: wiremock-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/openapi/wiremock-admin-api-openapi.yml
apis:
- description: The WireMock Admin REST API provides programmatic control over a running WireMock server instance. It supports creating, updating, and deleting stub mappings; querying the request journal; recording a
  name: WireMock Admin API
  slug: wiremock-admin-api
capabilities:
- description: Unified capability for API mocking and integration testing workflows using WireMock. Enables developers and QA engineers to create, manage, and verify mock API stubs; record and replay real traffic; d
  name: WireMock API Mocking and Testing
  slug: api-mocking-and-testing
common:
- title: ''
  type: Website
  url: https://wiremock.org/
- title: ''
  type: Documentation
  url: https://wiremock.org/docs/
- title: ''
  type: Reference
  url: https://wiremock.org/docs/standalone/admin-api-reference/
- title: ''
  type: GitHubRepository
  url: https://github.com/wiremock/wiremock
- title: ''
  type: GitHubOrganization
  url: https://github.com/wiremock
- title: ''
  type: SDK
  url: https://github.com/wiremock/python-wiremock
- title: ''
  type: SDK
  url: https://github.com/wiremock/wiremock-js
- title: ''
  type: SDK
  url: https://github.com/wiremock/WireMock.Net
- title: ''
  type: SDK
  url: https://github.com/wiremock/go-wiremock
- title: ''
  type: SDK
  url: https://github.com/wiremock/wiremock-php
- title: ''
  type: SDK
  url: https://github.com/wiremock/kotlin-wiremock
- title: ''
  type: Docker
  url: https://github.com/wiremock/wiremock-docker
- title: ''
  type: HelmChart
  url: https://github.com/wiremock/helm-charts
- title: ''
  type: SDK
  url: https://github.com/wiremock/wiremock-npm
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/json-ld/wiremock-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/vocabulary/wiremock-vocabulary.yml
created: '2025-01-08'
description: WireMock is an open source tool for mocking HTTP services and APIs. It enables developers to build stable, predictable development environments by creating mock APIs that simulate the behavior of real services. WireMock provides a comprehensive admin API for managing stub mappings, recording real traffic, verifying requests, and modeling stateful behavior through scenarios. The project is governed by the WireMock community on GitHub and supports Java, Python, JavaScript, .NET, Go, PHP, and Kotlin clients.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Wiremock Context
  property_count: 0
  slug: wiremock-context
layout: provider
modified: '2026-05-03'
name: WireMock
rules:
- name: WireMock API Rules
  rule_count: 7
  severity_counts:
    error: 0
    hint: 0
    info: 2
    warn: 5
  slug: wiremock-rules
skills: []
slug: wiremock
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wiremock\nname: WireMock\ndescription: >-\n  WireMock is an open source tool for mocking HTTP services and APIs. It enables\n  developers to build stable, predictable development environments by creating\n  mock APIs that simulate the behavior of real services. WireMock provides a\n  comprehensive admin API for managing stub mappings, recording real traffic,\n  verifying requests, and modeling stateful behavior through scenarios. The\n  project is governed by the WireMock community on GitHub and supports Java,\n  Python, JavaScript, .NET, Go, PHP, and Kotlin clients.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Mocking\n  - Mock Server\n  - Mocking\n  - Platform\n  - Stubs\n  - Testing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/apis.yml\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  -\
  \ aid: wiremock:wiremock-admin-api\n    name: WireMock Admin API\n    description: >-\n      The WireMock Admin REST API provides programmatic control over a running\n      WireMock server instance. It supports creating, updating, and deleting stub\n      mappings; querying the request journal; recording and replaying real API\n      traffic; managing stateful scenarios; and performing system operations such\n      as reset and shutdown. The API is described in OpenAPI 3.0 and available\n      under the /__admin/ path prefix on any running WireMock instance.\n    humanURL: https://wiremock.org/docs/standalone/admin-api-reference/\n    baseURL: http://localhost:8080\n    tags:\n      - Admin API\n      - API Mocking\n      - Mock Server\n      - Stub Management\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://wiremock.org/docs/standalone/admin-api-reference/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/openapi/wiremock-admin-api-openapi.yml\n\
  \      - type: Rules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/rules/wiremock-rules.yml\n      - type: Capabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/capabilities/api-mocking-and-testing.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/json-schema/wiremock-stub-mapping-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/json-structure/wiremock-stub-mapping-structure.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/examples/wiremock-create-stub-mapping-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/examples/wiremock-scenario-stub-example.json\n\
  \ncommon:\n  - url: https://wiremock.org/\n    name: WireMock\n    type: Website\n    description: Official WireMock project website.\n  - url: https://wiremock.org/docs/\n    name: WireMock Documentation\n    type: Documentation\n    description: Official WireMock documentation.\n  - url: https://wiremock.org/docs/standalone/admin-api-reference/\n    name: WireMock Admin API Reference\n    type: Reference\n    description: Reference documentation for the WireMock Admin REST API.\n  - url: https://github.com/wiremock/wiremock\n    name: WireMock GitHub Repository\n    type: GitHubRepository\n    description: Main WireMock Java repository on GitHub.\n  - url: https://github.com/wiremock\n    name: WireMock GitHub Organization\n    type: GitHubOrganization\n    description: WireMock GitHub organization with SDKs for Java, Python, JS, .NET, Go, PHP, and Kotlin.\n  - url: https://github.com/wiremock/python-wiremock\n    name: WireMock Python Client\n    type: SDK\n    description: Official\
  \ WireMock Python client library.\n  - url: https://github.com/wiremock/wiremock-js\n    name: WireMock JavaScript Client\n    type: SDK\n    description: Official WireMock JavaScript/Node.js client library.\n  - url: https://github.com/wiremock/WireMock.Net\n    name: WireMock.Net\n    type: SDK\n    description: Official WireMock .NET client library.\n  - url: https://github.com/wiremock/go-wiremock\n    name: WireMock Go Client\n    type: SDK\n    description: Official WireMock Go client library.\n  - url: https://github.com/wiremock/wiremock-php\n    name: WireMock PHP Client\n    type: SDK\n    description: Official WireMock PHP client library.\n  - url: https://github.com/wiremock/kotlin-wiremock\n    name: WireMock Kotlin Client\n    type: SDK\n    description: Official WireMock Kotlin client library.\n  - url: https://github.com/wiremock/wiremock-docker\n    name: WireMock Docker\n    type: Docker\n    description: Official WireMock Docker images.\n  - url: https://github.com/wiremock/helm-charts\n\
  \    name: WireMock Helm Charts\n    type: HelmChart\n    description: Official WireMock Helm charts for Kubernetes deployment.\n  - url: https://github.com/wiremock/wiremock-npm\n    name: WireMock npm Package\n    type: SDK\n    description: WireMock npm package for Node.js.\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/json-ld/wiremock-context.jsonld\n    name: WireMock JSON-LD Context\n    type: JSONLDContext\n    description: JSON-LD context for WireMock domain vocabulary.\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/vocabulary/wiremock-vocabulary.yml\n    name: WireMock Vocabulary\n    type: Vocabulary\n    description: Domain vocabulary for WireMock API mocking concepts.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/apis.yml
tags:
- API Mocking
- Mock Server
- Mocking
- Platform
- Stubs
- Testing
url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/apis.yml
use_cases: []
---
