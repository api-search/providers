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
