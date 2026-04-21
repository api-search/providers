---
api_count: 3
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
