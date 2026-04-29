---
api_count: 1
api_specs:
- filename: amazon-entity-resolution-openapi.yml
  format: yaml
  label: Amazon Entity Resolution API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-entity-resolution/refs/heads/main/openapi/amazon-entity-resolution-openapi.yml
apis:
- description: API for creating and managing matching workflows, schema mappings, and ID mapping tables for matching and linking related records across data sources.
  name: Amazon Entity Resolution API
  slug: ''
capabilities:
- description: Unified capability for managing Amazon Entity Resolution resources. Combines Amazon Entity Resolution APIs for Data Analyst workflows in Data Quality.
  name: Amazon Entity Resolution Management
  slug: amazon-entity-resolution-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/entity-resolution/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/entity-resolution/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/entityresolution/
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
  url: https://aws.amazon.com/entity-resolution/faqs/
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
  url: https://stackoverflow.com/questions/tagged/entity-resolution
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-entity-resolution-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-entity-resolution-capability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-entity-resolution-vocabulary.yaml
created: '2024-01-15'
description: Amazon Entity Resolution is a service that helps you match and link related records across multiple applications, channels, and data stores using machine learning and configurable matching techniques to identify and consolidate records that refer to the same entity.
features:
- description: Use machine learning models to match records across disparate datasets
  name: ML-Based Matching
- description: Configure deterministic matching rules for exact and fuzzy matching
  name: Rule-Based Matching
- description: Create and manage identity graphs linking records across data sources
  name: ID Mapping
- description: Map input data schemas to standardized formats for consistent matching
  name: Schema Mapping
- description: Enrich records with data from LiveRamp, Unified ID 2.0, and others
  name: Third-Party Data Providers
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Use Glue Data Catalog to discover and access input data sources
  name: AWS Glue
- description: Store matching job input and output data in S3
  name: Amazon S3
- description: Query matching results using Athena SQL
  name: Amazon Athena
- description: Access LiveRamp identity data through the third-party provider integration
  name: LiveRamp
jsonld:
- class_count: 49
  name: Amazon Entity Resolution Context
  property_count: 48
  slug: amazon-entity-resolution-context
layout: provider
modified: '2026-04-19'
name: Amazon Entity Resolution
rules:
- name: Amazon Entity Resolution API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-entity-resolution-spectral-rules
skills: []
slug: amazon-entity-resolution
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Entity Resolution\ndescription: Amazon Entity Resolution is a service that helps you match and link related records across multiple applications, channels, and data stores using machine learning and configurable \n  matching techniques to identify and consolidate records that refer to the same entity.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/entity-resolution/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Amazon Web Services\n- AWS\n- Data Integration\n- Data Matching\n- Entity Resolution\n- Machine Learning\napis:\n- name: Amazon Entity Resolution API\n  description: API for creating and managing matching workflows, schema mappings, and ID mapping tables for matching and linking related records across data sources.\n  humanURL: https://aws.amazon.com/entity-resolution/\n  baseURL: https://entityresolution.amazonaws.com\n  tags:\n  - Data Integration\n\
  \  - Data Matching\n  - Entity Resolution\n  - Machine Learning\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/entityresolution/latest/userguide/\n  - type: OpenAPI\n    url: openapi/amazon-entity-resolution-openapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/entityresolution/latest/apireference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/entity-resolution/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/entity-resolution/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/entity-resolution/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-entity-resolution-access-denied-exception-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-entity-resolution-attribute-matching-model-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-entity-resolution-attribute-name-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-entity-resolution-context.jsonld\ncommon:\n- type: Portal\n\
  \  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/entity-resolution/\n- type: Documentation\n  url: https://docs.aws.amazon.com/entity-resolution/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/entityresolution/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: FAQ\n  url: https://aws.amazon.com/entity-resolution/faqs/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n\
  - type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/entity-resolution\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-entity-resolution-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-entity-resolution-capability.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/api.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-entity-resolution-vocabulary.yaml\n- type: Features\n  data:\n  - name: ML-Based Matching\n    description: Use machine learning models to match records across disparate datasets\n  - name: Rule-Based Matching\n    description: Configure deterministic matching rules for exact and fuzzy matching\n  - name: ID Mapping\n    description: Create and manage identity graphs linking records across data sources\n  - name: Schema Mapping\n    description: Map input data schemas to standardized formats for\
  \ consistent matching\n  - name: Third-Party Data Providers\n    description: Enrich records with data from LiveRamp, Unified ID 2.0, and others\n- type: UseCases\n  data:\n  - name: Customer Data Unification\n    description: Create a single customer view by matching records across CRM, marketing, and transaction systems\n  - name: Data Deduplication\n    description: Identify and remove duplicate records from databases and data lakes\n  - name: Identity Resolution for Advertising\n    description: Link user identities across devices and channels for targeted advertising\n  - name: Healthcare Record Matching\n    description: Match patient records across different healthcare providers and systems\n- type: Integrations\n  data:\n  - name: AWS Glue\n    description: Use Glue Data Catalog to discover and access input data sources\n  - name: Amazon S3\n    description: Store matching job input and output data in S3\n  - name: Amazon Athena\n    description: Query matching results using Athena\
  \ SQL\n  - name: LiveRamp\n    description: Access LiveRamp identity data through the third-party provider integration\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-entity-resolution/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- AWS
- Data Integration
- Data Matching
- Entity Resolution
- Machine Learning
url: https://aws.amazon.com/entity-resolution/
use_cases:
- description: Create a single customer view by matching records across CRM, marketing, and transaction systems
  name: Customer Data Unification
- description: Identify and remove duplicate records from databases and data lakes
  name: Data Deduplication
- description: Link user identities across devices and channels for targeted advertising
  name: Identity Resolution for Advertising
- description: Match patient records across different healthcare providers and systems
  name: Healthcare Record Matching
---
