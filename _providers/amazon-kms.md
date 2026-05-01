---
api_count: 1
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Amazon KMS API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/kms/2014-11-01/openapi.yaml
apis:
- description: The AWS Key Management Service API provides programmatic access to create and manage cryptographic keys, encrypt and decrypt data, generate data keys, and manage key policies and grants for controllin
  name: Amazon KMS API
  slug: ''
capabilities:
- description: Unified workflow capability for Amazon KMS combining resource management and operations.
  name: Amazon KMS Workflow
  slug: amazon-kms-workflow
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/security/category/security-identity-compliance/aws-key-management-service/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/kms/home
- title: ''
  type: CLI
  url: https://docs.aws.amazon.com/cli/latest/reference/kms/
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Portal
  url: https://aws.amazon.com/kms/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/kms/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/kms/pricing/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/kms/getting-started/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/kms/faqs/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: rules/amazon-kms-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-kms-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-kms-vocabulary.yaml
created: '2024-01-15'
description: AWS Key Management Service (KMS) is a managed service that makes it easy to create and control the cryptographic keys used to protect your data, integrated with other AWS services to simplify encryption of data stored and managed in those services.
features:
- description: Create, import, rotate, disable, delete, and audit usage of cryptographic keys from a central location.
  name: Centralized Key Management
- description: Keys are protected by FIPS 140-2 validated hardware security modules (HSMs).
  name: Hardware Security Modules
- description: Enable automatic annual rotation of KMS keys without changing key ARNs.
  name: Automatic Key Rotation
- description: Create multi-Region keys that can be replicated into multiple AWS Regions.
  name: Multi-Region Keys
- description: Generate and use asymmetric RSA and ECC key pairs for encryption and signing.
  name: Asymmetric Key Support
- description: Every KMS API call is logged to AWS CloudTrail for auditing and compliance.
  name: CloudTrail Integration
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Encrypt S3 objects at rest using SSE-KMS with customer managed keys.
  name: Amazon S3
- description: Encrypt RDS database instances and automated backups with KMS keys.
  name: Amazon RDS
- description: All KMS API usage is automatically logged for audit and compliance.
  name: AWS CloudTrail
- description: Encrypt secrets stored in Secrets Manager with KMS keys.
  name: AWS Secrets Manager
- description: Encrypt Lambda environment variables with KMS customer managed keys.
  name: AWS Lambda
jsonld:
- class_count: 1
  name: Amazon Kms Context
  property_count: 7
  slug: amazon-kms-context
layout: provider
modified: '2026-04-19'
name: Amazon KMS
rules:
- name: Amazon KMS API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-kms-spectral-rules
skills: []
slug: amazon-kms
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon KMS\nsegments:\n- Security\n- Encryption\ndescription: AWS Key Management Service (KMS) is a managed service that makes it easy to create and control the cryptographic keys used to protect your data, integrated with other AWS services to \n  simplify encryption of data stored and managed in those services.\nurl: https://aws.amazon.com/kms/\ntype: Index\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ntags:\n- AWS\n- Cryptography\n- Data Protection\n- Encryption\n- Key Management\n- Security\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon KMS API\n  description: The AWS Key Management Service API provides programmatic access to create and manage cryptographic keys, encrypt and decrypt data, generate data keys, and manage key policies and grants\n    for controlling access to encryption operations.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/kms/\n\
  \  baseURL: https://kms.amazonaws.com\n  tags:\n  - Cryptography\n  - Encryption\n  - Key Management\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kms/latest/developerguide/overview.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/kms/2014-11-01/openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/kms/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/kms/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/kms/faqs/\n  - type: Features\n    url: https://aws.amazon.com/kms/features/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kms/latest/developerguide/overview.html\n  - type: APIReference\n    url: https://docs.aws.amazon.com/kms/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-kms-openapi.yml\n  - type: JSONLD\n    url: json-ld/amazon-kms-context.jsonld\n  - type: JSONSchema\n    url: json-schema/amazon-kms-key-schema.json\ncommon:\n- type:\
  \ Blog\n  url: https://aws.amazon.com/blogs/security/category/security-identity-compliance/aws-key-management-service/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Console\n  url: https://console.aws.amazon.com/kms/home\n- type: CLI\n  url: https://docs.aws.amazon.com/cli/latest/reference/kms/\n- type: SDK\n  url: https://aws.amazon.com/tools/\n- type: StatusPage\n  url: https://status.aws.amazon.com/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: Portal\n  url: https://aws.amazon.com/kms/\n- type: Documentation\n  url: https://docs.aws.amazon.com/kms/\n- type: Pricing\n  url: https://aws.amazon.com/kms/pricing/\n- type: GettingStarted\n  url: https://aws.amazon.com/kms/getting-started/\n- type: FAQ\n  url: https://aws.amazon.com/kms/faqs/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n\
  - type: GitHubOrganization\n  url: https://github.com/aws\n- type: Features\n  data:\n  - name: Centralized Key Management\n    description: Create, import, rotate, disable, delete, and audit usage of cryptographic keys from a central location.\n  - name: Hardware Security Modules\n    description: Keys are protected by FIPS 140-2 validated hardware security modules (HSMs).\n  - name: Automatic Key Rotation\n    description: Enable automatic annual rotation of KMS keys without changing key ARNs.\n  - name: Multi-Region Keys\n    description: Create multi-Region keys that can be replicated into multiple AWS Regions.\n  - name: Asymmetric Key Support\n    description: Generate and use asymmetric RSA and ECC key pairs for encryption and signing.\n  - name: CloudTrail Integration\n    description: Every KMS API call is logged to AWS CloudTrail for auditing and compliance.\n- type: UseCases\n  data:\n  - name: Data at Rest Encryption\n    description: Encrypt data stored in S3, RDS, EBS, and\
  \ other AWS services using KMS keys.\n  - name: Envelope Encryption\n    description: Use KMS to generate data encryption keys for envelope encryption patterns.\n  - name: Digital Signatures\n    description: Use asymmetric KMS keys to sign and verify digital signatures.\n  - name: BYOK (Bring Your Own Key)\n    description: Import your own cryptographic key material into AWS KMS for compliance requirements.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Encrypt S3 objects at rest using SSE-KMS with customer managed keys.\n  - name: Amazon RDS\n    description: Encrypt RDS database instances and automated backups with KMS keys.\n  - name: AWS CloudTrail\n    description: All KMS API usage is automatically logged for audit and compliance.\n  - name: AWS Secrets Manager\n    description: Encrypt secrets stored in Secrets Manager with KMS keys.\n  - name: AWS Lambda\n    description: Encrypt Lambda environment variables with KMS customer managed keys.\n- type: SpectralRules\n\
  \  url: rules/amazon-kms-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-kms-workflow.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-kms-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-kms/refs/heads/main/apis.yml
tags:
- Cryptography
- Data Protection
- Encryption
- Key Management
- Security
url: https://aws.amazon.com/kms/
use_cases:
- description: Encrypt data stored in S3, RDS, EBS, and other AWS services using KMS keys.
  name: Data at Rest Encryption
- description: Use KMS to generate data encryption keys for envelope encryption patterns.
  name: Envelope Encryption
- description: Use asymmetric KMS keys to sign and verify digital signatures.
  name: Digital Signatures
- description: Import your own cryptographic key material into AWS KMS for compliance requirements.
  name: BYOK (Bring Your Own Key)
---
