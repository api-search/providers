---
api_count: 3
apis:
- description: The Amazon Redshift API for managing clusters, snapshots, and configurations.
  name: Amazon Redshift API
  slug: ''
- description: The Amazon Redshift Data API for running SQL statements without managing connections. Supports asynchronous execution with IAM and Secrets Manager authentication.
  name: Amazon Redshift Data API
  slug: ''
- description: The Amazon Redshift Serverless API for managing serverless data warehouse workgroups, namespaces, and capacity without provisioning clusters.
  name: Amazon Redshift Serverless API
  slug: ''
capabilities:
- description: Data warehouse analytics workflow combining Redshift Data API for SQL execution, statement management, and database metadata exploration. Used by data analysts and engineers for ad-hoc queries, ETL pr
  name: Amazon Redshift Data Warehouse Analytics
  slug: data-warehouse-analytics
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/big-data/category/database/amazon-redshift/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/redshift/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/redshift/getting-started/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/redshift/faqs/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/redshift/pricing/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/redshift/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
created: '2024-01-01'
description: Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.
features:
- description: Distributed query execution across multiple nodes for petabyte-scale analytics with sub-second response times.
  name: Massively Parallel Processing
- description: Auto-scaling compute capacity without cluster provisioning, paying only for compute used during queries.
  name: Serverless Data Warehouse
- description: Run SQL statements without managing database connections using IAM-based authentication and asynchronous execution.
  name: Data API
- description: Query data across Amazon RDS, Aurora, and S3 data lakes without moving data using federated query capabilities.
  name: Federated Query
- description: Build, train, and deploy ML models directly in Redshift using SQL with Amazon SageMaker integration.
  name: Machine Learning Integration
- description: Automatically add transient capacity to handle bursts of concurrent queries without performance degradation.
  name: Concurrency Scaling
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Load data from and query data in S3 using COPY commands, Redshift Spectrum, and data lake integration.
  name: Amazon S3
- description: Automated ETL job orchestration and data catalog integration for data warehouse loading.
  name: AWS Glue
- description: Connect QuickSight directly to Redshift for serverless BI dashboards and visualizations.
  name: Amazon QuickSight
- description: Trigger Lambda functions from Redshift Data API results for event-driven data processing workflows.
  name: AWS Lambda
- description: Provision and manage Redshift clusters and serverless workgroups using Terraform infrastructure-as-code.
  name: Terraform
jsonld:
- class_count: 0
  name: Amazon Redshift Context
  property_count: 6
  slug: amazon-redshift-context
- class_count: 0
  name: Amazon Redshift Data Context
  property_count: 0
  slug: amazon-redshift-data-context
layout: provider
modified: '2026-04-18'
name: Amazon Redshift
rules:
- name: Amazon Redshift API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: amazon-redshift-spectral-rules
skills: []
slug: amazon-redshift
solutions: []
source_yaml: "aid: amazon-redshift\nname: Amazon Redshift\ndescription: >-\n  Amazon Redshift is a fast, fully managed cloud data warehouse that makes it\n  simple and cost-effective to analyze all your data using standard SQL and your\n  existing Business Intelligence (BI) tools.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-redshift/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Big Data\n  - Cloud\n  - Data Lake\n  - Data Warehouse\n  - ETL\n  - Machine Learning\n  - Serverless\n  - SQL\napis:\n  - name: Amazon Redshift API\n    description: >-\n      The Amazon Redshift API for managing clusters, snapshots, and configurations.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/redshift/\n    baseURL: https://redshift.amazonaws.com\n\
  \    tags:\n      - Clusters\n      - Data Warehouse\n      - Snapshots\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/redshift/\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/redshift/2012-12-01/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/redshift/latest/APIReference/Welcome.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/redshift/latest/gsg/getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/redshift/pricing/\n      - type: Console\n        url: https://console.aws.amazon.com/redshift/\n      - type: SDK\n        url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift.html\n        title: Python SDK\n      - type: SDK\n        url: https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/client/redshift/\n        title: JavaScript SDK\n      - type: CLI\n        url: https://docs.aws.amazon.com/cli/latest/reference/redshift/\n\
  \      - type: BestPractices\n        url: https://docs.aws.amazon.com/redshift/latest/dg/best-practices.html\n      - type: Security\n        url: https://docs.aws.amazon.com/redshift/latest/mgmt/security.html\n      - type: FAQ\n        url: https://aws.amazon.com/redshift/faqs/\n      - type: ReleaseNotes\n        url: https://docs.aws.amazon.com/redshift/latest/mgmt/cluster-versions.html\n      - type: ChangeLog\n        url: https://docs.aws.amazon.com/redshift/latest/mgmt/document-history.html\n  - name: Amazon Redshift Data API\n    description: >-\n      The Amazon Redshift Data API for running SQL statements without managing\n      connections. Supports asynchronous execution with IAM and Secrets Manager\n      authentication.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/redshift/latest/mgmt/data-api.html\n    baseURL: https://redshift-data.amazonaws.com\n    tags:\n      - Data API\n      -\
  \ Serverless\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/redshift/latest/mgmt/data-api.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/redshift-data/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-redshift-data-api-openapi.yml\n      - type: SDK\n        url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html\n        title: Python SDK\n      - type: SDK\n        url: https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/client/redshift-data/\n        title: JavaScript SDK\n      - type: CLI\n        url: https://docs.aws.amazon.com/cli/latest/reference/redshift-data/\n      - type: GettingStarted\n        url: https://aws.amazon.com/blogs/big-data/get-started-with-the-amazon-redshift-data-api/\n  - name: Amazon Redshift Serverless API\n    description: >-\n      The Amazon Redshift Serverless API for managing serverless data\
  \ warehouse\n      workgroups, namespaces, and capacity without provisioning clusters.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/redshift/latest/mgmt/serverless-whatis.html\n    baseURL: https://redshift-serverless.amazonaws.com\n    tags:\n      - Data Warehouse\n      - Namespaces\n      - Serverless\n      - Workgroups\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-serverless.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/redshift-serverless/latest/APIReference/Welcome.html\n      - type: SDK\n        url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html\n        title: Python SDK\n      - type: SDK\n        url: https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/client/redshift-serverless/\n        title: JavaScript SDK\n      - type: CLI\n\
  \        url: https://docs.aws.amazon.com/cli/latest/reference/redshift-serverless/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/redshift/latest/mgmt/serverless-whatis.html\n      - type: Pricing\n        url: https://aws.amazon.com/redshift/pricing/\ncommon:\n  - type: Blog\n    url: https://aws.amazon.com/blogs/big-data/category/database/amazon-redshift/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/redshift/\n  - type: GettingStarted\n    url: https://aws.amazon.com/redshift/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/redshift/faqs/\n  - type: Pricing\n    url: https://aws.amazon.com/redshift/pricing/\n  - type: Console\n    url: https://console.aws.amazon.com/redshift/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n\
  \  - type: Features\n    data:\n      - name: Massively Parallel Processing\n        description: Distributed query execution across multiple nodes for petabyte-scale analytics with sub-second response times.\n      - name: Serverless Data Warehouse\n        description: Auto-scaling compute capacity without cluster provisioning, paying only for compute used during queries.\n      - name: Data API\n        description: Run SQL statements without managing database connections using IAM-based authentication and asynchronous execution.\n      - name: Federated Query\n        description: Query data across Amazon RDS, Aurora, and S3 data lakes without moving data using federated query capabilities.\n      - name: Machine Learning Integration\n        description: Build, train, and deploy ML models directly in Redshift using SQL with Amazon SageMaker integration.\n      - name: Concurrency Scaling\n        description: Automatically add transient capacity to handle bursts of concurrent queries\
  \ without performance degradation.\n  - type: UseCases\n    data:\n      - name: Business Intelligence Analytics\n        description: Run complex analytical queries across petabytes of structured data for BI dashboards and reporting.\n      - name: Data Lake Analytics\n        description: Query data directly in Amazon S3 using Redshift Spectrum without loading it into the warehouse.\n      - name: Real-Time Analytics\n        description: Ingest streaming data and run near-real-time analytics on operational data for instant insights.\n      - name: ETL Pipeline Processing\n        description: Transform and load large datasets using SQL-based ETL operations within the data warehouse.\n      - name: Serverless Ad-Hoc Queries\n        description: Run on-demand analytical queries without provisioning clusters using Redshift Serverless and Data API.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: Load data from and query data in S3 using COPY commands,\
  \ Redshift Spectrum, and data lake integration.\n      - name: AWS Glue\n        description: Automated ETL job orchestration and data catalog integration for data warehouse loading.\n      - name: Amazon QuickSight\n        description: Connect QuickSight directly to Redshift for serverless BI dashboards and visualizations.\n      - name: AWS Lambda\n        description: Trigger Lambda functions from Redshift Data API results for event-driven data processing workflows.\n      - name: Terraform\n        description: Provision and manage Redshift clusters and serverless workgroups using Terraform infrastructure-as-code.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-redshift/refs/heads/main/apis.yml
tags:
- Analytics
- Big Data
- Cloud
- Data Lake
- Data Warehouse
- ETL
- Machine Learning
- Serverless
- SQL
url: https://raw.githubusercontent.com/api-evangelist/amazon-redshift/refs/heads/main/apis.yml
use_cases:
- description: Run complex analytical queries across petabytes of structured data for BI dashboards and reporting.
  name: Business Intelligence Analytics
- description: Query data directly in Amazon S3 using Redshift Spectrum without loading it into the warehouse.
  name: Data Lake Analytics
- description: Ingest streaming data and run near-real-time analytics on operational data for instant insights.
  name: Real-Time Analytics
- description: Transform and load large datasets using SQL-based ETL operations within the data warehouse.
  name: ETL Pipeline Processing
- description: Run on-demand analytical queries without provisioning clusters using Redshift Serverless and Data API.
  name: Serverless Ad-Hoc Queries
---
