---
api_count: 3
api_specs:
- filename: aws-redshift-openapi.json
  format: json
  label: Amazon Redshift API
  slug: amazon-redshift-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/openapi/aws-redshift-openapi.json
- filename: aws-redshift-data-openapi.json
  format: json
  label: Amazon Redshift Data API
  slug: amazon-redshift-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/openapi/aws-redshift-data-openapi.json
apis:
- description: The Amazon Redshift API provides programmatic access to create and manage Amazon Redshift clusters and their associated resources including snapshots, parameter groups, subnet groups, and reserved nod
  name: Amazon Redshift API
  slug: amazon-redshift-api
- description: The Amazon Redshift Data API enables you to run SQL statements without managing connections via a secure HTTP endpoint. It supports both synchronous and asynchronous SQL execution against Redshift clu
  name: Amazon Redshift Data API
  slug: amazon-redshift-data-api
- description: API for Amazon Redshift Serverless, which makes it easy to run analytics workloads without managing data warehouse infrastructure. Automatically provisions and scales data warehouse capacity on demand
  name: Amazon Redshift Serverless API
  slug: amazon-redshift-serverless-api
capabilities:
- description: Workflow capability for managing Amazon Redshift clusters and executing SQL queries for data analytics.
  name: Amazon Redshift Data Warehouse Workflow
  slug: data-warehouse-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/redshift/
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
  type: Blog
  url: https://aws.amazon.com/blogs/big-data/category/database/amazon-redshift/
- title: ''
  type: ChangeLog
  url: https://aws.amazon.com/releasenotes/Amazon-Redshift/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Pricing
  url: https://aws.amazon.com/redshift/pricing/
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/redshift/latest/gsg/getting-started.html
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/redshift/
- title: ''
  type: SpectralRules
  url: rules/aws-redshift-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-redshift-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-warehouse-workflow.yaml
created: '2024-01-01'
description: Amazon Redshift is a fast, fully managed, petabyte-scale data warehouse service that makes it simple and cost-effective to analyze all your data using standard SQL and existing Business Intelligence tools.
features:
- description: Store and query petabytes of structured and semi-structured data with columnar storage.
  name: Petabyte-Scale Storage
- description: Query data using standard SQL and connect with existing BI tools via JDBC/ODBC.
  name: Standard SQL Support
- description: Distribute SQL operations across multiple nodes for high-performance query execution.
  name: Massively Parallel Processing
- description: Store data in columnar format for efficient analytical query performance and compression.
  name: Columnar Storage
- description: Automated and manual snapshots for point-in-time recovery of your cluster data.
  name: Automated Snapshots
- description: Share live data across Redshift clusters and accounts without copying data.
  name: Data Sharing
- description: Run Amazon Redshift ML to create, train, and deploy machine learning models using SQL.
  name: ML Integration
- description: Run analytics workloads without managing cluster infrastructure with Redshift Serverless.
  name: Serverless Mode
- description: Query data across operational databases, data warehouses, and data lakes.
  name: Federated Query
- description: Advanced Query Accelerator for up to 10x faster query performance using distributed hardware-accelerated cache.
  name: AQUA
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Load data from S3 and query data lake files using Redshift Spectrum.
  name: Amazon S3
- description: Catalog and ETL data into Redshift from various data sources.
  name: Amazon Glue
- description: Connect QuickSight for BI visualization directly to Redshift.
  name: Amazon QuickSight
- description: Manage fine-grained data access controls across Redshift and S3.
  name: AWS Lake Formation
- description: Export training data and import ML model results from SageMaker.
  name: Amazon SageMaker
- description: Transform data in Redshift using dbt data transformation framework.
  name: dbt
- description: Connect Tableau via JDBC/ODBC for interactive data visualization.
  name: Tableau
jsonld:
- class_count: 240
  name: Aws Redshift Redshift Context
  property_count: 379
  slug: aws-redshift-redshift-context
- class_count: 28
  name: Aws Redshift Redshift Data Context
  property_count: 80
  slug: aws-redshift-redshift-data-context
layout: provider
modified: '2026-04-19'
name: AWS Redshift
rules:
- name: AWS Redshift API Rules
  rule_count: 11
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 6
  slug: aws-redshift-spectral-rules
skills: []
slug: aws-redshift
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aws-redshift\nname: AWS Redshift\ndescription: >-\n  Amazon Redshift is a fast, fully managed, petabyte-scale data warehouse\n  service that makes it simple and cost-effective to analyze all your data using\n  standard SQL and existing Business Intelligence tools.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Big Data\n  - Cloud Database\n  - Data Warehouse\n  - SQL\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-redshift:amazon-redshift-api\n    name: Amazon Redshift API\n    description: >-\n      The Amazon Redshift API provides programmatic access to create and manage\n      Amazon Redshift clusters and their associated resources including\n      snapshots, parameter groups, subnet groups, and reserved nodes.\n    humanURL: https://aws.amazon.com/redshift/\n\
  \    baseURL: https://redshift.{region}.amazonaws.com\n    tags:\n      - Clusters\n      - Data Warehouse\n      - Snapshots\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/redshift/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/aws-redshift-openapi.json\n  - aid: aws-redshift:amazon-redshift-data-api\n    name: Amazon Redshift Data API\n    description: >-\n      The Amazon Redshift Data API enables you to run SQL statements without\n      managing connections via a secure HTTP endpoint. It supports both\n      synchronous and asynchronous SQL execution against Redshift clusters and\n      Redshift Serverless workgroups.\n    humanURL: https://docs.aws.amazon.com/redshift/latest/mgmt/data-api.html\n    baseURL: https://redshift-data.{region}.amazonaws.com\n    tags:\n      - Data Access\n      - Serverless\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/redshift-data/latest/APIReference/Welcome.html\n\
  \      - type: OpenAPI\n        url: openapi/aws-redshift-data-openapi.json\n  - aid: aws-redshift:amazon-redshift-serverless-api\n    name: Amazon Redshift Serverless API\n    description: >-\n      API for Amazon Redshift Serverless, which makes it easy to run analytics\n      workloads without managing data warehouse infrastructure. Automatically\n      provisions and scales data warehouse capacity on demand.\n    humanURL: https://aws.amazon.com/redshift/redshift-serverless/\n    baseURL: https://redshift-serverless.{region}.amazonaws.com\n    tags:\n      - Analytics\n      - Auto-Scaling\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/redshift-serverless/latest/APIReference/Welcome.html\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/redshift/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url:\
  \ https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/big-data/category/database/amazon-redshift/\n  - type: ChangeLog\n    url: https://aws.amazon.com/releasenotes/Amazon-Redshift/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Pricing\n    url: https://aws.amazon.com/redshift/pricing/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/redshift/latest/gsg/getting-started.html\n  - type: Documentation\n    url: https://docs.aws.amazon.com/redshift/\n  - type: SpectralRules\n    url: rules/aws-redshift-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/aws-redshift-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/data-warehouse-workflow.yaml\n  - type: Features\n    data:\n      - name: Petabyte-Scale Storage\n        description: Store and query petabytes of structured and semi-structured data with columnar storage.\n      - name: Standard SQL Support\n        description:\
  \ Query data using standard SQL and connect with existing BI tools via JDBC/ODBC.\n      - name: Massively Parallel Processing\n        description: Distribute SQL operations across multiple nodes for high-performance query execution.\n      - name: Columnar Storage\n        description: Store data in columnar format for efficient analytical query performance and compression.\n      - name: Automated Snapshots\n        description: Automated and manual snapshots for point-in-time recovery of your cluster data.\n      - name: Data Sharing\n        description: Share live data across Redshift clusters and accounts without copying data.\n      - name: ML Integration\n        description: Run Amazon Redshift ML to create, train, and deploy machine learning models using SQL.\n      - name: Serverless Mode\n        description: Run analytics workloads without managing cluster infrastructure with Redshift Serverless.\n      - name: Federated Query\n        description: Query data across operational\
  \ databases, data warehouses, and data lakes.\n      - name: AQUA\n        description: Advanced Query Accelerator for up to 10x faster query performance using distributed hardware-accelerated cache.\n  - type: UseCases\n    data:\n      - name: Business Intelligence\n        description: Power BI dashboards and reports with fast analytical queries over large datasets.\n      - name: Log Analytics\n        description: Analyze application logs and clickstream data for operational insights.\n      - name: Financial Analytics\n        description: Process financial transactions and generate regulatory reports over historical data.\n      - name: Data Lake Analytics\n        description: Query data in Amazon S3 data lakes using Redshift Spectrum without loading.\n      - name: Machine Learning\n        description: Build and deploy ML models directly within the warehouse using SQL with Redshift ML.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: Load data\
  \ from S3 and query data lake files using Redshift Spectrum.\n      - name: Amazon Glue\n        description: Catalog and ETL data into Redshift from various data sources.\n      - name: Amazon QuickSight\n        description: Connect QuickSight for BI visualization directly to Redshift.\n      - name: AWS Lake Formation\n        description: Manage fine-grained data access controls across Redshift and S3.\n      - name: Amazon SageMaker\n        description: Export training data and import ML model results from SageMaker.\n      - name: dbt\n        description: Transform data in Redshift using dbt data transformation framework.\n      - name: Tableau\n        description: Connect Tableau via JDBC/ODBC for interactive data visualization.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/apis.yml
tags:
- Analytics
- Big Data
- Cloud Database
- Data Warehouse
- SQL
url: https://raw.githubusercontent.com/api-evangelist/aws-redshift/refs/heads/main/apis.yml
use_cases:
- description: Power BI dashboards and reports with fast analytical queries over large datasets.
  name: Business Intelligence
- description: Analyze application logs and clickstream data for operational insights.
  name: Log Analytics
- description: Process financial transactions and generate regulatory reports over historical data.
  name: Financial Analytics
- description: Query data in Amazon S3 data lakes using Redshift Spectrum without loading.
  name: Data Lake Analytics
- description: Build and deploy ML models directly within the warehouse using SQL with Redshift ML.
  name: Machine Learning
---
