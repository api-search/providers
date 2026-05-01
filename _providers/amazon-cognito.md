---
api_count: 2
api_specs:
- filename: amazon-cognito-user-pools-openapi.yml
  format: yaml
  label: Cognito User Pools API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/openapi/amazon-cognito-user-pools-openapi.yml
- filename: amazon-cognito-identity-pools-openapi.yml
  format: yaml
  label: Cognito Identity Pools API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/openapi/amazon-cognito-identity-pools-openapi.yml
apis:
- description: Amazon Cognito User Pools API provides user directory management, sign-up, sign-in, and token-based authentication for web and mobile applications. It supports multi-factor authentication, account rec
  name: Cognito User Pools API
  slug: ''
- description: Amazon Cognito Identity Pools (Federated Identities) API enables developers to create unique identities for users and federate them with identity providers. It provides temporary, limited-privilege AW
  name: Cognito Identity Pools API
  slug: ''
capabilities:
- description: Workflow capability for managing user authentication, identity federation, and access control using Amazon Cognito User Pools and Identity Pools. Used by application developers and platform administra
  name: Amazon Cognito User Authentication
  slug: user-authentication
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cognito/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cognito/
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
  url: https://console.aws.amazon.com/cognito/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-cognito
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-cognito-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/user-authentication.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cognito-vocabulary.yaml
created: '2016-04-18'
description: Amazon Cognito is a fully managed user identity and authentication service that enables developers to add sign-up, sign-in, and access control to web and mobile applications. It supports OAuth 2.0, SAML 2.0, and OpenID Connect standards, providing secure user directories that scale to millions of users. Cognito offers user pools for authentication and identity pools for authorization, allowing integration with social identity providers and enterprise identity systems.
features:
- description: Fully managed user directories with sign-up, sign-in, and account management supporting millions of users.
  name: User Pools
- description: Grant temporary AWS credentials to authenticated users from social identity providers, SAML, or user pools.
  name: Identity Pools (Federated Identities)
- description: Add SMS-based, TOTP, or email-based MFA to user pools for enhanced security.
  name: Multi-Factor Authentication
- description: Standards-compliant OAuth 2.0 authorization server with OIDC support for easy integration.
  name: OAuth 2.0 and OpenID Connect
- description: Federate with Google, Facebook, Amazon, Apple, and any OIDC or SAML 2.0 compatible provider.
  name: Social Identity Providers
- description: Risk-based adaptive authentication, compromised credential detection, and IP-based restriction.
  name: Advanced Security Features
- description: Lambda triggers for custom authentication challenges, migration, pre/post sign-up, and token customization.
  name: Customizable Authentication Flows
- description: Organize users into groups with associated IAM roles for role-based access control.
  name: User Groups
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Authorize API requests using Cognito User Pool authorizers.
  name: AWS API Gateway
- description: Customize authentication with Lambda triggers for sign-up, sign-in, and token generation.
  name: AWS Lambda
- description: Map Cognito groups and roles to IAM permissions for granular access control.
  name: AWS IAM
- description: Secure GraphQL APIs with Cognito User Pool authorization.
  name: AWS AppSync
- description: Offload authentication to Cognito from Application Load Balancers.
  name: Amazon ALB
- description: Social identity provider federation for consumer applications.
  name: Google, Facebook, Apple
- description: Enterprise identity provider federation via SAML for corporate SSO.
  name: SAML 2.0 Providers
jsonld:
- class_count: 1
  name: Amazon Cognito Cognito Context
  property_count: 35
  slug: amazon-cognito-cognito-context
- class_count: 0
  name: Amazon Cognito Context
  property_count: 3
  slug: amazon-cognito-context
- class_count: 50
  name: Amazon Cognito Identity Pools Context
  property_count: 55
  slug: amazon-cognito-identity-pools-context
- class_count: 269
  name: Amazon Cognito User Pools Context
  property_count: 308
  slug: amazon-cognito-user-pools-context
layout: provider
modified: '2026-04-19'
name: Amazon Cognito
rules:
- name: Amazon Cognito API Rules
  rule_count: 24
  severity_counts:
    error: 10
    hint: 0
    info: 3
    warn: 11
  slug: amazon-cognito-spectral-rules
skills: []
slug: amazon-cognito
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-cognito\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/apis.yml\nname: Amazon Cognito\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  Amazon Cognito is a fully managed user identity and authentication service\n  that enables developers to add sign-up, sign-in, and access control to web\n  and mobile applications. It supports OAuth 2.0, SAML 2.0, and OpenID Connect\n  standards, providing secure user directories that scale to millions of users.\n  Cognito offers user pools for authentication and identity pools for\n  authorization, allowing integration with social identity providers and\n  enterprise identity systems.\ncreated: '2016-04-18'\nmodified: '2026-04-19'\ntags:\n  - Authentication\n  - AWS\n  - Identity\n  - OAuth\n  - User Management\napis:\n  - name: Cognito User Pools API\n    description: >-\n      Amazon Cognito\
  \ User Pools API provides user directory management,\n      sign-up, sign-in, and token-based authentication for web and mobile\n      applications. It supports multi-factor authentication, account recovery,\n      and customizable authentication flows with 103 operations covering user\n      pools, users, groups, app clients, and resource servers.\n    baseURL: https://cognito-idp.amazonaws.com\n    humanURL: https://aws.amazon.com/cognito/\n    tags:\n      - Authentication\n      - AWS\n      - Identity\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-identity-pools.html\n      - type: OpenAPI\n        url: openapi/amazon-cognito-user-pools-openapi.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html\n      - type: Pricing\n        url: https://aws.amazon.com/cognito/pricing/\n      - type: GettingStarted\n\
  \        url: https://docs.aws.amazon.com/cognito/latest/developerguide/getting-started-with-cognito-user-pools.html\n      - type: FAQ\n        url: https://aws.amazon.com/cognito/faqs/\n      - type: JSONSchema\n        url: json-schema/user-pools-user-pool-type-schema.json\n      - type: JSONStructure\n        url: json-structure/user-pools-user-pool-type-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-cognito-user-pools-context.jsonld\n  - name: Cognito Identity Pools API\n    description: >-\n      Amazon Cognito Identity Pools (Federated Identities) API enables\n      developers to create unique identities for users and federate them with\n      identity providers. It provides temporary, limited-privilege AWS\n      credentials to access AWS services with 23 operations covering identity\n      pool management, credential dispensing, and provider configuration.\n    baseURL: https://cognito-identity.amazonaws.com\n    humanURL: https://aws.amazon.com/cognito/\n\
  \    tags:\n      - Authentication\n      - AWS\n      - Federated Identity\n      - Authorization\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html\n      - type: OpenAPI\n        url: openapi/amazon-cognito-identity-pools-openapi.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html\n      - type: Pricing\n        url: https://aws.amazon.com/cognito/pricing/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/cognito/latest/developerguide/getting-started-with-identity-pools.html\n      - type: FAQ\n        url: https://aws.amazon.com/cognito/faqs/\n      - type: JSONSchema\n        url: json-schema/identity-pools-identity-pool-schema.json\n      - type: JSONStructure\n        url: json-structure/identity-pools-identity-pool-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-cognito-identity-pools-context.jsonld\n\
  common:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/cognito/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cognito/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/security/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/cognito/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: YouTube\n    url: https://www.youtube.com/user/AmazonWebServices\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/amazon-cognito\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n\
  \  - type: SpectralRules\n    url: rules/amazon-cognito-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/user-authentication.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-cognito-vocabulary.yaml\n  - type: Features\n    data:\n      - name: User Pools\n        description: Fully managed user directories with sign-up, sign-in, and account management supporting millions of users.\n      - name: Identity Pools (Federated Identities)\n        description: Grant temporary AWS credentials to authenticated users from social identity providers, SAML, or user pools.\n      - name: Multi-Factor Authentication\n        description: Add SMS-based, TOTP, or email-based MFA to user pools for enhanced security.\n      - name: OAuth 2.0 and OpenID Connect\n        description: Standards-compliant OAuth 2.0 authorization server with OIDC support for easy integration.\n      - name: Social Identity Providers\n        description: Federate with Google, Facebook, Amazon, Apple,\
  \ and any OIDC or SAML 2.0 compatible provider.\n      - name: Advanced Security Features\n        description: Risk-based adaptive authentication, compromised credential detection, and IP-based restriction.\n      - name: Customizable Authentication Flows\n        description: Lambda triggers for custom authentication challenges, migration, pre/post sign-up, and token customization.\n      - name: User Groups\n        description: Organize users into groups with associated IAM roles for role-based access control.\n  - type: UseCases\n    data:\n      - name: Web and Mobile App Authentication\n        description: Add user sign-up and sign-in to web and mobile applications without managing authentication infrastructure.\n      - name: API Authorization\n        description: Protect APIs using Cognito-issued JWT tokens validated by API Gateway or application code.\n      - name: Enterprise SSO\n        description: Federate with corporate SAML 2.0 identity providers for single sign-on in\
  \ enterprise applications.\n      - name: Social Login\n        description: Enable users to sign in with their Google, Facebook, or Apple credentials.\n      - name: Serverless App Security\n        description: Secure serverless applications with temporary AWS credentials dispensed through identity pools.\n      - name: Multi-Tenant SaaS\n        description: Create isolated user pools per tenant for multi-tenant SaaS applications.\n  - type: Integrations\n    data:\n      - name: AWS API Gateway\n        description: Authorize API requests using Cognito User Pool authorizers.\n      - name: AWS Lambda\n        description: Customize authentication with Lambda triggers for sign-up, sign-in, and token generation.\n      - name: AWS IAM\n        description: Map Cognito groups and roles to IAM permissions for granular access control.\n      - name: AWS AppSync\n        description: Secure GraphQL APIs with Cognito User Pool authorization.\n      - name: Amazon ALB\n        description:\
  \ Offload authentication to Cognito from Application Load Balancers.\n      - name: Google, Facebook, Apple\n        description: Social identity provider federation for consumer applications.\n      - name: SAML 2.0 Providers\n        description: Enterprise identity provider federation via SAML for corporate SSO.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/apis.yml
tags:
- Authentication
- Identity
- OAuth
- User Management
url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/apis.yml
use_cases:
- description: Add user sign-up and sign-in to web and mobile applications without managing authentication infrastructure.
  name: Web and Mobile App Authentication
- description: Protect APIs using Cognito-issued JWT tokens validated by API Gateway or application code.
  name: API Authorization
- description: Federate with corporate SAML 2.0 identity providers for single sign-on in enterprise applications.
  name: Enterprise SSO
- description: Enable users to sign in with their Google, Facebook, or Apple credentials.
  name: Social Login
- description: Secure serverless applications with temporary AWS credentials dispensed through identity pools.
  name: Serverless App Security
- description: Create isolated user pools per tenant for multi-tenant SaaS applications.
  name: Multi-Tenant SaaS
---
