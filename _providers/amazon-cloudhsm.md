---
api_count: 1
apis:
- description: API for creating and managing CloudHSM clusters and HSM instances for dedicated hardware-based cryptographic key management.
  name: Amazon CloudHSM API
  slug: ''
capabilities:
- description: Workflow for cryptographic key management using Amazon CloudHSM for Security Engineer personas.
  name: Amazon CloudHSM Cryptographic Key Management
  slug: cryptographic-key-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloudhsm/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cloudhsm/latest/APIReference/
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
  url: https://aws.amazon.com/blogs/security/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cloudhsm/
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
  url: https://stackoverflow.com/questions/tagged/aws-cloudhsm
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloudhsm-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloudhsm-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/cryptographic-key-management.yaml
created: '2026-03-16'
description: AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to manage cryptographic keys on dedicated FIPS 140-2 Level 3 validated, single-tenant HSM instances running within your own VPC for regulatory compliance and data security.
features:
- description: Dedicated single-tenant HSM instances meeting the highest FIPS validation levels.
  name: FIPS 140-2 Level 3 Validated
- description: Complete control over cryptographic keys with no AWS access to key material.
  name: Full Key Control
- description: Add or remove HSMs from clusters as needed, paying only for active resources hourly.
  name: Elastic Capacity
- description: Multi-AZ HSM clusters provide redundancy and automatic failover.
  name: High Availability
- description: Supports PKCS#11, Java JCE, and Microsoft CNG APIs for application integration.
  name: Industry-Standard APIs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use CloudHSM keys for Oracle TDE and SQL Server TDE in RDS.
  name: Amazon RDS
- description: Use CloudHSM as a custom key store for AWS KMS operations.
  name: AWS KMS
- description: HSM instances run inside your VPC for network isolation.
  name: Amazon VPC
- description: Control access to HSM cluster management operations.
  name: AWS IAM
- description: Audit HSM management API calls via CloudTrail.
  name: AWS CloudTrail
layout: provider
modified: '2026-04-19'
name: Amazon CloudHSM
rules:
- name: Amazon CloudHSM API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: amazon-cloudhsm-spectral-rules
skills: []
slug: amazon-cloudhsm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-cloudhsm\nname: Amazon CloudHSM\ndescription: >-\n  AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to manage cryptographic keys on dedicated FIPS 140-2 Level 3 validated, single-tenant HSM instances running within your own\n  VPC for regulatory compliance and data security.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- CloudHSM\n- Security\n- Cryptography\n- HSM\n- Compliance\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cloudhsm/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- name: Amazon CloudHSM API\n  description: API for creating and managing CloudHSM clusters and HSM instances for dedicated hardware-based cryptographic key management.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/cloudhsm/\n  baseURL:\
  \ https://cloudhsm.us-east-1.amazonaws.com\n  tags:\n  - AWS\n  - CloudHSM\n  - Security\n  - Cryptography\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cloudhsm/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudhsm/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudhsm/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudhsm/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/cloudhsm/latest/APIReference/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudhsmv2/\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/cloudhsm/\n- type: Documentation\n  url: https://docs.aws.amazon.com/cloudhsm/latest/APIReference/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n\
  - type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/security/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudhsm/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-cloudhsm\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-cloudhsm-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloudhsm-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/cryptographic-key-management.yaml\n- type: Features\n  data:\n  - name: FIPS 140-2 Level 3 Validated\n    description: Dedicated\
  \ single-tenant HSM instances meeting the highest FIPS validation levels.\n  - name: Full Key Control\n    description: Complete control over cryptographic keys with no AWS access to key material.\n  - name: Elastic Capacity\n    description: Add or remove HSMs from clusters as needed, paying only for active resources hourly.\n  - name: High Availability\n    description: Multi-AZ HSM clusters provide redundancy and automatic failover.\n  - name: Industry-Standard APIs\n    description: Supports PKCS#11, Java JCE, and Microsoft CNG APIs for application integration.\n- type: UseCases\n  data:\n  - name: Data Encryption\n    description: Protect sensitive data with hardware-backed encryption keys.\n  - name: SSL/TLS Offloading\n    description: Manage SSL/TLS certificates and private keys in dedicated HSMs.\n  - name: Certificate Authority\n    description: Secure private CA keys for organizations issuing their own certificates.\n  - name: Database Encryption\n    description: Support transparent\
  \ data encryption (TDE) for Oracle and SQL Server databases.\n  - name: Regulatory Compliance\n    description: Meet PCI DSS, HIPAA, and other regulatory requirements for key management.\n- type: Integrations\n  data:\n  - name: Amazon RDS\n    description: Use CloudHSM keys for Oracle TDE and SQL Server TDE in RDS.\n  - name: AWS KMS\n    description: Use CloudHSM as a custom key store for AWS KMS operations.\n  - name: Amazon VPC\n    description: HSM instances run inside your VPC for network isolation.\n  - name: AWS IAM\n    description: Control access to HSM cluster management operations.\n  - name: AWS CloudTrail\n    description: Audit HSM management API calls via CloudTrail.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudhsm/refs/heads/main/apis.yml
tags:
- CloudHSM
- Security
- Cryptography
- HSM
- Compliance
url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudhsm/refs/heads/main/apis.yml
use_cases:
- description: Protect sensitive data with hardware-backed encryption keys.
  name: Data Encryption
- description: Manage SSL/TLS certificates and private keys in dedicated HSMs.
  name: SSL/TLS Offloading
- description: Secure private CA keys for organizations issuing their own certificates.
  name: Certificate Authority
- description: Support transparent data encryption (TDE) for Oracle and SQL Server databases.
  name: Database Encryption
- description: Meet PCI DSS, HIPAA, and other regulatory requirements for key management.
  name: Regulatory Compliance
---
