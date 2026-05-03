---
api_count: 2
api_specs:
- filename: tray-io-platform-api-openapi.yml
  format: yaml
  label: Tray.io Platform API
  slug: tray-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/openapi/tray-io-platform-api-openapi.yml
apis:
- description: The Tray.io Platform API allows developers to leverage the power of Tray's service connectors without using the Builder UI, enabling native integration of third-party APIs into applications without wo
  name: Tray.io Platform API
  slug: tray-platform-api
- description: The Tray.io Embedded API provides GraphQL-based APIs for embedding Tray's automation capabilities into your own products, enabling end users to configure and manage integrations directly.
  name: Tray.io Embedded API
  slug: tray-embedded-api
capabilities:
- description: Workflow capability for the Tray.io integration platform covering connector discovery, invocation, authentication management, trigger subscriptions, and workspace administration. Designed for automati
  name: Tray.io Integration Platform
  slug: integration-platform
common:
- title: ''
  type: Website
  url: https://tray.ai
- title: ''
  type: Documentation
  url: https://tray.ai/documentation
- title: ''
  type: Developer Portal
  url: https://developer.tray.ai/
- title: ''
  type: Pricing
  url: https://tray.ai/pricing
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tray-io
- title: ''
  type: X (Twitter)
  url: https://x.com/tray
- title: ''
  type: NaftikoCapability
  url: capabilities/integration-platform.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tray-io-vocabulary.yml
created: '2026-03-26'
description: Tray.io (now also known as Tray.ai) is an AI-ready integration platform as a service (iPaaS) that enables businesses to integrate and automate workflows across cloud applications using a visual editor, pre-built connectors, and API-level access. The platform includes Merlin Agent Builder for building AI agents and a Universal Automation Cloud for connecting data and systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Tray Io Context
  property_count: 0
  slug: tray-io-context
layout: provider
modified: '2026-05-03'
name: Tray.io
rules:
- name: Tray.io API Rules
  rule_count: 6
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 5
  slug: tray-io-rules
skills: []
slug: tray-io
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tray-io\nname: Tray.io\ndescription: >-\n  Tray.io (now also known as Tray.ai) is an AI-ready integration platform as a\n  service (iPaaS) that enables businesses to integrate and automate workflows\n  across cloud applications using a visual editor, pre-built connectors, and\n  API-level access. The platform includes Merlin Agent Builder for building AI\n  agents and a Universal Automation Cloud for connecting data and systems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Agents\n  - API Aggregation\n  - Automation\n  - Connectors\n  - Integration\n  - iPaaS\n  - Workflow Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tray-io:tray-platform-api\n    name: Tray.io Platform API\n    description: >-\n      The Tray.io Platform API allows developers to leverage\
  \ the power of\n      Tray's service connectors without using the Builder UI, enabling native\n      integration of third-party APIs into applications without worrying about\n      different protocols and data formats.\n    humanURL: https://developer.tray.ai/openapi/trayapi-introduction/\n    baseURL: https://api.tray.io/core/v1\n    tags:\n      - API Management\n      - Automation\n      - Connectors\n      - Integration\n      - iPaaS\n    properties:\n      - type: Documentation\n        url: https://developer.tray.ai/openapi/trayapi-introduction/\n      - type: Developer Portal\n        url: https://developer.tray.ai/\n      - type: OpenAPI\n        url: openapi/tray-io-platform-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tray-io-connector-schema.json\n      - type: JSONSchema\n        url: json-schema/tray-io-authentication-schema.json\n      - type: JSONSchema\n        url: json-schema/tray-io-workspace-schema.json\n      - type: JSONLD\n        url: json-ld/tray-io-context.jsonld\n\
  \      - type: JSONStructure\n        url: json-structure/tray-io-connector-structure.json\n      - type: Example\n        url: examples/tray-io-list-connectors-example.json\n      - type: Example\n        url: examples/tray-io-call-connector-example.json\n      - type: SpectralRuleset\n        url: rules/tray-io-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/shared/platform-api.yaml\n  - aid: tray-io:tray-embedded-api\n    name: Tray.io Embedded API\n    description: >-\n      The Tray.io Embedded API provides GraphQL-based APIs for embedding\n      Tray's automation capabilities into your own products, enabling end\n      users to configure and manage integrations directly.\n    humanURL: https://embedded-api-docs.tray.io/\n    tags:\n      - Embedded Integration\n      - GraphQL\n      - White Label\n    properties:\n      - type: Documentation\n        url: https://embedded-api-docs.tray.io/\n      - type: Developer Portal\n        url: https://developer.tray.ai/\n\
  common:\n  - type: Website\n    url: https://tray.ai\n  - type: Documentation\n    url: https://tray.ai/documentation\n  - type: Developer Portal\n    url: https://developer.tray.ai/\n  - type: Pricing\n    url: https://tray.ai/pricing\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/tray-io\n  - type: X (Twitter)\n    url: https://x.com/tray\n  - type: NaftikoCapability\n    url: capabilities/integration-platform.yaml\n  - type: Vocabulary\n    url: vocabulary/tray-io-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/apis.yml
tags:
- AI Agents
- API Aggregation
- Automation
- Connectors
- Integration
- iPaaS
- Workflow Automation
url: https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/apis.yml
use_cases: []
---
