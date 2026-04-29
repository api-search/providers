---
api_count: 1
apis:
- description: The Amazon S3 Glacier API provides programmatic access to manage long-term archive storage. It enables developers to create and manage vaults, upload and retrieve archives, configure vault notificatio
  name: Amazon S3 Glacier API
  slug: ''
capabilities:
- description: Workflow capability for Amazon S3 Glacier. Enables automation of Amazon S3 Glacier resources for cloud operations teams.
  name: Amazon S3 Glacier Operations
  slug: amazon-s3-glacier
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Portal
  url: https://aws.amazon.com/s3/storage-classes/glacier/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/amazonglacier/
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
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Portal
  url: https://console.aws.amazon.com/glacier/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: JSON-LD
  url: json-ld/amazon-s3-glacier-api-describe-vault-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-s3-glacier-api-job-parameters-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-s3-glacier-api-list-vaults-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-s3-glacier-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-s3-glacier-vault-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/amazon-s3-glacier-api-describe-vault-output-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-s3-glacier-api-job-parameters-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-s3-glacier-api-list-vaults-output-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-s3-glacier-vault-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-s3-glacier-api-describe-vault-output-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-s3-glacier-api-job-parameters-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-s3-glacier-api-list-vaults-output-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-s3-glacier-vault-structure.json
- title: ''
  type: Example
  url: examples/amazon-s3-glacier-api-describe-vault-output-example.json
- title: ''
  type: Example
  url: examples/amazon-s3-glacier-api-job-parameters-example.json
- title: ''
  type: Example
  url: examples/amazon-s3-glacier-api-list-vaults-output-example.json
- title: ''
  type: Example
  url: examples/amazon-s3-glacier-vault-example.json
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-s3-glacier.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-s3-glacier.yaml
- title: ''
  type: SpectralRules
  url: rules/amazon-s3-glacier-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-s3-glacier-vocabulary.yaml
- title: ''
  type: OpenAPI
  url: openapi/amazon-s3-glacier-api-openapi.yml
created: '2024-01-15'
description: Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 storage class purpose-built for long-term data archiving and digital preservation. It provides comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements, with retrieval options ranging from minutes to hours depending on your access needs.
features: []
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 1
  name: Amazon S3 Glacier Api Describe Vault Context
  property_count: 6
  slug: amazon-s3-glacier-api-describe-vault-context
- class_count: 1
  name: Amazon S3 Glacier Api Job Parameters Context
  property_count: 6
  slug: amazon-s3-glacier-api-job-parameters-context
- class_count: 1
  name: Amazon S3 Glacier Api List Vaults Context
  property_count: 2
  slug: amazon-s3-glacier-api-list-vaults-context
- class_count: 0
  name: Amazon S3 Glacier Context
  property_count: 3
  slug: amazon-s3-glacier-context
- class_count: 1
  name: Amazon S3 Glacier Vault Context
  property_count: 9
  slug: amazon-s3-glacier-vault-context
layout: provider
modified: '2026-04-19'
name: Amazon S3 Glacier
rules:
- name: Amazon S3 Glacier API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 10
  slug: amazon-s3-glacier-spectral-rules
skills: []
slug: amazon-s3-glacier
solutions: []
source_yaml: "name: Amazon S3 Glacier\ndescription: Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 storage class purpose-built for long-term data archiving and digital preservation. It provides comprehensive \n  security and compliance capabilities that can help meet even the most stringent regulatory requirements, with retrieval options ranging from minutes to hours depending on your access needs.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon S3 Glacier API\n  description: >-\n    The Amazon S3 Glacier API provides programmatic access to manage long-term\n    archive storage. It enables developers to create and manage vaults, upload\n    and retrieve archives, configure vault notifications and access policies,\n    initiate inventory retrieval jobs, and manage\
  \ data lifecycle for cost-\n    effective archival storage.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/s3/storage-classes/glacier/\n  baseURL: https://glacier.amazonaws.com\n  tags:\n  - Archive\n  - AWS\n  - Backup\n  - Storage\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazonglacier/\n  - type: OpenAPI\n    url: openapi/amazon-s3-glacier-openapi.yml\n  - type: Pricing\n    url: https://aws.amazon.com/s3/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/s3/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/s3/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Portal\n  url: https://aws.amazon.com/s3/storage-classes/glacier/\n- type: Documentation\n  url: https://docs.aws.amazon.com/amazonglacier/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n\
  - type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Portal\n  url: https://console.aws.amazon.com/glacier/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: JSON-LD\n  url: json-ld/amazon-s3-glacier-api-describe-vault-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-s3-glacier-api-job-parameters-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-s3-glacier-api-list-vaults-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-s3-glacier-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-s3-glacier-vault-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-s3-glacier-api-describe-vault-output-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-s3-glacier-api-job-parameters-schema.json\n\
  - type: JSONSchema\n  url: json-schema/amazon-s3-glacier-api-list-vaults-output-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-s3-glacier-vault-schema.json\n- type: JSONStructure\n  url: json-structure/amazon-s3-glacier-api-describe-vault-output-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-s3-glacier-api-job-parameters-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-s3-glacier-api-list-vaults-output-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-s3-glacier-vault-structure.json\n- type: Example\n  url: examples/amazon-s3-glacier-api-describe-vault-output-example.json\n- type: Example\n  url: examples/amazon-s3-glacier-api-job-parameters-example.json\n- type: Example\n  url: examples/amazon-s3-glacier-api-list-vaults-output-example.json\n- type: Example\n  url: examples/amazon-s3-glacier-vault-example.json\n- type: NaftikoCapability\n  url: capabilities/amazon-s3-glacier.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-s3-glacier.yaml\n\
  - type: SpectralRules\n  url: rules/amazon-s3-glacier-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-s3-glacier-vocabulary.yaml\n- type: OpenAPI\n  url: openapi/amazon-s3-glacier-api-openapi.yml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- Archive\n- AWS\n- Backup\n- Storage\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/apis.yml
tags:
- Archive
- AWS
- Backup
- Storage
url: https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/apis.yml
use_cases: []
---
