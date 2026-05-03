---
api_count: 6
api_specs:
- filename: talend-orchestration-openapi.yml
  format: yaml
  label: Talend Cloud Orchestration API
  slug: talend-orchestration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/openapi/talend-orchestration-openapi.yml
- filename: talend-processing-openapi.yml
  format: yaml
  label: Talend Cloud Processing API
  slug: talend-processing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/openapi/talend-processing-openapi.yml
apis:
- description: Manages tasks, plans, schedules, workspaces, environments, connections, artifacts, promotions, and resources in Qlik Talend Cloud. Use this API to automate data integration pipeline management, config
  name: Talend Cloud Orchestration API
  slug: talend-orchestration-api
- description: Manages task and plan executions, remote engines and clusters, and run profiles in Qlik Talend Cloud. Use this API to trigger and monitor data integration job runs, manage remote engine lifecycles, an
  name: Talend Cloud Processing API
  slug: talend-processing-api
- description: Manages user, group, and role identity information for Talend Cloud accounts. Supports SCIM v2 for automated provisioning from enterprise identity providers.
  name: Talend Cloud Identities Management API
  slug: talend-identities-api
- description: Load account audit logs for monitoring activities on Talend Cloud applications, ensuring data security and regulatory compliance.
  name: Talend Cloud Audit Logs API
  slug: talend-audit-logs-api
- description: Administers connections used by datasets and crawlers to retrieve data at scale.
  name: Talend Cloud Connections API
  slug: talend-connections-api
- description: Retrieve logs about task runs for debugging and monitoring data integration pipeline executions.
  name: Talend Cloud Execution Logs API
  slug: talend-execution-logs-api
capabilities:
- description: Workflow capability for data engineers and platform teams to manage, execute, and monitor data integration pipelines in Qlik Talend Cloud. Combines orchestration (task and plan management) with proces
  name: Talend Data Pipeline Management
  slug: data-pipeline-management
common:
- title: ''
  type: Portal
  url: https://talend.qlik.dev/
- title: ''
  type: Documentation
  url: https://talend.qlik.dev/
- title: ''
  type: APIs
  url: https://talend.qlik.dev/apis/
- title: ''
  type: Getting Started
  url: https://talend.qlik.dev/getting-started/
- title: ''
  type: Website
  url: https://www.talend.com/
- title: ''
  type: Qlik Data Fabric
  url: https://www.qlik.com/us/products/talend-data-fabric
- title: ''
  type: GitHub Org
  url: https://github.com/Talend
- title: ''
  type: Help
  url: https://help.qlik.com/en-US/cloud-services/Content/Sense_Helpsites/Home-talend-cloud.htm
- title: ''
  type: JSON Schema
  url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/json-schema/talend-task-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/vocabulary/talend-vocabulary.yml
created: '2026-03-16'
description: Talend (now part of Qlik) provides data integration, quality, and API management capabilities through cloud-native APIs for ETL, data pipelines, and application integration. The Qlik Talend Cloud platform exposes REST APIs for orchestrating tasks and plans, executing data integration jobs, managing remote engines, configuring connections, monitoring execution history, and administering identities, workspaces, and environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Talend Context
  property_count: 24
  slug: talend-context
layout: provider
modified: '2026-05-03'
name: Talend
rules:
- name: Talend API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 5
  slug: talend-api-rules
skills: []
slug: talend
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: talend\nname: Talend\ndescription: >-\n  Talend (now part of Qlik) provides data integration, quality, and API\n  management capabilities through cloud-native APIs for ETL, data pipelines,\n  and application integration. The Qlik Talend Cloud platform exposes REST APIs\n  for orchestrating tasks and plans, executing data integration jobs, managing\n  remote engines, configuring connections, monitoring execution history, and\n  administering identities, workspaces, and environments.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Management\n  - Data Integration\n  - Data Quality\n  - ETL\n  - Orchestration\n  - Pipelines\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: talend:talend-orchestration-api\n    name: Talend Cloud Orchestration\
  \ API\n    description: >-\n      Manages tasks, plans, schedules, workspaces, environments, connections,\n      artifacts, promotions, and resources in Qlik Talend Cloud. Use this API\n      to automate data integration pipeline management, configure execution\n      schedules, and manage workspace resources via Bearer token authentication.\n    humanURL: https://talend.qlik.dev/apis/orchestration/2021-03/\n    baseURL: https://api.{region}.cloud.talend.com\n    tags:\n      - Artifacts\n      - Connections\n      - ETL\n      - Orchestration\n      - Plans\n      - Tasks\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://talend.qlik.dev/apis/orchestration/2021-03/\n      - type: Getting Started\n        url: https://talend.qlik.dev/getting-started/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/openapi/talend-orchestration-openapi.yml\n  - aid: talend:talend-processing-api\n\
  \    name: Talend Cloud Processing API\n    description: >-\n      Manages task and plan executions, remote engines and clusters, and run\n      profiles in Qlik Talend Cloud. Use this API to trigger and monitor data\n      integration job runs, manage remote engine lifecycles, and configure\n      execution profiles.\n    humanURL: https://talend.qlik.dev/apis/processing/2021-03/\n    baseURL: https://api.{region}.cloud.talend.com\n    tags:\n      - ETL\n      - Execution\n      - Monitoring\n      - Remote Engine\n      - Run Profiles\n    properties:\n      - type: Documentation\n        url: https://talend.qlik.dev/apis/processing/2021-03/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/openapi/talend-processing-openapi.yml\n  - aid: talend:talend-identities-api\n    name: Talend Cloud Identities Management API\n    description: >-\n      Manages user, group, and role identity information for Talend Cloud\n\
  \      accounts. Supports SCIM v2 for automated provisioning from enterprise\n      identity providers.\n    humanURL: https://talend.qlik.dev/apis/identities-management/2021-03/\n    baseURL: https://api.{region}.cloud.talend.com\n    tags:\n      - Identity Management\n      - SCIM\n      - User Provisioning\n    properties:\n      - type: Documentation\n        url: https://talend.qlik.dev/apis/identities-management/2021-03/\n  - aid: talend:talend-audit-logs-api\n    name: Talend Cloud Audit Logs API\n    description: >-\n      Load account audit logs for monitoring activities on Talend Cloud\n      applications, ensuring data security and regulatory compliance.\n    humanURL: https://talend.qlik.dev/apis/audit-logs/2021-03/\n    baseURL: https://api.{region}.cloud.talend.com\n    tags:\n      - Audit\n      - Compliance\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://talend.qlik.dev/apis/audit-logs/2021-03/\n  - aid: talend:talend-connections-api\n\
  \    name: Talend Cloud Connections API\n    description: >-\n      Administers connections used by datasets and crawlers to retrieve data\n      at scale.\n    humanURL: https://talend.qlik.dev/apis/connections/2021-03/\n    baseURL: https://api.{region}.cloud.talend.com\n    tags:\n      - Connections\n      - Data Sources\n    properties:\n      - type: Documentation\n        url: https://talend.qlik.dev/apis/connections/2021-03/\n  - aid: talend:talend-execution-logs-api\n    name: Talend Cloud Execution Logs API\n    description: >-\n      Retrieve logs about task runs for debugging and monitoring data\n      integration pipeline executions.\n    humanURL: https://talend.qlik.dev/apis/execution-logs/2021-03/\n    baseURL: https://api.{region}.cloud.talend.com\n    tags:\n      - Execution Logs\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://talend.qlik.dev/apis/execution-logs/2021-03/\ncommon:\n  - type: Portal\n    url: https://talend.qlik.dev/\n\
  \  - type: Documentation\n    url: https://talend.qlik.dev/\n  - type: APIs\n    url: https://talend.qlik.dev/apis/\n  - type: Getting Started\n    url: https://talend.qlik.dev/getting-started/\n  - type: Website\n    url: https://www.talend.com/\n  - type: Qlik Data Fabric\n    url: https://www.qlik.com/us/products/talend-data-fabric\n  - type: GitHub Org\n    url: https://github.com/Talend\n  - type: Help\n    url: https://help.qlik.com/en-US/cloud-services/Content/Sense_Helpsites/Home-talend-cloud.htm\n  - type: JSON Schema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/json-schema/talend-task-schema.json\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/vocabulary/talend-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/apis.yml
tags:
- API Management
- Data Integration
- Data Quality
- ETL
- Orchestration
- Pipelines
url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/apis.yml
use_cases: []
---
