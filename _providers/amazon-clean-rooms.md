---
api_count: 1
api_specs:
- filename: amazon-clean-rooms-openapi.yml
  format: yaml
  label: Amazon Clean Rooms API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-clean-rooms/refs/heads/main/openapi/amazon-clean-rooms-openapi.yml
apis:
- description: API for creating and managing secure collaboration workspaces, memberships, configured tables, analysis templates, and executing privacy-preserving protected queries and jobs.
  name: Amazon Clean Rooms API
  slug: ''
capabilities:
- description: Workflow for establishing and operating secure multi-party data clean rooms on AWS, enabling data analysts and marketing teams to run collaborative analytics without sharing raw data.
  name: Amazon Clean Rooms Secure Data Collaboration
  slug: secure-data-collaboration
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/clean-rooms/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/clean-rooms/
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
  url: https://aws.amazon.com/blogs/big-data/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cleanrooms/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-clean-rooms
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-clean-rooms-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-clean-rooms-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/secure-data-collaboration.yaml
created: '2026-03-16'
description: Amazon Clean Rooms enables organizations to collaborate and analyze shared datasets without exposing underlying raw data to partners. Create secure data clean rooms in minutes and collaborate with any company while maintaining data privacy through differential privacy, cryptographic computing, and flexible analytics.
features:
- description: Analyze shared datasets without exposing underlying raw data using differential privacy and cryptographic computing.
  name: Privacy-Preserving Analytics
- description: Collaborate with Snowflake and AWS datasets without data movement or ETL pipelines.
  name: Zero-ETL Integration
- description: Execute SQL, PySpark, or ML model queries on partner data with configurable privacy controls.
  name: Protected Queries
- description: Run analytics using SQL, PySpark, or custom ML models with granular access controls.
  name: Flexible Analysis Methods
- description: Audit data usage with analysis logging to track all queries run within a collaboration.
  name: Analysis Logging
- description: Match customer records across applications and channels without sharing PII.
  name: Customer Record Matching
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store and retrieve collaboration data and query results in S3.
  name: Amazon S3
- description: Zero-ETL integration with Snowflake datasets for cross-platform collaboration.
  name: Snowflake
- description: Configure Glue tables as the underlying data source for Clean Rooms configured tables.
  name: AWS Glue
- description: Run analytics on collaboration results stored in S3 using Athena.
  name: Amazon Athena
- description: Apply ML models within protected Clean Rooms jobs.
  name: Amazon SageMaker
- description: Control access to Clean Rooms resources with IAM policies.
  name: AWS IAM
- description: Audit all Clean Rooms API calls via CloudTrail.
  name: AWS CloudTrail
jsonld:
- class_count: 19
  name: Amazon Clean Rooms Context
  property_count: 32
  slug: amazon-clean-rooms-context
layout: provider
modified: '2026-04-19'
name: Amazon Clean Rooms
rules:
- name: Amazon Clean Rooms API Rules
  rule_count: 29
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 13
  slug: amazon-clean-rooms-spectral-rules
skills: []
slug: amazon-clean-rooms
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-clean-rooms\nname: Amazon Clean Rooms\ndescription: >-\n  Amazon Clean Rooms enables organizations to collaborate and analyze shared datasets without exposing underlying raw data to partners. Create secure data clean rooms in minutes and collaborate with any\n  company while maintaining data privacy through differential privacy, cryptographic computing, and flexible analytics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Clean Rooms\n- Data Collaboration\n- Privacy\n- Analytics\n- Marketing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-clean-rooms/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- name: Amazon Clean Rooms API\n  description: API for creating and managing secure collaboration workspaces, memberships, configured tables, analysis templates, and executing privacy-preserving protected queries and jobs.\n\
  \  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/clean-rooms/\n  baseURL: https://cleanrooms.us-east-1.amazonaws.com\n  tags:\n  - AWS\n  - Clean Rooms\n  - Data Collaboration\n  - Privacy\n  - Analytics\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/clean-rooms/latest/apireference/\n  - type: OpenAPI\n    url: openapi/amazon-clean-rooms-openapi.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/clean-rooms/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/clean-rooms/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/clean-rooms/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/clean-rooms/latest/apireference/\n  - type: UserGuide\n    url: https://docs.aws.amazon.com/clean-rooms/latest/userguide/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cleanrooms/\n  - type: JSONSchema\n    url: json-schema/clean-rooms-collaboration-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/clean-rooms-membership-schema.json\n  - type: JSONSchema\n    url: json-schema/clean-rooms-protected-query-schema.json\n  - type: JSONSchema\n    url: json-schema/clean-rooms-configured-table-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-clean-rooms-context.jsonld\n  - type: Example\n    url: examples/clean-rooms-collaboration-example.json\n  - type: Example\n    url: examples/clean-rooms-membership-example.json\n  - type: Example\n    url: examples/clean-rooms-protected-query-example.json\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/clean-rooms/\n- type: Documentation\n  url: https://docs.aws.amazon.com/clean-rooms/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n-\
  \ type: Blog\n  url: https://aws.amazon.com/blogs/big-data/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cleanrooms/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-clean-rooms\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-clean-rooms-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-clean-rooms-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/secure-data-collaboration.yaml\n- type: Features\n  data:\n  - name: Privacy-Preserving Analytics\n    description: Analyze shared datasets without exposing underlying raw data\
  \ using differential privacy and cryptographic computing.\n  - name: Zero-ETL Integration\n    description: Collaborate with Snowflake and AWS datasets without data movement or ETL pipelines.\n  - name: Protected Queries\n    description: Execute SQL, PySpark, or ML model queries on partner data with configurable privacy controls.\n  - name: Flexible Analysis Methods\n    description: Run analytics using SQL, PySpark, or custom ML models with granular access controls.\n  - name: Analysis Logging\n    description: Audit data usage with analysis logging to track all queries run within a collaboration.\n  - name: Customer Record Matching\n    description: Match customer records across applications and channels without sharing PII.\n- type: UseCases\n  data:\n  - name: Marketing Measurement\n    description: Measure campaign effectiveness by combining advertiser and publisher data in a privacy-safe environment.\n  - name: Customer Insights\n    description: Build comprehensive customer views\
  \ by combining data from multiple channels and partners.\n  - name: Collaborative Research\n    description: Enable multi-company research and product development with secure data sharing.\n  - name: Risk Assessment\n    description: Analyze sensitive financial or health data across organizations for risk prediction without data exposure.\n  - name: Audience Activation\n    description: Create and activate privacy-safe audience segments across advertising platforms.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Store and retrieve collaboration data and query results in S3.\n  - name: Snowflake\n    description: Zero-ETL integration with Snowflake datasets for cross-platform collaboration.\n  - name: AWS Glue\n    description: Configure Glue tables as the underlying data source for Clean Rooms configured tables.\n  - name: Amazon Athena\n    description: Run analytics on collaboration results stored in S3 using Athena.\n  - name: Amazon SageMaker\n    description:\
  \ Apply ML models within protected Clean Rooms jobs.\n  - name: AWS IAM\n    description: Control access to Clean Rooms resources with IAM policies.\n  - name: AWS CloudTrail\n    description: Audit all Clean Rooms API calls via CloudTrail.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-clean-rooms/refs/heads/main/apis.yml
tags:
- Clean Rooms
- Data Collaboration
- Privacy
- Analytics
- Marketing
url: https://raw.githubusercontent.com/api-evangelist/amazon-clean-rooms/refs/heads/main/apis.yml
use_cases:
- description: Measure campaign effectiveness by combining advertiser and publisher data in a privacy-safe environment.
  name: Marketing Measurement
- description: Build comprehensive customer views by combining data from multiple channels and partners.
  name: Customer Insights
- description: Enable multi-company research and product development with secure data sharing.
  name: Collaborative Research
- description: Analyze sensitive financial or health data across organizations for risk prediction without data exposure.
  name: Risk Assessment
- description: Create and activate privacy-safe audience segments across advertising platforms.
  name: Audience Activation
---
