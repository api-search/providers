---
api_count: 1
api_specs:
- filename: amazon-cloudtrail-openapi.yml
  format: yaml
  label: Amazon CloudTrail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/openapi/amazon-cloudtrail-openapi.yml
apis:
- description: API for creating and managing CloudTrail trails, event data stores, and channels for capturing AWS API activity and storing audit logs.
  name: Amazon CloudTrail API
  slug: ''
capabilities:
- description: Workflow for audit trail management using Amazon CloudTrail for Security Analyst personas.
  name: Amazon CloudTrail Audit Trail Management
  slug: audit-trail-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloudtrail/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/awscloudtrail/latest/APIReference/
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
  url: https://console.aws.amazon.com/cloudtrail/
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
  url: https://stackoverflow.com/questions/tagged/aws-cloudtrail
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloudtrail-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloudtrail-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/audit-trail-management.yaml
created: '2024-01-15'
description: AWS CloudTrail enables governance, compliance, operational auditing, and risk auditing of your AWS account by tracking user activity and API usage across AWS environments, hybrid setups, and multicloud deployments with immutable audit trails.
features:
- description: Consolidate activity events from AWS, external providers, on-premises, and SaaS into a unified audit trail.
  name: Event Aggregation
- description: Store audit-worthy events immutably to ensure tamper-proof compliance records.
  name: Immutable Audit Logs
- description: Detect unusual API activity patterns with anomaly detection on management and data events.
  name: CloudTrail Insights
- description: Investigate issues using SQL queries or natural language with Amazon Athena integration.
  name: SQL Query Support
- description: Create trails that capture events from all AWS regions in a single S3 bucket.
  name: Multi-Region Trails
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store CloudTrail logs in S3 buckets with lifecycle management.
  name: Amazon S3
- description: Query CloudTrail logs using SQL via Athena integration.
  name: Amazon Athena
- description: Stream CloudTrail events to CloudWatch Logs for real-time monitoring.
  name: Amazon CloudWatch
- description: Trigger Lambda functions based on CloudTrail events for automated response.
  name: AWS Lambda
- description: Send CloudTrail findings to Security Hub for centralized security management.
  name: AWS Security Hub
jsonld:
- class_count: 9
  name: Amazon Cloudtrail Context
  property_count: 21
  slug: amazon-cloudtrail-context
layout: provider
modified: '2026-04-19'
name: Amazon CloudTrail
rules:
- name: Amazon CloudTrail API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: amazon-cloudtrail-spectral-rules
skills: []
slug: amazon-cloudtrail
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-cloudtrail\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/apis.yml\nname: Amazon CloudTrail\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  AWS CloudTrail enables governance, compliance, operational auditing, and risk auditing of your AWS account by tracking user activity and API usage across AWS environments, hybrid setups, and multicloud\n  deployments with immutable audit trails.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon CloudTrail API\n  description: API for creating and managing CloudTrail trails, event data stores, and channels for capturing AWS API activity and storing audit logs.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/cloudtrail/\n  baseURL: https://cloudtrail.us-east-1.amazonaws.com\n  tags:\n  - AWS\n\
  \  - CloudTrail\n  - Audit\n  - Compliance\n  - Security\n  properties:\n  - type: OpenAPI\n    url: openapi/amazon-cloudtrail-openapi.yml\n  - type: Documentation\n    url: https://docs.aws.amazon.com/awscloudtrail/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudtrail/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudtrail/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudtrail/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/awscloudtrail/latest/APIReference/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudtrail/\n  - type: JSONSchema\n    url: json-schema/cloudtrail-create-trail-request-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudtrail-create-trail-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudtrail-describe-trails-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudtrail-lookup-events-request-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/cloudtrail-lookup-events-response-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-cloudtrail-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/cloudtrail/\n- type: Documentation\n  url: https://docs.aws.amazon.com/awscloudtrail/latest/APIReference/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/security/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudtrail/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n\
  \  url: https://stackoverflow.com/questions/tagged/aws-cloudtrail\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-cloudtrail-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloudtrail-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/audit-trail-management.yaml\n- type: Features\n  data:\n  - name: Event Aggregation\n    description: Consolidate activity events from AWS, external providers, on-premises, and SaaS into a unified audit trail.\n  - name: Immutable Audit Logs\n    description: Store audit-worthy events immutably to ensure tamper-proof compliance records.\n  - name: CloudTrail Insights\n    description: Detect unusual API activity patterns with anomaly detection on management and data events.\n  - name: SQL Query Support\n    description: Investigate issues using SQL queries or natural language with Amazon Athena integration.\n\
  \  - name: Multi-Region Trails\n    description: Create trails that capture events from all AWS regions in a single S3 bucket.\n- type: UseCases\n  data:\n  - name: Compliance Auditing\n    description: Demonstrate adherence to SOC, PCI DSS, and HIPAA regulations with audit logs.\n  - name: Security Monitoring\n    description: Record and monitor user and API activity for security incident detection.\n  - name: Operational Debugging\n    description: Investigate operational issues by querying historical API activity.\n  - name: Governance\n    description: Track who made changes to AWS resources and when for governance accountability.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Store CloudTrail logs in S3 buckets with lifecycle management.\n  - name: Amazon Athena\n    description: Query CloudTrail logs using SQL via Athena integration.\n  - name: Amazon CloudWatch\n    description: Stream CloudTrail events to CloudWatch Logs for real-time monitoring.\n  - name:\
  \ AWS Lambda\n    description: Trigger Lambda functions based on CloudTrail events for automated response.\n  - name: AWS Security Hub\n    description: Send CloudTrail findings to Security Hub for centralized security management.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- CloudTrail\n- Audit\n- Compliance\n- Governance\n- Security\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/apis.yml
tags:
- AWS
- CloudTrail
- Audit
- Compliance
- Governance
- Security
url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/apis.yml
use_cases:
- description: Demonstrate adherence to SOC, PCI DSS, and HIPAA regulations with audit logs.
  name: Compliance Auditing
- description: Record and monitor user and API activity for security incident detection.
  name: Security Monitoring
- description: Investigate operational issues by querying historical API activity.
  name: Operational Debugging
- description: Track who made changes to AWS resources and when for governance accountability.
  name: Governance
---
