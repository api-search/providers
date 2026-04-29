---
api_count: 1
api_specs:
- filename: amazon-mainframe-modernization-openapi-original.yaml
  format: yaml
  label: AWS Mainframe Modernization API
  slug: aws-mainframe-modernization-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mainframe-modernization/refs/heads/main/openapi/amazon-mainframe-modernization-openapi-original.yaml
apis:
- description: 'The AWS Mainframe Modernization API provides programmatic access to create and manage applications, environments, deployments, and batch job executions for mainframe application modernization on AWS. '
  name: AWS Mainframe Modernization API
  slug: aws-mainframe-modernization-api
capabilities:
- description: Workflow capability for platform and migration teams to manage mainframe application modernization, including application lifecycle management, environment configuration, and batch job execution on AW
  name: Amazon Mainframe Modernization - Migration Workflow
  slug: modernization-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/mainframe-modernization/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/m2/
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
  url: https://aws.amazon.com/blogs/modernizing-with-aws/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/m2/
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
  url: rules/amazon-mainframe-modernization-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-mainframe-modernization-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/modernization-workflow.yaml
created: '2026-03-16'
description: AWS Mainframe Modernization provides tools and resources to help you plan and implement migration and modernization of your mainframe applications to AWS. It supports automated refactoring and replatforming of COBOL applications to run natively on AWS with managed runtime environments, deployment pipelines, and batch job execution capabilities.
features:
- description: Automatically refactor COBOL mainframe applications to run natively on AWS.
  name: Automated Refactoring
- description: Create and manage runtime environments using Micro Focus or Blue Age engines on AWS.
  name: Managed Runtime Environments
- description: Deploy and manage versions of modernized mainframe applications.
  name: Application Deployment
- description: Execute batch jobs migrated from mainframe in managed AWS environments.
  name: Batch Job Execution
- description: Import and manage mainframe data sets for use by modernized applications.
  name: Data Set Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use Micro Focus Enterprise Server as the runtime engine for replatformed applications.
  name: Micro Focus Runtime
- description: Use Blue Age as the runtime engine for refactored applications.
  name: Blue Age Runtime
- description: Store application artifacts and data sets in Elastic File System.
  name: Amazon EFS
- description: Monitor application and batch job metrics through CloudWatch.
  name: AWS CloudWatch
- description: Deploy environments within a Virtual Private Cloud for network isolation.
  name: AWS VPC
jsonld:
- class_count: 108
  name: Amazon Mainframe Modernization Context
  property_count: 121
  slug: amazon-mainframe-modernization-context
layout: provider
modified: '2026-04-19'
name: Amazon Mainframe Modernization
rules:
- name: Amazon Mainframe Modernization API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 4
    warn: 7
  slug: amazon-mainframe-modernization-spectral-rules
skills: []
slug: amazon-mainframe-modernization
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-mainframe-modernization\nname: Amazon Mainframe Modernization\ndescription: >-\n  AWS Mainframe Modernization provides tools and resources to help you plan and\n  implement migration and modernization of your mainframe applications to AWS.\n  It supports automated refactoring and replatforming of COBOL applications\n  to run natively on AWS with managed runtime environments, deployment pipelines,\n  and batch job execution capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - COBOL\n  - Mainframe\n  - Migration\n  - Modernization\n  - Batch Processing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-mainframe-modernization/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-mainframe-modernization:aws-mainframe-modernization-api\n    name: AWS Mainframe Modernization API\n    description: >-\n  \
  \    The AWS Mainframe Modernization API provides programmatic access to\n      create and manage applications, environments, deployments, and batch\n      job executions for mainframe application modernization on AWS. Covers\n      25 paths and 33 operations for the full modernization lifecycle.\n    humanURL: https://aws.amazon.com/mainframe-modernization/\n    baseURL: https://m2.amazonaws.com\n    tags:\n      - Mainframe\n      - Migration\n      - Modernization\n      - COBOL\n      - Batch Processing\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/m2/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-mainframe-modernization-openapi-original.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/mainframe-modernization/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/mainframe-modernization/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/mainframe-modernization/faqs/\n\
  \      - type: JSONSchema\n        url: json-schema/amazon-mainframe-modernization-application-summary-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-mainframe-modernization-application-summary-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-mainframe-modernization-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/mainframe-modernization/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/m2/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/modernizing-with-aws/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/m2/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n\
  \  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-mainframe-modernization-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-mainframe-modernization-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/modernization-workflow.yaml\n  - type: Features\n    data:\n      - name: Automated Refactoring\n        description: Automatically refactor COBOL mainframe applications to run natively on AWS.\n      - name: Managed Runtime Environments\n        description: Create and manage runtime environments using Micro Focus or Blue Age engines on AWS.\n      - name: Application Deployment\n        description: Deploy and manage versions of modernized mainframe applications.\n      - name: Batch Job Execution\n        description: Execute batch jobs migrated from mainframe in managed AWS environments.\n      - name: Data Set Management\n\
  \        description: Import and manage mainframe data sets for use by modernized applications.\n  - type: UseCases\n    data:\n      - name: COBOL Modernization\n        description: Refactor legacy COBOL applications to Java or other modern languages running on AWS.\n      - name: Mainframe Replatforming\n        description: Replatform mainframe workloads to AWS-managed environments without code changes.\n      - name: Batch Job Migration\n        description: Migrate batch processing workloads from mainframe to AWS for cost savings and scalability.\n      - name: Mainframe Retirement\n        description: Decommission on-premises mainframe hardware by migrating all workloads to AWS.\n  - type: Integrations\n    data:\n      - name: Micro Focus Runtime\n        description: Use Micro Focus Enterprise Server as the runtime engine for replatformed applications.\n      - name: Blue Age Runtime\n        description: Use Blue Age as the runtime engine for refactored applications.\n     \
  \ - name: Amazon EFS\n        description: Store application artifacts and data sets in Elastic File System.\n      - name: AWS CloudWatch\n        description: Monitor application and batch job metrics through CloudWatch.\n      - name: AWS VPC\n        description: Deploy environments within a Virtual Private Cloud for network isolation.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-mainframe-modernization/refs/heads/main/apis.yml
tags:
- AWS
- COBOL
- Mainframe
- Migration
- Modernization
- Batch Processing
url: https://raw.githubusercontent.com/api-evangelist/amazon-mainframe-modernization/refs/heads/main/apis.yml
use_cases:
- description: Refactor legacy COBOL applications to Java or other modern languages running on AWS.
  name: COBOL Modernization
- description: Replatform mainframe workloads to AWS-managed environments without code changes.
  name: Mainframe Replatforming
- description: Migrate batch processing workloads from mainframe to AWS for cost savings and scalability.
  name: Batch Job Migration
- description: Decommission on-premises mainframe hardware by migrating all workloads to AWS.
  name: Mainframe Retirement
---
