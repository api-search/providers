---
api_count: 6
apis:
- description: REST API for executing Power Query mashups and managing data transformations programmatically.
  name: Power Query REST API
  slug: rest-api
- description: API and language reference for the M formula language used in Power Query for data transformation expressions and custom functions.
  name: Power Query M Formula Language
  slug: m-language
- description: API for building and managing custom data connectors for Power Query using the M language and Connector SDK.
  name: Power Query Connectors API
  slug: connectors-api
- description: API for managing and executing Power Query dataflows in Power Platform and Power BI for self-service ETL workflows.
  name: Power Query Dataflows API
  slug: dataflows-api
- description: Development toolkit for building custom Power Query connectors using Visual Studio Code, including project scaffolding, testing, and packaging of .mez connector files.
  name: Power Query SDK
  slug: sdk
- description: REST API for programmatically executing Power Query M transformations in Microsoft Fabric, enabling integration with Spark notebooks, pipelines, and external applications.
  name: Fabric Power Query Programmatic API
  slug: fabric-api
common:
- title: ''
  type: Portal
  url: https://app.powerbi.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-query/
- title: ''
  type: GettingStarted
  url: https://www.microsoft.com/en-us/power-platform/products/power-bi/getting-started-with-power-bi
- title: ''
  type: Blog
  url: https://powerbi.microsoft.com/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/MicrosoftDocs/powerquery-docs
- title: ''
  type: Support
  url: https://powerbi.microsoft.com/en-us/support/
- title: ''
  type: Pricing
  url: https://powerbi.microsoft.com/pricing/
- title: ''
  type: StatusPage
  url: https://support.fabric.microsoft.com/
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/servicesagreement/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SignUp
  url: https://www.microsoft.com/en-us/power-platform/products/power-bi/landing/free-account
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/powerquery
- title: ''
  type: YouTube
  url: https://www.youtube.com/channel/UCFp1vaKzpfvoGai0vE5VJ0w
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-change-log
created: '2024-01-01'
description: Power Query is a data transformation and mashup engine used across Microsoft products including Excel, Power BI, and Azure. This API collection provides programmatic access to Power Query functionality for data connectivity, transformation, and integration using the M formula language and connector SDK.
features:
- description: Powerful M formula language for complex data transformations including filtering, pivoting, merging, and custom functions.
  name: Data Transformation Engine
- description: Build custom data connectors using the Power Query SDK for connecting to any data source.
  name: Custom Connector Development
- description: Dataflows provide self-service ETL capabilities for business users without IT dependency.
  name: Self-Service ETL
- description: Pre-built connectors for databases, cloud services, files, and web APIs.
  name: 300+ Built-In Connectors
- description: Efficient data loading with incremental refresh policies for large datasets.
  name: Incremental Refresh
- description: Execute Power Query transformations programmatically in Microsoft Fabric pipelines.
  name: Microsoft Fabric Integration
image: /assets/icons/power-query.png
integrations:
- description: Native integration with Power BI for data preparation and visualization workflows.
  name: Power BI
- description: Built-in Power Query editor in Excel for spreadsheet-based data transformation.
  name: Microsoft Excel
- description: Mapping data flows using Power Query transformations in Azure Data Factory.
  name: Azure Data Factory
- description: Programmatic execution of Power Query in Fabric notebooks and pipelines.
  name: Microsoft Fabric
- description: Direct connectivity and query folding optimization for SQL Server databases.
  name: SQL Server
layout: provider
modified: '2026-04-18'
name: Power Query
skills: []
slug: power-query
solutions: []
source_yaml: "aid: power-query\nname: Power Query\ndescription: >-\n  Power Query is a data transformation and mashup engine used across Microsoft\n  products including Excel, Power BI, and Azure. This API collection provides\n  programmatic access to Power Query functionality for data connectivity,\n  transformation, and integration using the M formula language and connector SDK.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/power-query/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Business Intelligence\n  - Data Integration\n  - Data Transformation\n  - ETL\n  - Microsoft\napis:\n  - aid: power-query:rest-api\n    name: Power Query REST API\n    description: >-\n      REST API for executing Power Query mashups and managing data transformations\n      programmatically.\n    humanURL: https://docs.microsoft.com/en-us/power-query/power-query-rest-api\n\
  \    baseURL: https://api.powerquery.microsoft.com/v1.0\n    tags:\n      - Data Query\n      - Mashup Engine\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-query/power-query-rest-api\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/power-query/authentication\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-query/power-query-what-is-power-query\n  - aid: power-query:m-language\n    name: Power Query M Formula Language\n    description: >-\n      API and language reference for the M formula language used in Power Query\n      for data transformation expressions and custom functions.\n    humanURL: https://docs.microsoft.com/en-us/powerquery-m/\n    baseURL: https://docs.microsoft.com/powerquery-m/\n    tags:\n      - Formula Language\n      - Functions\n      - M Language\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/powerquery-m/\n\
  \      - type: APIReference\n        url: https://docs.microsoft.com/en-us/powerquery-m/power-query-m-function-reference\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/powerquery-m/quick-tour-of-the-power-query-m-formula-language\n  - aid: power-query:connectors-api\n    name: Power Query Connectors API\n    description: >-\n      API for building and managing custom data connectors for Power Query using\n      the M language and Connector SDK.\n    humanURL: https://docs.microsoft.com/en-us/power-query/connectors/\n    baseURL: https://github.com/Microsoft/DataConnectors\n    tags:\n      - Connectors\n      - Data Sources\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-query/installingsdk\n      - type: SDK\n        url: https://aka.ms/powerquerysdk\n      - type: GitHubRepository\n        url: https://github.com/Microsoft/DataConnectors\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-query/creating-first-connector\n\
  \  - aid: power-query:dataflows-api\n    name: Power Query Dataflows API\n    description: >-\n      API for managing and executing Power Query dataflows in Power Platform\n      and Power BI for self-service ETL workflows.\n    humanURL: https://docs.microsoft.com/en-us/power-query/dataflows/\n    baseURL: https://api.powerbi.com/v1.0/myorg/groups/{groupId}/dataflows\n    tags:\n      - Dataflows\n      - Power Platform\n      - Self-Service ETL\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-bi/transform-model/dataflows/dataflows-introduction-self-service\n      - type: APIReference\n        url: https://docs.microsoft.com/en-us/rest/api/power-bi/dataflows\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-bi/transform-model/dataflows/dataflows-introduction-self-service\n  - aid: power-query:sdk\n    name: Power Query SDK\n    description: >-\n      Development toolkit for building custom Power Query\
  \ connectors using\n      Visual Studio Code, including project scaffolding, testing, and packaging\n      of .mez connector files.\n    humanURL: https://learn.microsoft.com/en-us/power-query/install-sdk\n    baseURL: https://learn.microsoft.com/en-us/power-query/power-query-sdk-vs-code\n    tags:\n      - Connector Development\n      - SDK\n      - Tooling\n      - VS Code\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-query/power-query-sdk-vs-code\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-query/install-sdk\n      - type: GitHubRepository\n        url: https://github.com/microsoft/vscode-powerquery-sdk\n  - aid: power-query:fabric-api\n    name: Fabric Power Query Programmatic API\n    description: >-\n      REST API for programmatically executing Power Query M transformations in\n      Microsoft Fabric, enabling integration with Spark notebooks, pipelines,\n      and external applications.\n\
  \    humanURL: https://blog.fabric.microsoft.com/en-US/blog/execute-power-query-programmatically-in-microsoft-fabric/\n    baseURL: https://learn.microsoft.com/en-us/fabric/data-factory/\n    tags:\n      - Microsoft Fabric\n      - Pipelines\n      - Programmatic Execution\n      - REST\n    properties:\n      - type: Documentation\n        url: https://blog.fabric.microsoft.com/en-US/blog/execute-power-query-programmatically-in-microsoft-fabric/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-rest-api\ncommon:\n  - type: Portal\n    url: https://app.powerbi.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-query/\n  - type: GettingStarted\n    url: https://www.microsoft.com/en-us/power-platform/products/power-bi/getting-started-with-power-bi\n  - type: Blog\n    url: https://powerbi.microsoft.com/blog/\n  - type: GitHubOrganization\n    url: https://github.com/MicrosoftDocs/powerquery-docs\n  - type:\
  \ Support\n    url: https://powerbi.microsoft.com/en-us/support/\n  - type: Pricing\n    url: https://powerbi.microsoft.com/pricing/\n  - type: StatusPage\n    url: https://support.fabric.microsoft.com/\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/servicesagreement/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: SignUp\n    url: https://www.microsoft.com/en-us/power-platform/products/power-bi/landing/free-account\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/powerquery\n  - type: YouTube\n    url: https://www.youtube.com/channel/UCFp1vaKzpfvoGai0vE5VJ0w\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-change-log\n  - type: Features\n    data:\n      - name: Data Transformation Engine\n        description: Powerful M formula language for complex data transformations including filtering, pivoting, merging, and custom functions.\n      -\
  \ name: Custom Connector Development\n        description: Build custom data connectors using the Power Query SDK for connecting to any data source.\n      - name: Self-Service ETL\n        description: Dataflows provide self-service ETL capabilities for business users without IT dependency.\n      - name: 300+ Built-In Connectors\n        description: Pre-built connectors for databases, cloud services, files, and web APIs.\n      - name: Incremental Refresh\n        description: Efficient data loading with incremental refresh policies for large datasets.\n      - name: Microsoft Fabric Integration\n        description: Execute Power Query transformations programmatically in Microsoft Fabric pipelines.\n  - type: UseCases\n    data:\n      - name: Data Preparation\n        description: Clean, transform, and shape data from multiple sources for analytics and reporting.\n      - name: Custom Data Connectors\n        description: Build reusable connectors for proprietary or specialized data\
  \ sources.\n      - name: Automated Data Pipelines\n        description: Create scheduled dataflows for automated data refresh and transformation workflows.\n      - name: Cross-Platform Data Integration\n        description: Integrate data across Power BI, Excel, Azure Data Factory, and Microsoft Fabric.\n      - name: Data Quality Management\n        description: Implement data quality rules and transformations for consistent enterprise data.\n  - type: Integrations\n    data:\n      - name: Power BI\n        description: Native integration with Power BI for data preparation and visualization workflows.\n      - name: Microsoft Excel\n        description: Built-in Power Query editor in Excel for spreadsheet-based data transformation.\n      - name: Azure Data Factory\n        description: Mapping data flows using Power Query transformations in Azure Data Factory.\n      - name: Microsoft Fabric\n        description: Programmatic execution of Power Query in Fabric notebooks and pipelines.\n\
  \      - name: SQL Server\n        description: Direct connectivity and query folding optimization for SQL Server databases.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/power-query/refs/heads/main/apis.yml
tags:
- Business Intelligence
- Data Integration
- Data Transformation
- ETL
- Microsoft
url: https://raw.githubusercontent.com/api-evangelist/power-query/refs/heads/main/apis.yml
use_cases:
- description: Clean, transform, and shape data from multiple sources for analytics and reporting.
  name: Data Preparation
- description: Build reusable connectors for proprietary or specialized data sources.
  name: Custom Data Connectors
- description: Create scheduled dataflows for automated data refresh and transformation workflows.
  name: Automated Data Pipelines
- description: Integrate data across Power BI, Excel, Azure Data Factory, and Microsoft Fabric.
  name: Cross-Platform Data Integration
- description: Implement data quality rules and transformations for consistent enterprise data.
  name: Data Quality Management
---
