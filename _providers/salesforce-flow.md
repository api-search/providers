---
api_count: 3
api_specs:
- filename: salesforce-flow-rest-api-openapi.yml
  format: yaml
  label: Salesforce Flow REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-flow/refs/heads/main/openapi/salesforce-flow-rest-api-openapi.yml
apis:
- description: REST API for managing and executing Salesforce Flows programmatically. Enables creating, updating, querying, and executing flow automation processes, flow interviews, and invocable actions within Sale
  name: Salesforce Flow REST API
  slug: ''
- description: Tooling API endpoints for managing Flow definitions and metadata. Supports deployment, retrieval, and management of Flow versions.
  name: Salesforce Tooling API (Flow)
  slug: ''
- description: API for executing and managing Flow interviews (instances). Provides endpoints to start, resume, pause, and monitor flow execution state.
  name: Salesforce Flow Interviews API
  slug: ''
capabilities:
- description: Unified workflow capability for managing and executing Salesforce Flow automation processes. Combines flow definition management, interview execution, and invocable action triggering for business proc
  name: Salesforce Flow Automation
  slug: flow-automation
common:
- title: ''
  type: Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Getting Started
  url: https://trailhead.salesforce.com/content/learn/modules/flow-builder
- title: ''
  type: Authentication
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm
- title: ''
  type: Rate Limits
  url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm
- title: ''
  type: Status
  url: https://status.salesforce.com/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/
- title: ''
  type: Trailhead Learning
  url: https://trailhead.salesforce.com/content/learn/modules/flow-builder
- title: ''
  type: GitHub Organization
  url: https://github.com/salesforce
- title: ''
  type: Spectral Rules
  url: rules/salesforce-flow-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/flow-automation.yaml
- title: Flow Definition Schema
  type: JSON Schema
  url: json-schema/salesforce-flow-flow-definition-schema.json
- title: Flow Interview Schema
  type: JSON Schema
  url: json-schema/salesforce-flow-flow-interview-schema.json
- title: ''
  type: JSON-LD Context
  url: json-ld/salesforce-flow-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-flow-vocabulary.yml
created: 2024-01-15 00:00:00+00:00
description: The Salesforce Flow API enables developers to interact with and manage Salesforce Flow automation processes programmatically. This includes creating, updating, querying, and executing flows within Salesforce using the REST API, Tooling API, and Invocable Actions framework.
features: []
image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg
integrations: []
jsonld:
- class_count: 0
  name: Salesforce Flow Context
  property_count: 23
  slug: salesforce-flow-context
layout: provider
modified: '2026-05-02'
name: Salesforce Flow
rules:
- name: Salesforce Flow API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 4
  slug: salesforce-flow-rules
skills: []
slug: salesforce-flow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Salesforce Flow\ndescription: >-\n  The Salesforce Flow API enables developers to interact with and manage\n  Salesforce Flow automation processes programmatically. This includes creating,\n  updating, querying, and executing flows within Salesforce using the REST API,\n  Tooling API, and Invocable Actions framework.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\nurl: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm\ncreated: 2024-01-15 00:00:00+00:00\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Automation\n  - Business Process\n  - CRM\n  - Flow\n  - Process Builder\n  - Salesforce\n  - Workflow\napis:\n  - name: Salesforce Flow REST API\n    description: >-\n      REST API for managing and executing Salesforce Flows programmatically.\n      Enables creating, updating, querying, and executing flow automation\n      processes, flow interviews, and invocable actions\
  \ within Salesforce.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0\n    tags:\n      - Automation\n      - Flow\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm\n      - type: OpenAPI\n        url: openapi/salesforce-flow-rest-api-openapi.yml\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n    contact:\n      - type: Support\n        url: https://help.salesforce.com/\n  - name: Salesforce Tooling API (Flow)\n    description: >-\n      Tooling API endpoints for managing Flow definitions and metadata.\n      Supports deployment, retrieval, and management\
  \ of Flow versions.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/tooling\n    tags:\n      - Flow Definition\n      - Metadata\n      - Tooling\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/tooling_api_objects_flow.htm\n  - name: Salesforce Flow Interviews API\n    description: >-\n      API for executing and managing Flow interviews (instances). Provides\n      endpoints to start, resume, pause, and monitor flow execution state.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_flow.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/actions/custom/flow\n\
  \    tags:\n      - Execution\n      - Flow Interview\n      - Runtime\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_flow.htm\ncommon:\n  - type: Portal\n    url: https://developer.salesforce.com/\n  - type: Getting Started\n    url: https://trailhead.salesforce.com/content/learn/modules/flow-builder\n  - type: Authentication\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n  - type: Rate Limits\n    url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm\n  - type: Status\n    url: https://status.salesforce.com/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  - type: Documentation\n\
  \    url: https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/\n  - type: Trailhead Learning\n    url: https://trailhead.salesforce.com/content/learn/modules/flow-builder\n  - type: GitHub Organization\n    url: https://github.com/salesforce\n  - type: Spectral Rules\n    url: rules/salesforce-flow-rules.yml\n  - type: Capabilities\n    url: capabilities/flow-automation.yaml\n  - type: JSON Schema\n    url: json-schema/salesforce-flow-flow-definition-schema.json\n    title: Flow Definition Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-flow-flow-interview-schema.json\n    title: Flow Interview Schema\n  - type: JSON-LD Context\n    url: json-ld/salesforce-flow-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/salesforce-flow-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-flow/refs/heads/main/apis.yml
tags:
- Automation
- Business Process
- CRM
- Flow
- Process Builder
- Salesforce
- Workflow
url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm
use_cases: []
---
