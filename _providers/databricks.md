---
api_count: 57
api_specs:
- filename: databricks-openapi.yml
  format: yaml
  label: Databricks Clusters API
  slug: clusters-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/openapi/databricks-openapi.yml
- filename: databricks-openapi.yml
  format: yaml
  label: Databricks Jobs API
  slug: jobs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/openapi/databricks-openapi.yml
- filename: databricks-openapi.yml
  format: yaml
  label: Databricks Workspace API
  slug: workspace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/openapi/databricks-openapi.yml
apis:
- description: Databricks is a cloud-based data platform that simplifies and accelerates the process of preparing and analyzing large volumes of data. The platform integrates with popular data sources and tools, all
  name: Databricks
  slug: databricks
- description: The Databricks Clusters API allows you to create, start, edit, list, terminate, and delete clusters. Clusters are managed cloud resources that enable you to run data engineering and data science workl
  name: Databricks Clusters API
  slug: clusters-api
- description: The Databricks Jobs API allows you to create, edit, delete, and trigger jobs. Jobs are the primary mechanism for running automated workloads on Databricks, including notebooks, JARs, Python scripts, a
  name: Databricks Jobs API
  slug: jobs-api
- description: The Databricks File System (DBFS) API is a distributed file system mounted into a Databricks workspace and available on Databricks clusters. The API enables you to interact with object storage using d
  name: Databricks DBFS API
  slug: dbfs-api
- description: The Databricks Workspace API allows you to list, import, export, and delete notebooks, folders, and libraries in a Databricks workspace. It provides programmatic access to manage workspace objects, en
  name: Databricks Workspace API
  slug: workspace-api
- description: The Databricks SQL Warehouses API allows you to create, edit, list, start, stop, and delete SQL warehouses. SQL warehouses are compute resources that enable you to run SQL commands on data objects wit
  name: Databricks SQL Warehouses API
  slug: sql-warehouses-api
- description: The Databricks Pipelines API allows you to create, edit, delete, start, and stop Delta Live Tables pipelines. Delta Live Tables is a declarative framework for building reliable, maintainable, and test
  name: Databricks Pipelines API
  slug: pipelines-api
- description: The Databricks Serving Endpoints API allows you to create, update, query, and delete model serving endpoints. Mosaic AI Model Serving provides a unified interface to deploy, govern, and query AI model
  name: Databricks Serving Endpoints API
  slug: serving-endpoints-api
- description: The Databricks Secrets API allows you to manage secrets, secret scopes, and secret ACLs. Secrets provide a secure way to store and reference credentials and other sensitive information in notebooks an
  name: Databricks Secrets API
  slug: secrets-api
- description: The Databricks Instance Pools API allows you to create, edit, delete, and list instance pools. Instance pools reduce cluster start and auto-scaling times by maintaining a set of idle, ready-to-use clo
  name: Databricks Instance Pools API
  slug: instance-pools-api
- description: The Databricks Token Management API enables workspace administrators to manage personal access tokens for users and service principals. It allows creating, listing, and revoking tokens, providing cent
  name: Databricks Token Management API
  slug: token-management-api
- description: The Databricks Catalogs API is part of Unity Catalog and allows you to create, update, list, and delete catalogs. Catalogs are the top-level container for data objects in Unity Catalog, providing a th
  name: Databricks Catalogs API
  slug: catalogs-api
- description: The Databricks Vector Search Indexes API allows you to create, manage, query, and delete vector search indexes. Vector Search enables you to store vector representations of your data and perform simil
  name: Databricks Vector Search Indexes API
  slug: vector-search-indexes-api
- description: The Databricks Model Versions API allows you to manage model versions within the Unity Catalog model registry. It provides programmatic access to create, update, list, and delete model versions, enabl
  name: Databricks Model Versions API
  slug: model-versions-api
- description: The Databricks Permissions API allows you to manage permissions on workspace objects such as clusters, jobs, notebooks, and SQL warehouses. It provides programmatic access to get, set, and update acce
  name: Databricks Permissions API
  slug: permissions-api
- description: The Databricks Repos API allows you to manage Git repositories within a Databricks workspace. It provides programmatic access to create, update, delete, and list repos, as well as perform Git operatio
  name: Databricks Repos API
  slug: repos-api
- description: The Databricks Git Credentials API allows you to manage Git credentials for authenticating with Git providers. It provides programmatic access to create, update, delete, and list stored Git credential
  name: Databricks Git Credentials API
  slug: git-credentials-api
- description: The Databricks Cluster Policies API allows administrators to create, edit, delete, and list cluster policies. Cluster policies limit the ability to configure clusters based on a set of rules, enabling
  name: Databricks Cluster Policies API
  slug: cluster-policies-api
- description: The Databricks Libraries API allows you to install, uninstall, and list libraries on clusters. It provides programmatic management of Python, Java, Scala, and R library dependencies for cluster worklo
  name: Databricks Libraries API
  slug: libraries-api
- description: The Databricks Global Init Scripts API enables workspace administrators to manage global initialization scripts that run on every cluster in the workspace. It provides programmatic access to create, u
  name: Databricks Global Init Scripts API
  slug: global-init-scripts-api
- description: The Databricks Command Execution API allows you to execute Python, Scala, SQL, or R commands on running Databricks clusters. It provides programmatic access to create execution contexts, run commands,
  name: Databricks Command Execution API
  slug: command-execution-api
- description: The Databricks Statement Execution API allows you to execute SQL statements on Databricks SQL warehouses and retrieve results. It provides a synchronous and asynchronous interface for running SQL quer
  name: Databricks Statement Execution API
  slug: statement-execution-api
- description: The Databricks Queries API allows you to create, update, delete, list, and run saved SQL queries in Databricks SQL. It provides programmatic management of SQL query objects, enabling automation of ana
  name: Databricks Queries API
  slug: queries-api
- description: The Databricks Alerts API allows you to create, update, delete, and list alerts in Databricks SQL. Alerts automate query execution, evaluate custom conditions, and deliver notifications when those con
  name: Databricks Alerts API
  slug: alerts-api
- description: The Databricks Schemas API is part of Unity Catalog and allows you to create, update, list, and delete schemas. Schemas, also known as databases, reside within catalogs and contain tables, views, volu
  name: Databricks Schemas API
  slug: schemas-api
- description: 'The Databricks Tables API is part of Unity Catalog and allows you to create, update, list, and delete tables. Tables reside within schemas and represent structured data assets, supporting managed and '
  name: Databricks Tables API
  slug: tables-api
- description: The Databricks Volumes API is part of Unity Catalog and allows you to create, update, list, and delete volumes. Volumes provide a governed location for storing and accessing non-tabular data files suc
  name: Databricks Volumes API
  slug: volumes-api
- description: The Databricks Functions API is part of Unity Catalog and allows you to create, list, and delete user-defined functions. Functions reside within schemas and can be used in SQL queries and notebooks, w
  name: Databricks Functions API
  slug: functions-api
- description: The Databricks Grants API is part of Unity Catalog and allows you to get, update, and manage permissions on Unity Catalog securable objects. It provides programmatic control over access to catalogs, s
  name: Databricks Grants API
  slug: grants-api
- description: The Databricks External Locations API is part of Unity Catalog and allows you to create, update, list, and delete external locations. External locations combine a cloud storage path with a storage cre
  name: Databricks External Locations API
  slug: external-locations-api
- description: The Databricks Storage Credentials API is part of Unity Catalog and allows you to create, update, list, and delete storage credentials. Storage credentials contain long-term cloud credentials that pro
  name: Databricks Storage Credentials API
  slug: storage-credentials-api
- description: The Databricks Metastores API is part of Unity Catalog and allows you to create, update, list, and delete metastores. A metastore is the top-level container of objects in Unity Catalog, providing cent
  name: Databricks Metastores API
  slug: metastores-api
- description: The Databricks Connections API is part of Unity Catalog and allows you to create, update, list, and delete connections to external data sources. Connections enable federated queries across external da
  name: Databricks Connections API
  slug: connections-api
- description: The Databricks Registered Models API allows you to create, update, list, and delete registered models in the Unity Catalog model registry. It provides centralized model lifecycle management with versi
  name: Databricks Registered Models API
  slug: registered-models-api
- description: The Databricks Experiments API allows you to create, update, list, and manage MLflow experiments. Experiments are the primary unit of organization in MLflow, grouping runs that track parameters, metri
  name: Databricks Experiments API
  slug: experiments-api
- description: The Databricks Online Tables API allows you to create, get, and delete online tables. Online tables are materialized copies of Delta tables optimized for low-latency lookups, enabling real-time featur
  name: Databricks Online Tables API
  slug: online-tables-api
- description: The Databricks Quality Monitors API allows you to create, update, get, and delete data quality monitors for tables. Quality monitors enable automated data profiling and anomaly detection, providing co
  name: Databricks Quality Monitors API
  slug: quality-monitors-api
- description: 'The Databricks Vector Search Endpoints API allows you to create, list, get, and delete vector search endpoints. Vector search endpoints are compute resources that host vector search indexes, enabling '
  name: Databricks Vector Search Endpoints API
  slug: vector-search-endpoints-api
- description: The Databricks Shares API is part of Delta Sharing and allows you to create, update, list, and delete shares. A share is a read-only logical collection of tables and table partitions that a data provi
  name: Databricks Shares API
  slug: shares-api
- description: The Databricks Recipients API is part of Delta Sharing and allows you to create, update, list, and delete recipients. A recipient is an entity that receives shared data from a provider, and can be eit
  name: Databricks Recipients API
  slug: recipients-api
- description: The Databricks Providers API is part of Delta Sharing and allows you to create, update, list, and delete data providers. Providers represent organizations that share data through Delta Sharing, enabli
  name: Databricks Providers API
  slug: providers-api
- description: The Databricks Clean Rooms API allows you to create, update, list, and delete clean rooms. Clean rooms use Delta Sharing and serverless compute to provide a secure and privacy-protecting environment w
  name: Databricks Clean Rooms API
  slug: clean-rooms-api
- description: The Databricks Notification Destinations API allows you to create, update, list, and delete notification destinations for a workspace. Notification destinations define where alerts and notifications a
  name: Databricks Notification Destinations API
  slug: notification-destinations-api
- description: The Databricks Apps API allows you to create, deploy, manage, and delete Databricks Apps. Apps run directly on a Databricks workspace, integrating with workspace data and services to build custom data
  name: Databricks Apps API
  slug: apps-api
- description: The Databricks Lakeview API allows you to create, update, get, list, and delete AI/BI dashboards. Lakeview dashboards provide a modern visualization experience built on top of Databricks SQL, enabling
  name: Databricks Lakeview API
  slug: lakeview-api
- description: The Databricks Files API provides a standard HTTP interface for reading, writing, listing, and deleting files and directories in Unity Catalog volumes and other workspace storage locations. It support
  name: Databricks Files API
  slug: files-api
- description: The Databricks Tokens API allows you to create, list, and revoke personal access tokens. Personal access tokens are used to authenticate with the Databricks REST API and integrations, providing an alt
  name: Databricks Tokens API
  slug: tokens-api
- description: The Databricks IP Access Lists API allows administrators to configure IP allow lists and block lists for a workspace. It provides programmatic management of network security rules to restrict access t
  name: Databricks IP Access Lists API
  slug: ip-access-lists-api
- description: 'The Databricks Current User API allows you to retrieve information about the currently authenticated user or service principal. It returns identity details including username, display name, and group '
  name: Databricks Current User API
  slug: current-user-api
- description: The Databricks Groups API allows you to create, update, list, and delete groups in a workspace. Groups simplify identity management by enabling administrators to assign access permissions to collectio
  name: Databricks Groups API
  slug: groups-api
- description: 'The Databricks Service Principals API allows you to create, update, list, and delete service principals in a workspace. Service principals are identities for automated tools, jobs, scripts, apps, and '
  name: Databricks Service Principals API
  slug: service-principals-api
- description: The Databricks Users API allows you to create, update, list, and delete users in a workspace. It provides programmatic management of user identities and their workspace access, supporting SCIM protoco
  name: Databricks Users API
  slug: users-api
- description: The Databricks Dashboards API allows you to create, update, list, and delete legacy SQL dashboards. Dashboards provide visual representations of query results, enabling business intelligence reporting
  name: Databricks Dashboards API
  slug: dashboards-api
- description: The Databricks Model Registry API provides the workspace model registry for managing the full lifecycle of ML models. It enables creating registered models, managing model versions, transitioning stag
  name: Databricks Model Registry API
  slug: model-registry-api
- description: The Databricks Workspace Bindings API allows you to manage the binding of Unity Catalog securables to specific workspaces. It enables configuring whether catalogs and other objects are available acros
  name: Databricks Workspace Bindings API
  slug: workspace-bindings-api
- description: The Databricks System Schemas API allows you to enable, disable, and list system schemas within a metastore. System schemas contain system tables that provide operational data about your Databricks ac
  name: Databricks System Schemas API
  slug: system-schemas-api
- description: 'The Databricks Table Constraints API allows you to create and delete primary key and foreign key constraints on Unity Catalog tables. Table constraints define relationships between tables, supporting '
  name: Databricks Table Constraints API
  slug: table-constraints-api
capabilities:
- description: Unified workflow for Databricks data engineering including cluster management, job orchestration, and workspace operations. Used by data engineers and platform administrators.
  name: Databricks Data Engineering
  slug: data-engineering
common:
- title: ''
  type: Authentication
  url: https://docs.databricks.com/dev-tools/auth.html
- title: ''
  type: Getting Started
  url: https://docs.databricks.com/getting-started/index.html
- title: ''
  type: SDKs
  url: https://docs.databricks.com/dev-tools/sdks.html
- title: ''
  type: StatusPage
  url: https://status.databricks.com/
- title: ''
  type: Support
  url: https://help.databricks.com/
- title: ''
  type: API Reference
  url: https://docs.databricks.com/api/workspace/introduction
- title: ''
  type: Documentation
  url: https://docs.databricks.com/aws/en/reference/api
- title: ''
  type: Pricing
  url: https://www.databricks.com/product/pricing
- title: ''
  type: Sign Up
  url: https://www.databricks.com/try-databricks
- title: ''
  type: PrivacyPolicy
  url: https://www.databricks.com/legal/privacynotice
- title: ''
  type: TermsOfService
  url: https://www.databricks.com/legal/terms-of-use
- title: ''
  type: Security
  url: https://www.databricks.com/trust
- title: ''
  type: RateLimits
  url: https://docs.databricks.com/aws/en/resources/limits
- title: ''
  type: ChangeLog
  url: https://docs.databricks.com/aws/en/release-notes/
- title: ''
  type: Blog
  url: https://www.databricks.com/blog
- title: Community Forum
  type: Support
  url: https://community.databricks.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/databricks
- title: Python SDK
  type: SDK
  url: https://github.com/databricks/databricks-sdk-py
- title: Go SDK
  type: SDK
  url: https://github.com/databricks/databricks-sdk-go
- title: ''
  type: CLI
  url: https://github.com/databricks/cli
- title: ''
  type: Documentation
  url: https://docs.databricks.com/aws/en/dev-tools/cli
- title: ''
  type: X
  url: https://twitter.com/databricks
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/databricks
- title: ''
  type: Login
  url: https://login.databricks.com/
- title: ''
  type: Contact
  url: https://www.databricks.com/company/contact
- title: ''
  type: Training
  url: https://www.databricks.com/learn/training/home
- title: ''
  type: Academy
  url: https://customer-academy.databricks.com/learn
- title: Java SDK
  type: SDK
  url: https://github.com/databricks/databricks-sdk-java
- title: Python SQL SDK
  type: SDK
  url: https://github.com/databricks/databricks-sql-python
- title: Terraform Provider
  type: SDK
  url: https://github.com/databricks/terraform-provider-databricks
- title: MLflow API Reference
  type: APIReference
  url: https://docs.databricks.com/aws/en/reference/mlflow-api
- title: ''
  type: Security
  url: https://www.databricks.com/trust/security-features
- title: ''
  type: Authentication
  url: https://docs.databricks.com/aws/en/dev-tools/auth
- title: ''
  type: APIReference
  url: https://api-docs.databricks.com/
- title: ''
  type: OpenAPI
  url: openapi/databricks-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/databricks-cluster-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/databricks-job-schema.json
- title: ''
  type: JSONLD
  url: json-ld/databricks-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/databricks-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-engineering.yaml
created: '2025-01-14'
description: Collection of Databricks REST APIs for managing workspaces, clusters, jobs, and data operations.
features:
- description: Combine data warehousing and data lake capabilities in a single, open platform built on Delta Lake.
  name: Unified Data Lakehouse
- description: Auto-scaling serverless SQL warehouses and compute that eliminate infrastructure management.
  name: Serverless Compute
- description: Unified governance for data and AI assets with fine-grained access control and lineage tracking.
  name: Unity Catalog
- description: Declarative ETL framework for building reliable, maintainable data processing pipelines.
  name: Delta Live Tables
- description: Integrated AI platform for building, deploying, and monitoring machine learning and generative AI models.
  name: Mosaic AI
- description: Built-in vector similarity search for RAG applications and AI-powered retrieval.
  name: Vector Search
- description: Open protocol for secure cross-organization data sharing without data copying.
  name: Delta Sharing
image: https://www.databricks.com/en-website-assets/static/f9f2b15ae456c41f7d2e5b303c8c6c6e/databricks-logo.svg
integrations:
- description: Native integration with Apache Spark for distributed data processing at scale.
  name: Apache Spark
- description: Built on Delta Lake open format for ACID transactions and time travel on data lakes.
  name: Delta Lake
- description: Open-source platform for managing the complete machine learning lifecycle.
  name: MLflow
- description: Infrastructure-as-code provider for automating Databricks workspace provisioning.
  name: Terraform
- description: Integration with dbt for SQL-based data transformation workflows.
  name: dbt
jsonld:
- class_count: 0
  name: Databricks Context
  property_count: 0
  slug: databricks-context
layout: provider
modified: '2026-04-18'
name: Databricks
rules:
- name: Databricks API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: databricks-spectral-rules
skills: []
slug: databricks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: databricks\nurl: https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/apis.yml\napis:\n  - aid: databricks:databricks\n    name: Databricks\n    tags:\n      - Analytics\n      - Data\n      - Visualize\n    humanURL: ' https://www.databricks.com'\n    properties:\n      - url: ' https://www.databricks.com'\n        type: Documentation\n      - url: https://docs.databricks.com/api/workspace/introduction\n        type: API Reference\n    description: >-\n      Databricks is a cloud-based data platform that simplifies and accelerates the\n      process of preparing and analyzing large volumes of data. The platform integrates\n      with popular data sources and tools, allowing data engineers and data scientists\n      to collaborate and work more efficiently. Databricks offers powerful features\n      such as data visualization, machine learning, and real-time analytics, helping\n      organizations make data-driven decisions and improve their business\
  \ outcomes.\n  - aid: databricks:clusters-api\n    name: Databricks Clusters API\n    tags:\n      - Clusters\n      - Compute\n      - Infrastructure\n    humanURL: https://docs.databricks.com/api/workspace/clusters\n    properties:\n      - url: https://docs.databricks.com/api/workspace/clusters\n        type: Documentation\n      - url: openapi/databricks-openapi.yml\n        type: OpenAPI\n      - url: json-schema/databricks-cluster-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-create-cluster-request-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-edit-cluster-request-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-cluster-details-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-spark-node-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-auto-scale-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-aws-attributes-schema.json\n\
  \        type: JSONSchema\n      - url: json-schema/databricks-azure-attributes-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-gcp-attributes-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-init-script-info-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-cluster-event-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-error-response-schema.json\n        type: JSONSchema\n      - url: json-ld/databricks-context.jsonld\n        type: JSONLD\n    description: The Databricks Clusters API allows you to create, start, edit, list, terminate, and delete clusters. Clusters are managed cloud resources that enable you to run data engineering and data science workloads on Apache Spark in the cloud. The API provides programmatic control over cluster lifecycle management, configuration, and monitoring.\n  - aid: databricks:jobs-api\n    name: Databricks Jobs API\n    tags:\n      - Jobs\n      -\
  \ Orchestration\n      - Scheduling\n      - Workflows\n    humanURL: https://docs.databricks.com/api/workspace/jobs\n    properties:\n      - url: https://docs.databricks.com/api/workspace/jobs\n        type: Documentation\n      - url: openapi/databricks-openapi.yml\n        type: OpenAPI\n      - url: json-schema/databricks-job-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-create-job-request-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-task-settings-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-job-cluster-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-job-email-notifications-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-webhook-notifications-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-cron-schedule-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-git-source-schema.json\n        type:\
  \ JSONSchema\n      - url: json-schema/databricks-library-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-access-control-request-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-job-settings-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-run-schema.json\n        type: JSONSchema\n      - url: json-schema/databricks-run-task-schema.json\n        type: JSONSchema\n      - url: json-ld/databricks-context.jsonld\n        type: JSONLD\n    description: The Databricks Jobs API allows you to create, edit, delete, and trigger jobs. Jobs are the primary mechanism for running automated workloads on Databricks, including notebooks, JARs, Python scripts, and Spark submit applications. The API supports complex multi-task workflows with dependencies, scheduling, and monitoring capabilities.\n  - aid: databricks:dbfs-api\n    name: Databricks DBFS API\n    tags:\n      - Data\n      - Files\n      - Storage\n    humanURL:\
  \ https://docs.databricks.com/api/workspace/dbfs\n    properties:\n      - url: https://docs.databricks.com/api/workspace/dbfs\n        type: Documentation\n    description: The Databricks File System (DBFS) API is a distributed file system mounted into a Databricks workspace and available on Databricks clusters. The API enables you to interact with object storage using directory and file semantics, allowing you to put, get, list, and delete files and directories programmatically.\n  - aid: databricks:workspace-api\n    name: Databricks Workspace API\n    tags:\n      - Folders\n      - Notebooks\n      - Workspace\n    humanURL: https://docs.databricks.com/api/workspace/workspace\n    properties:\n      - url: https://docs.databricks.com/api/workspace/workspace\n        type: Documentation\n      - url: openapi/databricks-openapi.yml\n        type: OpenAPI\n      - url: json-schema/databricks-workspace-object-schema.json\n        type: JSONSchema\n      - url: json-ld/databricks-context.jsonld\n\
  \        type: JSONLD\n    description: The Databricks Workspace API allows you to list, import, export, and delete notebooks, folders, and libraries in a Databricks workspace. It provides programmatic access to manage workspace objects, enabling automation of notebook deployment and workspace organization.\n  - aid: databricks:sql-warehouses-api\n    name: Databricks SQL Warehouses API\n    tags:\n      - Analytics\n      - SQL\n      - Warehouses\n    humanURL: https://docs.databricks.com/api/workspace/warehouses\n    properties:\n      - url: https://docs.databricks.com/api/workspace/warehouses\n        type: Documentation\n    description: The Databricks SQL Warehouses API allows you to create, edit, list, start, stop, and delete SQL warehouses. SQL warehouses are compute resources that enable you to run SQL commands on data objects within Databricks SQL, providing serverless or classic compute options for analytical workloads.\n  - aid: databricks:pipelines-api\n    name: Databricks\
  \ Pipelines API\n    tags:\n      - Delta Live Tables\n      - ETL\n      - Pipelines\n    humanURL: https://docs.databricks.com/api/workspace/pipelines\n    properties:\n      - url: https://docs.databricks.com/api/workspace/pipelines\n        type: Documentation\n    description: The Databricks Pipelines API allows you to create, edit, delete, start, and stop Delta Live Tables pipelines. Delta Live Tables is a declarative framework for building reliable, maintainable, and testable data processing pipelines. The API provides full lifecycle management of ETL pipelines.\n  - aid: databricks:serving-endpoints-api\n    name: Databricks Serving Endpoints API\n    tags:\n      - AI\n      - Machine Learning\n      - Model Serving\n    humanURL: https://docs.databricks.com/api/workspace/servingendpoints\n    properties:\n      - url: https://docs.databricks.com/api/workspace/servingendpoints\n        type: Documentation\n    description: The Databricks Serving Endpoints API allows you to create,\
  \ update, query, and delete model serving endpoints. Mosaic AI Model Serving provides a unified interface to deploy, govern, and query AI models, including custom models, generative AI models, and large language models, with high availability and low latency.\n  - aid: databricks:secrets-api\n    name: Databricks Secrets API\n    tags:\n      - Credentials\n      - Secrets\n      - Security\n    humanURL: https://docs.databricks.com/api/workspace/secrets\n    properties:\n      - url: https://docs.databricks.com/api/workspace/secrets\n        type: Documentation\n    description: The Databricks Secrets API allows you to manage secrets, secret scopes, and secret ACLs. Secrets provide a secure way to store and reference credentials and other sensitive information in notebooks and jobs without exposing them in plaintext.\n  - aid: databricks:instance-pools-api\n    name: Databricks Instance Pools API\n    tags:\n      - Clusters\n      - Compute\n      - Infrastructure\n    humanURL: https://docs.databricks.com/api/workspace/instancepools\n\
  \    properties:\n      - url: https://docs.databricks.com/api/workspace/instancepools\n        type: Documentation\n    description: The Databricks Instance Pools API allows you to create, edit, delete, and list instance pools. Instance pools reduce cluster start and auto-scaling times by maintaining a set of idle, ready-to-use cloud instances, improving performance and reducing costs for frequently used cluster configurations.\n  - aid: databricks:token-management-api\n    name: Databricks Token Management API\n    tags:\n      - Authentication\n      - Security\n      - Tokens\n    humanURL: https://docs.databricks.com/api/workspace/tokenmanagement\n    properties:\n      - url: https://docs.databricks.com/api/workspace/tokenmanagement\n        type: Documentation\n    description: The Databricks Token Management API enables workspace administrators to manage personal access tokens for users and service principals. It allows creating, listing, and revoking tokens, providing centralized\
  \ control over API authentication credentials.\n  - aid: databricks:catalogs-api\n    name: Databricks Catalogs API\n    tags:\n      - Data Governance\n      - Metadata\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/catalogs\n    properties:\n      - url: https://docs.databricks.com/api/workspace/catalogs\n        type: Documentation\n    description: The Databricks Catalogs API is part of Unity Catalog and allows you to create, update, list, and delete catalogs. Catalogs are the top-level container for data objects in Unity Catalog, providing a three-level namespace (catalog.schema.table) for organizing and governing data assets across workspaces.\n  - aid: databricks:vector-search-indexes-api\n    name: Databricks Vector Search Indexes API\n    tags:\n      - AI\n      - Embeddings\n      - Vector Search\n    humanURL: https://docs.databricks.com/api/workspace/vectorsearchindexes\n    properties:\n      - url: https://docs.databricks.com/api/workspace/vectorsearchindexes\n\
  \        type: Documentation\n    description: The Databricks Vector Search Indexes API allows you to create, manage, query, and delete vector search indexes. Vector Search enables you to store vector representations of your data and perform similarity searches, powering retrieval-augmented generation (RAG) applications and other AI use cases.\n  - aid: databricks:model-versions-api\n    name: Databricks Model Versions API\n    tags:\n      - Machine Learning\n      - MLflow\n      - Model Registry\n    humanURL: https://docs.databricks.com/api/workspace/modelversions\n    properties:\n      - url: https://docs.databricks.com/api/workspace/modelversions\n        type: Documentation\n    description: The Databricks Model Versions API allows you to manage model versions within the Unity Catalog model registry. It provides programmatic access to create, update, list, and delete model versions, enabling automated ML lifecycle management and model governance.\n  - aid: databricks:permissions-api\n\
  \    name: Databricks Permissions API\n    tags:\n      - Access Control\n      - Authorization\n      - Security\n    humanURL: https://docs.databricks.com/api/workspace/permissions\n    properties:\n      - url: https://docs.databricks.com/api/workspace/permissions\n        type: Documentation\n    description: The Databricks Permissions API allows you to manage permissions on workspace objects such as clusters, jobs, notebooks, and SQL warehouses. It provides programmatic access to get, set, and update access control lists for various Databricks resources, enabling fine-grained authorization management.\n  - aid: databricks:repos-api\n    name: Databricks Repos API\n    tags:\n      - Git\n      - Repositories\n      - Version Control\n    humanURL: https://docs.databricks.com/api/workspace/repos\n    properties:\n      - url: https://docs.databricks.com/api/workspace/repos\n        type: Documentation\n    description: The Databricks Repos API allows you to manage Git repositories\
  \ within a Databricks workspace. It provides programmatic access to create, update, delete, and list repos, as well as perform Git operations like pulling latest changes, enabling version-controlled notebook and code development.\n  - aid: databricks:git-credentials-api\n    name: Databricks Git Credentials API\n    tags:\n      - Authentication\n      - Credentials\n      - Git\n    humanURL: https://docs.databricks.com/api/workspace/gitcredentials\n    properties:\n      - url: https://docs.databricks.com/api/workspace/gitcredentials\n        type: Documentation\n    description: The Databricks Git Credentials API allows you to manage Git credentials for authenticating with Git providers. It provides programmatic access to create, update, delete, and list stored Git credentials, enabling seamless integration with GitHub, GitLab, Bitbucket, and other Git hosting services.\n  - aid: databricks:cluster-policies-api\n    name: Databricks Cluster Policies API\n    tags:\n      - Clusters\n\
  \      - Governance\n      - Policies\n    humanURL: https://docs.databricks.com/api/workspace/clusterpolicies\n    properties:\n      - url: https://docs.databricks.com/api/workspace/clusterpolicies\n        type: Documentation\n    description: The Databricks Cluster Policies API allows administrators to create, edit, delete, and list cluster policies. Cluster policies limit the ability to configure clusters based on a set of rules, enabling administrators to enforce cost controls and governance over compute resources.\n  - aid: databricks:libraries-api\n    name: Databricks Libraries API\n    tags:\n      - Clusters\n      - Dependencies\n      - Libraries\n    humanURL: https://docs.databricks.com/api/workspace/libraries\n    properties:\n      - url: https://docs.databricks.com/api/workspace/libraries\n        type: Documentation\n    description: The Databricks Libraries API allows you to install, uninstall, and list libraries on clusters. It provides programmatic management of Python,\
  \ Java, Scala, and R library dependencies for cluster workloads, enabling automated environment configuration.\n  - aid: databricks:global-init-scripts-api\n    name: Databricks Global Init Scripts API\n    tags:\n      - Administration\n      - Compute\n      - Configuration\n    humanURL: https://docs.databricks.com/api/workspace/globalinitscripts\n    properties:\n      - url: https://docs.databricks.com/api/workspace/globalinitscripts\n        type: Documentation\n    description: The Databricks Global Init Scripts API enables workspace administrators to manage global initialization scripts that run on every cluster in the workspace. It provides programmatic access to create, update, delete, list, and reorder init scripts for consistent cluster configuration.\n  - aid: databricks:command-execution-api\n    name: Databricks Command Execution API\n    tags:\n      - Commands\n      - Compute\n      - Execution\n    humanURL: https://docs.databricks.com/api/workspace/commandexecution\n\
  \    properties:\n      - url: https://docs.databricks.com/api/workspace/commandexecution\n        type: Documentation\n    description: The Databricks Command Execution API allows you to execute Python, Scala, SQL, or R commands on running Databricks clusters. It provides programmatic access to create execution contexts, run commands, check status, and retrieve results, enabling remote interactive cluster usage.\n  - aid: databricks:statement-execution-api\n    name: Databricks Statement Execution API\n    tags:\n      - Queries\n      - SQL\n      - Warehouses\n    humanURL: https://docs.databricks.com/api/workspace/statementexecution\n    properties:\n      - url: https://docs.databricks.com/api/workspace/statementexecution\n        type: Documentation\n    description: The Databricks Statement Execution API allows you to execute SQL statements on Databricks SQL warehouses and retrieve results. It provides a synchronous and asynchronous interface for running SQL queries, checking execution\
  \ status, fetching result data, and canceling statements.\n  - aid: databricks:queries-api\n    name: Databricks Queries API\n    tags:\n      - Analytics\n      - Queries\n      - SQL\n    humanURL: https://docs.databricks.com/api/workspace/queries\n    properties:\n      - url: https://docs.databricks.com/api/workspace/queries\n        type: Documentation\n    description: The Databricks Queries API allows you to create, update, delete, list, and run saved SQL queries in Databricks SQL. It provides programmatic management of SQL query objects, enabling automation of analytical workflows and query lifecycle management.\n  - aid: databricks:alerts-api\n    name: Databricks Alerts API\n    tags:\n      - Alerts\n      - Monitoring\n      - SQL\n    humanURL: https://docs.databricks.com/api/workspace/alerts\n    properties:\n      - url: https://docs.databricks.com/api/workspace/alerts\n        type: Documentation\n    description: The Databricks Alerts API allows you to create, update,\
  \ delete, and list alerts in Databricks SQL. Alerts automate query execution, evaluate custom conditions, and deliver notifications when those conditions are met, enabling proactive monitoring of business data.\n  - aid: databricks:schemas-api\n    name: Databricks Schemas API\n    tags:\n      - Data Governance\n      - Schemas\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/schemas\n    properties:\n      - url: https://docs.databricks.com/api/workspace/schemas\n        type: Documentation\n    description: The Databricks Schemas API is part of Unity Catalog and allows you to create, update, list, and delete schemas. Schemas, also known as databases, reside within catalogs and contain tables, views, volumes, functions, and models, providing the second level of the three-level namespace for data organization.\n  - aid: databricks:tables-api\n    name: Databricks Tables API\n    tags:\n      - Data Governance\n      - Tables\n      - Unity Catalog\n    humanURL:\
  \ https://docs.databricks.com/api/workspace/tables\n    properties:\n      - url: https://docs.databricks.com/api/workspace/tables\n        type: Documentation\n    description: The Databricks Tables API is part of Unity Catalog and allows you to create, update, list, and delete tables. Tables reside within schemas and represent structured data assets, supporting managed and external table types with full governance and access control through Unity Catalog.\n  - aid: databricks:volumes-api\n    name: Databricks Volumes API\n    tags:\n      - Storage\n      - Unity Catalog\n      - Volumes\n    humanURL: https://docs.databricks.com/api/workspace/volumes\n    properties:\n      - url: https://docs.databricks.com/api/workspace/volumes\n        type: Documentation\n    description: The Databricks Volumes API is part of Unity Catalog and allows you to create, update, list, and delete volumes. Volumes provide a governed location for storing and accessing non-tabular data files such as images,\
  \ documents, and other unstructured data within the Unity Catalog namespace.\n  - aid: databricks:functions-api\n    name: Databricks Functions API\n    tags:\n      - Functions\n      - SQL\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/functions\n    properties:\n      - url: https://docs.databricks.com/api/workspace/functions\n        type: Documentation\n    description: The Databricks Functions API is part of Unity Catalog and allows you to create, list, and delete user-defined functions. Functions reside within schemas and can be used in SQL queries and notebooks, with full governance and access control managed through Unity Catalog.\n  - aid: databricks:grants-api\n    name: Databricks Grants API\n    tags:\n      - Access Control\n      - Security\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/grants\n    properties:\n      - url: https://docs.databricks.com/api/workspace/grants\n        type: Documentation\n   \
  \ description: The Databricks Grants API is part of Unity Catalog and allows you to get, update, and manage permissions on Unity Catalog securable objects. It provides programmatic control over access to catalogs, schemas, tables, volumes, and other data assets, enabling fine-grained data governance.\n  - aid: databricks:external-locations-api\n    name: Databricks External Locations API\n    tags:\n      - Cloud Storage\n      - Storage\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/externallocations\n    properties:\n      - url: https://docs.databricks.com/api/workspace/externallocations\n        type: Documentation\n    description: The Databricks External Locations API is part of Unity Catalog and allows you to create, update, list, and delete external locations. External locations combine a cloud storage path with a storage credential, enabling governed access to data stored in external cloud storage systems.\n  - aid: databricks:storage-credentials-api\n\
  \    name: Databricks Storage Credentials API\n    tags:\n      - Cloud Storage\n      - Security\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/storagecredentials\n    properties:\n      - url: https://docs.databricks.com/api/workspace/storagecredentials\n        type: Documentation\n    description: The Databricks Storage Credentials API is part of Unity Catalog and allows you to create, update, list, and delete storage credentials. Storage credentials contain long-term cloud credentials that provide access to cloud storage, and are referenced when creating external locations for governing data access.\n  - aid: databricks:metastores-api\n    name: Databricks Metastores API\n    tags:\n      - Data Governance\n      - Metadata\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/metastores\n    properties:\n      - url: https://docs.databricks.com/api/workspace/metastores\n        type: Documentation\n    description: The Databricks\
  \ Metastores API is part of Unity Catalog and allows you to create, update, list, and delete metastores. A metastore is the top-level container of objects in Unity Catalog, providing centralized metadata management, access control, and data governance across workspaces.\n  - aid: databricks:connections-api\n    name: Databricks Connections API\n    tags:\n      - Connections\n      - External Data\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/connections\n    properties:\n      - url: https://docs.databricks.com/api/workspace/connections\n        type: Documentation\n    description: The Databricks Connections API is part of Unity Catalog and allows you to create, update, list, and delete connections to external data sources. Connections enable federated queries across external databases and data systems, extending Unity Catalog governance to data outside the lakehouse.\n  - aid: databricks:registered-models-api\n    name: Databricks Registered Models\
  \ API\n    tags:\n      - Machine Learning\n      - MLflow\n      - Model Registry\n    humanURL: https://docs.databricks.com/api/workspace/registeredmodels\n    properties:\n      - url: https://docs.databricks.com/api/workspace/registeredmodels\n        type: Documentation\n    description: The Databricks Registered Models API allows you to create, update, list, and delete registered models in the Unity Catalog model registry. It provides centralized model lifecycle management with versioning, aliasing, and governance capabilities for machine learning models.\n  - aid: databricks:experiments-api\n    name: Databricks Experiments API\n    tags:\n      - Experiments\n      - Machine Learning\n      - MLflow\n    humanURL: https://docs.databricks.com/api/workspace/experiments\n    properties:\n      - url: https://docs.databricks.com/api/workspace/experiments\n        type: Documentation\n    description: The Databricks Experiments API allows you to create, update, list, and manage MLflow\
  \ experiments. Experiments are the primary unit of organization in MLflow, grouping runs that track parameters, metrics, and artifacts for machine learning model development and comparison.\n  - aid: databricks:online-tables-api\n    name: Databricks Online Tables API\n    tags:\n      - Feature Serving\n      - Real-Time\n      - Tables\n    humanURL: https://docs.databricks.com/api/workspace/onlinetables\n    properties:\n      - url: https://docs.databricks.com/api/workspace/onlinetables\n        type: Documentation\n    description: The Databricks Online Tables API allows you to create, get, and delete online tables. Online tables are materialized copies of Delta tables optimized for low-latency lookups, enabling real-time feature serving and online inference workloads for machine learning applications.\n  - aid: databricks:quality-monitors-api\n    name: Databricks Quality Monitors API\n    tags:\n      - Data Quality\n      - Monitoring\n      - Observability\n    humanURL: https://docs.databricks.com/api/workspace/qualitymonitors\n\
  \    properties:\n      - url: https://docs.databricks.com/api/workspace/qualitymonitors\n        type: Documentation\n    description: The Databricks Quality Monitors API allows you to create, update, get, and delete data quality monitors for tables. Quality monitors enable automated data profiling and anomaly detection, providing continuous monitoring of data quality metrics and statistical properties.\n  - aid: databricks:vector-search-endpoints-api\n    name: Databricks Vector Search Endpoints API\n    tags:\n      - AI\n      - Compute\n      - Vector Search\n    humanURL: https://docs.databricks.com/api/workspace/vectorsearchendpoints\n    properties:\n      - url: https://docs.databricks.com/api/workspace/vectorsearchendpoints\n        type: Documentation\n    description: The Databricks Vector Search Endpoints API allows you to create, list, get, and delete vector search endpoints. Vector search endpoints are compute resources that host vector search indexes, enabling similarity\
  \ search queries for retrieval-augmented generation and other AI applications.\n  - aid: databricks:shares-api\n    name: Databricks Shares API\n    tags:\n      - Collaboration\n      - Data Sharing\n      - Delta Sharing\n    humanURL: https://docs.databricks.com/api/workspace/shares\n    properties:\n      - url: https://docs.databricks.com/api/workspace/shares\n        type: Documentation\n    description: The Databricks Shares API is part of Delta Sharing and allows you to create, update, list, and delete shares. A share is a read-only logical collection of tables and table partitions that a data provider wants to share with one or more recipients for secure cross-organization data sharing.\n  - aid: databricks:recipients-api\n    name: Databricks Recipients API\n    tags:\n      - Access Control\n      - Data Sharing\n      - Delta Sharing\n    humanURL: https://docs.databricks.com/api/workspace/recipients\n    properties:\n      - url: https://docs.databricks.com/api/workspace/recipients\n\
  \        type: Documentation\n    description: The Databricks Recipients API is part of Delta Sharing and allows you to create, update, list, and delete recipients. A recipient is an entity that receives shared data from a provider, and can be either a Databricks workspace or an open-protocol recipient using bearer tokens.\n  - aid: databricks:providers-api\n    name: Databricks Providers API\n    tags:\n      - Data Sharing\n      - Delta Sharing\n      - Marketplace\n    humanURL: https://docs.databricks.com/api/workspace/providers\n    properties:\n      - url: https://docs.databricks.com/api/workspace/providers\n        type: Documentation\n    description: The Databricks Providers API is part of Delta Sharing and allows you to create, update, list, and delete data providers. Providers represent organizations that share data through Delta Sharing, enabling secure and governed cross-organization data exchange.\n  - aid: databricks:clean-rooms-api\n    name: Databricks Clean Rooms API\n\
  \    tags:\n      - Clean Rooms\n      - Collaboration\n      - Privacy\n    humanURL: https://docs.databricks.com/api/workspace/cleanrooms\n    properties:\n      - url: https://docs.databricks.com/api/workspace/cleanrooms\n        type: Documentation\n    description: The Databricks Clean Rooms API allows you to create, update, list, and delete clean rooms. Clean rooms use Delta Sharing and serverless compute to provide a secure and privacy-protecting environment where multiple parties can collaborate on sensitive enterprise data without exposing raw data.\n  - aid: databricks:notification-destinations-api\n    name: Databricks Notification Destinations API\n    tags:\n      - Alerts\n      - Integration\n      - Notifications\n    humanURL: https://docs.databricks.com/api/workspace/notificationdestinations\n    properties:\n      - url: https://docs.databricks.com/api/workspace/notificationdestinations\n        type: Documentation\n    description: The Databricks Notification Destinations\
  \ API allows you to create, update, list, and delete notification destinations for a workspace. Notification destinations define where alerts and notifications are sent, supporting integrations with email, Slack, PagerDuty, webhooks, and other channels.\n  - aid: databricks:apps-api\n    name: Databricks Apps API\n    tags:\n      - Applications\n      - Deployment\n      - Development\n    humanURL: https://docs.databricks.com/api/workspace/apps\n    properties:\n      - url: https://docs.databricks.com/api/workspace/apps\n        type: Documentation\n    description: The Databricks Apps API allows you to create, deploy, manage, and delete Databricks Apps. Apps run directly on a Databricks workspace, integrating with workspace data and services to build custom data applications, dashboards, and tools with built-in authentication and authorization.\n  - aid: databricks:lakeview-api\n    name: Databricks Lakeview API\n    tags:\n      - Analytics\n      - Dashboards\n      - Visualization\n\
  \    humanURL: https://docs.databricks.com/api/workspace/lakeview\n    properties:\n      - url: https://docs.databricks.com/api/workspace/lakeview\n        type: Documentation\n    description: The Databricks Lakeview API allows you to create, update, get, list, and delete AI/BI dashboards. Lakeview dashboards provide a modern visualization experience built on top of Databricks SQL, enabling interactive data exploration and business intelligence reporting.\n  - aid: databricks:files-api\n    name: Databricks Files API\n    tags:\n      - Files\n      - Storage\n      - Unity Catalog\n    humanURL: https://docs.databricks.com/api/workspace/files\n    properties:\n      - url: https://docs.databricks.com/api/workspace/files\n        type: Documentation\n    description: The Databricks Files API provides a standard HTTP interface for reading, writing, listing, and deleting files and directories in Unity Catalog volumes and other workspace storage locations. It supports direct file access\
  \ by URI, enabling seamless file management for data and ML workloads.\n  - aid: databricks:tokens-api\n    name: Databricks Tokens API\n    tags:\n      - Authentication\n      - Security\n      - Tokens\n    humanURL: https://docs.databricks.com/api/workspace/tokens\n    properties:\n      - url: https://docs.databricks.com/api/workspace/tokens\n        type: Documentation\n    description: The Databricks Tokens API allows you to create, list, and revoke personal access tokens. Personal access tokens are used to authenticate with the Databricks REST API and integrations, providing an alternative to OAuth for programmatic access.\n  - aid: databricks:ip-access-lists-api\n    name: Databricks IP Access Lists API\n    tags:\n      - Access Control\n      - Networking\n      - Security\n    humanURL: https://docs.databricks.com/api/workspace/ipaccesslists\n    properties:\n      - url: https://docs.databricks.com/api/workspace/ipaccesslists\n        type: Documentation\n    description:\
  \ The Databricks IP Access Lists API allows administrators to configure IP allow lists and block lists for a workspace. It provides programmatic management of network security rules to restr\n\n# --- truncated at 32 KB (43 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/apis.yml
tags:
- AI
- Analytics
- Apache Spark
- Big Data
- Clean Rooms
- Cloud Computing
- Data
- Data Analytics
- Data Engineering
- Data Governance
- Delta Lake
- Delta Sharing
- ETL
- Identity Management
- Lakehouse
- Machine Learning
- MLflow
- Model Serving
- Security
- SQL
- Unity Catalog
- Vector Search
- Visualize
url: https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/apis.yml
use_cases:
- description: Build and orchestrate ETL pipelines with Delta Live Tables and multi-task workflows.
  name: Data Engineering
- description: Run analytical SQL queries on lakehouse data with serverless SQL warehouses.
  name: Data Warehousing
- description: Train, track, and deploy ML models with MLflow experiment tracking and model registry.
  name: Machine Learning
- description: Process streaming data with structured streaming and serve results through online tables.
  name: Real-Time Analytics
- description: Govern data assets across the organization with Unity Catalog metadata management.
  name: Data Governance
---
