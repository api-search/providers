---
api_count: 39
api_specs:
- filename: azure-databricks-openapi.yml
  format: yaml
  label: Azure Databricks REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-databricks/refs/heads/main/openapi/azure-databricks-openapi.yml
- filename: azure-databricks-openapi.yml
  format: yaml
  label: Clusters API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-databricks/refs/heads/main/openapi/azure-databricks-openapi.yml
- filename: azure-databricks-openapi.yml
  format: yaml
  label: Jobs API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-databricks/refs/heads/main/openapi/azure-databricks-openapi.yml
- filename: azure-databricks-openapi.yml
  format: yaml
  label: Workspace API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-databricks/refs/heads/main/openapi/azure-databricks-openapi.yml
apis:
- description: Core REST API for managing Azure Databricks workspaces, clusters, jobs, notebooks, and other resources programmatically.
  name: Azure Databricks REST API
  slug: ''
- description: Manage Databricks clusters for running Spark jobs including creating, starting, editing, listing, terminating, and deleting clusters.
  name: Clusters API
  slug: ''
- description: Create, manage, and run jobs on Databricks clusters including scheduling, listing runs, and managing job permissions.
  name: Jobs API
  slug: ''
- description: Manage notebooks, folders, and other workspace objects including listing, importing, exporting, and deleting workspace items.
  name: Workspace API
  slug: ''
- description: Access Databricks File System (DBFS) for file operations including uploading, downloading, listing, and deleting files and directories.
  name: DBFS API
  slug: ''
- description: Manage libraries and dependencies on clusters including installing, uninstalling, and listing library statuses.
  name: Libraries API
  slug: ''
- description: Manage secrets and secret scopes for secure credential storage including creating scopes, putting secrets, and managing ACLs.
  name: Secrets API
  slug: ''
- description: Create and manage personal access tokens for API authentication including creating, listing, and revoking tokens.
  name: Token Management API
  slug: ''
- description: Manage SQL warehouses, queries, and dashboards for Databricks SQL analytics workloads.
  name: SQL Analytics API
  slug: ''
- description: Track experiments, log metrics, and manage ML models using the MLflow tracking and registry APIs.
  name: MLflow API
  slug: ''
- description: Create and manage instance pools to reduce cluster start and autoscaling times by maintaining a set of idle ready-to-use cloud instances.
  name: Instance Pools API
  slug: ''
- description: Create, list, and edit cluster policies to control cluster configurations and limit the ability to configure clusters based on a set of rules.
  name: Cluster Policies API
  slug: ''
- description: Manage Git repositories within Databricks workspaces for version control of notebooks and files.
  name: Repos API
  slug: ''
- description: Manage Git credentials for authenticating with Git providers when using Databricks Repos.
  name: Git Credentials API
  slug: ''
- description: Create, edit, delete, start, and view details about Delta Live Tables pipelines for building reliable data pipelines.
  name: Pipelines API
  slug: ''
- description: Manage permissions on workspace objects including clusters, jobs, notebooks, and other resources using access control lists.
  name: Permissions API
  slug: ''
- description: Manage Unity Catalog catalogs for organizing and governing data assets across workspaces.
  name: Unity Catalog - Catalogs API
  slug: ''
- description: Manage schemas within Unity Catalog catalogs for organizing tables, views, and functions.
  name: Unity Catalog - Schemas API
  slug: ''
- description: Manage tables within Unity Catalog schemas including listing, getting, and deleting tables.
  name: Unity Catalog - Tables API
  slug: ''
- description: Manage Unity Catalog volumes for governing non-tabular data such as files and directories.
  name: Unity Catalog - Volumes API
  slug: ''
- description: Manage permissions and grants on Unity Catalog objects including catalogs, schemas, tables, and other securable objects.
  name: Unity Catalog - Grants API
  slug: ''
- description: Manage external locations in Unity Catalog for connecting to cloud storage paths.
  name: Unity Catalog - External Locations API
  slug: ''
- description: Manage storage credentials in Unity Catalog for authenticating access to cloud storage.
  name: Unity Catalog - Storage Credentials API
  slug: ''
- description: Manage Unity Catalog metastores which serve as the top-level container for data governance.
  name: Unity Catalog - Metastores API
  slug: ''
- description: Create and manage model serving endpoints for deploying machine learning models as REST API endpoints.
  name: Model Serving Endpoints API
  slug: ''
- description: Manage registered models and model versions in the Databricks Model Registry for model lifecycle management.
  name: Model Registry API
  slug: ''
- description: Manage registered models in Unity Catalog for centralized model governance and sharing.
  name: Registered Models API
  slug: ''
- description: Manage global cluster initialization scripts that run on every cluster in the workspace.
  name: Global Init Scripts API
  slug: ''
- description: Manage IP access lists to control network access to Azure Databricks workspaces.
  name: IP Access Lists API
  slug: ''
- description: Execute SQL statements on SQL warehouses and retrieve results for programmatic SQL access.
  name: Statement Execution API
  slug: ''
- description: Execute commands on running clusters and retrieve results programmatically.
  name: Command Execution API
  slug: ''
- description: Manage files in Unity Catalog volumes and workspace filesystem with operations for uploading, downloading, and deleting files.
  name: Files API
  slug: ''
- description: Deploy and manage Databricks Apps including creating, starting, stopping, and listing custom applications.
  name: Apps API
  slug: ''
- description: Manage Lakeview dashboards programmatically including creating, updating, and publishing dashboards.
  name: Lakeview API
  slug: ''
- description: Manage online tables for low-latency serving of feature data in Unity Catalog.
  name: Online Tables API
  slug: ''
- description: Manage vector search indexes for similarity search and retrieval-augmented generation workloads.
  name: Vector Search Indexes API
  slug: ''
- description: Manage vector search endpoints for hosting vector search indexes.
  name: Vector Search Endpoints API
  slug: ''
- description: Retrieve query history for SQL warehouses including query text, status, and performance metrics.
  name: Query History API
  slug: ''
- description: Manage users, groups, and service principals across the Databricks account using SCIM 2.0 protocol.
  name: Account SCIM API
  slug: ''
capabilities:
- description: Manage Azure Databricks clusters, jobs, and workspace objects for data engineering workflows. Used by data engineers and platform administrators.
  name: Azure Databricks Data Engineering
  slug: data-engineering
common:
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/azure/databricks/getting-started/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/pricing/details/databricks/
- title: ''
  type: StatusPage
  url: https://status.azuredatabricks.net/
- title: ''
  type: Security
  url: https://learn.microsoft.com/azure/databricks/security/
- title: ''
  type: SDK
  url: https://learn.microsoft.com/azure/databricks/dev-tools/
- title: ''
  type: CLI
  url: https://learn.microsoft.com/azure/databricks/dev-tools/cli/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/azure/databricks/dev-tools/auth/
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/azure/databricks/reference/api
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/azure/databricks/release-notes/product/
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/azure/databricks/release-notes/
- title: ''
  type: Support
  url: https://learn.microsoft.com/answers/tags/166/azure-databricks
- title: Python SDK
  type: SDK
  url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-python
- title: Java SDK
  type: SDK
  url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-java
- title: Go SDK
  type: SDK
  url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-go
- title: R SDK
  type: SDK
  url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-r
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/azure-databricks-client
- title: ''
  type: OpenAPI
  url: openapi/azure-databricks-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/azure-databricks-cluster-schema.json
- title: ''
  type: JSONLD
  url: json-ld/azure-databricks-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/azure-databricks-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/azure-databricks-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-engineering.yaml
created: '2024-01-01'
description: Azure Databricks is an Apache Spark-based analytics platform optimized for Microsoft Azure. It provides a collaborative workspace for data engineers, data scientists, and analysts to work together on big data and machine learning workloads.
features:
- Collaborative notebooks with multi-language support
- Auto-scaling Apache Spark clusters
- Delta Lake for reliable data lakehouse architecture
- Unity Catalog for unified data governance
- MLflow integration for ML lifecycle management
- Model serving endpoints for real-time inference
- Delta Live Tables for declarative ETL pipelines
- SQL analytics with serverless SQL warehouses
- Vector search for RAG and similarity search
- Lakeview dashboards for data visualization
- Git integration for version control of notebooks
- SCIM 2.0 for identity and access management
image: https://azure.microsoft.com/svghandler/databricks/
integrations:
- Azure Data Factory for orchestration
- Azure Synapse Analytics for data warehousing
- Azure Data Lake Storage for scalable storage
- Azure Key Vault for secret management
- Azure Active Directory for authentication
- Power BI for business intelligence dashboards
- Terraform for infrastructure as code
- Apache Kafka for streaming data ingestion
jsonld:
- class_count: 0
  name: Azure Databricks Context
  property_count: 0
  slug: azure-databricks-context
layout: provider
modified: '2026-04-28'
name: Azure Databricks
rules:
- name: Azure Databricks API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: azure-databricks-spectral-rules
skills: []
slug: microsoft-azure-databricks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Databricks\ndescription: >-\n  Azure Databricks is an Apache Spark-based analytics platform optimized for Microsoft\n  Azure. It provides a collaborative workspace for data engineers, data scientists,\n  and analysts to work together on big data and machine learning workloads.\nimage: https://azure.microsoft.com/svghandler/databricks/\ntags:\n  - Analytics\n  - Apache Spark\n  - Big Data\n  - Data Engineering\n  - Machine Learning\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/azure-databricks/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - name: Azure Databricks REST API\n    description: >-\n      Core REST API for managing Azure Databricks workspaces, clusters, jobs, notebooks,\n      and other resources programmatically.\n    image: https://azure.microsoft.com/svghandler/databricks/\n    humanURL: https://learn.microsoft.com/azure/databricks/\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api\n\
  \    tags:\n      - Clusters\n      - Jobs\n      - Notebooks\n      - Workspace\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/\n      - type: OpenAPI\n        url: openapi/azure-databricks-openapi.yml\n      - type: Authentication\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/authentication\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/introduction\n      - type: JSONSchema\n        url: json-schema/azure-databricks-cluster-schema.json\n      - type: JSONLD\n        url: json-ld/azure-databricks-context.jsonld\n    contact:\n      - type: Support\n        url: https://learn.microsoft.com/answers/tags/166/azure-databricks\n  - name: Clusters API\n    description: >-\n      Manage Databricks clusters for running Spark jobs including creating, starting,\n      editing, listing, terminating, and deleting clusters.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/clusters\n\
  \    tags:\n      - Clusters\n      - Compute\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/clusters\n      - type: OpenAPI\n        url: openapi/azure-databricks-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-databricks-cluster-schema.json\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/clusters\n  - name: Jobs API\n    description: >-\n      Create, manage, and run jobs on Databricks clusters including scheduling,\n      listing runs, and managing job permissions.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/jobs\n    tags:\n      - Automation\n      - Jobs\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/jobs\n      - type: OpenAPI\n        url: openapi/azure-databricks-openapi.yml\n      - type: APIReference\n       \
  \ url: https://docs.databricks.com/api/azure/workspace/jobs\n  - name: Workspace API\n    description: >-\n      Manage notebooks, folders, and other workspace objects including listing,\n      importing, exporting, and deleting workspace items.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/workspace\n    tags:\n      - Folders\n      - Notebooks\n      - Workspace\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/workspace\n      - type: OpenAPI\n        url: openapi/azure-databricks-openapi.yml\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/workspace\n  - name: DBFS API\n    description: >-\n      Access Databricks File System (DBFS) for file operations including uploading,\n      downloading, listing, and deleting files and directories.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/dbfs\n    tags:\n      - Files\n\
  \      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/dbfs\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/dbfs\n  - name: Libraries API\n    description: >-\n      Manage libraries and dependencies on clusters including installing,\n      uninstalling, and listing library statuses.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/libraries\n    tags:\n      - Dependencies\n      - Libraries\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/libraries\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/libraries\n  - name: Secrets API\n    description: >-\n      Manage secrets and secret scopes for secure credential storage including\n      creating scopes, putting secrets, and managing ACLs.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/secrets\n\
  \    tags:\n      - Credentials\n      - Secrets\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/secrets\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/secrets\n  - name: Token Management API\n    description: >-\n      Create and manage personal access tokens for API authentication including\n      creating, listing, and revoking tokens.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/token\n    tags:\n      - Authentication\n      - Security\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/token-management\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/tokenmanagement\n  - name: SQL Analytics API\n    description: >-\n      Manage SQL warehouses, queries, and dashboards for Databricks SQL analytics\n\
  \      workloads.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/sql\n    tags:\n      - Analytics\n      - Queries\n      - Sql\n      - Warehouses\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/sql/api/\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/warehouses\n  - name: MLflow API\n    description: >-\n      Track experiments, log metrics, and manage ML models using the MLflow tracking\n      and registry APIs.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/mlflow\n    tags:\n      - Experiments\n      - Machine Learning\n      - Mlops\n      - Model Tracking\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/mlflow/\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/experiments\n  - name: Instance Pools API\n    description: >-\n      Create\
  \ and manage instance pools to reduce cluster start and autoscaling times\n      by maintaining a set of idle ready-to-use cloud instances.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/instance-pools\n    tags:\n      - Clusters\n      - Compute\n      - Instance Pools\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/compute/pool-index\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/instancepools\n  - name: Cluster Policies API\n    description: >-\n      Create, list, and edit cluster policies to control cluster configurations and\n      limit the ability to configure clusters based on a set of rules.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/policies/clusters\n    tags:\n      - Clusters\n      - Governance\n      - Policies\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/admin/clusters/policy-definition\n\
  \      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/clusterpolicies\n  - name: Repos API\n    description: >-\n      Manage Git repositories within Databricks workspaces for version control of\n      notebooks and files.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/repos\n    tags:\n      - Git\n      - Repositories\n      - Version Control\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/repos/\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/repos\n  - name: Git Credentials API\n    description: >-\n      Manage Git credentials for authenticating with Git providers when using\n      Databricks Repos.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/git-credentials\n    tags:\n      - Authentication\n      - Credentials\n      - Git\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/gitcredentials\n\
  \  - name: Pipelines API\n    description: >-\n      Create, edit, delete, start, and view details about Delta Live Tables\n      pipelines for building reliable data pipelines.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/pipelines\n    tags:\n      - Data Engineering\n      - Delta Live Tables\n      - ETL\n      - Pipelines\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/ldp/\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/pipelines\n  - name: Permissions API\n    description: >-\n      Manage permissions on workspace objects including clusters, jobs, notebooks,\n      and other resources using access control lists.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/permissions\n    tags:\n      - Access Control\n      - Permissions\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/security/auth/access-control/\n\
  \      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/permissions\n  - name: Unity Catalog - Catalogs API\n    description: >-\n      Manage Unity Catalog catalogs for organizing and governing data assets across\n      workspaces.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/catalogs\n    tags:\n      - Catalogs\n      - Data Governance\n      - Unity Catalog\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/data-governance/unity-catalog/\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/catalogs\n  - name: Unity Catalog - Schemas API\n    description: >-\n      Manage schemas within Unity Catalog catalogs for organizing tables, views,\n      and functions.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/schemas\n    tags:\n      - Data Governance\n      - Schemas\n      - Unity\
  \ Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/schemas\n  - name: Unity Catalog - Tables API\n    description: >-\n      Manage tables within Unity Catalog schemas including listing, getting, and\n      deleting tables.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/tables\n    tags:\n      - Data Governance\n      - Tables\n      - Unity Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/tables\n  - name: Unity Catalog - Volumes API\n    description: >-\n      Manage Unity Catalog volumes for governing non-tabular data such as files and\n      directories.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/volumes\n    tags:\n      - Storage\n      - Unity Catalog\n      - Volumes\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/volumes\n\
  \  - name: Unity Catalog - Grants API\n    description: >-\n      Manage permissions and grants on Unity Catalog objects including catalogs,\n      schemas, tables, and other securable objects.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/permissions\n    tags:\n      - Data Governance\n      - Permissions\n      - Unity Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/grants\n  - name: Unity Catalog - External Locations API\n    description: >-\n      Manage external locations in Unity Catalog for connecting to cloud storage\n      paths.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/external-locations\n    tags:\n      - External Locations\n      - Storage\n      - Unity Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/externallocations\n  - name: Unity Catalog - Storage Credentials\
  \ API\n    description: >-\n      Manage storage credentials in Unity Catalog for authenticating access to cloud\n      storage.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/storage-credentials\n    tags:\n      - Credentials\n      - Security\n      - Storage\n      - Unity Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/storagecredentials\n  - name: Unity Catalog - Metastores API\n    description: >-\n      Manage Unity Catalog metastores which serve as the top-level container for\n      data governance.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/metastores\n    tags:\n      - Data Governance\n      - Metastores\n      - Unity Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/metastores\n  - name: Model Serving Endpoints API\n    description: >-\n      Create and manage model\
  \ serving endpoints for deploying machine learning\n      models as REST API endpoints.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/serving-endpoints\n    tags:\n      - Deployment\n      - Inference\n      - Machine Learning\n      - Model Serving\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/machine-learning/model-serving/create-manage-serving-endpoints\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/servingendpoints\n  - name: Model Registry API\n    description: >-\n      Manage registered models and model versions in the Databricks Model Registry\n      for model lifecycle management.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/mlflow/databricks\n    tags:\n      - Machine Learning\n      - Mlops\n      - Model Registry\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/modelregistry\n\
  \  - name: Registered Models API\n    description: >-\n      Manage registered models in Unity Catalog for centralized model governance\n      and sharing.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/models\n    tags:\n      - Machine Learning\n      - Model Registry\n      - Unity Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/registeredmodels\n  - name: Global Init Scripts API\n    description: >-\n      Manage global cluster initialization scripts that run on every cluster in the\n      workspace.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/global-init-scripts\n    tags:\n      - Administration\n      - Clusters\n      - Initialization\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/globalinitscripts\n  - name: IP Access Lists API\n    description: >-\n      Manage IP access lists to control\
  \ network access to Azure Databricks\n      workspaces.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/ip-access-lists\n    tags:\n      - Access Control\n      - Networking\n      - Security\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/ipaccesslists\n  - name: Statement Execution API\n    description: >-\n      Execute SQL statements on SQL warehouses and retrieve results for\n      programmatic SQL access.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/sql/statements\n    tags:\n      - Query Execution\n      - Sql\n      - Warehouses\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/statementexecution\n  - name: Command Execution API\n    description: >-\n      Execute commands on running clusters and retrieve results programmatically.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/1.2\n    tags:\n\
  \      - Clusters\n      - Commands\n      - Execution\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/commandexecution\n  - name: Files API\n    description: >-\n      Manage files in Unity Catalog volumes and workspace filesystem with\n      operations for uploading, downloading, and deleting files.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/fs/files\n    tags:\n      - Files\n      - Storage\n      - Unity Catalog\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/files\n  - name: Apps API\n    description: >-\n      Deploy and manage Databricks Apps including creating, starting, stopping, and\n      listing custom applications.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/apps\n    tags:\n      - Applications\n      - Deployment\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/apps\n\
  \  - name: Lakeview API\n    description: >-\n      Manage Lakeview dashboards programmatically including creating, updating, and\n      publishing dashboards.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/lakeview\n    tags:\n      - Dashboards\n      - Lakeview\n      - Visualization\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/lakeview\n  - name: Online Tables API\n    description: >-\n      Manage online tables for low-latency serving of feature data in Unity\n      Catalog.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/online-tables\n    tags:\n      - Feature Serving\n      - Machine Learning\n      - Online Tables\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/onlinetables\n  - name: Vector Search Indexes API\n    description: >-\n      Manage vector search indexes for similarity search and retrieval-augmented\n\
  \      generation workloads.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/vector-search/indexes\n    tags:\n      - AI\n      - RAG\n      - Similarity Search\n      - Vector Search\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/vectorsearchindexes\n  - name: Vector Search Endpoints API\n    description: >-\n      Manage vector search endpoints for hosting vector search indexes.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/vector-search/endpoints\n    tags:\n      - AI\n      - Endpoints\n      - Vector Search\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/vectorsearchendpoints\n  - name: Query History API\n    description: >-\n      Retrieve query history for SQL warehouses including query text, status, and\n      performance metrics.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/sql/history/queries\n\
  \    tags:\n      - Monitoring\n      - Query History\n      - Sql\n    properties:\n      - type: APIReference\n        url: https://docs.databricks.com/api/azure/workspace/queryhistory\n  - name: Account SCIM API\n    description: >-\n      Manage users, groups, and service principals across the Databricks account\n      using SCIM 2.0 protocol.\n    baseURL: https://<databricks-instance>.azuredatabricks.net/api/2.0/account/scim/v2\n    tags:\n      - Groups\n      - Identity Management\n      - SCIM\n      - Users\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/azure/databricks/reference/scim-2-1\n      - type: APIReference\n        url: https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/scim/scim-groups\ncommon:\n  - type: GettingStarted\n    url: https://learn.microsoft.com/azure/databricks/getting-started/\n  - type: Pricing\n    url: https://azure.microsoft.com/pricing/details/databricks/\n  - type: StatusPage\n    url: https://status.azuredatabricks.net/\n\
  \  - type: Security\n    url: https://learn.microsoft.com/azure/databricks/security/\n  - type: SDK\n    url: https://learn.microsoft.com/azure/databricks/dev-tools/\n  - type: CLI\n    url: https://learn.microsoft.com/azure/databricks/dev-tools/cli/\n  - type: Authentication\n    url: https://learn.microsoft.com/azure/databricks/dev-tools/auth/\n  - type: APIReference\n    url: https://learn.microsoft.com/azure/databricks/reference/api\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/azure/databricks/release-notes/product/\n  - type: ChangeLog\n    url: https://learn.microsoft.com/azure/databricks/release-notes/\n  - type: Support\n    url: https://learn.microsoft.com/answers/tags/166/azure-databricks\n  - type: SDK\n    url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-python\n    title: Python SDK\n  - type: SDK\n    url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-java\n    title: Java SDK\n  - type: SDK\n    url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-go\n\
  \    title: Go SDK\n  - type: SDK\n    url: https://learn.microsoft.com/azure/databricks/dev-tools/sdk-r\n    title: R SDK\n  - type: GitHubRepository\n    url: https://github.com/Azure/azure-databricks-client\n  - type: OpenAPI\n    url: openapi/azure-databricks-openapi.yml\n  - type: JSONSchema\n    url: json-schema/azure-databricks-cluster-schema.json\n  - type: JSONLD\n    url: json-ld/azure-databricks-context.jsonld\n  - type: SpectralRules\n    url: rules/azure-databricks-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/azure-databricks-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/data-engineering.yaml\n  - type: Features\n    data:\n      - Collaborative notebooks with multi-language support\n      - Auto-scaling Apache Spark clusters\n      - Delta Lake for reliable data lakehouse architecture\n      - Unity Catalog for unified data governance\n      - MLflow integration for ML lifecycle management\n      - Model serving endpoints for real-time\
  \ inference\n      - Delta Live Tables for declarative ETL pipelines\n      - SQL analytics with serverless SQL warehouses\n      - Vector search for RAG and similarity search\n      - Lakeview dashboards for data visualization\n      - Git integration for version control of notebooks\n      - SCIM 2.0 for identity and access management\n  - type: UseCases\n    data:\n      - Building and managing data lakehouse architectures\n      - Training and deploying machine learning models at scale\n      - Running ETL pipelines for data transformation\n      - Interactive data exploration and ad-hoc analytics\n      - Real-time streaming analytics with Structured Streaming\n      - Building retrieval-augmented generation (RAG) applications\n      - Data governance and compliance with Unity Catalog\n      - Collaborative data science with shared notebooks\n  - type: Integrations\n    data:\n      - Azure Data Factory for orchestration\n      - Azure Synapse Analytics for data warehousing\n    \
  \  - Azure Data Lake Storage for scalable storage\n      - Azure Key Vault for secret management\n      - Azure Active Directory for authentication\n      - Power BI for business intelligence dashboards\n      - Terraform for infrastructure as code\n      - Apache Kafka for streaming data ingestion\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-databricks/refs/heads/main/apis.yml
tags:
- Analytics
- Apache Spark
- Big Data
- Data Engineering
- Machine Learning
url: https://raw.githubusercontent.com/api-evangelist/azure-databricks/refs/heads/main/apis.yml
use_cases:
- Building and managing data lakehouse architectures
- Training and deploying machine learning models at scale
- Running ETL pipelines for data transformation
- Interactive data exploration and ad-hoc analytics
- Real-time streaming analytics with Structured Streaming
- Building retrieval-augmented generation (RAG) applications
- Data governance and compliance with Unity Catalog
- Collaborative data science with shared notebooks
---
