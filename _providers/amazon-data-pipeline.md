---
api_count: 1
api_specs:
- filename: amazon-data-pipeline-openapi.yml
  format: yaml
  label: AWS Data Pipeline API
  slug: aws-data-pipeline-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/openapi/amazon-data-pipeline-openapi.yml
apis:
- description: The AWS Data Pipeline API provides a web service for processing and moving data between different AWS compute and storage services as well as on-premises data sources at specified intervals. The API a
  name: AWS Data Pipeline API
  slug: aws-data-pipeline-api
capabilities:
- description: ''
  name: Etl Pipeline Operations
  slug: etl-pipeline-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/datapipeline/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/datapipeline/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/datapipeline/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/datapipeline/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-data-pipeline-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-data-pipeline-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/etl-pipeline-operations.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/data-pipeline.yaml
created: '2024-01-15'
description: AWS Data Pipeline is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals. With AWS Data Pipeline, you can regularly access your data where it is stored, transform and process it at scale, and efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR. It supports data-driven workflows with retry, failure handling, and scheduling capabilities.
features:
- description: Define complex data processing workflows with activities, data nodes, schedules, and preconditions using a declarative pipeline definition.
  name: Data-Driven Workflows
- description: Move and transform data between Amazon S3, Amazon RDS, Amazon DynamoDB, Amazon Redshift, and Amazon EMR in a single pipeline.
  name: Multi-Service Integration
- description: Schedule pipeline runs at fixed intervals (hourly, daily, weekly) or trigger them based on data availability preconditions.
  name: Flexible Scheduling
- description: Configure automatic retries for failed activities with configurable retry intervals, timeout settings, and failure notifications.
  name: Automated Retry and Failure Handling
- description: Process data from on-premises databases and file systems using the Data Pipeline Task Runner agent installed locally.
  name: On-Premises Data Support
- description: Launch and manage Amazon EMR clusters as pipeline resources to run Hive, Pig, and MapReduce jobs as part of data workflows.
  name: EMR Integration
- description: Manage active and latest pipeline definition versions, enabling updates to running pipelines without disrupting current execution.
  name: Pipeline Versioning
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary data node type for reading input data and writing output data in pipeline ETL activities using S3DataNode.
  name: Amazon S3
- description: Managed Hadoop/Spark cluster resource for running large-scale data processing activities including Hive, Pig, and MapReduce jobs.
  name: Amazon EMR
- description: Relational database data node for SQL-based data extraction and loading between RDS instances and S3 or Redshift.
  name: Amazon RDS
- description: NoSQL data node for importing and exporting DynamoDB table data in pipeline activities for batch processing workflows.
  name: Amazon DynamoDB
- description: Data warehouse target for loading processed pipeline output data for business intelligence and analytics queries.
  name: Amazon Redshift
- description: Modern alternative managed ETL service that can complement or replace Data Pipeline for serverless data transformation workflows.
  name: AWS Glue
- description: Monitor pipeline execution status, set up alarms for pipeline failures, and track activity completion metrics.
  name: Amazon CloudWatch
jsonld:
- class_count: 0
  name: Amazon Data Pipeline Context
  property_count: 30
  slug: amazon-data-pipeline-context
layout: provider
modified: '2026-04-19'
name: Amazon Data Pipeline
rules:
- name: Amazon Data Pipeline API Rules
  rule_count: 22
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 5
  slug: amazon-data-pipeline-spectral-rules
skills: []
slug: amazon-data-pipeline
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-data-pipeline\nname: Amazon Data Pipeline\ndescription: >-\n  AWS Data Pipeline is a web service that helps you reliably process and move\n  data between different AWS compute and storage services, as well as\n  on-premises data sources, at specified intervals. With AWS Data Pipeline, you\n  can regularly access your data where it is stored, transform and process it at\n  scale, and efficiently transfer the results to AWS services such as Amazon S3,\n  Amazon RDS, Amazon DynamoDB, and Amazon EMR. It supports data-driven workflows\n  with retry, failure handling, and scheduling capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Data Processing\n  - ETL\n  - Workflows\n  - Data Pipeline\n  - Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: amazon-data-pipeline:aws-data-pipeline-api\n    name: AWS Data Pipeline API\n    description: >-\n      The AWS Data Pipeline API provides a web service for processing and moving\n      data between different AWS compute and storage services as well as\n      on-premises data sources at specified intervals. The API allows you to\n      create pipeline definitions, schedule data transformations, configure retry\n      and failure handling logic, and monitor pipeline execution across Amazon S3,\n      Amazon RDS, Amazon DynamoDB, and Amazon EMR.\n    humanURL: https://aws.amazon.com/datapipeline/\n    baseURL: https://datapipeline.amazonaws.com\n    tags:\n      - AWS\n      - Data Processing\n      - ETL\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/datapipeline/\n      - type: OpenAPI\n        url: openapi/amazon-data-pipeline-openapi.yml\n      - type: Pricing\n        url: https://aws.amazon.com/datapipeline/pricing/\n\
  \      - type: GettingStarted\n        url: https://aws.amazon.com/datapipeline/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/datapipeline/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/datapipeline/latest/APIReference/\n      - type: JSONSchema\n        url: json-schema/pipeline-object-schema.json\n      - type: JSONSchema\n        url: json-schema/pipeline-description-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-data-pipeline-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/datapipeline/\n  - type: DeveloperPortal\n    url: https://aws.amazon.com/datapipeline/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/datapipeline/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n\
  \  - type: Console\n    url: https://console.aws.amazon.com/datapipeline/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-data-pipeline-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-data-pipeline-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/etl-pipeline-operations.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/data-pipeline.yaml\n  - type: Features\n    data:\n      - name: Data-Driven Workflows\n        description: >-\n          Define complex data processing workflows with activities, data nodes,\n          schedules, and preconditions using a declarative pipeline definition.\n      - name: Multi-Service Integration\n        description: >-\n          Move\
  \ and transform data between Amazon S3, Amazon RDS, Amazon\n          DynamoDB, Amazon Redshift, and Amazon EMR in a single pipeline.\n      - name: Flexible Scheduling\n        description: >-\n          Schedule pipeline runs at fixed intervals (hourly, daily, weekly) or\n          trigger them based on data availability preconditions.\n      - name: Automated Retry and Failure Handling\n        description: >-\n          Configure automatic retries for failed activities with configurable\n          retry intervals, timeout settings, and failure notifications.\n      - name: On-Premises Data Support\n        description: >-\n          Process data from on-premises databases and file systems using the\n          Data Pipeline Task Runner agent installed locally.\n      - name: EMR Integration\n        description: >-\n          Launch and manage Amazon EMR clusters as pipeline resources to run\n          Hive, Pig, and MapReduce jobs as part of data workflows.\n      - name: Pipeline\
  \ Versioning\n        description: >-\n          Manage active and latest pipeline definition versions, enabling\n          updates to running pipelines without disrupting current execution.\n  - type: UseCases\n    data:\n      - name: Daily ETL Workflows\n        description: >-\n          Schedule daily extraction, transformation, and loading of data from\n          relational databases into S3 or Redshift for analytics processing.\n      - name: Log Processing Pipelines\n        description: >-\n          Process application and server log files from S3 using EMR activities\n          to generate aggregated reports and analytics datasets.\n      - name: Database Migration\n        description: >-\n          Migrate data between on-premises databases and AWS managed database\n          services using scheduled pipeline activities.\n      - name: Data Lake Ingestion\n        description: >-\n          Automate the ingestion and transformation of raw data into structured\n          formats\
  \ in S3 data lakes for downstream analytics.\n      - name: Cross-Region Data Replication\n        description: >-\n          Replicate DynamoDB tables or S3 data across AWS regions using\n          scheduled pipeline copy activities for disaster recovery.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: >-\n          Primary data node type for reading input data and writing output data\n          in pipeline ETL activities using S3DataNode.\n      - name: Amazon EMR\n        description: >-\n          Managed Hadoop/Spark cluster resource for running large-scale data\n          processing activities including Hive, Pig, and MapReduce jobs.\n      - name: Amazon RDS\n        description: >-\n          Relational database data node for SQL-based data extraction and\n          loading between RDS instances and S3 or Redshift.\n      - name: Amazon DynamoDB\n        description: >-\n          NoSQL data node for importing and exporting DynamoDB table data\
  \ in\n          pipeline activities for batch processing workflows.\n      - name: Amazon Redshift\n        description: >-\n          Data warehouse target for loading processed pipeline output data\n          for business intelligence and analytics queries.\n      - name: AWS Glue\n        description: >-\n          Modern alternative managed ETL service that can complement or\n          replace Data Pipeline for serverless data transformation workflows.\n      - name: Amazon CloudWatch\n        description: >-\n          Monitor pipeline execution status, set up alarms for pipeline\n          failures, and track activity completion metrics.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/apis.yml
tags:
- AWS
- Data Processing
- ETL
- Workflows
- Data Pipeline
- Automation
url: https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/apis.yml
use_cases:
- description: Schedule daily extraction, transformation, and loading of data from relational databases into S3 or Redshift for analytics processing.
  name: Daily ETL Workflows
- description: Process application and server log files from S3 using EMR activities to generate aggregated reports and analytics datasets.
  name: Log Processing Pipelines
- description: Migrate data between on-premises databases and AWS managed database services using scheduled pipeline activities.
  name: Database Migration
- description: Automate the ingestion and transformation of raw data into structured formats in S3 data lakes for downstream analytics.
  name: Data Lake Ingestion
- description: Replicate DynamoDB tables or S3 data across AWS regions using scheduled pipeline copy activities for disaster recovery.
  name: Cross-Region Data Replication
---
