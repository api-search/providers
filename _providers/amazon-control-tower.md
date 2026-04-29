---
api_count: 1
api_specs:
- filename: amazon-control-tower-openapi.yml
  format: yaml
  label: AWS Control Tower API
  slug: aws-control-tower-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-control-tower/refs/heads/main/openapi/amazon-control-tower-openapi.yml
apis:
- description: The AWS Control Tower API provides programmatic access to manage landing zones, organizational units, accounts, controls (guardrails), and baselines within your AWS environment, enabling automated gov
  name: AWS Control Tower API
  slug: aws-control-tower-api
capabilities:
- description: ''
  name: Governance Operations
  slug: governance-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/controltower/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/controltower/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/controltower/
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
  url: https://aws.amazon.com/blogs/mt/category/management-tools/aws-control-tower/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/controltower/
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
  type: Pricing
  url: https://aws.amazon.com/controltower/pricing/
- title: ''
  type: SpectralRules
  url: rules/amazon-control-tower-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-control-tower-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/governance-operations.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/control-tower.yaml
created: '2026-03-16'
description: AWS Control Tower provides the easiest way to set up and govern a secure, multi-account AWS environment based on best practices. It establishes a landing zone with pre-configured governance and guardrails, enabling organizations to maintain compliance and manage accounts at scale. With over 750 preconfigured controls, it automates account creation, OU registration, and compliance enforcement across the entire AWS organization.
features:
- description: Create, configure, update, reset, and delete AWS Control Tower landing zones programmatically via API, automating multi-account environment setup.
  name: Landing Zone Management
- description: Over 750 preconfigured controls (guardrails) covering security, operations, and compliance. Enable or disable controls on organizational units via API.
  name: Controls (Guardrails) Library
- description: Apply and manage baselines on organizational units (OUs) to register them with AWS Control Tower and enforce standard configurations programmatically.
  name: Baseline Registration
- description: Automate creation of AWS accounts with built-in governance, policies, and security controls through integration with AWS Organizations.
  name: Multi-Account Governance
- description: Deploy preventive, detective, and proactive controls to enforce compliance standards including CIS, NIST, PCI-DSS, HIPAA, and SOC 2.
  name: Compliance Enforcement
- description: Centralized audit logging to Amazon S3 and AWS CloudTrail integration for full visibility into API calls and governance actions.
  name: Audit and Logging
- description: Seamlessly integrate third-party security, compliance, and ITSM tools at scale to enhance your AWS multi-account environment.
  name: Third-Party Integrations
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with AWS Organizations for multi-account structure, OU management, and account creation within a Control Tower landing zone.
  name: AWS Organizations
- description: Account Factory integration through AWS Service Catalog for self-service account provisioning with pre-approved configurations.
  name: AWS Service Catalog
- description: All Control Tower API calls are logged to AWS CloudTrail for audit trails, security investigations, and compliance reporting.
  name: AWS CloudTrail
- description: Detective controls are implemented using AWS Config rules to continuously evaluate resource compliance within managed accounts.
  name: AWS Config
- description: Integrate Control Tower findings with AWS Security Hub for centralized security posture management and cross-account visibility.
  name: AWS Security Hub
- description: Launch landing zones and enable controls using CloudFormation templates and resource providers for infrastructure-as-code governance.
  name: AWS CloudFormation
- description: Community-supported Terraform providers for managing Control Tower landing zones, controls, and account factory configurations.
  name: Terraform
jsonld:
- class_count: 46
  name: Amazon Control Tower Context
  property_count: 36
  slug: amazon-control-tower-context
layout: provider
modified: '2026-04-19'
name: Amazon Control Tower
rules:
- name: Amazon Control Tower API Rules
  rule_count: 27
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 10
  slug: amazon-control-tower-spectral-rules
skills: []
slug: amazon-control-tower
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-control-tower\nname: Amazon Control Tower\ndescription: >-\n  AWS Control Tower provides the easiest way to set up and govern a secure,\n  multi-account AWS environment based on best practices. It establishes a\n  landing zone with pre-configured governance and guardrails, enabling\n  organizations to maintain compliance and manage accounts at scale. With over\n  750 preconfigured controls, it automates account creation, OU registration,\n  and compliance enforcement across the entire AWS organization.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Compliance\n  - Governance\n  - Landing Zone\n  - Multi-Account\n  - Security\n  - Controls\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-control-tower/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-control-tower:aws-control-tower-api\n    name: AWS Control\
  \ Tower API\n    description: >-\n      The AWS Control Tower API provides programmatic access to manage landing\n      zones, organizational units, accounts, controls (guardrails), and baselines\n      within your AWS environment, enabling automated governance at scale. Supports\n      operations for landing zone lifecycle, control enablement/disablement, and\n      OU baseline registration.\n    humanURL: https://docs.aws.amazon.com/controltower/latest/APIReference/Welcome.html\n    baseURL: https://controltower.amazonaws.com\n    tags:\n      - Governance\n      - Landing Zone\n      - Multi-Account\n      - Controls\n      - Baselines\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/controltower/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-control-tower-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/controltower/2018-11-28/openapi.yaml\n      - type: GettingStarted\n\
  \        url: https://aws.amazon.com/controltower/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/controltower/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/controltower/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/controltower/latest/APIReference/API_Operations.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/controltower/latest/userguide/what-is-control-tower.html\n      - type: JSONSchema\n        url: json-schema/landing-zone-schema.json\n      - type: JSONSchema\n        url: json-schema/enabled-control-schema.json\n      - type: JSONSchema\n        url: json-schema/enabled-baseline-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-control-tower-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/controltower/\n  - type: DeveloperPortal\n    url: https://aws.amazon.com/controltower/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/controltower/\n\
  \  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/mt/category/management-tools/aws-control-tower/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/controltower/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: Pricing\n    url: https://aws.amazon.com/controltower/pricing/\n  - type: SpectralRules\n    url: rules/amazon-control-tower-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-control-tower-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/governance-operations.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/shared/control-tower.yaml\n  - type: Features\n    data:\n      - name: Landing Zone Management\n        description: >-\n          Create, configure, update, reset, and delete AWS Control Tower landing\n          zones programmatically via API, automating multi-account environment setup.\n      - name: Controls (Guardrails) Library\n        description: >-\n          Over 750 preconfigured controls (guardrails) covering security, operations,\n          and compliance. Enable or disable controls on organizational units via API.\n      - name: Baseline Registration\n        description: >-\n          Apply and manage baselines on organizational units (OUs) to register them\n          with AWS Control Tower and enforce standard configurations programmatically.\n      - name: Multi-Account Governance\n        description: >-\n          Automate creation of AWS accounts with built-in governance, policies, and\n          security controls\
  \ through integration with AWS Organizations.\n      - name: Compliance Enforcement\n        description: >-\n          Deploy preventive, detective, and proactive controls to enforce compliance\n          standards including CIS, NIST, PCI-DSS, HIPAA, and SOC 2.\n      - name: Audit and Logging\n        description: >-\n          Centralized audit logging to Amazon S3 and AWS CloudTrail integration for\n          full visibility into API calls and governance actions.\n      - name: Third-Party Integrations\n        description: >-\n          Seamlessly integrate third-party security, compliance, and ITSM tools at\n          scale to enhance your AWS multi-account environment.\n  - type: UseCases\n    data:\n      - name: Multi-Account Environment Setup\n        description: >-\n          Quickly set up a secure, well-architected multi-account AWS environment\n          with landing zone configuration completed in under 30 minutes.\n      - name: Compliance Automation\n        description:\
  \ >-\n          Deploy preconfigured controls to enforce regulatory compliance standards\n          such as PCI-DSS, HIPAA, NIST, and SOC 2 across all accounts.\n      - name: Account Vending\n        description: >-\n          Automate provisioning of new AWS accounts with built-in security policies,\n          IAM roles, and governance configurations using Account Factory.\n      - name: OU Governance\n        description: >-\n          Programmatically register organizational units with Control Tower baselines\n          and apply targeted controls for department-specific governance.\n      - name: Risk and Posture Management\n        description: >-\n          Continuously monitor compliance posture across all accounts and receive\n          alerts when controls are violated or drift is detected.\n  - type: Integrations\n    data:\n      - name: AWS Organizations\n        description: >-\n          Native integration with AWS Organizations for multi-account structure,\n          OU\
  \ management, and account creation within a Control Tower landing zone.\n      - name: AWS Service Catalog\n        description: >-\n          Account Factory integration through AWS Service Catalog for self-service\n          account provisioning with pre-approved configurations.\n      - name: AWS CloudTrail\n        description: >-\n          All Control Tower API calls are logged to AWS CloudTrail for audit\n          trails, security investigations, and compliance reporting.\n      - name: AWS Config\n        description: >-\n          Detective controls are implemented using AWS Config rules to continuously\n          evaluate resource compliance within managed accounts.\n      - name: AWS Security Hub\n        description: >-\n          Integrate Control Tower findings with AWS Security Hub for centralized\n          security posture management and cross-account visibility.\n      - name: AWS CloudFormation\n        description: >-\n          Launch landing zones and enable controls\
  \ using CloudFormation templates\n          and resource providers for infrastructure-as-code governance.\n      - name: Terraform\n        description: >-\n          Community-supported Terraform providers for managing Control Tower landing\n          zones, controls, and account factory configurations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-control-tower/refs/heads/main/apis.yml
tags:
- AWS
- Compliance
- Governance
- Landing Zone
- Multi-Account
- Security
- Controls
url: https://raw.githubusercontent.com/api-evangelist/amazon-control-tower/refs/heads/main/apis.yml
use_cases:
- description: Quickly set up a secure, well-architected multi-account AWS environment with landing zone configuration completed in under 30 minutes.
  name: Multi-Account Environment Setup
- description: Deploy preconfigured controls to enforce regulatory compliance standards such as PCI-DSS, HIPAA, NIST, and SOC 2 across all accounts.
  name: Compliance Automation
- description: Automate provisioning of new AWS accounts with built-in security policies, IAM roles, and governance configurations using Account Factory.
  name: Account Vending
- description: Programmatically register organizational units with Control Tower baselines and apply targeted controls for department-specific governance.
  name: OU Governance
- description: Continuously monitor compliance posture across all accounts and receive alerts when controls are violated or drift is detected.
  name: Risk and Posture Management
---
