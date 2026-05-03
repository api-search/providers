---
api_count: 4
api_specs:
- filename: tanium-platform-rest-api-openapi.yml
  format: yaml
  label: Tanium Platform REST API
  slug: platform-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/openapi/tanium-platform-rest-api-openapi.yml
- filename: tanium-threat-response-api-openapi.yml
  format: yaml
  label: Tanium Threat Response API
  slug: threat-response-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/openapi/tanium-threat-response-api-openapi.yml
- filename: tanium-connect-api-openapi.yml
  format: yaml
  label: Tanium Connect API
  slug: connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/openapi/tanium-connect-api-openapi.yml
apis:
- description: The Tanium API Gateway is a GraphQL interface for querying data and taking action in Tanium. It is the preferred method for integrating with Tanium, supporting asset queries, endpoint actions, and dat
  name: Tanium API Gateway
  slug: api-gateway
- description: The Tanium Platform REST API provides access to core platform functionality including gathering endpoint information, deploying actions, evaluating deployment health, managing certificates, updating p
  name: Tanium Platform REST API
  slug: platform-rest-api
- description: The Tanium Threat Response REST API enables starting investigations, viewing Recorder events, gathering evidence, and performing file and directory operations on endpoints for threat detection and inc
  name: Tanium Threat Response API
  slug: threat-response-api
- description: The Tanium Connect REST API allows creating, editing, and managing connections for delivering endpoint data to downstream systems via files, syslog, webhooks, and other destination types on a schedule
  name: Tanium Connect API
  slug: connect-api
capabilities:
- description: Workflow capability for unified endpoint management and security operations using Tanium. Combines the Platform REST API, Threat Response API, and Connect API to enable endpoint visibility, action dep
  name: Tanium Endpoint Management
  slug: endpoint-management
common:
- title: ''
  type: JSONSchema
  url: json-schema/tanium-endpoint-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tanium-question-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tanium-alert-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tanium-sensor-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tanium-package-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tanium-action-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tanium-connection-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/tanium-endpoint-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/tanium-action-structure.json
- title: ''
  type: JSONLD
  url: json-ld/tanium-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/tanium-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/endpoint-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tanium-vocabulary.yml
- title: ''
  type: Portal
  url: https://developer.tanium.com/
- title: ''
  type: Documentation
  url: https://help.tanium.com/
- title: ''
  type: GettingStarted
  url: https://developer.tanium.com/apis/api_intro
- title: ''
  type: Authentication
  url: https://docs.tanium.com/platform_user/platform_user/console_api_tokens.html
- title: ''
  type: Blog
  url: https://www.tanium.com/p/tanium-blog/
- title: ''
  type: Support
  url: https://community.tanium.com/s/
- title: ''
  type: TermsOfService
  url: https://www.tanium.com/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.tanium.com/privacy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/tanium
- title: ''
  type: Community
  url: https://community.tanium.com/s/
- title: ''
  type: Website
  url: https://www.tanium.com/
- title: ''
  type: Login
  url: https://community.tanium.com/s/login/
- title: ''
  type: SignUp
  url: https://community.tanium.com/CommunitiesSelfReg
- title: ''
  type: SDKs
  url: https://tanium.github.io/pytan/
- title: ''
  type: IntegrationGuide
  url: https://developer.tanium.com/guides/core-platform/integration_methods
- title: ''
  type: ChangeLog
  url: https://help.tanium.com/bundle/releasenotes/page/releasenotes/index.html
- title: ''
  type: Contact
  url: https://www.tanium.com/contact/
created: '2025-02-06'
description: Tanium is a unified endpoint management and security platform that provides real-time visibility and control across all endpoints. It offers a suite of APIs including a GraphQL-based API Gateway and platform REST APIs for integrating with endpoint management, security, compliance, and threat response capabilities.
features: []
image: https://www.tanium.com/images/tanium-logo.png
integrations: []
jsonld:
- class_count: 3
  name: Tanium Context
  property_count: 13
  slug: tanium-context
layout: provider
modified: '2026-05-03'
name: Tanium
rules:
- name: Tanium API Rules
  rule_count: 8
  severity_counts:
    error: 0
    hint: 2
    info: 1
    warn: 5
  slug: tanium-rules
skills: []
slug: tanium
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tanium\nname: Tanium\ndescription: Tanium is a unified endpoint management and security platform that provides real-time visibility and control across all endpoints. It offers a suite of APIs including a GraphQL-based API Gateway and platform REST APIs for integrating with endpoint management, security, compliance, and threat response capabilities.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://www.tanium.com/images/tanium-logo.png\ntags:\n  - Compliance\n  - Endpoint Management\n  - Patch Management\n  - Security\n  - Threat Detection\n  - Unified Endpoint Management\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/apis.yml\nspecificationVersion: '0.18'\napis:\n  - aid: tanium:api-gateway\n    name: Tanium API Gateway\n    description: The Tanium API Gateway is a GraphQL interface for querying data and taking action in Tanium. It is the preferred method for integrating with\
  \ Tanium, supporting asset queries, endpoint actions, and data retrieval across the platform.\n    humanURL: https://docs.tanium.com/api_gateway/api_gateway/overview.html\n    tags:\n      - API Gateway\n      - Endpoints\n      - GraphQL\n      - Integration\n      - Queries\n    properties:\n      - type: Documentation\n        url: https://docs.tanium.com/api_gateway/api_gateway/overview.html\n      - type: Reference\n        url: https://docs.tanium.com/api_gateway/api_gateway/api_gateway_examples.html\n      - type: GettingStarted\n        url: https://docs.tanium.com/api_gateway/api_gateway/api_gateway.html\n      - type: GraphQLSchema\n        url: https://developer.tanium.com/site/global/apis/graphql/schema/\n  - aid: tanium:platform-rest-api\n    name: Tanium Platform REST API\n    description: The Tanium Platform REST API provides access to core platform functionality including gathering endpoint information, deploying actions, evaluating deployment health, managing certificates,\
  \ updating packages, and downloading audit logs.\n    humanURL: https://developer.tanium.com/apis/api_intro\n    tags:\n      - Actions\n      - Endpoints\n      - Platform\n      - REST API\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.tanium.com/apis/api_intro\n      - type: IntegrationGuide\n        url: https://developer.tanium.com/guides/core-platform/integration_methods\n      - type: Authentication\n        url: https://docs.tanium.com/platform_user/platform_user/console_api_tokens.html\n      - type: OpenAPI\n        url: openapi/tanium-platform-rest-api-openapi.yml\n  - aid: tanium:threat-response-api\n    name: Tanium Threat Response API\n    description: The Tanium Threat Response REST API enables starting investigations, viewing Recorder events, gathering evidence, and performing file and directory operations on endpoints for threat detection and incident response.\n    humanURL: https://developer.tanium.com/site/global/docs/how_tos/tr_actions/index.gsp\n\
  \    tags:\n      - Incident Response\n      - Investigations\n      - Security\n      - Threat Detection\n      - Threat Response\n    properties:\n      - type: Documentation\n        url: https://developer.tanium.com/site/global/docs/how_tos/tr_actions/index.gsp\n      - type: GettingStarted\n        url: https://help.tanium.com/bundle/ug_threat_response_cloud/page/threat_response/gettingstarted.html\n      - type: OpenAPI\n        url: openapi/tanium-threat-response-api-openapi.yml\n  - aid: tanium:connect-api\n    name: Tanium Connect API\n    description: The Tanium Connect REST API allows creating, editing, and managing connections for delivering endpoint data to downstream systems via files, syslog, webhooks, and other destination types on a schedule or triggered by events.\n    humanURL: https://docs.tanium.com/connect/connect/index.html\n    tags:\n      - Connections\n      - Data Delivery\n      - Integration\n      - Syslog\n      - Webhooks\n    properties:\n      - type:\
  \ Documentation\n        url: https://docs.tanium.com/connect/connect/index.html\n      - type: OpenAPI\n        url: openapi/tanium-connect-api-openapi.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: JSONSchema\n    url: json-schema/tanium-endpoint-schema.json\n  - type: JSONSchema\n    url: json-schema/tanium-question-schema.json\n  - type: JSONSchema\n    url: json-schema/tanium-alert-schema.json\n  - type: JSONSchema\n    url: json-schema/tanium-sensor-schema.json\n  - type: JSONSchema\n    url: json-schema/tanium-package-schema.json\n  - type: JSONSchema\n    url: json-schema/tanium-action-schema.json\n  - type: JSONSchema\n    url: json-schema/tanium-connection-schema.json\n  - type: JSONStructure\n    url: json-structure/tanium-endpoint-structure.json\n  - type: JSONStructure\n    url: json-structure/tanium-action-structure.json\n  - type: JSONLD\n    url: json-ld/tanium-context.jsonld\n  - type: SpectralRules\n    url: rules/tanium-rules.yml\n\
  \  - type: NaftikoCapabilities\n    url: capabilities/endpoint-management.yaml\n  - type: Vocabulary\n    url: vocabulary/tanium-vocabulary.yml\n  - type: Portal\n    url: https://developer.tanium.com/\n  - type: Documentation\n    url: https://help.tanium.com/\n  - type: GettingStarted\n    url: https://developer.tanium.com/apis/api_intro\n  - type: Authentication\n    url: https://docs.tanium.com/platform_user/platform_user/console_api_tokens.html\n  - type: Blog\n    url: https://www.tanium.com/p/tanium-blog/\n  - type: Support\n    url: https://community.tanium.com/s/\n  - type: TermsOfService\n    url: https://www.tanium.com/terms-of-use/\n  - type: PrivacyPolicy\n    url: https://www.tanium.com/privacy/\n  - type: GitHubOrganization\n    url: https://github.com/tanium\n  - type: Community\n    url: https://community.tanium.com/s/\n  - type: Website\n    url: https://www.tanium.com/\n  - type: Login\n    url: https://community.tanium.com/s/login/\n  - type: SignUp\n    url: https://community.tanium.com/CommunitiesSelfReg\n\
  \  - type: SDKs\n    url: https://tanium.github.io/pytan/\n  - type: IntegrationGuide\n    url: https://developer.tanium.com/guides/core-platform/integration_methods\n  - type: UseCases\n    url: https://developer.tanium.com/use_cases\n  - type: ChangeLog\n    url: https://help.tanium.com/bundle/releasenotes/page/releasenotes/index.html\n  - type: Contact\n    url: https://www.tanium.com/contact/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/apis.yml
tags:
- Compliance
- Endpoint Management
- Patch Management
- Security
- Threat Detection
- Unified Endpoint Management
url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/apis.yml
use_cases: []
---
