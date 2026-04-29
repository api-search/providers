---
api_count: 1
api_specs:
- filename: acceldata-adoc-api.yaml
  format: yaml
  label: Acceldata Data Observability Cloud API
  slug: adoc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/acceldata/refs/heads/main/openapi/acceldata-adoc-api.yaml
apis:
- description: The ADOC API provides programmatic access to data observability features including alerts, data quality rules, pipeline monitoring, data lineage, users, groups, roles, and permissions within the Accel
  name: Acceldata Data Observability Cloud API
  slug: adoc-api
capabilities:
- description: ''
  name: Data Observability
  slug: data-observability
common:
- title: ''
  type: Website
  url: https://www.acceldata.io/
- title: ''
  type: Portal
  url: https://accounts.acceldata.app/login
- title: ''
  type: Documentation
  url: https://docs.acceldata.io/
- title: ''
  type: GettingStarted
  url: https://docs.acceldata.io/api/introduction
- title: ''
  type: Pricing
  url: https://www.acceldata.io/pricing
- title: ''
  type: Blog
  url: https://www.acceldata.io/blog
- title: ''
  type: PrivacyPolicy
  url: https://www.acceldata.io/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.acceldata.io/terms-of-use
- title: ''
  type: SpectralRules
  url: rules/acceldata-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-observability.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/acceldata-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/acceldata-adoc-api-context.jsonld
created: '2025-02-24'
description: Acceldata is an agentic data management platform that helps enterprises monitor, govern, and optimize data across cloud, lakehouse, and hybrid environments. The platform combines AI-powered agents with data observability to proactively detect issues, trace root causes, and automate remediation workflows. Key products include ADM (Agentic Data Management), ADOC (Acceldata Data Observability Cloud), Pulse for Hadoop environments, and Agent Studio for building custom AI agents. It supports integrations with Snowflake, Databricks, AWS, GCP, Azure, and Hadoop.
features:
- description: AI-powered agents that proactively detect issues, trace root causes, and automate data quality remediation workflows
  name: Agentic Data Management
- description: Multi-variate anomaly detection, column-level profiling, and proactive monitoring across all data platforms
  name: Data Quality Monitoring
- description: End-to-end data lineage visualization with schema change management and column-level impact analysis
  name: Data Lineage
- description: Real-time SLA monitoring, bottleneck identification, and root cause analysis for data pipelines
  name: Pipeline Health Monitoring
- description: Visibility into data spending, budget optimization, chargebacks, and cost forecasting across cloud environments
  name: Data Cost Management
- description: Natural language interface with contextual memory for querying data quality and observability insights
  name: Business Notebook
- description: Low-code environment for building and deploying custom AI agents for data management workflows
  name: Agent Studio
- description: Bring Your Own Large Language Model for enterprise-controlled AI inference within data operations
  name: BYOLLM Support
- description: Exabyte-scale, AI-aware processing engine supporting cloud hyperscalers and on-premises deployments
  name: xLake Reasoning Engine
image: /assets/icons/acceldata.png
integrations:
- description: Native integration for monitoring Snowflake data quality, query performance, and cost optimization
  name: Snowflake
- description: Integration for observing Databricks lakehouse pipelines, job health, and data quality
  name: Databricks
- description: Support for AWS data services including S3, Redshift, Glue, EMR, and Athena
  name: AWS
- description: Integration with GCP data services including BigQuery, Dataflow, and Cloud Storage
  name: Google Cloud Platform
- description: Integration with Azure Synapse, Azure Data Factory, and Azure Data Lake Storage
  name: Microsoft Azure
- description: Dedicated Pulse product for Hadoop ecosystem monitoring including HDFS, YARN, Hive, and Spark
  name: Hadoop / Apache
jsonld:
- class_count: 55
  name: Acceldata Adoc Api Context
  property_count: 5
  slug: acceldata-adoc-api-context
layout: provider
modified: '2026-04-19'
name: Acceldata
rules:
- name: Acceldata API Rules
  rule_count: 25
  severity_counts:
    error: 10
    hint: 0
    info: 3
    warn: 12
  slug: acceldata-spectral-rules
skills: []
slug: acceldata
solutions: []
source_filename: apis.yml
source_yaml: "aid: acceldata\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/acceldata/refs/heads/main/apis.yml\nname: Acceldata\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AI Agents\n- Data Management\n- Data Observability\n- Data Pipeline\n- Data Quality\n- Intelligence\n- Observability\ndescription: >-\n  Acceldata is an agentic data management platform that helps enterprises\n  monitor, govern, and optimize data across cloud, lakehouse, and hybrid\n  environments. The platform combines AI-powered agents with data observability\n  to proactively detect issues, trace root causes, and automate remediation\n  workflows. Key products include ADM (Agentic Data Management), ADOC\n  (Acceldata Data Observability Cloud), Pulse for Hadoop environments, and\n  Agent Studio for building custom AI agents. It supports integrations with\n  Snowflake, Databricks, AWS, GCP, Azure, and Hadoop.\ncreated: '2025-02-24'\nmodified: '2026-04-19'\n\
  specificationVersion: '0.19'\napis:\n- aid: acceldata:adoc-api\n  name: Acceldata Data Observability Cloud API\n  description: >-\n    The ADOC API provides programmatic access to data observability features\n    including alerts, data quality rules, pipeline monitoring, data lineage,\n    users, groups, roles, and permissions within the Acceldata Data\n    Observability Cloud platform.\n  humanURL: https://docs.acceldata.io/api/introduction\n  baseURL: https://api.acceldata.app/v1\n  tags:\n  - Data Observability\n  - Data Quality\n  - Alerts\n  - Data Pipeline\n  properties:\n  - url: https://docs.acceldata.io/api/introduction\n    type: Documentation\n  - url: https://docs.acceldata.io/api/authentication\n    type: Authentication\n  - url: openapi/acceldata-adoc-api.yaml\n    type: OpenAPI\n  - url: json-schema/adoc-api-alert-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-alert-list-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-data-quality-rule-schema.json\n\
  \    type: JSONSchema\n  - url: json-schema/adoc-api-data-quality-rule-list-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-dataset-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-dataset-list-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-lineage-node-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-lineage-graph-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-pipeline-job-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-pipeline-job-list-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-user-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-user-list-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-role-schema.json\n    type: JSONSchema\n  - url: json-schema/adoc-api-role-list-schema.json\n    type: JSONSchema\n  - url: json-structure/adoc-api-alert-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-alert-list-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/adoc-api-data-quality-rule-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-data-quality-rule-list-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-dataset-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-dataset-list-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-lineage-node-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-lineage-graph-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-pipeline-job-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-pipeline-job-list-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-user-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-user-list-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-role-structure.json\n    type: JSONStructure\n  - url: json-structure/adoc-api-role-list-structure.json\n\
  \    type: JSONStructure\n  - url: examples/adoc-api-alert-example.json\n    type: Example\n  - url: examples/adoc-api-alert-list-example.json\n    type: Example\n  - url: examples/adoc-api-data-quality-rule-example.json\n    type: Example\n  - url: examples/adoc-api-dataset-example.json\n    type: Example\n  - url: examples/adoc-api-lineage-graph-example.json\n    type: Example\n  - url: examples/adoc-api-pipeline-job-example.json\n    type: Example\n  - url: examples/adoc-api-user-example.json\n    type: Example\n  - url: examples/adoc-api-role-example.json\n    type: Example\ncommon:\n- type: Website\n  url: https://www.acceldata.io/\n- type: Portal\n  url: https://accounts.acceldata.app/login\n- type: Documentation\n  url: https://docs.acceldata.io/\n- type: GettingStarted\n  url: https://docs.acceldata.io/api/introduction\n- type: Pricing\n  url: https://www.acceldata.io/pricing\n- type: Blog\n  url: https://www.acceldata.io/blog\n- type: PrivacyPolicy\n  url: https://www.acceldata.io/privacy-policy\n\
  - type: TermsOfService\n  url: https://www.acceldata.io/terms-of-use\n- type: Features\n  data:\n  - name: Agentic Data Management\n    description: AI-powered agents that proactively detect issues, trace root \n      causes, and automate data quality remediation workflows\n  - name: Data Quality Monitoring\n    description: Multi-variate anomaly detection, column-level profiling, and \n      proactive monitoring across all data platforms\n  - name: Data Lineage\n    description: End-to-end data lineage visualization with schema change \n      management and column-level impact analysis\n  - name: Pipeline Health Monitoring\n    description: Real-time SLA monitoring, bottleneck identification, and root \n      cause analysis for data pipelines\n  - name: Data Cost Management\n    description: Visibility into data spending, budget optimization, \n      chargebacks, and cost forecasting across cloud environments\n  - name: Business Notebook\n    description: Natural language interface with\
  \ contextual memory for querying \n      data quality and observability insights\n  - name: Agent Studio\n    description: Low-code environment for building and deploying custom AI \n      agents for data management workflows\n  - name: BYOLLM Support\n    description: Bring Your Own Large Language Model for enterprise-controlled \n      AI inference within data operations\n  - name: xLake Reasoning Engine\n    description: Exabyte-scale, AI-aware processing engine supporting cloud \n      hyperscalers and on-premises deployments\n- type: UseCases\n  data:\n  - name: Data Quality Assurance\n    description: Continuously monitor and automatically remediate data quality \n      issues across cloud and hybrid environments\n  - name: Cloud Migration Validation\n    description: Validate data completeness, consistency, and accuracy during \n      cloud migration projects\n  - name: AI and LLM Data Readiness\n    description: Ensure data pipelines produce clean, reliable, and AI-ready \n   \
  \   datasets for training and inference\n  - name: Cost Optimization and FinOps\n    description: Identify and reduce wasteful data pipeline and infrastructure \n      costs with granular usage analytics\n  - name: Data Reconciliation\n    description: Automatically detect and resolve discrepancies between source \n      and target systems across platforms\n  - name: Compliance and Data Governance\n    description: Track data lineage and access patterns to support regulatory \n      compliance and data governance programs\n- type: Integrations\n  data:\n  - name: Snowflake\n    description: Native integration for monitoring Snowflake data quality, query\n      performance, and cost optimization\n  - name: Databricks\n    description: Integration for observing Databricks lakehouse pipelines, job \n      health, and data quality\n  - name: AWS\n    description: Support for AWS data services including S3, Redshift, Glue, \n      EMR, and Athena\n  - name: Google Cloud Platform\n    description:\
  \ Integration with GCP data services including BigQuery, \n      Dataflow, and Cloud Storage\n  - name: Microsoft Azure\n    description: Integration with Azure Synapse, Azure Data Factory, and Azure \n      Data Lake Storage\n  - name: Hadoop / Apache\n    description: Dedicated Pulse product for Hadoop ecosystem monitoring \n      including HDFS, YARN, Hive, and Spark\n\n- url: rules/acceldata-spectral-rules.yml\n  type: SpectralRules\n- url: capabilities/data-observability.yaml\n  type: NaftikoCapability\n- url: vocabulary/acceldata-vocabulary.yaml\n  type: Vocabulary\n- url: json-ld/acceldata-adoc-api-context.jsonld\n  type: JSON-LD\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acceldata/refs/heads/main/apis.yml
tags:
- AI Agents
- Data Management
- Data Observability
- Data Pipeline
- Data Quality
- Intelligence
- Observability
url: https://raw.githubusercontent.com/api-evangelist/acceldata/refs/heads/main/apis.yml
use_cases:
- description: Continuously monitor and automatically remediate data quality issues across cloud and hybrid environments
  name: Data Quality Assurance
- description: Validate data completeness, consistency, and accuracy during cloud migration projects
  name: Cloud Migration Validation
- description: Ensure data pipelines produce clean, reliable, and AI-ready datasets for training and inference
  name: AI and LLM Data Readiness
- description: Identify and reduce wasteful data pipeline and infrastructure costs with granular usage analytics
  name: Cost Optimization and FinOps
- description: Automatically detect and resolve discrepancies between source and target systems across platforms
  name: Data Reconciliation
- description: Track data lineage and access patterns to support regulatory compliance and data governance programs
  name: Compliance and Data Governance
---
