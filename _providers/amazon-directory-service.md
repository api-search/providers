---
api_count: 1
apis:
- description: The AWS Directory Service API provides programmatic access to create and manage directories, trusts, snapshots, and domain controllers for Microsoft Active Directory in the AWS Cloud.
  name: AWS Directory Service API
  slug: aws-directory-service-api
capabilities:
- description: 'Workflow capability for identity engineers and cloud architects to manage AWS Managed Microsoft Active Directory, including directory provisioning, trust relationships, domain controllers, snapshots, '
  name: Amazon Directory Service Active Directory Management
  slug: active-directory-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/directoryservice/
- title: ''
  type: Website
  url: https://aws.amazon.com/directoryservice/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/directoryservice/
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
  url: https://aws.amazon.com/blogs/security/tag/aws-directory-service/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/directoryservicev2/
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/rules/amazon-directory-service-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/vocabulary/amazon-directory-service-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/capabilities/active-directory-management.yaml
created: '2026-03-16'
description: AWS Directory Service for Microsoft Active Directory, also known as AWS Managed Microsoft AD, enables your directory-aware workloads and AWS resources to use managed Active Directory in AWS. It provides a fully managed, highly available Microsoft Active Directory in the AWS Cloud, with features including trust relationships, domain controllers, LDAPS, and multi-account sharing.
features:
- description: Fully managed AWS Managed Microsoft Active Directory with automatic patching and monitoring
  name: Managed Microsoft AD
- description: Standalone managed directory powered by Samba 4 for basic AD functionality
  name: Simple AD
- description: Proxy service for connecting AWS applications to existing on-premises AD
  name: AD Connector
- description: One-way and two-way trust relationships between AWS and on-premises directories
  name: Trust Relationships
- description: Replicate your AWS Managed Microsoft AD across multiple AWS Regions
  name: Multi-Region Replication
- description: Share a single directory across multiple AWS accounts and VPCs
  name: Directory Sharing
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Join WorkSpaces desktops to managed AD for enterprise desktop management
  name: Amazon WorkSpaces
- description: Enable Windows Authentication for SQL Server RDS instances via managed AD
  name: Amazon RDS
- description: Use managed AD as identity source for centralized access management
  name: AWS IAM Identity Center
- description: Audit all Directory Service API calls for compliance and security monitoring
  name: AWS CloudTrail
- description: Receive directory event notifications via SNS topic subscriptions
  name: Amazon SNS
jsonld:
- class_count: 26
  name: Amazon Directory Service Context
  property_count: 101
  slug: amazon-directory-service-context
layout: provider
modified: '2026-04-19'
name: Amazon Directory Service
rules:
- name: Amazon Directory Service API Rules
  rule_count: 18
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 4
  slug: amazon-directory-service-spectral-rules
skills: []
slug: amazon-directory-service
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-directory-service\nname: Amazon Directory Service\ndescription: >-\n  AWS Directory Service for Microsoft Active Directory, also known as AWS\n  Managed Microsoft AD, enables your directory-aware workloads and AWS resources\n  to use managed Active Directory in AWS. It provides a fully managed,\n  highly available Microsoft Active Directory in the AWS Cloud, with features\n  including trust relationships, domain controllers, LDAPS, and multi-account sharing.\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Active Directory\n  - Authentication\n  - AWS\n  - Directory Services\n  - Identity Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/apis.yml\ncreated: \"2026-03-16\"\nmodified: \"2026-04-19\"\nspecificationVersion: \"0.19\"\napis:\n  - aid: amazon-directory-service:aws-directory-service-api\n    name: AWS Directory Service\
  \ API\n    description: >-\n      The AWS Directory Service API provides programmatic access to create and\n      manage directories, trusts, snapshots, and domain controllers for\n      Microsoft Active Directory in the AWS Cloud.\n    humanURL: https://aws.amazon.com/directoryservice/\n    baseURL: https://ds.amazonaws.com\n    tags:\n      - Active Directory\n      - Directory Services\n      - Identity Management\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/directoryservice/latest/devguide/what_is.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/openapi/amazon-directory-service-openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/directoryservice/getting-started/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/directoryservice/\n  - type: Website\n    url: https://aws.amazon.com/directoryservice/\n  - type:\
  \ Documentation\n    url: https://docs.aws.amazon.com/directoryservice/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/security/tag/aws-directory-service/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/directoryservicev2/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/rules/amazon-directory-service-spectral-rules.yml\n  - type: Vocabulary\n    url:\
  \ >-\n      https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/vocabulary/amazon-directory-service-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/capabilities/active-directory-management.yaml\n  - type: Features\n    data:\n      - name: Managed Microsoft AD\n        description: Fully managed AWS Managed Microsoft Active Directory with automatic patching and monitoring\n      - name: Simple AD\n        description: Standalone managed directory powered by Samba 4 for basic AD functionality\n      - name: AD Connector\n        description: Proxy service for connecting AWS applications to existing on-premises AD\n      - name: Trust Relationships\n        description: One-way and two-way trust relationships between AWS and on-premises directories\n      - name: Multi-Region Replication\n        description: Replicate your AWS Managed Microsoft\
  \ AD across multiple AWS Regions\n      - name: Directory Sharing\n        description: Share a single directory across multiple AWS accounts and VPCs\n  - type: UseCases\n    data:\n      - name: Hybrid Identity\n        description: Extend on-premises Active Directory into AWS for unified identity management\n      - name: Workload Authentication\n        description: Enable Windows and Linux workloads to join and authenticate against managed AD\n      - name: AWS Application Integration\n        description: Use managed AD for AWS WorkSpaces, RDS, and other AD-aware services\n      - name: LDAPS Encryption\n        description: Secure LDAP communications with certificates for compliance requirements\n      - name: Disaster Recovery\n        description: Use directory snapshots for point-in-time recovery of directory data\n  - type: Integrations\n    data:\n      - name: Amazon WorkSpaces\n        description: Join WorkSpaces desktops to managed AD for enterprise desktop management\n\
  \      - name: Amazon RDS\n        description: Enable Windows Authentication for SQL Server RDS instances via managed AD\n      - name: AWS IAM Identity Center\n        description: Use managed AD as identity source for centralized access management\n      - name: AWS CloudTrail\n        description: Audit all Directory Service API calls for compliance and security monitoring\n      - name: Amazon SNS\n        description: Receive directory event notifications via SNS topic subscriptions\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/apis.yml
tags:
- Active Directory
- Authentication
- AWS
- Directory Services
- Identity Management
url: https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/apis.yml
use_cases:
- description: Extend on-premises Active Directory into AWS for unified identity management
  name: Hybrid Identity
- description: Enable Windows and Linux workloads to join and authenticate against managed AD
  name: Workload Authentication
- description: Use managed AD for AWS WorkSpaces, RDS, and other AD-aware services
  name: AWS Application Integration
- description: Secure LDAP communications with certificates for compliance requirements
  name: LDAPS Encryption
- description: Use directory snapshots for point-in-time recovery of directory data
  name: Disaster Recovery
---
