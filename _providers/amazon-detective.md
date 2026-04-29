---
api_count: 1
api_specs:
- filename: amazon-detective-openapi.yml
  format: yaml
  label: Amazon Detective API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-detective/refs/heads/main/openapi/amazon-detective-openapi.yml
apis:
- description: The Amazon Detective API provides programmatic access to manage security investigation workflows. It enables developers to create and manage behavior graphs, invite and manage member accounts, start a
  name: Amazon Detective API
  slug: ''
capabilities:
- description: Workflow capability for SOC analysts and security engineers to conduct end-to-end security investigations using Amazon Detective. Combines behavior graph management, member account administration, inv
  name: Amazon Detective Security Investigation
  slug: security-investigation
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/detective/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/detective/
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
  type: Console
  url: https://console.aws.amazon.com/detective/
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
  type: Blog
  url: https://aws.amazon.com/blogs/security/tag/amazon-detective/
- title: ''
  type: ReleaseNotes
  url: https://docs.aws.amazon.com/detective/latest/userguide/release-notes.html
- title: ''
  type: SpectralRules
  url: rules/amazon-detective-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-detective-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/security-investigation.yaml
created: '2024-01-15'
description: Amazon Detective is a security investigation service that makes it easy to analyze, investigate, and quickly identify the root cause of potential security issues or suspicious activities. It automatically collects log data from your AWS resources and uses machine learning, statistical analysis, and graph theory to build interactive visualizations that help you conduct faster and more efficient security investigations.
features:
- description: Automatically builds a behavior graph from log data using machine learning and graph theory to visualize security issues.
  name: Behavior Graph Analysis
- description: Start and manage structured investigations on IAM users and roles with scoped time ranges and severity scoring.
  name: Security Investigations
- description: Automatically identifies indicators including impossible travel, flagged IP addresses, new geolocations, new user agents, and TTP observations.
  name: Indicators of Compromise
- description: Aggregate security data from multiple AWS accounts using an administrator account and member account model.
  name: Multi-Account Support
- description: Automatically enable new organization accounts as member accounts in the organization behavior graph.
  name: AWS Organizations Integration
- description: Ingest security telemetry from CloudTrail, VPC Flow Logs, GuardDuty findings, EKS audit logs, and Active Directory audit logs.
  name: Data Source Packages
- description: Provides interactive graph visualizations in the AWS console to explore entity relationships and security events.
  name: Interactive Visualizations
- description: Assigns severity levels (Informational, Low, Medium, High, Critical) based on likelihood and impact of compromise indicators.
  name: Investigation Severity Scoring
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Automatically ingests GuardDuty findings into the behavior graph for deeper investigation context.
  name: Amazon GuardDuty
- description: Ingests CloudTrail API call logs to track user and service activity across your AWS environment.
  name: AWS CloudTrail
- description: Analyzes VPC flow logs to identify network communication patterns and anomalies.
  name: Amazon VPC Flow Logs
- description: Optionally ingests EKS audit logs to monitor Kubernetes API server activity.
  name: Amazon EKS
- description: Integrates with AWS Organizations to manage multi-account behavior graphs and auto-enable new accounts.
  name: AWS Organizations
- description: Surfaces Detective investigation context within Security Hub for consolidated security findings.
  name: AWS Security Hub
jsonld:
- class_count: 53
  name: Amazon Detective Context
  property_count: 55
  slug: amazon-detective-context
layout: provider
modified: '2026-04-19'
name: Amazon Detective
rules:
- name: Amazon Detective API Rules
  rule_count: 39
  severity_counts:
    error: 18
    hint: 0
    info: 9
    warn: 12
  slug: amazon-detective-spectral-rules
skills: []
slug: amazon-detective
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Detective\ndescription: Amazon Detective is a security investigation service that makes it easy to analyze, investigate, and quickly identify the root cause of potential security issues or suspicious activities. It automatically collects log data from your AWS resources and uses machine learning, statistical analysis, and graph theory to build interactive visualizations that help you conduct faster and more efficient security investigations.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/detective/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n  - name: Amazon Detective API\n    description: >-\n      The Amazon Detective API provides programmatic access to manage security\n      investigation workflows. It enables developers to create and manage behavior\n      graphs, invite and manage member accounts, start and manage investigations,\n      list indicators of compromise, manage data source\
  \ packages, and configure\n      AWS Organizations integration for multi-account security management.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/detective/\n    baseURL: https://api.detective.amazonaws.com\n    tags:\n      - AWS\n      - Forensics\n      - Investigation\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/detective/\n      - type: OpenAPI\n        url: openapi/amazon-detective-openapi.yml\n      - type: Pricing\n        url: https://aws.amazon.com/detective/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/detective/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/detective/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-detective-graph-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-detective-member-detail-schema.json\n      - type: JSONSchema\n\
  \        url: json-schema/amazon-detective-investigation-detail-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-detective-indicator-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-detective-administrator-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-detective-graph-structure.json\n      - type: JSONStructure\n        url: json-structure/amazon-detective-member-detail-structure.json\n      - type: JSONStructure\n        url: json-structure/amazon-detective-investigation-detail-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-detective-context.jsonld\n      - type: Example\n        url: examples/amazon-detective-graph-example.json\n      - type: Example\n        url: examples/amazon-detective-member-detail-example.json\n      - type: Example\n        url: examples/amazon-detective-investigation-detail-example.json\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n\
  \    url: https://aws.amazon.com/detective/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/detective/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/detective/\n  - type: SignUp\n    url: https://signin.aws.amazon.com/signup?request_type=register\n  - type: Login\n    url: https://aws.amazon.com/console/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/security/tag/amazon-detective/\n  - type: ReleaseNotes\n    url: https://docs.aws.amazon.com/detective/latest/userguide/release-notes.html\n  - type: SpectralRules\n    url: rules/amazon-detective-spectral-rules.yml\n\
  \  - type: Vocabulary\n    url: vocabulary/amazon-detective-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/security-investigation.yaml\n  - type: Features\n    data:\n      - name: Behavior Graph Analysis\n        description: Automatically builds a behavior graph from log data using machine learning and graph theory to visualize security issues.\n      - name: Security Investigations\n        description: Start and manage structured investigations on IAM users and roles with scoped time ranges and severity scoring.\n      - name: Indicators of Compromise\n        description: Automatically identifies indicators including impossible travel, flagged IP addresses, new geolocations, new user agents, and TTP observations.\n      - name: Multi-Account Support\n        description: Aggregate security data from multiple AWS accounts using an administrator account and member account model.\n      - name: AWS Organizations Integration\n        description: Automatically enable\
  \ new organization accounts as member accounts in the organization behavior graph.\n      - name: Data Source Packages\n        description: Ingest security telemetry from CloudTrail, VPC Flow Logs, GuardDuty findings, EKS audit logs, and Active Directory audit logs.\n      - name: Interactive Visualizations\n        description: Provides interactive graph visualizations in the AWS console to explore entity relationships and security events.\n      - name: Investigation Severity Scoring\n        description: Assigns severity levels (Informational, Low, Medium, High, Critical) based on likelihood and impact of compromise indicators.\n  - type: UseCases\n    data:\n      - name: Security Incident Investigation\n        description: Rapidly investigate security incidents by analyzing entity behavior, network activity, and API call patterns across your AWS environment.\n      - name: Threat Hunting\n        description: Proactively search for suspicious activity and potential threats using\
  \ behavior analysis and machine learning across your AWS accounts.\n      - name: Root Cause Analysis\n        description: Identify the root cause of security issues by exploring the relationships between resources, users, and events in a behavior graph.\n      - name: Compliance Forensics\n        description: Collect and preserve forensic evidence for compliance investigations using structured investigations with defined scope and time ranges.\n      - name: Multi-Account Security Operations\n        description: Centrally manage security investigations across an AWS Organization from a single administrator account.\n  - type: Integrations\n    data:\n      - name: Amazon GuardDuty\n        description: Automatically ingests GuardDuty findings into the behavior graph for deeper investigation context.\n      - name: AWS CloudTrail\n        description: Ingests CloudTrail API call logs to track user and service activity across your AWS environment.\n      - name: Amazon VPC Flow Logs\n\
  \        description: Analyzes VPC flow logs to identify network communication patterns and anomalies.\n      - name: Amazon EKS\n        description: Optionally ingests EKS audit logs to monitor Kubernetes API server activity.\n      - name: AWS Organizations\n        description: Integrates with AWS Organizations to manage multi-account behavior graphs and auto-enable new accounts.\n      - name: AWS Security Hub\n        description: Surfaces Detective investigation context within Security Hub for consolidated security findings.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - AWS\n  - Forensics\n  - Investigation\n  - Security\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-detective/refs/heads/main/apis.yml
tags:
- AWS
- Forensics
- Investigation
- Security
url: https://aws.amazon.com/detective/
use_cases:
- description: Rapidly investigate security incidents by analyzing entity behavior, network activity, and API call patterns across your AWS environment.
  name: Security Incident Investigation
- description: Proactively search for suspicious activity and potential threats using behavior analysis and machine learning across your AWS accounts.
  name: Threat Hunting
- description: Identify the root cause of security issues by exploring the relationships between resources, users, and events in a behavior graph.
  name: Root Cause Analysis
- description: Collect and preserve forensic evidence for compliance investigations using structured investigations with defined scope and time ranges.
  name: Compliance Forensics
- description: Centrally manage security investigations across an AWS Organization from a single administrator account.
  name: Multi-Account Security Operations
---
