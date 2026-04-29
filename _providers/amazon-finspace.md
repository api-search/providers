---
api_count: 1
api_specs:
- filename: amazon-finspace-openapi.yml
  format: yaml
  label: Amazon FinSpace API
  slug: amazon-finspace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/openapi/amazon-finspace-openapi.yml
apis:
- description: The Amazon FinSpace API provides programmatic access to create and manage FinSpace environments, datasets, data views, and user access controls for financial data management and analytics.
  name: Amazon FinSpace API
  slug: amazon-finspace-api
capabilities:
- description: Workflow capability for managing FinSpace environments, kdb clusters, databases, and users for financial analytics.
  name: Amazon FinSpace Financial Analytics
  slug: amazon-finspace-financial-analytics
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/finspace/
- title: ''
  type: Website
  url: https://aws.amazon.com/finspace/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/finspace/
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
  url: https://aws.amazon.com/blogs/industries/financial-services/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/finspace/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-finspace
- title: ''
  type: SpectralRules
  url: rules/amazon-finspace-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/finspace.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-finspace-financial-analytics.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-finspace-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-finspace-context.jsonld
created: '2026-03-16'
description: Amazon FinSpace is a data management and analytics service built specifically for the financial services industry. It reduces the time you spend on time-consuming data preparation tasks and makes it easy for analysts to access and analyze petabytes of financial data with a few clicks.
features:
- description: Fully managed kdb+ (kdb+/q) compute infrastructure with HDB, RDB, Gateway, and Tickerplant cluster types.
  name: Managed kdb Environment
- description: Isolated FinSpace environments with preconfigured tools for financial data ingestion, preparation, and analysis.
  name: Financial Analytics Workspace
- description: Store and query petabytes of financial time-series data including tick, OHLCV, and alternative datasets.
  name: Petabyte-Scale Data
- description: Configure auto-scaling policies for kdb clusters to match intraday compute demand.
  name: kdb+ Cluster Autoscaling
- description: Deploy kdb clusters across multiple availability zones for high availability.
  name: Multi-AZ Clusters
- description: Map FinSpace kdb users to IAM roles for fine-grained permission control.
  name: IAM-Integrated Users
- description: Access financial data from FinSpace environments directly within Amazon SageMaker Studio.
  name: SageMaker Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store and retrieve kdb database snapshots and bulk financial data files.
  name: Amazon S3
- description: Encrypt FinSpace environments and kdb databases with customer-managed KMS keys.
  name: AWS KMS
- description: Control user and application access to FinSpace resources with IAM roles and policies.
  name: AWS IAM
- description: Access FinSpace datasets and kdb environments from SageMaker Studio notebooks.
  name: Amazon SageMaker
- description: Monitor kdb cluster health, query performance, and resource utilization metrics.
  name: Amazon CloudWatch
- description: Connect kdb environments to on-premises networks and other VPCs via Transit Gateway.
  name: AWS Transit Gateway
- description: Deploy kdb clusters in isolated VPC networking with security group controls.
  name: Amazon VPC
jsonld:
- class_count: 5
  name: Amazon Finspace Context
  property_count: 22
  slug: amazon-finspace-context
layout: provider
modified: '2026-04-19'
name: Amazon FinSpace
skills: []
slug: amazon-finspace
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-finspace\nname: Amazon FinSpace\ndescription: >-\n  Amazon FinSpace is a data management and analytics service built specifically\n  for the financial services industry. It reduces the time you spend on\n  time-consuming data preparation tasks and makes it easy for analysts to access\n  and analyze petabytes of financial data with a few clicks.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Capital Markets\n- Data Analytics\n- Data Management\n- Financial Services\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-finspace:amazon-finspace-api\n  name: Amazon FinSpace API\n  description: >-\n    The Amazon FinSpace API provides programmatic access to create and manage\n    FinSpace environments, datasets, data views, and user access controls for\n    financial\
  \ data management and analytics.\n  humanURL: https://aws.amazon.com/finspace/\n  baseURL: https://finspace.amazonaws.com\n  tags:\n  - Data Analytics\n  - Data Management\n  - Financial Services\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/finspace/latest/management-api/fs-api-welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-finspace-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-finspace-environment-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-finspace-kx-environment-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-finspace-kx-cluster-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-finspace-kx-database-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-finspace-kx-user-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-finspace-environment-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-finspace-kx-environment-structure.json\n \
  \ - type: JSONStructure\n    url: json-structure/amazon-finspace-kx-cluster-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-finspace-kx-database-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-finspace-kx-user-structure.json\n  - type: Example\n    url: examples/amazon-finspace-environment-example.json\n  - type: Example\n    url: examples/amazon-finspace-kx-environment-example.json\n  - type: Example\n    url: examples/amazon-finspace-kx-cluster-example.json\n  - type: Example\n    url: examples/amazon-finspace-kx-database-example.json\n  - type: Example\n    url: examples/amazon-finspace-kx-user-example.json\n  - type: GettingStarted\n    url: https://aws.amazon.com/finspace/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/finspace/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/finspace/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/finspace/latest/management-api/fs-api-welcome.html\ncommon:\n\
  - type: Portal\n  url: https://aws.amazon.com/finspace/\n- type: Website\n  url: https://aws.amazon.com/finspace/\n- type: Documentation\n  url: https://docs.aws.amazon.com/finspace/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/industries/financial-services/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/finspace/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-finspace\n- type: SpectralRules\n  url: rules/amazon-finspace-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/finspace.yaml\n\
  - type: NaftikoCapability\n  url: capabilities/amazon-finspace-financial-analytics.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-finspace-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/amazon-finspace-context.jsonld\n- type: Features\n  data:\n  - name: Managed kdb Environment\n    description: Fully managed kdb+ (kdb+/q) compute infrastructure with HDB, RDB, Gateway, and Tickerplant cluster types.\n  - name: Financial Analytics Workspace\n    description: Isolated FinSpace environments with preconfigured tools for financial data ingestion, preparation, and analysis.\n  - name: Petabyte-Scale Data\n    description: Store and query petabytes of financial time-series data including tick, OHLCV, and alternative datasets.\n  - name: kdb+ Cluster Autoscaling\n    description: Configure auto-scaling policies for kdb clusters to match intraday compute demand.\n  - name: Multi-AZ Clusters\n    description: Deploy kdb clusters across multiple availability zones for high availability.\n \
  \ - name: IAM-Integrated Users\n    description: Map FinSpace kdb users to IAM roles for fine-grained permission control.\n  - name: SageMaker Integration\n    description: Access financial data from FinSpace environments directly within Amazon SageMaker Studio.\n- type: UseCases\n  data:\n  - name: Tick Data Management\n    description: Ingest, store, and query high-frequency market tick data (trades, quotes, order books) using kdb+ clusters.\n  - name: Risk Analytics\n    description: Run intraday risk calculations and post-trade analytics on financial time-series data at low latency.\n  - name: Quantitative Research\n    description: Provide quants and data scientists with managed kdb environments for backtesting and strategy development.\n  - name: Regulatory Reporting\n    description: Aggregate and transform trade and order data for regulatory submissions and compliance.\n  - name: Alternative Data Processing\n    description: Ingest and correlate alternative datasets (news, satellite,\
  \ ESG) with market data for signal generation.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Store and retrieve kdb database snapshots and bulk financial data files.\n  - name: AWS KMS\n    description: Encrypt FinSpace environments and kdb databases with customer-managed KMS keys.\n  - name: AWS IAM\n    description: Control user and application access to FinSpace resources with IAM roles and policies.\n  - name: Amazon SageMaker\n    description: Access FinSpace datasets and kdb environments from SageMaker Studio notebooks.\n  - name: Amazon CloudWatch\n    description: Monitor kdb cluster health, query performance, and resource utilization metrics.\n  - name: AWS Transit Gateway\n    description: Connect kdb environments to on-premises networks and other VPCs via Transit Gateway.\n  - name: Amazon VPC\n    description: Deploy kdb clusters in isolated VPC networking with security group controls.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/apis.yml
tags:
- AWS
- Capital Markets
- Data Analytics
- Data Management
- Financial Services
url: https://raw.githubusercontent.com/api-evangelist/amazon-finspace/refs/heads/main/apis.yml
use_cases:
- description: Ingest, store, and query high-frequency market tick data (trades, quotes, order books) using kdb+ clusters.
  name: Tick Data Management
- description: Run intraday risk calculations and post-trade analytics on financial time-series data at low latency.
  name: Risk Analytics
- description: Provide quants and data scientists with managed kdb environments for backtesting and strategy development.
  name: Quantitative Research
- description: Aggregate and transform trade and order data for regulatory submissions and compliance.
  name: Regulatory Reporting
- description: Ingest and correlate alternative datasets (news, satellite, ESG) with market data for signal generation.
  name: Alternative Data Processing
---
