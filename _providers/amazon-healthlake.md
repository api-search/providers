---
api_count: 1
api_specs:
- filename: amazon-healthlake-openapi.yaml
  format: yaml
  label: Amazon HealthLake API
  slug: amazon-healthlake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-healthlake/refs/heads/main/openapi/amazon-healthlake-openapi.yaml
apis:
- description: The Amazon HealthLake API provides programmatic access to create and manage FHIR datastores, import and export health data, and run analytics on FHIR-formatted health records.
  name: Amazon HealthLake API
  slug: amazon-healthlake-api
capabilities:
- description: ''
  name: Amazon Healthlake Health Data Operations
  slug: amazon-healthlake-health-data-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/healthlake/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/healthlake/
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
  url: https://aws.amazon.com/blogs/industries/healthcare/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/healthlake/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SDK
  url: https://aws.amazon.com/developer/tools/
- title: ''
  type: CLI
  url: https://awscli.amazonaws.com/v2/documentation/api/latest/reference/healthlake/index.html
- title: ''
  type: SpectralRules
  url: rules/amazon-healthlake-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-healthlake-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-healthlake-health-data-operations.yaml
created: '2026-03-16'
description: Amazon HealthLake is a HIPAA-eligible service that gives healthcare providers, health insurance companies, and pharmaceutical companies the ability to store, transform, query, and analyze health data at scale in the cloud. It uses the Fast Healthcare Interoperability Resources (FHIR) standard.
features:
- description: Fully compliant with the FHIR R4 standard for healthcare data interoperability.
  name: FHIR Compliance
- description: HIPAA-eligible service for storing and processing protected health information.
  name: HIPAA-Eligible
- description: Bulk import FHIR-formatted health data from Amazon S3 with automated validation.
  name: Integrated Data Import
- description: Export FHIR health data to Amazon S3 for analytics, archiving, or migration.
  name: Data Export
- description: Query FHIR resources using standard FHIR search operations for clinical workflows.
  name: Integrated Search
- description: Built-in de-identification capabilities for removing PHI from health data.
  name: Automated De-identification
- description: Integrated analytics with Amazon Comprehend Medical and other AWS analytics services.
  name: Analytics Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Import and export FHIR health data using S3 as the data source and destination.
  name: Amazon S3
- description: Control access to HealthLake resources using IAM roles and policies.
  name: AWS IAM
- description: Monitor HealthLake operations and performance metrics through CloudWatch.
  name: Amazon CloudWatch
- description: Extract medical entities from unstructured health data using Comprehend Medical.
  name: Amazon Comprehend Medical
- description: Apply SageMaker ML models to FHIR data for predictive health analytics.
  name: Amazon SageMaker
- description: Transform and catalog FHIR health data for analytics using AWS Glue.
  name: AWS Glue
jsonld:
- class_count: 76
  name: Amazon Healthlake Context
  property_count: 0
  slug: amazon-healthlake-context
layout: provider
modified: '2026-04-19'
name: Amazon HealthLake
rules:
- name: Amazon HealthLake API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 3
    warn: 2
  slug: amazon-healthlake-spectral-rules
skills: []
slug: amazon-healthlake
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-healthlake\nname: Amazon HealthLake\ndescription: >-\n  Amazon HealthLake is a HIPAA-eligible service that gives healthcare providers,\n  health insurance companies, and pharmaceutical companies the ability to store,\n  transform, query, and analyze health data at scale in the cloud. It uses the\n  Fast Healthcare Interoperability Resources (FHIR) standard.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - FHIR\n  - Health Data\n  - Healthcare\n  - HIPAA\n  - Cloud Computing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-healthlake/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-healthlake:amazon-healthlake-api\n    name: Amazon HealthLake API\n    description: >-\n      The Amazon HealthLake API provides programmatic access to create and\n      manage FHIR datastores, import and export health data,\
  \ and run analytics\n      on FHIR-formatted health records.\n    humanURL: https://aws.amazon.com/healthlake/\n    baseURL: https://healthlake.amazonaws.com\n    tags:\n      - FHIR\n      - Health Data\n      - Healthcare\n      - HIPAA\n      - Datastores\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/healthlake/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-healthlake-openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/healthlake/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/healthlake/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/healthlake/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/healthlake/latest/APIReference/Welcome.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/healthlake/latest/APIReference/CommonParameters.html\n      - type: JSONSchema\n        url: json-schema/healthlake-create-fhir-datastore-request-schema.json\n\
  \      - type: JSONLD\n        url: json-ld/amazon-healthlake-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/healthlake/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/healthlake/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/industries/healthcare/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/healthlake/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SDK\n    url: https://aws.amazon.com/developer/tools/\n  - type: CLI\n    url: https://awscli.amazonaws.com/v2/documentation/api/latest/reference/healthlake/index.html\n\
  \  - type: Features\n    data:\n      - name: FHIR Compliance\n        description: Fully compliant with the FHIR R4 standard for healthcare data interoperability.\n      - name: HIPAA-Eligible\n        description: HIPAA-eligible service for storing and processing protected health information.\n      - name: Integrated Data Import\n        description: Bulk import FHIR-formatted health data from Amazon S3 with automated validation.\n      - name: Data Export\n        description: Export FHIR health data to Amazon S3 for analytics, archiving, or migration.\n      - name: Integrated Search\n        description: Query FHIR resources using standard FHIR search operations for clinical workflows.\n      - name: Automated De-identification\n        description: Built-in de-identification capabilities for removing PHI from health data.\n      - name: Analytics Integration\n        description: Integrated analytics with Amazon Comprehend Medical and other AWS analytics services.\n  - type: UseCases\n\
  \    data:\n      - name: Clinical Data Repository\n        description: Create a centralized FHIR-compliant repository for clinical data from multiple sources.\n      - name: Health Data Exchange\n        description: Enable interoperable health data exchange between healthcare providers and payers.\n      - name: Population Health Management\n        description: Analyze aggregated health data to identify trends and manage population health programs.\n      - name: AI-Powered Clinical Insights\n        description: Apply machine learning to FHIR data to generate clinical insights and predictions.\n      - name: Research Data Platform\n        description: Create de-identified research datasets from FHIR health records for clinical studies.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: Import and export FHIR health data using S3 as the data source and destination.\n      - name: AWS IAM\n        description: Control access to HealthLake resources using\
  \ IAM roles and policies.\n      - name: Amazon CloudWatch\n        description: Monitor HealthLake operations and performance metrics through CloudWatch.\n      - name: Amazon Comprehend Medical\n        description: Extract medical entities from unstructured health data using Comprehend Medical.\n      - name: Amazon SageMaker\n        description: Apply SageMaker ML models to FHIR data for predictive health analytics.\n      - name: AWS Glue\n        description: Transform and catalog FHIR health data for analytics using AWS Glue.\n  - type: SpectralRules\n    url: rules/amazon-healthlake-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-healthlake-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/amazon-healthlake-health-data-operations.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-healthlake/refs/heads/main/apis.yml
tags:
- FHIR
- Health Data
- Healthcare
- HIPAA
- Cloud Computing
url: https://raw.githubusercontent.com/api-evangelist/amazon-healthlake/refs/heads/main/apis.yml
use_cases:
- description: Create a centralized FHIR-compliant repository for clinical data from multiple sources.
  name: Clinical Data Repository
- description: Enable interoperable health data exchange between healthcare providers and payers.
  name: Health Data Exchange
- description: Analyze aggregated health data to identify trends and manage population health programs.
  name: Population Health Management
- description: Apply machine learning to FHIR data to generate clinical insights and predictions.
  name: AI-Powered Clinical Insights
- description: Create de-identified research datasets from FHIR health records for clinical studies.
  name: Research Data Platform
---
