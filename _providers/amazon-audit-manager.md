---
api_count: 1
api_specs:
- filename: amazon-audit-manager-openapi.yml
  format: yaml
  label: Amazon Audit Manager API
  slug: amazon-audit-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/openapi/amazon-audit-manager-openapi.yml
apis:
- description: REST management API for Amazon Audit Manager covering assessments, frameworks, controls, evidence, assessment reports, and account settings.
  name: Amazon Audit Manager API
  slug: amazon-audit-manager-api
capabilities:
- description: Workflow capability for conducting continuous compliance auditing with Amazon Audit Manager including assessment creation, evidence collection, and report generation.
  name: Compliance Auditing Workflow
  slug: compliance-auditing
common: []
created: '2026-03-16'
description: AWS Audit Manager helps you continuously audit your AWS usage to simplify how you assess risk and compliance with regulations and industry standards.
features:
- Continuous compliance monitoring with automated evidence collection
- Pre-built frameworks for SOC 2, PCI DSS, HIPAA, GDPR, and more
- Custom framework and control creation for internal policies
- Automated evidence collection from AWS Config, Security Hub, and CloudTrail
- Evidence folder organization by control and control set
- Assessment delegation to process owners and resource owners
- Assessment report generation in PDF format
- Multi-account support through AWS Organizations
- Evidence finder for cross-assessment evidence search
- Integration with AWS Security Hub for security findings
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- AWS Config
- AWS Security Hub
- AWS CloudTrail
- AWS IAM
- Amazon S3
- Amazon SNS
- AWS Organizations
- AWS KMS
- Amazon CloudWatch
- AWS Systems Manager
jsonld:
- class_count: 6
  name: Amazon Audit Manager Context
  property_count: 0
  slug: amazon-audit-manager-context
layout: provider
modified: '2026-04-19'
name: Amazon Audit Manager
rules:
- name: Amazon Audit Manager API Rules
  rule_count: 15
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 5
  slug: amazon-audit-manager-spectral-rules
skills: []
slug: amazon-audit-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-audit-manager\nname: Amazon Audit Manager\ndescription: >-\n  AWS Audit Manager helps you continuously audit your AWS usage to simplify how you assess risk and compliance with regulations and industry standards.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon Audit Manager\n  - Compliance\n  - Audit\n  - Risk Management\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-audit-manager:amazon-audit-manager-api\n    name: Amazon Audit Manager API\n    description: >-\n      REST management API for Amazon Audit Manager covering assessments, frameworks, controls, evidence, assessment reports, and account settings.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/audit-manager/latest/APIReference/Welcome.html\n\
  \    baseURL: https://auditmanager.us-east-1.amazonaws.com\n    tags:\n      - Amazon Audit Manager\n      - Compliance\n      - Audit\n      - Risk Management\n      - AWS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/openapi/amazon-audit-manager-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/rules/amazon-audit-manager-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/capabilities/shared/audit-manager-api.yaml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/capabilities/compliance-auditing.yaml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/vocabulary/amazon-audit-manager-vocabulary.yaml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/json-schema/audit-manager-assessment-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/json-schema/audit-manager-framework-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/json-schema/audit-manager-control-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/json-structure/audit-manager-assessment-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/json-structure/audit-manager-framework-structure.json\n      - type: JSONLD\n        url: >-\n \
  \         https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/json-ld/amazon-audit-manager-context.jsonld\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/examples/audit-manager-assessment-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/examples/audit-manager-framework-example.json\ncommon:\n  - type: Features\n    data:\n      - Continuous compliance monitoring with automated evidence collection\n      - Pre-built frameworks for SOC 2, PCI DSS, HIPAA, GDPR, and more\n      - Custom framework and control creation for internal policies\n      - Automated evidence collection from AWS Config, Security Hub, and CloudTrail\n      - Evidence folder organization by control and control set\n      - Assessment delegation to process owners and resource owners\n      - Assessment\
  \ report generation in PDF format\n      - Multi-account support through AWS Organizations\n      - Evidence finder for cross-assessment evidence search\n      - Integration with AWS Security Hub for security findings\n  - type: UseCases\n    data:\n      - Automate SOC 2 compliance evidence collection\n      - Prepare for PCI DSS and HIPAA audits with continuous monitoring\n      - Build custom compliance frameworks for internal policies\n      - Delegate control reviews to business process owners\n      - Generate audit-ready reports for external auditors\n      - Monitor compliance posture across multiple AWS accounts\n  - type: Integrations\n    data:\n      - AWS Config\n      - AWS Security Hub\n      - AWS CloudTrail\n      - AWS IAM\n      - Amazon S3\n      - Amazon SNS\n      - AWS Organizations\n      - AWS KMS\n      - Amazon CloudWatch\n      - AWS Systems Manager\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/apis.yml
tags:
- Amazon Audit Manager
- Compliance
- Audit
- Risk Management
url: https://raw.githubusercontent.com/api-evangelist/amazon-audit-manager/refs/heads/main/apis.yml
use_cases:
- Automate SOC 2 compliance evidence collection
- Prepare for PCI DSS and HIPAA audits with continuous monitoring
- Build custom compliance frameworks for internal policies
- Delegate control reviews to business process owners
- Generate audit-ready reports for external auditors
- Monitor compliance posture across multiple AWS accounts
---
