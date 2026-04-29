---
api_count: 2
apis:
- description: Control plane API for managing Cognito user pools, app clients, users, groups, identity providers, and resource servers. Supports user authentication flows including SRP, custom, and hosted UI authent
  name: Amazon Cognito Identity Provider
  slug: aws-cognito-identity-provider
- description: Federated identity service that issues temporary AWS credentials to authenticated and unauthenticated users from Cognito user pools, social identity providers (Facebook, Google, Apple), and SAML-based
  name: Amazon Cognito Identity (Federated Identities)
  slug: aws-cognito-identity
capabilities:
- description: Unified workflow for identity and access management engineers to manage Cognito user pools, user accounts, groups, and federated identity pools. Combines the Identity Provider and Federated Identity A
  name: Amazon Cognito Identity Management Workflow
  slug: identity-management-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/cognito/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cognito/
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/cognito/latest/developerguide/getting-started-with-cognito-user-pools.html
- title: ''
  type: Pricing
  url: https://aws.amazon.com/cognito/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/cognito/faqs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws-amplify
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cognito/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/security/tag/amazon-cognito/
- title: ''
  type: SpectralRules
  url: rules/aws-cognito-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-cognito-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/identity-management-workflow.yaml
created: '2026-03-25'
description: 'Amazon Cognito is an AWS service that provides authentication, authorization, and user management for web and mobile applications. It supports OAuth2, OIDC, SAML federation, and social identity providers. Cognito has two main components: User Pools for user authentication and app integration, and Federated Identities for granting temporary AWS credentials to authenticated users. It includes multi-factor authentication, advanced security features, and customizable authentication flows.'
features:
- description: Fully managed user directories with sign-up, sign-in, and user profile management.
  name: User Pools
- description: Standards-based OAuth2 authorization server and OpenID Connect identity provider for apps.
  name: OAuth2 and OIDC
- description: Integrate enterprise identity providers via SAML 2.0 for single sign-on.
  name: SAML Federation
- description: Sign in with Google, Facebook, Apple, and Amazon without custom backend code.
  name: Social Identity Providers
- description: Built-in MFA with SMS, TOTP, and email verification options.
  name: Multi-Factor Authentication
- description: Lambda triggers for custom authentication challenges, pre-signup validation, and post-confirmation.
  name: Customizable Auth Flows
- description: Risk-based adaptive authentication with compromised credential detection and device tracking.
  name: Advanced Security Features
- description: Grant temporary AWS credentials to users authenticated via user pools or social providers.
  name: Federated Identities
- description: Pre-built customizable sign-in/sign-up pages with OAuth2 endpoint support.
  name: Hosted UI
- description: Attribute-based access control with group-based IAM role assignment.
  name: Fine-Grained Authorization
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Validate Cognito JWTs for API Gateway authorizer integration.
  name: Amazon API Gateway
- description: Pre-built Amplify Auth library for easy Cognito integration in React, Vue, and mobile apps.
  name: AWS Amplify
- description: Trigger Lambda functions for custom authentication logic and user data enrichment.
  name: AWS Lambda
- description: Use Cognito identity IDs as DynamoDB partition keys for per-user data isolation.
  name: Amazon DynamoDB
- description: Map Cognito groups to IAM roles for role-based access control to AWS services.
  name: AWS IAM
- description: Use Cognito user pools as authorization mode for GraphQL API access control.
  name: AWS AppSync
jsonld:
- class_count: 50
  name: Aws Cognito Cognito Identity Context
  property_count: 55
  slug: aws-cognito-cognito-identity-context
- class_count: 263
  name: Aws Cognito Cognito Idp Context
  property_count: 304
  slug: aws-cognito-cognito-idp-context
layout: provider
modified: '2026-04-19'
name: Amazon Cognito
rules:
- name: Amazon Cognito API Rules
  rule_count: 16
  severity_counts:
    error: 11
    hint: 0
    info: 0
    warn: 5
  slug: aws-cognito-spectral-rules
skills: []
slug: aws-cognito
solutions: []
source_yaml: "aid: aws-cognito\nname: Amazon Cognito\ndescription: >-\n  Amazon Cognito is an AWS service that provides authentication, authorization,\n  and user management for web and mobile applications. It supports OAuth2, OIDC,\n  SAML federation, and social identity providers. Cognito has two main components:\n  User Pools for user authentication and app integration, and Federated Identities\n  for granting temporary AWS credentials to authenticated users. It includes\n  multi-factor authentication, advanced security features, and customizable\n  authentication flows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - Authorization\n  - AWS\n  - Identity\n  - Identity Provider\n  - OAuth2\n  - OIDC\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-cognito/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-cognito:aws-cognito-identity-provider\n\
  \    name: Amazon Cognito Identity Provider\n    description: >-\n      Control plane API for managing Cognito user pools, app clients, users,\n      groups, identity providers, and resource servers. Supports user\n      authentication flows including SRP, custom, and hosted UI authentication.\n    humanURL: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-pools.html\n    baseURL: https://cognito-idp.{region}.amazonaws.com\n    tags:\n      - Authentication\n      - AWS\n      - Identity Provider\n      - OAuth2\n      - User Pools\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-pools.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/cognito/latest/developerguide/security-iam.html\n      - type: OpenAPI\n        url: openapi/aws-cognito-identity-provider-openapi.yaml\n\
  \  - aid: aws-cognito:aws-cognito-identity\n    name: Amazon Cognito Identity (Federated Identities)\n    description: >-\n      Federated identity service that issues temporary AWS credentials to\n      authenticated and unauthenticated users from Cognito user pools, social\n      identity providers (Facebook, Google, Apple), and SAML-based enterprise\n      IdPs.\n    humanURL: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html\n    baseURL: https://cognito-identity.{region}.amazonaws.com\n    tags:\n      - AWS\n      - Credentials\n      - Federation\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/aws-cognito-identity-openapi.yaml\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/cognito/\n\
  \  - type: Documentation\n    url: https://docs.aws.amazon.com/cognito/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/cognito/latest/developerguide/getting-started-with-cognito-user-pools.html\n  - type: Pricing\n    url: https://aws.amazon.com/cognito/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cognito/faqs/\n  - type: GitHubOrganization\n    url: https://github.com/aws-amplify\n  - type: Console\n    url: https://console.aws.amazon.com/cognito/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/security/tag/amazon-cognito/\n  - type: SpectralRules\n    url: rules/aws-cognito-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/aws-cognito-vocabulary.yaml\n  - type:\
  \ NaftikoCapability\n    url: capabilities/identity-management-workflow.yaml\n  - type: Features\n    data:\n      - name: User Pools\n        description: Fully managed user directories with sign-up, sign-in, and user profile management.\n      - name: OAuth2 and OIDC\n        description: Standards-based OAuth2 authorization server and OpenID Connect identity provider for apps.\n      - name: SAML Federation\n        description: Integrate enterprise identity providers via SAML 2.0 for single sign-on.\n      - name: Social Identity Providers\n        description: Sign in with Google, Facebook, Apple, and Amazon without custom backend code.\n      - name: Multi-Factor Authentication\n        description: Built-in MFA with SMS, TOTP, and email verification options.\n      - name: Customizable Auth Flows\n        description: Lambda triggers for custom authentication challenges, pre-signup validation, and post-confirmation.\n      - name: Advanced Security Features\n        description:\
  \ Risk-based adaptive authentication with compromised credential detection and device tracking.\n      - name: Federated Identities\n        description: Grant temporary AWS credentials to users authenticated via user pools or social providers.\n      - name: Hosted UI\n        description: Pre-built customizable sign-in/sign-up pages with OAuth2 endpoint support.\n      - name: Fine-Grained Authorization\n        description: Attribute-based access control with group-based IAM role assignment.\n  - type: UseCases\n    data:\n      - name: Web and Mobile App Authentication\n        description: Add user registration, login, and session management to web and mobile applications.\n      - name: Enterprise SSO Integration\n        description: Connect enterprise SAML identity providers for single sign-on to AWS-hosted applications.\n      - name: API Authorization\n        description: Use Cognito JWT tokens to authorize access to API Gateway, AppSync, and custom APIs.\n      - name: B2C\
  \ Identity Management\n        description: Manage consumer user accounts with self-service registration and profile management.\n      - name: Temporary AWS Credentials\n        description: Issue scoped AWS credentials to authenticated users for direct service access.\n  - type: Integrations\n    data:\n      - name: Amazon API Gateway\n        description: Validate Cognito JWTs for API Gateway authorizer integration.\n      - name: AWS Amplify\n        description: Pre-built Amplify Auth library for easy Cognito integration in React, Vue, and mobile apps.\n      - name: AWS Lambda\n        description: Trigger Lambda functions for custom authentication logic and user data enrichment.\n      - name: Amazon DynamoDB\n        description: Use Cognito identity IDs as DynamoDB partition keys for per-user data isolation.\n      - name: AWS IAM\n        description: Map Cognito groups to IAM roles for role-based access control to AWS services.\n      - name: AWS AppSync\n        description:\
  \ Use Cognito user pools as authorization mode for GraphQL API access control.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-cognito/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- AWS
- Identity
- Identity Provider
- OAuth2
- OIDC
url: https://raw.githubusercontent.com/api-evangelist/aws-cognito/refs/heads/main/apis.yml
use_cases:
- description: Add user registration, login, and session management to web and mobile applications.
  name: Web and Mobile App Authentication
- description: Connect enterprise SAML identity providers for single sign-on to AWS-hosted applications.
  name: Enterprise SSO Integration
- description: Use Cognito JWT tokens to authorize access to API Gateway, AppSync, and custom APIs.
  name: API Authorization
- description: Manage consumer user accounts with self-service registration and profile management.
  name: B2C Identity Management
- description: Issue scoped AWS credentials to authenticated users for direct service access.
  name: Temporary AWS Credentials
---
