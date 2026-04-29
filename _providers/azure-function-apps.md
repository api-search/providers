---
api_count: 1
apis:
- description: REST API for managing Azure Function Apps, including creating, updating, and deleting function apps, as well as managing settings and deployments.
  name: Azure Function Apps REST API
  slug: azure-function-apps-rest-api
capabilities:
- description: Workflow capability for managing Azure Function Apps resources. Used by cloud engineers and DevOps teams.
  name: Azure Function Apps Management
  slug: azure-function-apps-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/azure-functions/
- title: ''
  type: Status
  url: https://status.azure.com
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/azure-functions/bg-p/AzureFunctionsBlog
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure/azure-functions
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/rules/azure-function-apps-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/vocabulary/azure-function-apps-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/json-ld/azure-function-apps-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/capabilities/azure-function-apps-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/capabilities/shared/azure-function-apps.yaml
created: '2024-01-01'
description: Azure Functions is a serverless compute service that lets you run event-triggered code without having to explicitly provision or manage infrastructure, with APIs for managing function apps, deployments, and runtime operations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Azure Function Apps Context
  property_count: 60
  slug: azure-function-apps-context
layout: provider
modified: '2026-04-19'
name: Azure Function Apps
rules:
- name: Azure Function Apps API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-function-apps-spectral-rules
skills: []
slug: azure-function-apps
solutions: []
source_yaml: "aid: azure-function-apps\nname: Azure Function Apps\ndescription: >-\n  Azure Functions is a serverless compute service that lets you run event-triggered\n  code without having to explicitly provision or manage infrastructure, with\n  APIs for managing function apps, deployments, and runtime operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Azure\n- Compute\n- FaaS\n- Functions\n- Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-function-apps:azure-function-apps-rest-api\n  name: Azure Function Apps REST API\n  description: >-\n    REST API for managing Azure Function Apps, including creating, updating,\n    and deleting function apps, as well as managing settings and deployments.\n  humanURL: https://learn.microsoft.com/en-us/azure/azure-functions/\n\
  \  baseURL: https://management.azure.com\n  tags:\n  - Functions\n  - Management\n  - Serverless\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/appservice/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/web/resource-manager/Microsoft.Web/stable/2022-09-01/WebApps.json\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook-trigger\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-get-started\ncommon:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/azure-functions/\n- type: Status\n  url: https://status.azure.com\n- type: Blog\n  url: https://techcommunity.microsoft.com/t5/azure-functions/bg-p/AzureFunctionsBlog\n- type: GitHub Organization\n  url: https://github.com/Azure/azure-functions\n\
  - type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/rules/azure-function-apps-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/vocabulary/azure-function-apps-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/json-ld/azure-function-apps-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/capabilities/azure-function-apps-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/capabilities/shared/azure-function-apps.yaml\nmaintainers:\n- FN: Kin Lane\n\
  \  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/apis.yml
tags:
- Azure
- Compute
- FaaS
- Functions
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/apis.yml
use_cases: []
---
