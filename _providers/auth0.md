---
api_count: 4
api_specs:
- filename: auth0-api-openapi.yml
  format: yaml
  label: Auth0 Management API
  slug: auth0-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/auth0/refs/heads/main/openapi/auth0-api-openapi.yml
apis:
- description: The Auth0 Management API enables programmatic management of your Auth0 tenant, including users, connections, applications, rules, and logs.
  name: Auth0 Management API
  slug: auth0-management-api
- description: The Auth0 Authentication API implements OpenID Connect and OAuth 2.0 protocols for authentication and authorization.
  name: Auth0 Authentication API
  slug: auth0-authentication-api
- description: The Auth0 My Account API provides user self-service endpoints for managing authentication factors, authentication methods, and account settings.
  name: Auth0 My Account API
  slug: auth0-my-account-api
- description: The Auth0 My Organization API provides organization-scoped endpoints for business customers to manage their own Organizations, including IdP configuration, SCIM, and Home Realm Discovery.
  name: Auth0 My Organization API
  slug: auth0-my-organization-api
common:
- title: ''
  type: Website
  url: https://auth0.com/
- title: ''
  type: Documentation
  url: https://auth0.com/docs/
- title: ''
  type: Getting Started
  url: https://auth0.com/docs/get-started
- title: ''
  type: Blog
  url: https://auth0.com/blog/
- title: ''
  type: Sign Up
  url: https://auth0.com/signup
- title: ''
  type: Login
  url: https://manage.auth0.com/
- title: ''
  type: Pricing
  url: https://auth0.com/pricing
- title: ''
  type: GitHub Organization
  url: https://github.com/auth0
- title: ''
  type: Status
  url: https://status.auth0.com/
- title: ''
  type: Community
  url: https://community.auth0.com/
- title: ''
  type: Support
  url: https://support.auth0.com/
- title: ''
  type: Terms of Service
  url: https://auth0.com/legal/tos
- title: ''
  type: Privacy Policy
  url: https://auth0.com/privacy
- title: ''
  type: SDK
  url: https://auth0.com/docs/libraries
- title: ''
  type: RateLimits
  url: https://auth0.com/docs/troubleshoot/customer-support/operational-policies/rate-limit-policy
- title: ''
  type: ChangeLog
  url: https://auth0.com/changelog
created: '2024-04-14'
description: Auth0 (now part of Okta) is a leading identity and access management platform providing secure authentication and authorization for applications, APIs, and devices. It implements OpenID Connect, OAuth 2.0, and SAML 2.0 protocols and offers a Management API, Authentication API, My Account API, and My Organization API for programmatic control over identity infrastructure.
features:
- description: Centralized login page that can be customized and handles authentication flows for all application types.
  name: Universal Login
- description: Integrate Google, Facebook, GitHub, Twitter, and 30+ social identity providers with minimal configuration.
  name: Social Login
- description: Add TOTP, SMS, push notification, and WebAuthn MFA to any application using built-in Auth0 factors.
  name: Multi-Factor Authentication
- description: Enable SSO across multiple applications and APIs using standard protocols including SAML 2.0 and OpenID Connect.
  name: Single Sign-On
- description: Connect enterprise identity providers including Active Directory, LDAP, Azure AD, and SAML IdPs for workforce authentication.
  name: Enterprise Federation
- description: Customize authentication pipelines with serverless Actions that execute code at key points in authentication flows.
  name: Actions
- description: Multi-tenant B2B identity management with per-organization branding, connections, and user management.
  name: Organizations
- description: Automatic protection against credential stuffing, brute force attacks, and suspicious login patterns.
  name: Anomaly Detection
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Auth0 is now part of Okta, enabling combined workforce and customer identity capabilities.
  name: Okta
- description: Connect on-premises Active Directory and LDAP directories for enterprise user authentication.
  name: Active Directory/LDAP
- description: Federate with Azure Active Directory for Microsoft ecosystem authentication and SSO.
  name: Azure AD
- description: Use Auth0 as identity provider for Salesforce apps and customer communities.
  name: Salesforce
- description: Secure AWS API Gateway and Lambda functions with Auth0-issued JWT access tokens.
  name: AWS
- description: Send OTP and MFA verification codes via Twilio SMS and voice using Auth0 MFA integration.
  name: Twilio
layout: provider
modified: '2026-04-19'
name: Auth0
skills: []
slug: auth0
solutions:
- description: Comprehensive CIAM solution for customer-facing applications with self-service registration, social login, and adaptive MFA.
  name: Customer Identity Access Management
- description: Enterprise identity management for employees with federation, MFA, and SSO across all applications.
  name: Workforce Identity
- description: Multi-tenant identity infrastructure for SaaS platforms requiring per-customer branding, SSO, and user management.
  name: B2B SaaS Identity
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: auth0\nname: Auth0\ndescription: |\n  Auth0 (now part of Okta) is a leading identity and access management platform providing secure authentication and authorization for applications, APIs, and devices. It implements OpenID Connect, OAuth 2.0, and SAML 2.0 protocols and offers a Management API, Authentication API, My Account API, and My Organization API for programmatic control over identity infrastructure.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Authentication\n- Authorization\n- Identity Management\n- OAuth\n- Okta\n- OpenID Connect\n- SAML\n- Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/auth0/refs/heads/main/apis.yml\ncreated: '2024-04-14'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: auth0:auth0-management-api\n  name: Auth0 Management API\n  description: >-\n    The Auth0 Management API enables programmatic management of your Auth0\n    tenant, including\
  \ users, connections, applications, rules, and logs.\n  humanURL: https://auth0.com/docs/api/management/v2\n  baseURL: https://your-tenant.auth0.com/api/v2\n  tags:\n  - Authentication\n  - Identity\n  - User Management\n  properties:\n  - type: Documentation\n    url: https://auth0.com/docs/api/management/v2\n  - type: GettingStarted\n    url: https://auth0.com/docs/get-started\n  - type: Authentication\n    url: https://auth0.com/docs/secure/tokens\n  - type: OpenAPI\n    url: openapi/auth0-api-openapi.yml\n- aid: auth0:auth0-authentication-api\n  name: Auth0 Authentication API\n  description: >-\n    The Auth0 Authentication API implements OpenID Connect and OAuth 2.0\n    protocols for authentication and authorization.\n  humanURL: https://auth0.com/docs/api/authentication\n  baseURL: https://your-tenant.auth0.com\n  tags:\n  - Authentication\n  - OAuth\n  - OpenID Connect\n  properties:\n  - type: Documentation\n    url: https://auth0.com/docs/api/authentication\n  - type: APIReference\n\
  \    url: https://auth0.com/docs/api/authentication\n- aid: auth0:auth0-my-account-api\n  name: Auth0 My Account API\n  description: |\n    The Auth0 My Account API provides user self-service endpoints for managing authentication factors, authentication methods, and account settings.\n  humanURL: https://auth0.com/docs/api/myaccount\n  baseURL: https://your-tenant.auth0.com\n  tags:\n  - Account Management\n  - Authentication\n  - MFA\n  - Self-Service\n  properties:\n  - type: Documentation\n    url: https://auth0.com/docs/api/myaccount\n- aid: auth0:auth0-my-organization-api\n  name: Auth0 My Organization API\n  description: |\n    The Auth0 My Organization API provides organization-scoped endpoints for business customers to manage their own Organizations, including IdP configuration, SCIM, and Home Realm Discovery.\n  humanURL: https://auth0.com/docs/api/myorganization\n  baseURL: https://your-tenant.auth0.com\n  tags:\n  - Authentication\n  - B2B\n  - Identity\n  - Organizations\n\
  \  properties:\n  - type: Documentation\n    url: https://auth0.com/docs/api/myorganization\ncommon:\n- type: Website\n  url: https://auth0.com/\n- type: Documentation\n  url: https://auth0.com/docs/\n- type: Getting Started\n  url: https://auth0.com/docs/get-started\n- type: Blog\n  url: https://auth0.com/blog/\n- type: Sign Up\n  url: https://auth0.com/signup\n- type: Login\n  url: https://manage.auth0.com/\n- type: Pricing\n  url: https://auth0.com/pricing\n- type: GitHub Organization\n  url: https://github.com/auth0\n- type: Status\n  url: https://status.auth0.com/\n- type: Community\n  url: https://community.auth0.com/\n- type: Support\n  url: https://support.auth0.com/\n- type: Terms of Service\n  url: https://auth0.com/legal/tos\n- type: Privacy Policy\n  url: https://auth0.com/privacy\n- type: SDK\n  url: https://auth0.com/docs/libraries\n- type: Features\n  data:\n  - name: Universal Login\n    description: Centralized login page that can be customized and handles authentication\
  \ flows for all application types.\n  - name: Social Login\n    description: Integrate Google, Facebook, GitHub, Twitter, and 30+ social identity providers with minimal configuration.\n  - name: Multi-Factor Authentication\n    description: Add TOTP, SMS, push notification, and WebAuthn MFA to any application using built-in Auth0 factors.\n  - name: Single Sign-On\n    description: Enable SSO across multiple applications and APIs using standard protocols including SAML 2.0 and OpenID Connect.\n  - name: Enterprise Federation\n    description: Connect enterprise identity providers including Active Directory, LDAP, Azure AD, and SAML IdPs for workforce authentication.\n  - name: Actions\n    description: Customize authentication pipelines with serverless Actions that execute code at key points in authentication flows.\n  - name: Organizations\n    description: Multi-tenant B2B identity management with per-organization branding, connections, and user management.\n  - name: Anomaly Detection\n\
  \    description: Automatic protection against credential stuffing, brute force attacks, and suspicious login patterns.\n- type: UseCases\n  data:\n  - name: Customer Identity\n    description: Add secure, scalable authentication to customer-facing web and mobile applications with social login and passwordless options.\n  - name: Workforce Identity\n    description: Federate with enterprise IdPs for employee authentication with SSO, MFA, and SCIM provisioning.\n  - name: B2B Identity\n    description: Provide multi-tenant identity for SaaS applications with per-customer organization management and custom login flows.\n  - name: API Authorization\n    description: Secure REST and GraphQL APIs using OAuth 2.0 access tokens with audience and scope validation.\n  - name: Machine-to-Machine Auth\n    description: Issue OAuth 2.0 client credentials tokens for service-to-service API authentication without user involvement.\n- type: Integrations\n  data:\n  - name: Okta\n    description: Auth0\
  \ is now part of Okta, enabling combined workforce and customer identity capabilities.\n  - name: Active Directory/LDAP\n    description: Connect on-premises Active Directory and LDAP directories for enterprise user authentication.\n  - name: Azure AD\n    description: Federate with Azure Active Directory for Microsoft ecosystem authentication and SSO.\n  - name: Salesforce\n    description: Use Auth0 as identity provider for Salesforce apps and customer communities.\n  - name: AWS\n    description: Secure AWS API Gateway and Lambda functions with Auth0-issued JWT access tokens.\n  - name: Twilio\n    description: Send OTP and MFA verification codes via Twilio SMS and voice using Auth0 MFA integration.\n- type: Solutions\n  data:\n  - name: Customer Identity Access Management\n    description: Comprehensive CIAM solution for customer-facing applications with self-service registration, social login, and adaptive MFA.\n  - name: Workforce Identity\n    description: Enterprise identity management\
  \ for employees with federation, MFA, and SSO across all applications.\n  - name: B2B SaaS Identity\n    description: Multi-tenant identity infrastructure for SaaS platforms requiring per-customer branding, SSO, and user management.\n- type: RateLimits\n  url: https://auth0.com/docs/troubleshoot/customer-support/operational-policies/rate-limit-policy\n- type: ChangeLog\n  url: https://auth0.com/changelog\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/auth0/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Identity Management
- OAuth
- Okta
- OpenID Connect
- SAML
- Security
url: https://raw.githubusercontent.com/api-evangelist/auth0/refs/heads/main/apis.yml
use_cases:
- description: Add secure, scalable authentication to customer-facing web and mobile applications with social login and passwordless options.
  name: Customer Identity
- description: Federate with enterprise IdPs for employee authentication with SSO, MFA, and SCIM provisioning.
  name: Workforce Identity
- description: Provide multi-tenant identity for SaaS applications with per-customer organization management and custom login flows.
  name: B2B Identity
- description: Secure REST and GraphQL APIs using OAuth 2.0 access tokens with audience and scope validation.
  name: API Authorization
- description: Issue OAuth 2.0 client credentials tokens for service-to-service API authentication without user involvement.
  name: Machine-to-Machine Auth
---
