---
api_count: 4
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
