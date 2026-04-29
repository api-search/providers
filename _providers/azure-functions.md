---
api_count: 2
apis:
- description: REST API for managing Azure Functions apps, function deployments, and configuration.
  name: Azure Functions Management API
  slug: azure-functions-management-api
- description: API for invoking and interacting with deployed Azure Functions.
  name: Azure Functions Runtime API
  slug: azure-functions-runtime-api
capabilities:
- description: Workflow capability for managing Azure Functions resources. Used by cloud engineers and DevOps teams.
  name: Azure Functions Management
  slug: azure-functions-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/azure-functions/
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/azure-functions/bg-p/AzureFunctionsBlog
- title: ''
  type: Status
  url: https://status.azure.com
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure/Azure-Functions
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/rules/azure-functions-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/vocabulary/azure-functions-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/json-ld/azure-functions-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/capabilities/azure-functions-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/capabilities/shared/azure-functions.yaml
created: '2024-01-01'
description: Azure Functions is a serverless compute service that lets you run event-triggered code without having to explicitly provision or manage infrastructure, supporting multiple programming languages and integration patterns.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Azure Functions Context
  property_count: 60
  slug: azure-functions-context
layout: provider
modified: '2026-04-19'
name: Azure Functions
rules:
- name: Azure Functions API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-functions-spectral-rules
skills: []
slug: azure-functions
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: azure-functions\nname: Azure Functions\ndescription: >-\n  Azure Functions is a serverless compute service that lets you run\n  event-triggered code without having to explicitly provision or manage\n  infrastructure, supporting multiple programming languages and integration\n  patterns.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Cloud\n- Compute\n- Event-Driven\n- Functions\n- Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-functions:azure-functions-management-api\n  name: Azure Functions Management API\n  description: REST API for managing Azure Functions apps, function deployments, and configuration.\n  humanURL: https://docs.microsoft.com/en-us/azure/azure-functions/\n  baseURL: https://management.azure.com\n  tags:\n  - Deployment\n  - Functions\n\
  \  - Management\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/rest/api/appservice/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/web/resource-manager/Microsoft.Web/stable/2022-03-01/WebApps.json\n  - type: Getting Started\n    url: https://docs.microsoft.com/en-us/azure/azure-functions/functions-get-started\n- aid: azure-functions:azure-functions-runtime-api\n  name: Azure Functions Runtime API\n  description: API for invoking and interacting with deployed Azure Functions.\n  humanURL: https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference\n  baseURL: https://{function-app-name}.azurewebsites.net\n  tags:\n  - HTTP Triggers\n  - Invocation\n  - Runtime\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/openapi/azure-functions-openapi.yaml\n\
  common:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/azure-functions/\n- type: Blog\n  url: https://techcommunity.microsoft.com/t5/azure-functions/bg-p/AzureFunctionsBlog\n- type: Status\n  url: https://status.azure.com\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/options/\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: GitHub Organization\n  url: https://github.com/Azure/Azure-Functions\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/rules/azure-functions-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/vocabulary/azure-functions-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/json-ld/azure-functions-context.jsonld\n\
  - type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/capabilities/azure-functions-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/capabilities/shared/azure-functions.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/apis.yml
tags:
- Cloud
- Compute
- Event-Driven
- Functions
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/apis.yml
use_cases: []
---
