---
api_count: 2
api_specs:
- filename: teradata-querygrid-manager-api.yaml
  format: yaml
  label: Teradata QueryGrid Manager API
  slug: querygrid-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/openapi/teradata-querygrid-manager-api.yaml
- filename: teradata-query-service-api.yaml
  format: yaml
  label: Teradata Query Service API
  slug: query-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/openapi/teradata-query-service-api.yaml
apis:
- description: REST API for centralized administration and monitoring of Teradata QueryGrid, the data fabric that enables seamless cross-system analytics. Manage data centers, systems, bridges, connectors, links, fa
  name: Teradata QueryGrid Manager API
  slug: querygrid-manager-api
- description: REST API for executing SQL queries against Teradata Vantage systems. Provides HTTP-based access to run queries, retrieve results, and manage sessions for application integration and browser-based quer
  name: Teradata Query Service API
  slug: query-service-api
capabilities:
- description: Workflow capability for managing Teradata's data fabric infrastructure. Combines QueryGrid Manager for fabric configuration with Query Service for validating cross-system connectivity. Used by data en
  name: Teradata Data Fabric Management
  slug: data-fabric-management
- description: Workflow capability for executing SQL queries and analytics against Teradata Vantage systems. Combines Query Service for SQL execution with QueryGrid for cross-system query monitoring. Used by data an
  name: Teradata Query and Analytics
  slug: query-and-analytics
common:
- title: ''
  type: Portal
  url: https://developer.teradata.com
- title: ''
  type: Documentation
  url: https://docs.teradata.com
- title: ''
  type: GettingStarted
  url: https://quickstarts.teradata.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/Teradata
- title: ''
  type: Support
  url: https://support.teradata.com
- title: ''
  type: Blog
  url: https://www.teradata.com/blog
- title: ''
  type: Training
  url: https://www.teradata.com/University
- title: ''
  type: TermsOfService
  url: https://www.teradata.com/Legal/Terms-of-Use
- title: ''
  type: PrivacyPolicy
  url: https://www.teradata.com/Legal/Privacy
- title: Python SQL Driver
  type: SDK
  url: https://pypi.org/project/teradatasql/
- title: Node.js SQL Driver
  type: SDK
  url: https://www.npmjs.com/package/teradatasql
- title: R SQL Driver
  type: SDK
  url: https://github.com/Teradata/r-driver
- title: Rust API
  type: SDK
  url: https://github.com/Teradata/teradatarustapi
- title: Go SQL Driver
  type: SDK
  url: https://github.com/Teradata/gosql-driver
- title: JDBC Driver
  type: SDK
  url: https://github.com/Teradata/jdbc-driver
- title: VS Code SQL Extension
  type: CLI
  url: https://github.com/Teradata/teradata-vscode-sql-extension
- title: MCP Server
  type: Tools
  url: https://github.com/Teradata/teradata-mcp-server
- title: QueryGrid MCP Server
  type: Tools
  url: https://github.com/Teradata/teradata-qg-mcp-server
- title: ''
  type: SpectralRules
  url: rules/teradata-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/teradata-vocabulary.yaml
- title: Data Fabric Management
  type: NaftikoCapability
  url: capabilities/data-fabric-management.yaml
- title: Query and Analytics
  type: NaftikoCapability
  url: capabilities/query-and-analytics.yaml
created: '2026-04-18'
description: Teradata provides enterprise analytics and data management solutions. The Teradata VantageCloud platform delivers connected multi-cloud data analytics with capabilities for data warehousing, advanced analytics, and machine learning at scale. Teradata offers REST APIs for managing QueryGrid data fabric connections, running SQL queries, and administering platform resources.
features:
- description: Cloud-native analytics platform available on AWS, Azure, and Google Cloud.
  name: VantageCloud
- description: Advanced analytics engine with machine learning, graph analytics, and AI capabilities built into Vantage.
  name: ClearScape Analytics
- description: Data fabric for multi-system analytics enabling queries across Teradata, Hadoop, Spark, and cloud object storage.
  name: QueryGrid
- description: Model lifecycle management for deploying, monitoring, and governing machine learning models.
  name: ModelOps
- description: On-demand AI and ML engine for exploratory analytics without infrastructure management.
  name: AI Unlimited
- description: Support for Apache Iceberg and open table formats for lakehouse analytics.
  name: Open Table Formats
image: /assets/icons/teradata.png
integrations:
- description: dbt adapter for Teradata Vantage enabling data transformations using dbt workflows.
  name: dbt
- description: Airflow provider for orchestrating Teradata data pipeline workflows.
  name: Apache Airflow
- description: Dagster integration for Teradata data orchestration and observability.
  name: Dagster
- description: Airbyte connector for ELT data pipelines to and from Teradata.
  name: Airbyte
- description: Fivetran destination connector for automated data loading into Teradata.
  name: Fivetran
- description: MuleSoft connector for integrating Teradata with enterprise application networks.
  name: MuleSoft
- description: Dataiku plugin for running analytics within the Teradata Vantage environment.
  name: Dataiku
- description: LangChain integration for using Teradata as a vector store and data source in AI applications.
  name: LangChain
- description: Teradata support for Apache Iceberg open table format for lakehouse analytics.
  name: Apache Iceberg
jsonld:
- class_count: 4
  name: Teradata Query Service Api Context
  property_count: 13
  slug: teradata-query-service-api-context
- class_count: 15
  name: Teradata Querygrid Manager Api Context
  property_count: 23
  slug: teradata-querygrid-manager-api-context
layout: provider
modified: '2026-04-18'
name: Teradata
rules:
- name: Teradata API Rules
  rule_count: 30
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 13
  slug: teradata-spectral-rules
skills: []
slug: teradata
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: teradata\nname: Teradata\ndescription: >-\n  Teradata provides enterprise analytics and data management solutions. The\n  Teradata VantageCloud platform delivers connected multi-cloud data analytics\n  with capabilities for data warehousing, advanced analytics, and machine\n  learning at scale. Teradata offers REST APIs for managing QueryGrid data\n  fabric connections, running SQL queries, and administering platform resources.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Cloud\n  - Data Management\n  - Data Warehousing\n  - Database\n  - Enterprise\n  - Machine Learning\n  - SQL\nurl: https://www.teradata.com\ncreated: '2026-04-18'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: teradata:querygrid-manager-api\n    name: Teradata QueryGrid Manager API\n    description: >-\n      REST API for centralized administration and monitoring\
  \ of Teradata\n      QueryGrid, the data fabric that enables seamless cross-system analytics.\n      Manage data centers, systems, bridges, connectors, links, fabrics,\n      networks, and node configurations. Perform diagnostic checks, software\n      installations, and query monitoring across connected systems.\n    humanURL: https://github.com/Teradata/querygrid-apidocs\n    baseURL: https://querygrid.teradata.com/api/v1\n    tags:\n      - Configuration\n      - Data Fabric\n      - Diagnostics\n      - Monitoring\n      - QueryGrid\n    properties:\n      - type: Documentation\n        url: https://github.com/Teradata/querygrid-apidocs\n      - type: OpenAPI\n        url: openapi/teradata-querygrid-manager-api.yaml\n  - aid: teradata:query-service-api\n    name: Teradata Query Service API\n    description: >-\n      REST API for executing SQL queries against Teradata Vantage systems.\n      Provides HTTP-based access to run queries, retrieve results, and manage\n      sessions for\
  \ application integration and browser-based query tools.\n    humanURL: https://docs.teradata.com\n    baseURL: https://vantage.teradata.com/api/query/v1\n    tags:\n      - Query\n      - REST\n      - SQL\n      - Vantage\n    properties:\n      - type: Documentation\n        url: https://docs.teradata.com\n      - type: OpenAPI\n        url: openapi/teradata-query-service-api.yaml\ncommon:\n  - type: Portal\n    url: https://developer.teradata.com\n  - type: Documentation\n    url: https://docs.teradata.com\n  - type: GettingStarted\n    url: https://quickstarts.teradata.com\n  - type: GitHubOrganization\n    url: https://github.com/Teradata\n  - type: Support\n    url: https://support.teradata.com\n  - type: Blog\n    url: https://www.teradata.com/blog\n  - type: Training\n    url: https://www.teradata.com/University\n  - type: TermsOfService\n    url: https://www.teradata.com/Legal/Terms-of-Use\n  - type: PrivacyPolicy\n    url: https://www.teradata.com/Legal/Privacy\n  - type: SDK\n\
  \    url: https://pypi.org/project/teradatasql/\n    title: Python SQL Driver\n  - type: SDK\n    url: https://www.npmjs.com/package/teradatasql\n    title: Node.js SQL Driver\n  - type: SDK\n    url: https://github.com/Teradata/r-driver\n    title: R SQL Driver\n  - type: SDK\n    url: https://github.com/Teradata/teradatarustapi\n    title: Rust API\n  - type: SDK\n    url: https://github.com/Teradata/gosql-driver\n    title: Go SQL Driver\n  - type: SDK\n    url: https://github.com/Teradata/jdbc-driver\n    title: JDBC Driver\n  - type: CLI\n    url: https://github.com/Teradata/teradata-vscode-sql-extension\n    title: VS Code SQL Extension\n  - type: Tools\n    url: https://github.com/Teradata/teradata-mcp-server\n    title: MCP Server\n  - type: Tools\n    url: https://github.com/Teradata/teradata-qg-mcp-server\n    title: QueryGrid MCP Server\n  - type: Integrations\n    data:\n      - name: dbt\n        description: >-\n          dbt adapter for Teradata Vantage enabling data transformations\
  \ using\n          dbt workflows.\n      - name: Apache Airflow\n        description: >-\n          Airflow provider for orchestrating Teradata data pipeline workflows.\n      - name: Dagster\n        description: >-\n          Dagster integration for Teradata data orchestration and observability.\n      - name: Airbyte\n        description: >-\n          Airbyte connector for ELT data pipelines to and from Teradata.\n      - name: Fivetran\n        description: >-\n          Fivetran destination connector for automated data loading into\n          Teradata.\n      - name: MuleSoft\n        description: >-\n          MuleSoft connector for integrating Teradata with enterprise\n          application networks.\n      - name: Dataiku\n        description: >-\n          Dataiku plugin for running analytics within the Teradata Vantage\n          environment.\n      - name: LangChain\n        description: >-\n          LangChain integration for using Teradata as a vector store and data\n   \
  \       source in AI applications.\n      - name: Apache Iceberg\n        description: >-\n          Teradata support for Apache Iceberg open table format for lakehouse\n          analytics.\n  - type: Features\n    data:\n      - name: VantageCloud\n        description: >-\n          Cloud-native analytics platform available on AWS, Azure, and Google\n          Cloud.\n      - name: ClearScape Analytics\n        description: >-\n          Advanced analytics engine with machine learning, graph analytics, and\n          AI capabilities built into Vantage.\n      - name: QueryGrid\n        description: >-\n          Data fabric for multi-system analytics enabling queries across\n          Teradata, Hadoop, Spark, and cloud object storage.\n      - name: ModelOps\n        description: >-\n          Model lifecycle management for deploying, monitoring, and governing\n          machine learning models.\n      - name: AI Unlimited\n        description: >-\n          On-demand AI and ML engine\
  \ for exploratory analytics without\n          infrastructure management.\n      - name: Open Table Formats\n        description: >-\n          Support for Apache Iceberg and open table formats for lakehouse\n          analytics.\n  - type: UseCases\n    data:\n      - name: Enterprise Data Warehousing\n        description: >-\n          Centralized data warehousing with petabyte-scale analytics for\n          enterprise reporting and BI.\n      - name: Advanced Analytics\n        description: >-\n          In-database machine learning, statistical analysis, and predictive\n          modeling at scale.\n      - name: Multi-Cloud Analytics\n        description: >-\n          Connected analytics across AWS, Azure, and Google Cloud with data\n          fabric integration.\n      - name: AI and ML Operations\n        description: >-\n          End-to-end machine learning model lifecycle management with ModelOps.\n      - name: Real-Time Data Integration\n        description: >-\n         \
  \ Real-time data ingestion and analytics with QueryGrid cross-system\n          query federation.\n  - type: SpectralRules\n    url: rules/teradata-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/teradata-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/data-fabric-management.yaml\n    title: Data Fabric Management\n  - type: NaftikoCapability\n    url: capabilities/query-and-analytics.yaml\n    title: Query and Analytics\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/apis.yml
tags:
- Analytics
- Cloud
- Data Management
- Data Warehousing
- Database
- Enterprise
- Machine Learning
- SQL
url: https://www.teradata.com
use_cases:
- description: Centralized data warehousing with petabyte-scale analytics for enterprise reporting and BI.
  name: Enterprise Data Warehousing
- description: In-database machine learning, statistical analysis, and predictive modeling at scale.
  name: Advanced Analytics
- description: Connected analytics across AWS, Azure, and Google Cloud with data fabric integration.
  name: Multi-Cloud Analytics
- description: End-to-end machine learning model lifecycle management with ModelOps.
  name: AI and ML Operations
- description: Real-time data ingestion and analytics with QueryGrid cross-system query federation.
  name: Real-Time Data Integration
---
