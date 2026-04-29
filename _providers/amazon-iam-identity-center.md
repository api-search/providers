---
api_count: 2
api_specs:
- filename: amazon-iam-identity-center-sso-admin-openapi-original.yml
  format: yaml
  label: AWS IAM Identity Center SSO Admin API
  slug: aws-sso-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/openapi/amazon-iam-identity-center-sso-admin-openapi-original.yml
- filename: amazon-iam-identity-center-identitystore-openapi-original.yml
  format: yaml
  label: AWS IAM Identity Center Identity Store API
  slug: aws-identitystore-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/openapi/amazon-iam-identity-center-identitystore-openapi-original.yml
apis:
- description: Manages permission sets, account assignments, instances, and SSO configurations for centralized identity and access management across AWS accounts and organizations.
  name: AWS IAM Identity Center SSO Admin API
  slug: aws-sso-admin-api
- description: Manages users, groups, and group memberships in the IAM Identity Center identity store, enabling programmatic provisioning of workforce identities.
  name: AWS IAM Identity Center Identity Store API
  slug: aws-identitystore-api
capabilities:
- description: Unified capability for IT administrators to manage workforce identities, provision access to AWS accounts, and configure SSO for enterprise applications.
  name: Amazon IAM Identity Center - Identity and Access Management
  slug: identity-access-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iam/identity-center/
- title: ''
  type: Website
  url: https://aws.amazon.com/iam/identity-center/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/singlesignon/
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
  url: https://aws.amazon.com/blogs/security/tag/aws-iam-identity-center/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/singlesignon/
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
  url: rules/amazon-iam-identity-center-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/sso-admin.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/identitystore.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/identity-access-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iam-identity-center-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iam-identity-center-context.jsonld
created: '2026-03-16'
description: AWS IAM Identity Center (successor to AWS Single Sign-On) is where you create, or connect, your workforce identities in AWS once and manage access centrally across your AWS organization. You can create user identities directly in IAM Identity Center, or bring them from Microsoft Active Directory, and then use IAM Identity Center to manage user access to AWS accounts and business applications with single sign-on.
features:
- description: Create and manage workforce user identities directly or connect from an external identity provider.
  name: Workforce Identity Management
- description: Enable employees to sign in once and access all assigned AWS accounts and business applications.
  name: Single Sign-On
- description: Manage access to multiple AWS accounts from a single place using permission sets.
  name: Centralized Access Management
- description: Connect Microsoft Active Directory, Okta, Azure AD, and other SAML 2.0 identity providers.
  name: External Identity Provider Integration
- description: Define and reuse permission policies that can be assigned to users across multiple AWS accounts.
  name: Permission Set Management
- description: Automatically provision and de-provision users and groups using SCIM 2.0.
  name: Automated Provisioning
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sync users and groups from Active Directory for SSO and access management.
  name: Microsoft Active Directory
- description: Connect Okta as an external identity provider using SAML 2.0 and SCIM.
  name: Okta
- description: Federate with Azure AD for identity synchronization and SSO.
  name: Azure Active Directory
- description: Manage access across all accounts in an AWS Organization from a single SSO configuration.
  name: AWS Organizations
jsonld:
- class_count: 130
  name: Amazon Iam Identity Center Context
  property_count: 96
  slug: amazon-iam-identity-center-context
layout: provider
modified: '2026-04-19'
name: Amazon IAM Identity Center
rules:
- name: Amazon IAM Identity Center API Rules
  rule_count: 18
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 8
  slug: amazon-iam-identity-center-spectral-rules
skills: []
slug: amazon-iam-identity-center
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-iam-identity-center\nname: Amazon IAM Identity Center\ndescription: >-\n  AWS IAM Identity Center (successor to AWS Single Sign-On) is where you create,\n  or connect, your workforce identities in AWS once and manage access centrally\n  across your AWS organization. You can create user identities directly in IAM\n  Identity Center, or bring them from Microsoft Active Directory, and then use\n  IAM Identity Center to manage user access to AWS accounts and business\n  applications with single sign-on.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Access Control\n  - Authentication\n  - AWS\n  - Identity Management\n  - Single Sign-On\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iam-identity-center:aws-sso-admin-api\n    name: AWS IAM Identity\
  \ Center SSO Admin API\n    description: >-\n      Manages permission sets, account assignments, instances, and SSO\n      configurations for centralized identity and access management across\n      AWS accounts and organizations.\n    humanURL: https://aws.amazon.com/iam/identity-center/\n    baseURL: https://sso.amazonaws.com\n    tags:\n      - Access Control\n      - Identity Management\n      - Single Sign-On\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/singlesignon/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-iam-identity-center-sso-admin-openapi-original.yml\n      - type: GettingStarted\n        url: https://aws.amazon.com/iam/identity-center/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/iam/identity-center/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iam/identity-center/faqs/\n  - aid: amazon-iam-identity-center:aws-identitystore-api\n    name:\
  \ AWS IAM Identity Center Identity Store API\n    description: >-\n      Manages users, groups, and group memberships in the IAM Identity Center\n      identity store, enabling programmatic provisioning of workforce identities.\n    humanURL: https://docs.aws.amazon.com/singlesignon/latest/IdentityStoreAPIReference/welcome.html\n    baseURL: https://identitystore.amazonaws.com\n    tags:\n      - Groups\n      - Identity Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/singlesignon/latest/IdentityStoreAPIReference/welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-iam-identity-center-identitystore-openapi-original.yml\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iam/identity-center/\n  - type: Website\n    url: https://aws.amazon.com/iam/identity-center/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/singlesignon/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n\
  \  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/security/tag/aws-iam-identity-center/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/singlesignon/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iam-identity-center-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/sso-admin.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/identitystore.yaml\n  - type: NaftikoCapability\n    url: capabilities/identity-access-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iam-identity-center-vocabulary.yaml\n\
  \  - type: JSONLD\n    url: json-ld/amazon-iam-identity-center-context.jsonld\n  - type: Features\n    data:\n      - name: Workforce Identity Management\n        description: Create and manage workforce user identities directly or connect from an external identity provider.\n      - name: Single Sign-On\n        description: Enable employees to sign in once and access all assigned AWS accounts and business applications.\n      - name: Centralized Access Management\n        description: Manage access to multiple AWS accounts from a single place using permission sets.\n      - name: External Identity Provider Integration\n        description: Connect Microsoft Active Directory, Okta, Azure AD, and other SAML 2.0 identity providers.\n      - name: Permission Set Management\n        description: Define and reuse permission policies that can be assigned to users across multiple AWS accounts.\n      - name: Automated Provisioning\n        description: Automatically provision and de-provision\
  \ users and groups using SCIM 2.0.\n  - type: UseCases\n    data:\n      - name: Workforce SSO\n        description: Enable employees to access all AWS accounts and business apps with a single set of credentials.\n      - name: Centralized AWS Account Access\n        description: Manage access to dozens or hundreds of AWS accounts from a single control plane.\n      - name: Just-in-Time Access\n        description: Grant temporary elevated access to AWS accounts without permanent permissions.\n      - name: Compliance and Audit\n        description: Centralize access logging and produce audit reports for security compliance reviews.\n  - type: Integrations\n    data:\n      - name: Microsoft Active Directory\n        description: Sync users and groups from Active Directory for SSO and access management.\n      - name: Okta\n        description: Connect Okta as an external identity provider using SAML 2.0 and SCIM.\n      - name: Azure Active Directory\n        description: Federate with\
  \ Azure AD for identity synchronization and SSO.\n      - name: AWS Organizations\n        description: Manage access across all accounts in an AWS Organization from a single SSO configuration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/apis.yml
tags:
- Access Control
- Authentication
- AWS
- Identity Management
- Single Sign-On
url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/apis.yml
use_cases:
- description: Enable employees to access all AWS accounts and business apps with a single set of credentials.
  name: Workforce SSO
- description: Manage access to dozens or hundreds of AWS accounts from a single control plane.
  name: Centralized AWS Account Access
- description: Grant temporary elevated access to AWS accounts without permanent permissions.
  name: Just-in-Time Access
- description: Centralize access logging and produce audit reports for security compliance reviews.
  name: Compliance and Audit
---
