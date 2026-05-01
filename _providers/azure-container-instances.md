---
api_count: 1
api_specs:
- filename: azure-container-instances-openapi.yaml
  format: yaml
  label: Azure Container Instances
  slug: azure-container-instances
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/openapi/azure-container-instances-openapi.yaml
apis:
- description: Azure Container Instances is a service that enables you to run containers directly on the Microsoft Azure cloud without managing virtual machines or adopting orchestration services. It provides fast s
  name: Azure Container Instances
  slug: azure-container-instances
capabilities:
- description: Workflow capability for managing Azure Container Instances resources. Used by cloud engineers and DevOps teams.
  name: Azure Container Instances Management
  slug: azure-container-instances-management
common:
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/container-instances
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/container-instances/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/container-instances/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free/
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/rules/azure-container-instances-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/vocabulary/azure-container-instances-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/json-ld/azure-container-instances-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/capabilities/azure-container-instances-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/capabilities/shared/azure-container-instances.yaml
created: '2026-03-26'
description: Azure Container Instances (ACI) is the fastest and simplest way to run containers in Azure without having to manage virtual machines or adopt a higher-level orchestration service. It offers serverless containers with per-second billing, custom sizes, and seamless integration with the Azure ecosystem for burst and event-driven workloads.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Azure Container Instances Context
  property_count: 50
  slug: azure-container-instances-context
layout: provider
modified: '2026-04-19'
name: Azure Container Instances
rules:
- name: Azure Container Instances API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-container-instances-spectral-rules
skills: []
slug: azure-container-instances
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: azure-container-instances\nname: Azure Container Instances\ndescription: >-\n  Azure Container Instances (ACI) is the fastest and simplest way to run\n  containers in Azure without having to manage virtual machines or adopt a\n  higher-level orchestration service. It offers serverless containers with\n  per-second billing, custom sizes, and seamless integration with the Azure\n  ecosystem for burst and event-driven workloads.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Azure\n- Cloud\n- Container Instances\n- Containers\n- Microsoft\n- Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-container-instances:azure-container-instances\n  name: Azure Container Instances\n  description: >-\n    Azure Container Instances is a service that enables you\
  \ to run containers\n    directly on the Microsoft Azure cloud without managing virtual machines\n    or adopting orchestration services. It provides fast startup times,\n    per-second billing, custom CPU and memory sizing, and persistent storage\n    with Azure Files integration for both Linux and Windows containers.\n  humanURL: https://azure.microsoft.com/en-us/products/container-instances\n  tags:\n  - Azure\n  - Cloud\n  - Container Instances\n  - Containers\n  - Microsoft\n  - Serverless\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/container-instances/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/container-instances/container-instances-quickstart\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/openapi/azure-container-instances-openapi.yaml\ncommon:\n- type: Website\n  url: https://azure.microsoft.com/en-us/products/container-instances\n\
  - type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/container-instances/\n- type: Pricing\n  url: https://azure.microsoft.com/en-us/pricing/details/container-instances/\n- type: Blog\n  url: https://azure.microsoft.com/en-us/blog/\n- type: Sign Up\n  url: https://azure.microsoft.com/en-us/free/\n- type: GitHub Organization\n  url: https://github.com/Azure\n- type: Status\n  url: https://status.azure.com/\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/rules/azure-container-instances-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/vocabulary/azure-container-instances-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/json-ld/azure-container-instances-context.jsonld\n\
  - type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/capabilities/azure-container-instances-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/capabilities/shared/azure-container-instances.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/apis.yml
tags:
- Azure
- Cloud
- Container Instances
- Containers
- Microsoft
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/apis.yml
use_cases: []
---
