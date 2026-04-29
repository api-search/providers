---
api_count: 2
apis:
- description: REST API for managing Azure Synapse Analytics workspaces, SQL pools, Spark pools, and pipelines.
  name: Azure Synapse REST API
  slug: azure-synapse-rest-api
- description: API for creating and managing data integration pipelines.
  name: Azure Synapse Pipeline API
  slug: azure-synapse-pipeline-api
capabilities:
- description: Workflow capability for managing Azure Synapse Analytics resources. Used by cloud engineers and DevOps teams.
  name: Azure Synapse Analytics Management
  slug: azure-synapse-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://docs.microsoft.com/en-us/azure/synapse-analytics/
- title: ''
  type: Getting Started
  url: https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/bg-p/AzureSynapseAnalyticsBlog
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure/azure-synapse-analytics
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/rules/azure-synapse-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/vocabulary/azure-synapse-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/json-ld/azure-synapse-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/capabilities/azure-synapse-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/capabilities/shared/azure-synapse.yaml
created: '2024-01-01'
description: Azure Synapse Analytics is an enterprise analytics service that accelerates time to insight across data warehouses and big data systems. It brings together SQL technologies, Spark technologies, Data Explorer, and integrated pipelines for data integration and ETL/ELT.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Azure Synapse Context
  property_count: 8
  slug: azure-synapse-context
layout: provider
modified: '2026-04-19'
name: Azure Synapse Analytics
rules:
- name: Azure Synapse Analytics API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-synapse-spectral-rules
skills: []
slug: azure-synapse
solutions: []
source_filename: apis.yml
source_yaml: "aid: azure-synapse\nname: Azure Synapse Analytics\ndescription: >-\n  Azure Synapse Analytics is an enterprise analytics service that accelerates\n  time to insight across data warehouses and big data systems. It brings\n  together SQL technologies, Spark technologies, Data Explorer, and integrated\n  pipelines for data integration and ETL/ELT.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Analytics\n- Apache Spark\n- Big Data\n- Data Warehouse\n- ETL\n- SQL\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-synapse:azure-synapse-rest-api\n  name: Azure Synapse REST API\n  description: >-\n    REST API for managing Azure Synapse Analytics workspaces, SQL pools,\n    Spark pools, and pipelines.\n  humanURL: https://docs.microsoft.com/en-us/rest/api/synapse/\n  baseURL: https://management.azure.com\n\
  \  tags:\n  - Management\n  - REST API\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/rest/api/synapse/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/synapse/resource-manager/Microsoft.Synapse/stable/2021-06-01/synapse.json\n  - type: Authentication\n    url: https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios\n- aid: azure-synapse:azure-synapse-pipeline-api\n  name: Azure Synapse Pipeline API\n  description: API for creating and managing data integration pipelines.\n  humanURL: https://docs.microsoft.com/en-us/rest/api/synapse/data-plane/pipeline\n  baseURL: https://{workspaceName}.dev.azuresynapse.net\n  tags:\n  - Data Integration\n  - ETL\n  - Pipeline\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/rest/api/synapse/data-plane/pipeline\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/openapi/azure-synapse-openapi.yaml\n\
  common:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n  url: https://docs.microsoft.com/en-us/azure/synapse-analytics/\n- type: Getting Started\n  url: https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started\n- type: Status\n  url: https://status.azure.com/\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/\n- type: Blog\n  url: https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/bg-p/AzureSynapseAnalyticsBlog\n- type: GitHub Organization\n  url: https://github.com/Azure/azure-synapse-analytics\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/rules/azure-synapse-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/vocabulary/azure-synapse-vocabulary.yaml\n\
  - type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/json-ld/azure-synapse-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/capabilities/azure-synapse-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/capabilities/shared/azure-synapse.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/apis.yml
tags:
- Analytics
- Apache Spark
- Big Data
- Data Warehouse
- ETL
- SQL
url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/apis.yml
use_cases: []
---
