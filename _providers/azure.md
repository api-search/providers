---
api_count: 3
apis:
- description: Manage virtual machines, containers, and serverless computing resources.
  name: Azure Compute API
  slug: azure-compute-api
- description: Scalable cloud storage for data objects, files, messages, and more.
  name: Azure Storage API
  slug: azure-storage-api
- description: Add AI capabilities including vision, speech, language, and decision-making.
  name: Azure Cognitive Services API
  slug: azure-cognitive-services-api
capabilities:
- description: Workflow capability for managing Microsoft Azure resources. Used by cloud engineers and DevOps teams.
  name: Microsoft Azure Management
  slug: azure-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/rules/azure-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/vocabulary/azure-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/json-ld/azure-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/capabilities/azure-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/capabilities/shared/azure.yaml
created: '2024-01-01'
description: Microsoft Azure is a comprehensive cloud computing platform offering IaaS, PaaS, and SaaS solutions for building, deploying, and managing applications through Microsoft's global network of datacenters.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Azure Context
  property_count: 16
  slug: azure-context
layout: provider
modified: '2026-04-19'
name: Microsoft Azure
rules:
- name: Microsoft Azure API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-spectral-rules
skills: []
slug: azure
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: azure\nname: Microsoft Azure\ndescription: >-\n  Microsoft Azure is a comprehensive cloud computing platform offering IaaS,\n  PaaS, and SaaS solutions for building, deploying, and managing applications\n  through Microsoft's global network of datacenters.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Cloud Computing\n- Databases\n- Infrastructure\n- Machine Learning\n- Networking\n- Platform as a Service\n- Storage\nurl: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure:azure-compute-api\n  name: Azure Compute API\n  description: Manage virtual machines, containers, and serverless computing resources.\n  humanURL: https://azure.microsoft.com/en-us/products/category/compute\n  baseURL: https://management.azure.com\n  tags:\n  - Containers\n  - Functions\n  - Kubernetes\n  - Virtual Machines\n\
  \  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/compute/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/openapi/azure-management-openapi.yaml\n- aid: azure:azure-storage-api\n  name: Azure Storage API\n  description: Scalable cloud storage for data objects, files, messages, and more.\n  humanURL: https://azure.microsoft.com/en-us/products/category/storage\n  baseURL: https://management.azure.com\n  tags:\n  - Blob Storage\n  - File Storage\n  - Queue Storage\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/storageservices/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/openapi/azure-management-openapi.yaml\n- aid: azure:azure-cognitive-services-api\n  name: Azure Cognitive Services API\n  description: Add AI capabilities including vision, speech, language, and decision-making.\n  humanURL: https://azure.microsoft.com/en-us/products/cognitive-services\n\
  \  baseURL: https://{region}.api.cognitive.microsoft.com\n  tags:\n  - Artificial Intelligence\n  - Computer Vision\n  - Natural Language\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/cognitive-services/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/openapi/azure-management-openapi.yaml\ncommon:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/\n- type: Status\n  url: https://status.azure.com/\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/\n- type: Blog\n  url: https://azure.microsoft.com/en-us/blog/\n- type: GitHub Organization\n  url: https://github.com/Azure\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: Sign Up\n  url: https://azure.microsoft.com/en-us/free/\n- type:\
  \ SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/rules/azure-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/vocabulary/azure-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/json-ld/azure-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/capabilities/azure-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/capabilities/shared/azure.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/apis.yml
tags:
- Cloud Computing
- Databases
- Infrastructure
- Machine Learning
- Networking
- Platform as a Service
- Storage
url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/apis.yml
use_cases: []
---
