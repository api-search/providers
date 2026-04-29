---
api_count: 1
api_specs:
- filename: amazon-signer.yaml
  format: yaml
  label: AWS Signer API
  slug: aws-signer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-signer/refs/heads/main/openapi/amazon-signer.yaml
apis:
- description: The AWS Signer API provides programmatic access to create and manage signing profiles, signing jobs, and signing platform permissions for code signing of Lambda functions and IoT device software.
  name: AWS Signer API
  slug: aws-signer-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/signer/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/signer/
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
  url: https://aws.amazon.com/blogs/compute/tag/aws-signer/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/signer/
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
  url: rules/amazon-signer-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-signer-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-signer.yaml
created: '2026-03-16'
description: AWS Signer is a fully managed code-signing service to ensure the trust and integrity of your code. It manages the code-signing certificate public and private keys and enables central management and deployment of code signing certificates for Lambda functions and IoT devices.
features:
- description: Security administrators define signing policies and which IAM roles can sign code.
  name: Centralized Code Signing
- description: Automatically manages code-signing certificate public and private keys.
  name: Certificate Management
- description: Central management and deployment of code-signing certificates.
  name: Lifecycle Management
- description: Integration with AWS CloudTrail tracks who generates signatures for compliance.
  name: Compliance Tracking
- description: No infrastructure to maintain — fully managed code signing service.
  name: Fully Managed
- description: Revoke signing profiles and individual signatures with effective timestamps.
  name: Signature Revocation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sign Lambda deployment packages; Lambda verifies signatures at deployment.
  name: AWS Lambda
- description: Sign firmware images for IoT microcontrollers and OTA updates.
  name: Amazon FreeRTOS
- description: Sign container images using Notation CLI stored in ECR registry.
  name: Amazon ECR
- description: Verify image ownership and integrity at Kubernetes deployment time.
  name: Amazon EKS
- description: Create or import SSL/TLS certificates used for code signing.
  name: AWS Certificate Manager
- description: Record and audit all API calls to AWS Signer for compliance.
  name: AWS CloudTrail
- description: Sign code for IoT devices managed by AWS IoT Device Management.
  name: AWS IoT Device Management
jsonld:
- class_count: 60
  name: Amazon Signer Context
  property_count: 69
  slug: amazon-signer-context
layout: provider
modified: '2026-04-19'
name: Amazon Signer
rules:
- name: Amazon Signer API Rules
  rule_count: 25
  severity_counts:
    error: 12
    hint: 0
    info: 4
    warn: 9
  slug: amazon-signer-spectral-rules
skills: []
slug: amazon-signer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-signer\nname: Amazon Signer\ndescription: >-\n  AWS Signer is a fully managed code-signing service to ensure the trust and\n  integrity of your code. It manages the code-signing certificate public and\n  private keys and enables central management and deployment of code signing\n  certificates for Lambda functions and IoT devices.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Code Signing\n- IoT\n- Lambda\n- Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-signer/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-signer:aws-signer-api\n  name: AWS Signer API\n  description: >-\n    The AWS Signer API provides programmatic access to create and manage\n    signing profiles, signing jobs, and signing platform permissions for\n    code signing of Lambda functions and IoT device software.\n  humanURL: https://aws.amazon.com/signer/\n\
  \  baseURL: https://signer.amazonaws.com\n  tags:\n  - Code Signing\n  - Lambda\n  - Security\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/signer/latest/api/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-signer.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/signer/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/signer/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/signer/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/signer/\n- type: Documentation\n  url: https://docs.aws.amazon.com/signer/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/tag/aws-signer/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/signer/\n-\
  \ type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-signer-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-signer-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-signer.yaml\n- type: Features\n  data:\n  - name: Centralized Code Signing\n    description: Security administrators define signing policies and which IAM roles can sign code.\n  - name: Certificate Management\n    description: Automatically manages code-signing certificate public and private keys.\n  - name: Lifecycle Management\n    description: Central management and deployment of code-signing certificates.\n  - name: Compliance Tracking\n    description: Integration with AWS CloudTrail tracks who generates signatures for compliance.\n\
  \  - name: Fully Managed\n    description: No infrastructure to maintain — fully managed code signing service.\n  - name: Signature Revocation\n    description: Revoke signing profiles and individual signatures with effective timestamps.\n- type: UseCases\n  data:\n  - name: Lambda Code Signing\n    description: Sign Lambda deployment packages to ensure only trusted code is deployed.\n  - name: IoT Firmware Signing\n    description: Sign firmware images for microcontrollers and over-the-air (OTA) updates via Amazon FreeRTOS.\n  - name: Container Image Signing\n    description: Sign container images using Notation CLI with Amazon ECR and verify at EKS deployment.\n  - name: Audit and Compliance\n    description: Track all signing operations via CloudTrail for audit and compliance requirements.\n- type: Integrations\n  data:\n  - name: AWS Lambda\n    description: Sign Lambda deployment packages; Lambda verifies signatures at deployment.\n  - name: Amazon FreeRTOS\n    description: Sign\
  \ firmware images for IoT microcontrollers and OTA updates.\n  - name: Amazon ECR\n    description: Sign container images using Notation CLI stored in ECR registry.\n  - name: Amazon EKS\n    description: Verify image ownership and integrity at Kubernetes deployment time.\n  - name: AWS Certificate Manager\n    description: Create or import SSL/TLS certificates used for code signing.\n  - name: AWS CloudTrail\n    description: Record and audit all API calls to AWS Signer for compliance.\n  - name: AWS IoT Device Management\n    description: Sign code for IoT devices managed by AWS IoT Device Management.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nx-type: company\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-signer/refs/heads/main/apis.yml
tags:
- AWS
- Code Signing
- IoT
- Lambda
- Security
url: https://raw.githubusercontent.com/api-evangelist/amazon-signer/refs/heads/main/apis.yml
use_cases:
- description: Sign Lambda deployment packages to ensure only trusted code is deployed.
  name: Lambda Code Signing
- description: Sign firmware images for microcontrollers and over-the-air (OTA) updates via Amazon FreeRTOS.
  name: IoT Firmware Signing
- description: Sign container images using Notation CLI with Amazon ECR and verify at EKS deployment.
  name: Container Image Signing
- description: Track all signing operations via CloudTrail for audit and compliance requirements.
  name: Audit and Compliance
---
