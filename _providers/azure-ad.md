---
api_count: 2
apis:
- description: The primary API for accessing Azure AD and other Microsoft 365 services.
  name: Microsoft Graph API
  slug: microsoft-graph-api
- description: Business-to-consumer identity management solution.
  name: Azure AD B2C API
  slug: azure-ad-b2c-api
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/active-directory/
- title: ''
  type: StatusPage
  url: https://status.azure.com
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/azure-active-directory-identity/bg-p/Identity
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/active-directory/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/get-started-azure-ad
created: '2024-01-01'
description: Microsoft's cloud-based identity and access management service that helps employees sign in and access resources. Azure AD provides OAuth, OpenID Connect, SAML, and other identity protocols for securing applications and managing user identities.
features:
- description: Enable users to sign in once and access all connected apps without re-authenticating.
  name: Single Sign-On
- description: Enforce MFA to add an extra layer of security beyond passwords.
  name: Multi-Factor Authentication
- description: Define access policies based on user, device, location, and risk signals.
  name: Conditional Access
- description: Industry-standard protocols for authorization and authentication.
  name: OAuth 2.0 and OpenID Connect
- description: Federate with thousands of SAML-based SaaS applications.
  name: SAML 2.0 Support
- description: Detect and respond to identity-based risks with AI-powered signals.
  name: Identity Protection
- description: Just-in-time privileged access with approval workflows and audit.
  name: Privileged Identity Management
- description: Invite external users from partner organizations to access your resources.
  name: B2B Collaboration
- description: Enable customer and partner identity management with Azure AD B2C and B2B.
  name: External Identities
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Provides identity and access management for all Microsoft 365 applications.
  name: Microsoft 365
- description: SAML-based SSO integration with Salesforce CRM and Platform.
  name: Salesforce
- description: Federated SSO and user provisioning for ServiceNow via SAML and SCIM.
  name: ServiceNow
- description: SAML SSO and SCIM provisioning for GitHub Enterprise organizations.
  name: GitHub Enterprise
- description: Federate Azure AD with AWS IAM Identity Center for cross-cloud SSO.
  name: AWS
layout: provider
modified: '2026-04-19'
name: Azure Active Directory
skills: []
slug: azure-ad
solutions: []
tags:
- Authentication
- Authorization
- Identity
- OAuth
- OpenID Connect
- Single Sign-On
url: https://raw.githubusercontent.com/api-evangelist/azure-ad/refs/heads/main/apis.yml
use_cases:
- description: Provide single sign-on for employees across thousands of SaaS applications.
  name: Enterprise SSO
- description: Implement zero trust architecture with identity as the control plane.
  name: Zero Trust Security
- description: Build customer-facing login with Azure AD B2C supporting social identities.
  name: Consumer Identity
- description: Secure APIs with OAuth 2.0 tokens issued by Azure AD.
  name: API Security
- description: Extend on-premises Active Directory to the cloud with Azure AD Connect.
  name: Hybrid Identity
---
