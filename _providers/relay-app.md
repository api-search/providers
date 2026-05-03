---
api_count: 1
api_specs:
- filename: relay-app-openapi.yml
  format: yaml
  label: Relay App Automation API
  slug: relay-app-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/openapi/relay-app-openapi.yml
apis:
- description: The Relay.app API enables programmatic triggering of workflows via webhooks, custom HTTP requests to external APIs, and scheduled automation runs. Developers can use webhook endpoints to trigger workf
  name: Relay App Automation API
  slug: relay-app-api
capabilities:
- description: Unified workflow automation capability for Relay.app. Combines webhook-triggered workflow execution, workflow management, run status monitoring, human-in-the-loop approval workflows, and run cancellat
  name: Relay App Workflow Automation
  slug: workflow-automation
common:
- title: ''
  type: Website
  url: https://www.relay.app
- title: ''
  type: Documentation
  url: https://docs.relay.app/
- title: ''
  type: Blog
  url: https://www.relay.app/blog
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/json-ld/relay-app-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/vocabulary/relay-app-vocabulary.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/rules/relay-app-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/capabilities/workflow-automation.yaml
created: '2026-03-16'
description: Relay.app is an AI-powered workflow automation platform that converts plain language into reliable visual workflows across 200+ app integrations. It supports webhook triggers, custom HTTP requests, scheduled automation, human-in-the-loop approval workflows, and MCP server tooling for AI agent integration. Developer features include API-triggered workflows, custom JavaScript execution, and integration with OpenAI, Anthropic, and other AI providers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Relay App Context
  property_count: 22
  slug: relay-app-context
layout: provider
modified: '2026-05-02'
name: Relay App
rules:
- name: Relay App API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 7
  slug: relay-app-rules
skills: []
slug: relay-app
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: relay-app\nname: Relay App\ndescription: >-\n  Relay.app is an AI-powered workflow automation platform that converts plain\n  language into reliable visual workflows across 200+ app integrations. It supports\n  webhook triggers, custom HTTP requests, scheduled automation, human-in-the-loop\n  approval workflows, and MCP server tooling for AI agent integration. Developer\n  features include API-triggered workflows, custom JavaScript execution, and\n  integration with OpenAI, Anthropic, and other AI providers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Workflow\n  - Integration\n  - No-Code\n  - AI\n  - Webhooks\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: relay-app:relay-app-api\n    name: Relay App Automation API\n    description: >-\n      The Relay.app\
  \ API enables programmatic triggering of workflows via webhooks,\n      custom HTTP requests to external APIs, and scheduled automation runs. Developers\n      can use webhook endpoints to trigger workflow runs, pass JSON payloads, configure\n      deduplication, and receive custom response codes. The API supports GET and POST\n      HTTP methods with configurable headers and payloads.\n    humanURL: https://docs.relay.app/\n    baseURL: https://api.relay.app\n    tags:\n      - Webhook\n      - Automation\n      - Workflow Triggers\n      - HTTP\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://docs.relay.app/\n      - type: Webhook Documentation\n        url: https://docs.relay.app/triggers/webhook-trigger\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/openapi/relay-app-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/json-schema/relay-app-workflow-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/json-schema/relay-app-workflow-run-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/json-structure/relay-app-workflow-structure.json\n\ncommon:\n  - type: Website\n    url: https://www.relay.app\n  - type: Documentation\n    url: https://docs.relay.app/\n  - type: Integrations\n    url: https://www.relay.app/apps\n  - type: Blog\n    url: https://www.relay.app/blog\n  - type: Features\n    url: https://www.relay.app/features\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/json-ld/relay-app-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/vocabulary/relay-app-vocabulary.yml\n  - type: SpectralRules\n    url: >-\n \
  \     https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/rules/relay-app-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/capabilities/workflow-automation.yaml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/apis.yml
tags:
- Automation
- Workflow
- Integration
- No-Code
- AI
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/apis.yml
use_cases: []
---
