---
api_count: 2
apis:
- description: The Microsoft Fabric REST API provides programmatic access to the unified analytics platform. Developers can manage workspaces, lakehouses, warehouses, data pipelines, notebooks, and other Fabric item
  name: Microsoft Fabric REST API
  slug: rest-api
- description: 'Microsoft Fabric provides SQL connectivity to lakehouses and data warehouses through TDS endpoints. Developers can query Fabric data using standard SQL tools, JDBC/ODBC drivers, and client libraries, '
  name: Microsoft Fabric SQL Connection
  slug: sql-connection-api
common:
- title: ''
  type: Portal
  url: https://app.fabric.microsoft.com/
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-fabric
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/fabric/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/fabric/get-started/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/microsoft-fabric/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/fabric/security/permission-model
- title: ''
  type: Blog
  url: https://blog.fabric.microsoft.com/
- title: ''
  type: Community
  url: https://community.fabric.microsoft.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: Status
  url: https://status.fabric.microsoft.com/
created: '2024-01-01'
description: Microsoft Fabric is a unified analytics platform that brings together data engineering, data science, real-time analytics, and business intelligence. It provides REST APIs for managing workspaces, lakehouses, warehouses, data pipelines, notebooks, and other Fabric items.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Fabric
skills: []
slug: microsoft-fabric
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-fabric\nname: Microsoft Fabric\ndescription: >-\n  Microsoft Fabric is a unified analytics platform that brings together data\n  engineering, data science, real-time analytics, and business intelligence.\n  It provides REST APIs for managing workspaces, lakehouses, warehouses,\n  data pipelines, notebooks, and other Fabric items.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Analytics\n  - Data Engineering\n  - Data Platform\n  - Lakehouse\n  - Microsoft\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-fabric/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-fabric:rest-api\n    name: Microsoft Fabric REST API\n    description: >-\n      The Microsoft Fabric REST API provides programmatic access to the\n      unified analytics platform. Developers can manage workspaces,\n      lakehouses, warehouses,\
  \ data pipelines, notebooks, and other Fabric\n      items. The API supports data engineering, data science, real-time\n      analytics, and business intelligence workloads in a single platform.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/fabric/\n    baseURL: https://api.fabric.microsoft.com/v1/\n    tags:\n      - Data Analytics\n      - Data Engineering\n      - Data Platform\n      - Lakehouse\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/fabric/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/fabric/get-started/\n  - aid: microsoft-fabric:sql-connection-api\n    name: Microsoft Fabric SQL Connection\n    description: >-\n      Microsoft Fabric provides SQL connectivity to lakehouses and data\n      warehouses through TDS endpoints. Developers can query Fabric data\n      using standard SQL tools, JDBC/ODBC drivers, and client libraries,\n      enabling integration with existing SQL-based\
  \ applications and\n      reporting tools.\n    humanURL: https://learn.microsoft.com/en-us/fabric/data-warehouse/connectivity\n    baseURL: https://{workspace}.datawarehouse.fabric.microsoft.com/\n    tags:\n      - Data Warehouse\n      - Lakehouse\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/fabric/data-warehouse/connectivity\ncommon:\n  - type: Portal\n    url: https://app.fabric.microsoft.com/\n  - type: Website\n    url: https://www.microsoft.com/en-us/microsoft-fabric\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/fabric/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/fabric/get-started/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/microsoft-fabric/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/fabric/security/permission-model\n  - type: Blog\n    url: https://blog.fabric.microsoft.com/\n  - type: Community\n    url:\
  \ https://community.fabric.microsoft.com/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: Status\n    url: https://status.fabric.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-fabric/refs/heads/main/apis.yml
tags:
- Data Analytics
- Data Engineering
- Data Platform
- Lakehouse
- Microsoft
url: https://raw.githubusercontent.com/api-evangelist/microsoft-fabric/refs/heads/main/apis.yml
use_cases: []
---
