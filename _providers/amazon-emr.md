---
api_count: 1
api_specs:
- filename: amazon-emr-openapi.yml
  format: yaml
  label: Amazon EMR API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-emr/refs/heads/main/openapi/amazon-emr-openapi.yml
apis:
- description: API for creating and managing Amazon EMR clusters, steps, instance groups, and running distributed big data processing workloads.
  name: Amazon EMR API
  slug: ''
capabilities:
- description: Unified capability for managing Amazon EMR resources. Combines Amazon EMR APIs for Data Engineer workflows in Big Data Processing.
  name: Amazon EMR Management
  slug: amazon-emr-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/emr/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/emr/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/emr/
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
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/emr/faqs/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/emr
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-emr-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-emr-capability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-emr-vocabulary.yaml
created: '2024-01-15'
description: Amazon EMR is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning applications using open-source analytics frameworks such as Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi, and Presto.
features:
- description: Run Apache Spark jobs for large-scale data processing and machine learning
  name: Apache Spark Support
- description: Automatically adjust cluster size based on workload demand
  name: Auto Scaling
- description: Use EC2 Spot instances to reduce costs up to 90%
  name: Spot Instance Integration
- description: Run analytics without provisioning or managing clusters
  name: EMR Serverless
- description: Develop and debug jobs using EMR Studio Jupyter notebooks
  name: Studio Notebooks
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Use S3 as data lake storage for EMR clusters
  name: Amazon S3
- description: Integrate with Glue Data Catalog for metadata management
  name: AWS Glue
- description: Query data processed by EMR using Athena SQL
  name: Amazon Athena
- description: Hand off processed data to SageMaker for model training
  name: Amazon SageMaker
jsonld:
- class_count: 0
  name: Amazon Emr Context
  property_count: 2
  slug: amazon-emr-context
layout: provider
modified: '2026-04-19'
name: Amazon EMR
rules:
- name: Amazon EMR API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-emr-spectral-rules
skills: []
slug: amazon-emr
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon EMR\ndescription: Amazon EMR is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning applications using open-source analytics \n  frameworks such as Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi, and Presto.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/emr/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Amazon Web Services\n- Analytics\n- Apache Spark\n- AWS\n- Big Data\n- Data Processing\n- Hadoop\napis:\n- name: Amazon EMR API\n  description: API for creating and managing Amazon EMR clusters, steps, instance groups, and running distributed big data processing workloads.\n  humanURL: https://aws.amazon.com/emr/\n  baseURL: https://elasticmapreduce.amazonaws.com\n  tags:\n  - Analytics\n  - Big Data\n  - Data Processing\n  - Spark\n  properties:\n  - type: Documentation\n\
  \    url: https://docs.aws.amazon.com/emr/latest/ManagementGuide/\n  - type: OpenAPI\n    url: openapi/amazon-emr-openapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/emr/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/emr/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/emr/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/emr/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-emr-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-emr-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/emr/\n- type: Documentation\n  url: https://docs.aws.amazon.com/emr/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/emr/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n\
  - type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: FAQ\n  url: https://aws.amazon.com/emr/faqs/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/emr\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-emr-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-emr-capability.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/api.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-emr-vocabulary.yaml\n- type: Features\n\
  \  data:\n  - name: Apache Spark Support\n    description: Run Apache Spark jobs for large-scale data processing and machine learning\n  - name: Auto Scaling\n    description: Automatically adjust cluster size based on workload demand\n  - name: Spot Instance Integration\n    description: Use EC2 Spot instances to reduce costs up to 90%\n  - name: EMR Serverless\n    description: Run analytics without provisioning or managing clusters\n  - name: Studio Notebooks\n    description: Develop and debug jobs using EMR Studio Jupyter notebooks\n- type: UseCases\n  data:\n  - name: ETL Data Processing\n    description: Extract, transform, and load large datasets across data lakes and warehouses\n  - name: Machine Learning\n    description: Train machine learning models on large datasets using Spark MLlib\n  - name: Log Analytics\n    description: Process and analyze application logs at petabyte scale\n  - name: Financial Risk Analysis\n    description: Run Monte Carlo simulations and risk models\
  \ on large datasets\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Use S3 as data lake storage for EMR clusters\n  - name: AWS Glue\n    description: Integrate with Glue Data Catalog for metadata management\n  - name: Amazon Athena\n    description: Query data processed by EMR using Athena SQL\n  - name: Amazon SageMaker\n    description: Hand off processed data to SageMaker for model training\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-emr/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- Analytics
- Apache Spark
- Big Data
- Data Processing
- Hadoop
url: https://aws.amazon.com/emr/
use_cases:
- description: Extract, transform, and load large datasets across data lakes and warehouses
  name: ETL Data Processing
- description: Train machine learning models on large datasets using Spark MLlib
  name: Machine Learning
- description: Process and analyze application logs at petabyte scale
  name: Log Analytics
- description: Run Monte Carlo simulations and risk models on large datasets
  name: Financial Risk Analysis
---
