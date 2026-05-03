---
api_count: 3
api_specs:
- filename: webmethods-api-gateway-openapi.yml
  format: yaml
  label: webMethods API Gateway Service Management API
  slug: webmethods-api-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/openapi/webmethods-api-gateway-openapi.yml
apis:
- description: The webMethods API Gateway Service Management API provides REST endpoints for managing APIs within the API Gateway platform. It supports creating, reading, updating, and deleting REST, SOAP, WebSocket
  name: webMethods API Gateway Service Management API
  slug: webmethods-api-gateway
- description: The webMethods Developer Portal provides a marketplace for publishing and discovering REST, SOAP, and OData APIs for third-party developers and partners. It enables developer onboarding, API subscript
  name: webMethods Developer Portal
  slug: webmethods-developer-portal
- description: The webMethods Integration Server is a comprehensive integration platform that enables connectivity between enterprise applications, databases, legacy systems, and cloud services. It provides flow ser
  name: webMethods Integration Server
  slug: webmethods-integration-server
capabilities:
- description: Unified API management workflow for Software AG webMethods, combining API Gateway management operations for creating, activating, publishing, and monitoring APIs in enterprise integration environments
  name: Software AG webMethods API Management
  slug: api-management
common:
- title: ''
  type: Portal
  url: https://developer.softwareag.com/
- title: ''
  type: Website
  url: https://www.softwareag.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/SoftwareAG
- title: ''
  type: Documentation
  url: https://documentation.softwareag.com/
- title: ''
  type: Blog
  url: https://techcommunity.softwareag.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/software-ag
- title: ''
  type: Twitter
  url: https://twitter.com/SoftwareAG
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-ld/software-ag-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/vocabulary/software-ag-vocabulary.yml
created: '2026-03-16'
description: Software AG provides enterprise integration and API management through webMethods, a platform for connecting applications, processes, and people across hybrid cloud and on-premises environments. The webMethods platform includes API Gateway, Developer Portal, Integration Server, and cloud-native integration services. Software AG was acquired by IBM in 2024.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Software Ag Context
  property_count: 18
  slug: software-ag-context
layout: provider
modified: '2026-05-02'
name: Software AG
rules:
- name: Software AG API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 6
  slug: webmethods-api-gateway-rules
skills: []
slug: software-ag
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: software-ag\nname: Software AG\ndescription: >-\n  Software AG provides enterprise integration and API management through\n  webMethods, a platform for connecting applications, processes, and people\n  across hybrid cloud and on-premises environments. The webMethods platform\n  includes API Gateway, Developer Portal, Integration Server, and cloud-native\n  integration services. Software AG was acquired by IBM in 2024.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Management\n  - Enterprise Integration\n  - iPaaS\n  - webMethods\n  - Integration Platform\n  - API Gateway\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: software-ag:webmethods-api-gateway\n    name: webMethods API Gateway Service Management API\n    description: >-\n      The webMethods API Gateway Service\
  \ Management API provides REST endpoints\n      for managing APIs within the API Gateway platform. It supports creating,\n      reading, updating, and deleting REST, SOAP, WebSocket, and OData APIs,\n      as well as managing policies, applications, and gateway endpoints.\n    humanURL: https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/co-oview_what_is_api_portal.html\n    baseURL: http://localhost:5555/rest/apigateway\n    tags:\n      - API Management\n      - API Gateway\n      - Enterprise Integration\n      - webMethods\n    properties:\n      - type: Documentation\n        url: https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/gtw_manage_apis.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/openapi/webmethods-api-gateway-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/SoftwareAG/webmethods-api-gateway\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-schema/webmethods-api-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-structure/webmethods-api-structure.json\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/rules/webmethods-api-gateway-rules.yml\n      - type: NaftikoCapabilities\n        url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/capabilities/api-management.yaml\n\n  - aid: software-ag:webmethods-developer-portal\n    name: webMethods Developer Portal\n    description: >-\n      The webMethods Developer Portal provides a marketplace for publishing and\n      discovering REST, SOAP, and OData APIs for third-party developers and\n      partners. It enables developer onboarding, API subscription management,\n      and API\
  \ consumption analytics.\n    humanURL: https://www.softwareag.com/en_corporate/resources/api/ds/webmethods-developer-portal.html\n    baseURL: https://www.softwareag.com/\n    tags:\n      - Developer Portal\n      - API Management\n      - API Marketplace\n      - webMethods\n    properties:\n      - type: Documentation\n        url: https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/co-oview_what_is_api_portal.html\n      - type: GitHubRepository\n        url: https://github.com/SoftwareAG/webmethods-developer-portal\n\n  - aid: software-ag:webmethods-integration-server\n    name: webMethods Integration Server\n    description: >-\n      The webMethods Integration Server is a comprehensive integration platform\n      that enables connectivity between enterprise applications, databases,\n      legacy systems, and cloud services. It provides flow services, adapters,\n      and REST API exposure for business process integration.\n    humanURL:\
  \ https://documentation.softwareag.com/\n    baseURL: https://www.softwareag.com/\n    tags:\n      - Integration\n      - Enterprise\n      - Middleware\n      - webMethods\n      - iPaaS\n    properties:\n      - type: Documentation\n        url: https://documentation.softwareag.com/\n\ncommon:\n  - type: Portal\n    url: https://developer.softwareag.com/\n  - type: Website\n    url: https://www.softwareag.com/\n  - type: GitHubOrganization\n    url: https://github.com/SoftwareAG\n  - type: Documentation\n    url: https://documentation.softwareag.com/\n  - type: Blog\n    url: https://techcommunity.softwareag.com/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/software-ag\n  - type: Twitter\n    url: https://twitter.com/SoftwareAG\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-ld/software-ag-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/vocabulary/software-ag-vocabulary.yml\n\
  \nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/apis.yml
tags:
- API Management
- Enterprise Integration
- iPaaS
- webMethods
- Integration Platform
- API Gateway
url: https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/apis.yml
use_cases: []
---
