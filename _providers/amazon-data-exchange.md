---
api_count: 1
api_specs:
- filename: amazon-data-exchange-openapi.yml
  format: yaml
  label: AWS Data Exchange API
  slug: aws-data-exchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-data-exchange/refs/heads/main/openapi/amazon-data-exchange-openapi.yml
apis:
- description: The AWS Data Exchange API enables programmatic access to find, subscribe to, and use third-party data products. It supports managing data sets, revisions, assets, jobs, and event actions for cloud-bas
  name: AWS Data Exchange API
  slug: aws-data-exchange-api
capabilities:
- description: ''
  name: Data Marketplace Operations
  slug: data-marketplace-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/data-exchange/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/data-exchange/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/data-exchange/
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
  url: https://aws.amazon.com/blogs/big-data/category/analytics/aws-data-exchange/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/dataexchange/
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
  url: rules/amazon-data-exchange-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-data-exchange-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-marketplace-operations.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/data-exchange.yaml
created: '2026-03-16'
description: AWS Data Exchange makes it easy to find, subscribe to, and use third-party data in the cloud. Qualified data providers can publish data products consisting of data sets with versioned revisions and assets including S3 snapshots, Redshift data shares, API Gateway APIs, and Lake Formation permissions. Subscribers can find and subscribe to data products directly in the AWS Management Console and use the Data Exchange API to load data into Amazon S3 for analysis with AWS analytics and machine learning services.
features:
- description: Create, update, and manage data sets containing versioned collections of data available for subscription and distribution in the marketplace.
  name: Data Set Management
- description: Organize data into versioned revisions with comments, then finalize and publish them to make data available to subscribers automatically.
  name: Revision Publishing
- description: Support for S3 snapshots, Redshift data shares, API Gateway APIs, Lake Formation permissions, and S3 data access as asset types.
  name: Multi-Format Asset Support
- description: Asynchronous import/export jobs for transferring data between external sources (S3, Redshift) and Data Exchange revisions at scale.
  name: Import and Export Jobs
- description: Configurable event actions that automatically export revision data to S3 when a new revision is published, eliminating manual downloads.
  name: Event-Driven Delivery
- description: Seamlessly list and sell data products in AWS Marketplace with built-in billing, subscription management, and entitlement enforcement.
  name: AWS Marketplace Integration
- description: Control access to data products using AWS IAM policies and resource- level permissions with ARN-based resource identification.
  name: Fine-Grained Access Control
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary storage integration for Data Exchange assets — used as both source for imports and destination for exports via job operations.
  name: Amazon S3
- description: Share Redshift tables and views directly through Data Exchange without copying data, enabling live query access for subscribers.
  name: Amazon Redshift
- description: Distribute Lake Formation data permissions through Data Exchange, giving subscribers governed access to data lake resources.
  name: AWS Lake Formation
- description: Expose API-based data products through Data Exchange, allowing subscribers to call APIs for real-time data access.
  name: Amazon API Gateway
- description: Catalog and transform Data Exchange S3 datasets using AWS Glue for ETL and data lake integration workflows.
  name: AWS Glue
- description: Query Data Exchange S3 snapshot data directly with SQL using Athena for serverless analytics on subscribed datasets.
  name: Amazon Athena
- description: Use third-party datasets from Data Exchange as training data for machine learning models in Amazon SageMaker.
  name: Amazon SageMaker
jsonld:
- class_count: 0
  name: Amazon Data Exchange Context
  property_count: 49
  slug: amazon-data-exchange-context
layout: provider
modified: '2026-04-19'
name: Amazon Data Exchange
rules:
- name: Amazon Data Exchange API Rules
  rule_count: 30
  severity_counts:
    error: 13
    hint: 0
    info: 7
    warn: 10
  slug: amazon-data-exchange-spectral-rules
skills: []
slug: amazon-data-exchange
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-data-exchange\nname: Amazon Data Exchange\ndescription: >-\n  AWS Data Exchange makes it easy to find, subscribe to, and use third-party\n  data in the cloud. Qualified data providers can publish data products\n  consisting of data sets with versioned revisions and assets including S3\n  snapshots, Redshift data shares, API Gateway APIs, and Lake Formation\n  permissions. Subscribers can find and subscribe to data products directly\n  in the AWS Management Console and use the Data Exchange API to load data\n  into Amazon S3 for analysis with AWS analytics and machine learning services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Data Exchange\n  - Data Marketplace\n  - Third-Party Data\n  - Analytics\n  - Subscriptions\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-data-exchange/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: amazon-data-exchange:aws-data-exchange-api\n    name: AWS Data Exchange API\n    description: >-\n      The AWS Data Exchange API enables programmatic access to find, subscribe\n      to, and use third-party data products. It supports managing data sets,\n      revisions, assets, jobs, and event actions for cloud-based data exchange\n      workflows including S3 snapshot data, Redshift data shares, API Gateway\n      APIs, and Lake Formation permissions.\n    humanURL: https://aws.amazon.com/data-exchange/\n    baseURL: https://dataexchange.amazonaws.com\n    tags:\n      - Data Marketplace\n      - Data Products\n      - Subscriptions\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/data-exchange/latest/apireference/\n      - type: OpenAPI\n        url: openapi/amazon-data-exchange-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/dataexchange/2017-07-25/openapi.yaml\n\
  \      - type: GettingStarted\n        url: https://aws.amazon.com/data-exchange/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/data-exchange/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/data-exchange/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/data-exchange/latest/apireference/\n      - type: JSONSchema\n        url: json-schema/data-set-schema.json\n      - type: JSONSchema\n        url: json-schema/revision-schema.json\n      - type: JSONSchema\n        url: json-schema/asset-schema.json\n      - type: JSONSchema\n        url: json-schema/job-schema.json\n      - type: JSONSchema\n        url: json-schema/event-action-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-data-exchange-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/data-exchange/\n  - type: DeveloperPortal\n    url: https://aws.amazon.com/data-exchange/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/data-exchange/\n\
  \  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/big-data/category/analytics/aws-data-exchange/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/dataexchange/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-data-exchange-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-data-exchange-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/data-marketplace-operations.yaml\n  - type: NaftikoCapability\n    url:\
  \ capabilities/shared/data-exchange.yaml\n  - type: Features\n    data:\n      - name: Data Set Management\n        description: >-\n          Create, update, and manage data sets containing versioned collections\n          of data available for subscription and distribution in the marketplace.\n      - name: Revision Publishing\n        description: >-\n          Organize data into versioned revisions with comments, then finalize\n          and publish them to make data available to subscribers automatically.\n      - name: Multi-Format Asset Support\n        description: >-\n          Support for S3 snapshots, Redshift data shares, API Gateway APIs,\n          Lake Formation permissions, and S3 data access as asset types.\n      - name: Import and Export Jobs\n        description: >-\n          Asynchronous import/export jobs for transferring data between external\n          sources (S3, Redshift) and Data Exchange revisions at scale.\n      - name: Event-Driven Delivery\n        description:\
  \ >-\n          Configurable event actions that automatically export revision data\n          to S3 when a new revision is published, eliminating manual downloads.\n      - name: AWS Marketplace Integration\n        description: >-\n          Seamlessly list and sell data products in AWS Marketplace with\n          built-in billing, subscription management, and entitlement enforcement.\n      - name: Fine-Grained Access Control\n        description: >-\n          Control access to data products using AWS IAM policies and resource-\n          level permissions with ARN-based resource identification.\n  - type: UseCases\n    data:\n      - name: Third-Party Data Acquisition\n        description: >-\n          Subscribe to curated third-party datasets from financial data providers,\n          healthcare data aggregators, weather services, and market research firms.\n      - name: Data Product Monetization\n        description: >-\n          Publish and sell proprietary datasets to other AWS\
  \ customers via the\n          marketplace with automated billing and subscription management.\n      - name: Automated Data Pipelines\n        description: >-\n          Configure event actions to automatically deliver new data revisions to\n          S3, enabling downstream analytics pipelines to process fresh data.\n      - name: ML Training Data\n        description: >-\n          Access high-quality labeled datasets and specialized data products\n          from Data Exchange to train and improve machine learning models.\n      - name: Regulatory Compliance Data\n        description: >-\n          Subscribe to compliance reference data including sanctions lists,\n          legal entity identifiers, and regulatory taxonomies via Data Exchange.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: >-\n          Primary storage integration for Data Exchange assets — used as both\n          source for imports and destination for exports via job operations.\n\
  \      - name: Amazon Redshift\n        description: >-\n          Share Redshift tables and views directly through Data Exchange\n          without copying data, enabling live query access for subscribers.\n      - name: AWS Lake Formation\n        description: >-\n          Distribute Lake Formation data permissions through Data Exchange,\n          giving subscribers governed access to data lake resources.\n      - name: Amazon API Gateway\n        description: >-\n          Expose API-based data products through Data Exchange, allowing\n          subscribers to call APIs for real-time data access.\n      - name: AWS Glue\n        description: >-\n          Catalog and transform Data Exchange S3 datasets using AWS Glue\n          for ETL and data lake integration workflows.\n      - name: Amazon Athena\n        description: >-\n          Query Data Exchange S3 snapshot data directly with SQL using\n          Athena for serverless analytics on subscribed datasets.\n      - name: Amazon\
  \ SageMaker\n        description: >-\n          Use third-party datasets from Data Exchange as training data for\n          machine learning models in Amazon SageMaker.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-exchange/refs/heads/main/apis.yml
tags:
- AWS
- Data Exchange
- Data Marketplace
- Third-Party Data
- Analytics
- Subscriptions
url: https://raw.githubusercontent.com/api-evangelist/amazon-data-exchange/refs/heads/main/apis.yml
use_cases:
- description: Subscribe to curated third-party datasets from financial data providers, healthcare data aggregators, weather services, and market research firms.
  name: Third-Party Data Acquisition
- description: Publish and sell proprietary datasets to other AWS customers via the marketplace with automated billing and subscription management.
  name: Data Product Monetization
- description: Configure event actions to automatically deliver new data revisions to S3, enabling downstream analytics pipelines to process fresh data.
  name: Automated Data Pipelines
- description: Access high-quality labeled datasets and specialized data products from Data Exchange to train and improve machine learning models.
  name: ML Training Data
- description: Subscribe to compliance reference data including sanctions lists, legal entity identifiers, and regulatory taxonomies via Data Exchange.
  name: Regulatory Compliance Data
---
