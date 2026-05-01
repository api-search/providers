---
api_count: 1
api_specs:
- filename: airbyte-openapi.yml
  format: yaml
  label: Airbyte
  slug: airbyte
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/openapi/airbyte-openapi.yml
apis:
- description: Airbyte is an open-source data integration platform that enables businesses to move and consolidate data from various sources into centralized destinations. The Airbyte API provides programmatic contr
  name: Airbyte
  slug: airbyte
capabilities:
- description: Unified workflow capability for managing Airbyte data integration pipelines — sources, destinations, connections, and sync jobs. Used by data engineers and platform teams.
  name: Airbyte Data Pipeline Management
  slug: data-pipeline-management
common:
- title: ''
  type: Portal
  url: https://airbyte.com
- title: ''
  type: Console
  url: https://cloud.airbyte.io
- title: ''
  type: SignUp
  url: https://cloud.airbyte.io
- title: ''
  type: Pricing
  url: https://airbyte.com/pricing
- title: ''
  type: GitHubOrganization
  url: https://github.com/airbytehq
- title: ''
  type: GitHubRepository
  url: https://github.com/airbytehq/airbyte
- title: ''
  type: GettingStarted
  url: https://docs.airbyte.com
- title: ''
  type: StatusPage
  url: https://status.airbyte.com
- title: ''
  type: Blog
  url: https://airbyte.com/blog
- title: ''
  type: Tutorials
  url: https://airbyte.com/tutorials
- title: ''
  type: Support
  url: https://support.airbyte.com/hc/en-us
- title: ''
  type: PrivacyPolicy
  url: https://airbyte.com/company/privacy-policy
- title: ''
  type: TermsOfService
  url: https://airbyte.com/company/terms
- title: ''
  type: Newsletter
  url: https://airbyte.com/community/newsletter
- title: ''
  type: ChangeLog
  url: https://docs.airbyte.com/category/release-notes/
- title: ''
  type: RoadMap
  url: https://github.com/orgs/airbytehq/projects/37/views/1
- title: PyAirbyte
  type: SDK
  url: https://github.com/airbytehq/PyAirbyte
- title: Airbyte CLI (abctl)
  type: CLI
  url: https://github.com/airbytehq/abctl
- title: Python Connector CDK
  type: SDK
  url: https://github.com/airbytehq/airbyte-python-cdk
- title: Agent SDK
  type: SDK
  url: https://github.com/airbytehq/airbyte-agent-sdk
- title: Helm Chart
  type: SDK
  url: https://artifacthub.io/packages/helm/airbyte/airbyte
- title: Airbyte Spectral Rules
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/rules/airbyte-spectral-rules.yml
- title: Data Pipeline Management
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/capabilities/data-pipeline-management.yaml
- title: Airbyte Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/vocabulary/airbyte-vocabulary.yaml
created: '2025-01-08'
description: Airbyte is an open-source data integration platform that enables businesses to easily and efficiently move and consolidate their data from various sources into one centralized location. With Airbyte, organizations can seamlessly connect and synchronize data from sources such as databases, APIs, and other third-party applications, allowing for real-time insights and analysis. Airbyte offers both self-hosted and cloud-hosted options, with a catalog of hundreds of pre-built connectors.
features:
- description: Connect and sync data from hundreds of sources to destinations.
  name: Data Integration
- description: Self-host Airbyte on your own infrastructure with full access to source code.
  name: Open Source
- description: Managed cloud offering with 30-day free trial at cloud.airbyte.io.
  name: Cloud Hosted
- description: Pre-built connectors for databases, APIs, SaaS tools, and data warehouses.
  name: Connector Catalog
- description: Build custom connectors using the Python CDK or low-code/no-code builder.
  name: Custom Connectors
- description: Airbyte Agent SDK provides AI agents with reliable, permission-aware access to data sources.
  name: AI Agent Integration
- description: Manage Airbyte infrastructure and connections as code with Terraform.
  name: Terraform Support
- description: Model Context Protocol support for integration with AI tools.
  name: MCP Servers
- description: Embed Airbyte connector UI into your own product for white-label data integration.
  name: Embedded Widget
- description: Python library for using Airbyte connectors programmatically in Python environments.
  name: PyAirbyte
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Orchestrate Airbyte syncs from Airflow DAGs.
  name: Apache Airflow
- description: Transform data after Airbyte syncs with dbt models.
  name: dbt
- description: Load data into Snowflake data warehouse.
  name: Snowflake
- description: Sync data to Google BigQuery.
  name: BigQuery
- description: Load data into Amazon Redshift.
  name: Redshift
- description: Ingest data into Databricks lakehouse.
  name: Databricks
- description: Infrastructure-as-code support for Airbyte resources.
  name: Terraform
- description: Deploy Airbyte on Kubernetes using official Helm charts.
  name: Kubernetes / Helm
jsonld:
- class_count: 108
  name: Airbyte Context
  property_count: 129
  slug: airbyte-context
layout: provider
modified: '2026-04-19'
name: Airbyte
rules:
- name: Airbyte API Rules
  rule_count: 28
  severity_counts:
    error: 9
    hint: 0
    info: 7
    warn: 12
  slug: airbyte-spectral-rules
skills: []
slug: airbyte
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: airbyte\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/apis.yml\napis:\n- aid: airbyte:airbyte\n  name: Airbyte\n  tags:\n  - Data Integration\n  - ETL\n  - ELT\n  - Open Source\n  - Data Pipeline\n  - Connectors\n  humanURL: https://airbyte.com\n  properties:\n  - url: https://docs.airbyte.com\n    type: Documentation\n  - url: https://reference.airbyte.com/reference/getting-started\n    type: APIReference\n  - url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/openapi/airbyte-openapi.yml\n    type: OpenAPI\n  - url: https://docs.airbyte.com/api-documentation\n    type: Authentication\n  - url: https://github.com/airbytehq/airbyte-api-python-sdk\n    type: SDK\n    title: Python SDK\n  - url: https://github.com/airbytehq/airbyte-api-java-sdk\n    type: SDK\n    title: Java SDK\n  - url: https://pypi.org/project/airbyte-api/\n    type: SDK\n    title: Python SDK PyPI\n  - url: https://github.com/airbytehq/terraform-provider-airbyte\n\
  \    type: SDK\n    title: Terraform Provider\n  description: >-\n    Airbyte is an open-source data integration platform that enables businesses to move and consolidate data from various sources into centralized destinations. The Airbyte API provides programmatic control\n    over sources, destinations, connections, jobs, workspaces, and organizations for both Airbyte Cloud and self-managed deployments.\n  baseURL: https://api.airbyte.com/v1\nname: Airbyte\ntags:\n- Data Integration\n- ETL\n- ELT\n- Open Source\n- Data Pipeline\n- Connectors\n- Data\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n- url: https://airbyte.com\n  type: Portal\n- url: https://cloud.airbyte.io\n  type: Console\n- url: https://cloud.airbyte.io\n  type: SignUp\n- url: https://airbyte.com/pricing\n  type: Pricing\n- url: https://github.com/airbytehq\n  type: GitHubOrganization\n- url: https://github.com/airbytehq/airbyte\n  type: GitHubRepository\n\
  - url: https://docs.airbyte.com\n  type: GettingStarted\n- url: https://status.airbyte.com\n  type: StatusPage\n- url: https://airbyte.com/blog\n  type: Blog\n- url: https://airbyte.com/tutorials\n  type: Tutorials\n- url: https://support.airbyte.com/hc/en-us\n  type: Support\n- url: https://airbyte.com/company/privacy-policy\n  type: PrivacyPolicy\n- url: https://airbyte.com/company/terms\n  type: TermsOfService\n- url: https://airbyte.com/community/newsletter\n  type: Newsletter\n- url: https://docs.airbyte.com/category/release-notes/\n  type: ChangeLog\n- url: https://github.com/orgs/airbytehq/projects/37/views/1\n  type: RoadMap\n- url: https://airbyte.com/connectors\n  type: Integrations\n- url: https://github.com/airbytehq/PyAirbyte\n  type: SDK\n  title: PyAirbyte\n- url: https://github.com/airbytehq/abctl\n  type: CLI\n  title: Airbyte CLI (abctl)\n- url: https://github.com/airbytehq/airbyte-python-cdk\n  type: SDK\n  title: Python Connector CDK\n- url: https://github.com/airbytehq/airbyte-agent-sdk\n\
  \  type: SDK\n  title: Agent SDK\n- url: https://artifacthub.io/packages/helm/airbyte/airbyte\n  type: SDK\n  title: Helm Chart\n- type: Features\n  data:\n  - name: Data Integration\n    description: Connect and sync data from hundreds of sources to destinations.\n  - name: Open Source\n    description: Self-host Airbyte on your own infrastructure with full access to source code.\n  - name: Cloud Hosted\n    description: Managed cloud offering with 30-day free trial at cloud.airbyte.io.\n  - name: Connector Catalog\n    description: Pre-built connectors for databases, APIs, SaaS tools, and data warehouses.\n  - name: Custom Connectors\n    description: Build custom connectors using the Python CDK or low-code/no-code builder.\n  - name: AI Agent Integration\n    description: Airbyte Agent SDK provides AI agents with reliable, permission-aware access to data sources.\n  - name: Terraform Support\n    description: Manage Airbyte infrastructure and connections as code with Terraform.\n  -\
  \ name: MCP Servers\n    description: Model Context Protocol support for integration with AI tools.\n  - name: Embedded Widget\n    description: Embed Airbyte connector UI into your own product for white-label data integration.\n  - name: PyAirbyte\n    description: Python library for using Airbyte connectors programmatically in Python environments.\n- type: UseCases\n  data:\n  - name: Data Warehouse Loading\n    description: Sync operational data to Snowflake, BigQuery, Redshift, or other warehouses.\n  - name: Data Lake Ingestion\n    description: Land raw data into S3, GCS, or Azure data lakes.\n  - name: Analytics Pipelines\n    description: Build ELT pipelines for business intelligence and analytics.\n  - name: AI/ML Data Preparation\n    description: Aggregate training data from multiple sources for machine learning.\n  - name: API Data Sync\n    description: Pull data from SaaS APIs (Salesforce, HubSpot, Stripe) into your data stack.\n  - name: Database Replication\n    description:\
  \ Replicate relational databases with CDC change data capture.\n  - name: Vector Database Population\n    description: Load and embed data into vector stores for AI search and retrieval.\n- type: Integrations\n  data:\n  - name: Apache Airflow\n    description: Orchestrate Airbyte syncs from Airflow DAGs.\n  - name: dbt\n    description: Transform data after Airbyte syncs with dbt models.\n  - name: Snowflake\n    description: Load data into Snowflake data warehouse.\n  - name: BigQuery\n    description: Sync data to Google BigQuery.\n  - name: Redshift\n    description: Load data into Amazon Redshift.\n  - name: Databricks\n    description: Ingest data into Databricks lakehouse.\n  - name: Terraform\n    description: Infrastructure-as-code support for Airbyte resources.\n  - name: Kubernetes / Helm\n    description: Deploy Airbyte on Kubernetes using official Helm charts.\n- url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/rules/airbyte-spectral-rules.yml\n\
  \  type: SpectralRules\n  title: Airbyte Spectral Rules\n- url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/capabilities/data-pipeline-management.yaml\n  type: NaftikoCapability\n  title: Data Pipeline Management\n- url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/vocabulary/airbyte-vocabulary.yaml\n  type: Vocabulary\n  title: Airbyte Vocabulary\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  Airbyte is an open-source data integration platform that enables businesses to easily and efficiently move and consolidate their data from various sources into one centralized location. With Airbyte,\n  organizations can seamlessly connect and synchronize data from sources such as databases, APIs, and other third-party applications, allowing for real-time insights and analysis. Airbyte offers both self-hosted\n  and cloud-hosted options, with a catalog of hundreds of pre-built connectors.\nmaintainers:\n\
  - FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/apis.yml
tags:
- Data Integration
- ETL
- ELT
- Open Source
- Data Pipeline
- Connectors
- Data
url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/apis.yml
use_cases:
- description: Sync operational data to Snowflake, BigQuery, Redshift, or other warehouses.
  name: Data Warehouse Loading
- description: Land raw data into S3, GCS, or Azure data lakes.
  name: Data Lake Ingestion
- description: Build ELT pipelines for business intelligence and analytics.
  name: Analytics Pipelines
- description: Aggregate training data from multiple sources for machine learning.
  name: AI/ML Data Preparation
- description: Pull data from SaaS APIs (Salesforce, HubSpot, Stripe) into your data stack.
  name: API Data Sync
- description: Replicate relational databases with CDC change data capture.
  name: Database Replication
- description: Load and embed data into vector stores for AI search and retrieval.
  name: Vector Database Population
---
