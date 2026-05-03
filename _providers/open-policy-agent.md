---
api_count: 7
api_specs:
- filename: policy-api.yml
  format: yaml
  label: Open Policy Agent Policy API
  slug: open-policy-agent-policy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/policy-api.yml
- filename: data-api.yml
  format: yaml
  label: Open Policy Agent Data API
  slug: open-policy-agent-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/data-api.yml
- filename: query-api.yml
  format: yaml
  label: Open Policy Agent Query API
  slug: open-policy-agent-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/query-api.yml
- filename: compile-api.yml
  format: yaml
  label: Open Policy Agent Compile API
  slug: open-policy-agent-compile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/compile-api.yml
- filename: health-api.yml
  format: yaml
  label: Open Policy Agent Health API
  slug: open-policy-agent-health-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/health-api.yml
- filename: config-api.yml
  format: yaml
  label: Open Policy Agent Config API
  slug: open-policy-agent-config-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/config-api.yml
- filename: status-api.yml
  format: yaml
  label: Open Policy Agent Status API
  slug: open-policy-agent-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/openapi/status-api.yml
apis:
- description: API for managing policy modules, allowing CRUD operations on Rego policy files stored in OPA.
  name: Open Policy Agent Policy API
  slug: open-policy-agent-policy-api
- description: API for reading and writing documents in OPA (Open Policy Agent).
  name: Open Policy Agent Data API
  slug: open-policy-agent-data-api
- description: API for executing simple and ad-hoc queries in OPA (Open Policy Agent).
  name: Open Policy Agent Query API
  slug: open-policy-agent-query-api
- description: API for partially evaluating Rego queries in OPA (Open Policy Agent).
  name: Open Policy Agent Compile API
  slug: open-policy-agent-compile-api
- description: API for checking the health and readiness of an OPA (Open Policy Agent) server.
  name: Open Policy Agent Health API
  slug: open-policy-agent-health-api
- description: API for retrieving OPA's active configuration, including discovered configurations.
  name: Open Policy Agent Config API
  slug: open-policy-agent-config-api
- description: API for accessing OPA (Open Policy Agent) status information via a pull-based mechanism.
  name: Open Policy Agent Status API
  slug: open-policy-agent-status-api
common:
- title: ''
  type: JSONSchema
  url: json-schema/opa-policy-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/opa-context.jsonld
- title: ''
  type: Website
  url: https://www.openpolicyagent.org/
- title: ''
  type: Documentation
  url: https://www.openpolicyagent.org/docs/latest/
- title: ''
  type: Documentation
  url: https://www.openpolicyagent.org/docs/latest/rest-api/
- title: ''
  type: Getting Started
  url: https://www.openpolicyagent.org/docs/latest/#running-opa
- title: ''
  type: Authentication
  url: https://www.openpolicyagent.org/docs/latest/rest-api/#authentication
- title: ''
  type: Errors
  url: https://www.openpolicyagent.org/docs/latest/rest-api/#errors
- title: ''
  type: GitHub Organization
  url: https://github.com/open-policy-agent
- title: ''
  type: GitHubRepository
  url: https://github.com/open-policy-agent/opa
- title: ''
  type: Blog
  url: https://blog.openpolicyagent.org/
- title: ''
  type: Community
  url: https://www.openpolicyagent.org/community/
- title: ''
  type: Slack
  url: https://slack.openpolicyagent.org/
- title: ''
  type: Change Log
  url: https://github.com/open-policy-agent/opa/blob/main/CHANGELOG.md
- title: ''
  type: Security
  url: https://github.com/open-policy-agent/opa/security/policy
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/open-policy-agent
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/api-evangelist/open-policy-agent/overview
- title: ''
  type: GitHubRepository
  url: https://github.com/api-search/open-policy-agent
created: '2024-11-18'
description: Open Policy Agent (OPA) is an open-source project that provides a flexible and powerful policy engine for cloud-native environments. OPA enables users to define and enforce policies across their infrastructure, applications, and services through a declarative language called Rego. OPA integrates seamlessly with popular tools and frameworks like Kubernetes, Istio, and Envoy, making it easy to implement fine-grained access control, security, and compliance policies.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Opa Context
  property_count: 12
  slug: opa-context
layout: provider
modified: '2026-04-28'
name: Open Policy Agent
skills: []
slug: open-policy-agent
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: open-policy-agent\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/apis.yml\napis:\n  - aid: open-policy-agent:open-policy-agent-policy-api\n    name: Open Policy Agent Policy API\n    tags:\n      - Management\n      - Policies\n      - Rego\n    humanURL: https://www.openpolicyagent.org/docs/latest/rest-api/#policy-api\n    properties:\n      - url: https://www.openpolicyagent.org/docs/latest/rest-api/#policy-api\n        type: Documentation\n      - url: openapi/policy-api.yml\n        type: OpenAPI\n      - url: json-schema/opa-policy-schema.json\n        type: JSONSchema\n      - url: policy/bruno.json\n        type: BrunoCollection\n      - url: >2-\n\n          https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-19ce2c88-97b8-4f58-a101-b8be70794a85\n        type: PostmanCollection\n    description: API for managing policy modules, allowing CRUD operations\
  \ on Rego policy files stored in OPA.\n  - aid: open-policy-agent:open-policy-agent-data-api\n    name: Open Policy Agent Data API\n    tags:\n      - Data\n      - Documents\n      - Storage\n    humanURL: https://www.openpolicyagent.org/docs/latest/rest-api/#data-api\n    properties:\n      - url: https://www.openpolicyagent.org/docs/latest/rest-api/#data-api\n        type: Documentation\n      - url: openapi/data-api.yml\n        type: OpenAPI\n      - url: data/bruno.json\n        type: BrunoCollection\n      - url: >2-\n\n          https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-96c58dc4-3514-48ee-a35f-a9c2aeb14fa0\n        type: PostmanCollection\n    description: API for reading and writing documents in OPA (Open Policy Agent).\n  - aid: open-policy-agent:open-policy-agent-query-api\n    name: Open Policy Agent Query API\n    tags:\n      - Evaluation\n      - Queries\n      - Rego\n    humanURL: https://www.openpolicyagent.org/docs/latest/rest-api/#query-api\n\
  \    properties:\n      - url: https://www.openpolicyagent.org/docs/latest/rest-api/#query-api\n        type: Documentation\n      - url: openapi/query-api.yml\n        type: OpenAPI\n      - url: query/bruno.json\n        type: BrunoCollection\n      - url: >2-\n\n          https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-9170dd84-c3d5-45a4-9efc-9ef6ab30744e\n        type: PostmanCollection\n    description: API for executing simple and ad-hoc queries in OPA (Open Policy Agent).\n  - aid: open-policy-agent:open-policy-agent-compile-api\n    name: Open Policy Agent Compile API\n    tags:\n      - Compile\n      - Evaluation\n      - Partial Evaluation\n    humanURL: https://www.openpolicyagent.org/docs/latest/rest-api/#compile-api\n    properties:\n      - url: https://www.openpolicyagent.org/docs/latest/rest-api/#compile-api\n        type: Documentation\n      - url: openapi/compile-api.yml\n        type: OpenAPI\n    \
  \  - url: compile/bruno.json\n        type: BrunoCollection\n      - url: >2-\n\n          https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-1e1d8e0e-7157-4b7f-99cf-611fa56a0c3c\n        type: PostmanCollection\n    description: API for partially evaluating Rego queries in OPA (Open Policy Agent).\n  - aid: open-policy-agent:open-policy-agent-health-api\n    name: Open Policy Agent Health API\n    tags:\n      - Availability\n      - Health\n      - Monitoring\n    humanURL: https://www.openpolicyagent.org/docs/latest/rest-api/#health-api\n    properties:\n      - url: https://www.openpolicyagent.org/docs/latest/rest-api/#health-api\n        type: Documentation\n      - url: openapi/health-api.yml\n        type: OpenAPI\n      - url: health/bruno.json\n        type: BrunoCollection\n      - url: >2-\n\n          https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-198cdb4f-e1d1-44c4-aa1f-ef8f66760d1a\n\
  \        type: PostmanCollection\n    description: >-\n      API for checking the health and readiness of an OPA (Open Policy Agent) server.\n  - aid: open-policy-agent:open-policy-agent-config-api\n    name: Open Policy Agent Config API\n    tags:\n      - Configurations\n      - Discovery\n      - Management\n    humanURL: https://www.openpolicyagent.org/docs/latest/rest-api/#config-api\n    properties:\n      - url: https://www.openpolicyagent.org/docs/latest/rest-api/#config-api\n        type: Documentation\n      - url: openapi/config-api.yml\n        type: OpenAPI\n      - url: config/bruno.json\n        type: BrunoCollection\n      - url: >2-\n\n          https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-979cbaf7-8515-4fd2-8035-134685590967\n        type: PostmanCollection\n    description: >-\n      API for retrieving OPA's active configuration, including discovered configurations.\n  - aid: open-policy-agent:open-policy-agent-status-api\n\
  \    name: Open Policy Agent Status API\n    tags:\n      - Monitoring\n      - Observability\n      - Status\n    humanURL: https://www.openpolicyagent.org/docs/latest/rest-api/#status-api\n    properties:\n      - url: https://www.openpolicyagent.org/docs/latest/rest-api/#status-api\n        type: Documentation\n      - url: openapi/status-api.yml\n        type: OpenAPI\n      - url: status/bruno.json\n        type: BrunoCollection\n      - url: >2-\n\n          https://api-evangelist.postman.co/workspace/Open-Policy-Agentbcc99d6c-728a-4d86-83fd-b6495f5e8fb8/collection/35240-b4943ca3-d651-4c68-a003-e6ca7feace03\n        type: PostmanCollection\n    description: >-\n      API for accessing OPA (Open Policy Agent) status information via a pull-based\n      mechanism.\nname: Open Policy Agent\ntags:\n  - Policies\n  - Standards\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: json-schema/opa-policy-schema.json\n\
  \    name: OPA Policy Schema\n    type: JSONSchema\n  - url: json-ld/opa-context.jsonld\n    name: OPA JSON-LD Context\n    type: JSON-LD\n  - url: https://www.openpolicyagent.org/\n    name: Website\n    type: Website\n  - url: https://www.openpolicyagent.org/docs/latest/\n    name: Documentation\n    type: Documentation\n  - url: https://www.openpolicyagent.org/docs/latest/rest-api/\n    name: REST API Documentation\n    type: Documentation\n  - url: https://www.openpolicyagent.org/docs/latest/#running-opa\n    name: Getting Started\n    type: Getting Started\n  - url: https://www.openpolicyagent.org/docs/latest/rest-api/#authentication\n    name: Authentication\n    type: Authentication\n  - url: https://www.openpolicyagent.org/docs/latest/rest-api/#errors\n    name: Errors\n    type: Errors\n  - url: https://github.com/open-policy-agent\n    name: GitHub Organization\n    type: GitHub Organization\n  - url: https://github.com/open-policy-agent/opa\n    name: OPA GitHub Repository\n\
  \    type: GitHubRepository\n  - url: https://blog.openpolicyagent.org/\n    name: Blog\n    type: Blog\n  - url: https://www.openpolicyagent.org/community/\n    name: Community\n    type: Community\n  - url: https://slack.openpolicyagent.org/\n    name: Slack\n    type: Slack\n  - url: https://github.com/open-policy-agent/opa/blob/main/CHANGELOG.md\n    name: Change Log\n    type: Change Log\n  - url: https://github.com/open-policy-agent/opa/security/policy\n    name: Security\n    type: Security\n  - url: https://stackoverflow.com/questions/tagged/open-policy-agent\n    name: Stack Overflow\n    type: Stack Overflow\n  - url: https://www.postman.com/api-evangelist/open-policy-agent/overview\n    name: Postman Workspace\n    type: PostmanWorkspace\n  - url: https://github.com/api-search/open-policy-agent\n    name: GitHub Repository\n    type: GitHubRepository\ncreated: '2024-11-18'\nmodified: '2026-04-28'\nposition: Consuming\ndescription: >-\n  Open Policy Agent (OPA) is an open-source\
  \ project that provides a flexible and powerful\n  policy engine for cloud-native environments. OPA enables users to define and enforce\n  policies across their infrastructure, applications, and services through a declarative\n  language called Rego. OPA integrates seamlessly with popular tools and frameworks\n  like Kubernetes, Istio, and Envoy, making it easy to implement fine-grained access\n  control, security, and compliance policies.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/apis.yml
tags:
- Policies
- Standards
url: https://raw.githubusercontent.com/api-evangelist/open-policy-agent/refs/heads/main/apis.yml
use_cases: []
---
