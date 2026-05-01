---
api_count: 1
api_specs:
- filename: amazon-iam-openapi.yml
  format: yaml
  label: AWS IAM API
  slug: aws-iam-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/openapi/amazon-iam-openapi.yml
apis:
- description: The AWS IAM API provides programmatic access to manage users, groups, roles, policies, and access keys for securing access to AWS services and resources.
  name: AWS IAM API
  slug: aws-iam-api
capabilities:
- description: Unified capability for cloud administrators to manage IAM users, roles, groups, and policies for AWS account access control and security governance.
  name: Amazon IAM - Access Management
  slug: iam-access-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iam/
- title: ''
  type: Website
  url: https://aws.amazon.com/iam/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/IAM/latest/UserGuide/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/security/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/iam/
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
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-iam
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: JSONLD
  url: json-ld/amazon-iam-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/amazon-iam-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iam.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/iam-access-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iam-vocabulary.yaml
created: '2026-03-16'
description: Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their access to AWS resources. IAM is a feature of your AWS account offered at no additional charge.
features:
- description: Create, manage, and delete IAM users with fine-grained permissions.
  name: User Management
- description: Define IAM roles that can be assumed by users, services, or applications.
  name: Role-Based Access Control
- description: Create and attach identity-based and resource-based policies to control access.
  name: Policy Management
- description: Enable MFA for IAM users to add an extra layer of security.
  name: Multi-Factor Authentication
- description: Programmatically manage AWS access keys for long-term credentials.
  name: Access Key Management
- description: Use permission boundaries to define the maximum permissions an entity can have.
  name: Permission Boundaries
- description: Centrally control the maximum available permissions across AWS accounts.
  name: Service Control Policies
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Apply Service Control Policies across multiple AWS accounts in an organization.
  name: AWS Organizations
- description: Log all IAM API calls for auditing and compliance tracking.
  name: AWS CloudTrail
- description: Monitor IAM configuration changes and evaluate compliance with rules.
  name: AWS Config
- description: Centralize IAM security findings with other AWS security services.
  name: AWS Security Hub
- description: Federate Cognito user pool identities with IAM roles for application access.
  name: Amazon Cognito
jsonld:
- class_count: 0
  name: Amazon Iam Context
  property_count: 6
  slug: amazon-iam-context
layout: provider
modified: '2026-04-19'
name: Amazon IAM
rules:
- name: Amazon IAM API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 3
    warn: 8
  slug: amazon-iam-spectral-rules
skills: []
slug: amazon-iam
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-iam\nname: Amazon IAM\ndescription: >-\n  Amazon Identity and Access Management (IAM) enables you to manage access to\n  AWS services and resources securely. Using IAM, you can create and manage AWS\n  users, groups, roles, and policies, and use permissions to allow and deny their\n  access to AWS resources. IAM is a feature of your AWS account offered at no\n  additional charge.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/apis.yml\nbaseURL: https://iam.amazonaws.com\ntags:\n  - Access Management\n  - Authentication\n  - Authorization\n  - AWS\n  - Identity\n  - Security\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iam:aws-iam-api\n    name: AWS IAM API\n    description: >-\n      The AWS IAM API provides programmatic access to manage users, groups, roles,\n      policies,\
  \ and access keys for securing access to AWS services and resources.\n    humanURL: https://aws.amazon.com/iam/\n    baseURL: https://iam.amazonaws.com\n    tags:\n      - Access Management\n      - Authentication\n      - Authorization\n      - Identity\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/IAM/latest/APIReference/\n      - type: OpenAPI\n        url: openapi/amazon-iam-openapi.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/IAM/latest/APIReference/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/iam/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iam/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-iam-user-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-iam-user-structure.json\n      - type: Example\n    \
  \    url: examples/amazon-iam-user-example.json\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iam/\n  - type: Website\n    url: https://aws.amazon.com/iam/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/IAM/latest/UserGuide/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/support/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/security/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/iam/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: YouTube\n    url: https://www.youtube.com/user/AmazonWebServices\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/amazon-iam\n\
  \  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: JSONLD\n    url: json-ld/amazon-iam-context.jsonld\n  - type: SpectralRules\n    url: rules/amazon-iam-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iam.yaml\n  - type: NaftikoCapability\n    url: capabilities/iam-access-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iam-vocabulary.yaml\n  - type: Features\n    data:\n      - name: User Management\n        description: Create, manage, and delete IAM users with fine-grained permissions.\n      - name: Role-Based Access Control\n        description: Define IAM roles that can be assumed by users, services, or applications.\n      - name: Policy Management\n        description: Create and attach identity-based and resource-based policies to control access.\n      - name: Multi-Factor Authentication\n        description: Enable MFA for IAM users to add an extra layer of security.\n      - name: Access Key Management\n\
  \        description: Programmatically manage AWS access keys for long-term credentials.\n      - name: Permission Boundaries\n        description: Use permission boundaries to define the maximum permissions an entity can have.\n      - name: Service Control Policies\n        description: Centrally control the maximum available permissions across AWS accounts.\n  - type: UseCases\n    data:\n      - name: Least Privilege Access\n        description: Grant only the permissions required for specific tasks to reduce the attack surface.\n      - name: Cross-Account Access\n        description: Enable users in one AWS account to assume roles in another account.\n      - name: Service-to-Service Authorization\n        description: Allow AWS services to access other services on your behalf through service roles.\n      - name: Temporary Credentials\n        description: Use STS to issue temporary security credentials for short-lived access.\n      - name: Security Compliance\n        description:\
  \ Audit IAM configurations to ensure compliance with security policies and regulations.\n  - type: Integrations\n    data:\n      - name: AWS Organizations\n        description: Apply Service Control Policies across multiple AWS accounts in an organization.\n      - name: AWS CloudTrail\n        description: Log all IAM API calls for auditing and compliance tracking.\n      - name: AWS Config\n        description: Monitor IAM configuration changes and evaluate compliance with rules.\n      - name: AWS Security Hub\n        description: Centralize IAM security findings with other AWS security services.\n      - name: Amazon Cognito\n        description: Federate Cognito user pool identities with IAM roles for application access.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/apis.yml
tags:
- Access Management
- Authentication
- Authorization
- Identity
- Security
url: https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/apis.yml
use_cases:
- description: Grant only the permissions required for specific tasks to reduce the attack surface.
  name: Least Privilege Access
- description: Enable users in one AWS account to assume roles in another account.
  name: Cross-Account Access
- description: Allow AWS services to access other services on your behalf through service roles.
  name: Service-to-Service Authorization
- description: Use STS to issue temporary security credentials for short-lived access.
  name: Temporary Credentials
- description: Audit IAM configurations to ensure compliance with security policies and regulations.
  name: Security Compliance
---
