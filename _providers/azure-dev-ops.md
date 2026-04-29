---
api_count: 2
apis:
- description: REST API for Azure DevOps Services and Azure DevOps Server.
  name: Azure DevOps REST API
  slug: azure-devops-rest-api
- description: API for managing CI/CD pipelines, runs, and pipeline resources.
  name: Azure DevOps Pipelines API
  slug: azure-devops-pipelines-api
capabilities:
- description: Workflow capability for managing Azure DevOps resources. Used by cloud engineers and DevOps teams.
  name: Azure DevOps Management
  slug: azure-dev-ops-management
common:
- title: ''
  type: Portal
  url: https://dev.azure.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/devops/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/devops/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate
- title: ''
  type: Status
  url: https://status.dev.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/devops/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/devops/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/rules/azure-dev-ops-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/vocabulary/azure-dev-ops-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/json-ld/azure-dev-ops-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/capabilities/azure-dev-ops-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/capabilities/shared/azure-dev-ops.yaml
created: '2024-01-01'
description: Azure DevOps provides developer services for support teams to plan work, collaborate on code development, and build and deploy applications through a comprehensive set of REST APIs covering builds, releases, Git, pipelines, work items, test management, and artifacts.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 17
  name: Azure Dev Ops Context
  property_count: 23
  slug: azure-dev-ops-context
layout: provider
modified: '2026-04-19'
name: Azure DevOps
rules:
- name: Azure DevOps API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-dev-ops-spectral-rules
skills: []
slug: azure-dev-ops
solutions: []
source_filename: apis.yml
source_yaml: "aid: azure-dev-ops\nname: Azure DevOps\ndescription: >-\n  Azure DevOps provides developer services for support teams to plan work,\n  collaborate on code development, and build and deploy applications through\n  a comprehensive set of REST APIs covering builds, releases, Git, pipelines,\n  work items, test management, and artifacts.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Azure\n- CI/CD\n- DevOps\n- Project Management\n- Version Control\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-dev-ops:azure-devops-rest-api\n  name: Azure DevOps REST API\n  description: REST API for Azure DevOps Services and Azure DevOps Server.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n  baseURL: https://dev.azure.com/{organization}\n  tags:\n  - CI/CD\n  - DevOps\n\
  \  - REST\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/openapi/azure-dev-ops-openapi.yaml\n- aid: azure-dev-ops:azure-devops-pipelines-api\n  name: Azure DevOps Pipelines API\n  description: API for managing CI/CD pipelines, runs, and pipeline resources.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/\n  baseURL: https://dev.azure.com/{organization}/{project}/_apis/pipelines\n  tags:\n  - Automation\n  - CI/CD\n  - Pipelines\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/openapi/azure-dev-ops-openapi.yaml\n\
  common:\n- type: Portal\n  url: https://dev.azure.com/\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/devops/\n- type: Getting Started\n  url: https://learn.microsoft.com/en-us/azure/devops/\n- type: Authentication\n  url: https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate\n- type: Status\n  url: https://status.dev.azure.com/\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/devops/\n- type: Blog\n  url: https://devblogs.microsoft.com/devops/\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/rules/azure-dev-ops-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/vocabulary/azure-dev-ops-vocabulary.yaml\n\
  - type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/json-ld/azure-dev-ops-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/capabilities/azure-dev-ops-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/capabilities/shared/azure-dev-ops.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/apis.yml
tags:
- Azure
- CI/CD
- DevOps
- Project Management
- Version Control
url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/apis.yml
use_cases: []
---
