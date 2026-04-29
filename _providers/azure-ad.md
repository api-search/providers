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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: azure-ad\nname: Azure Active Directory\ndescription: >-\n  Microsoft's cloud-based identity and access management service that helps\n  employees sign in and access resources. Azure AD provides OAuth, OpenID\n  Connect, SAML, and other identity protocols for securing applications and\n  managing user identities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Authentication\n- Authorization\n- Identity\n- OAuth\n- OpenID Connect\n- Single Sign-On\nurl: \n  https://raw.githubusercontent.com/api-evangelist/azure-ad/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-ad:microsoft-graph-api\n  name: Microsoft Graph API\n  description: The primary API for accessing Azure AD and other Microsoft 365 \n    services.\n  humanURL: https://docs.microsoft.com/en-us/graph/overview\n  baseURL: https://graph.microsoft.com\n  tags:\n  - Directory\n  - Identity\n\
  \  - Microsoft 365\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/graph/api/overview\n  - type: OpenAPI\n    url: \n      https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n  - type: Authentication\n    url: https://docs.microsoft.com/en-us/graph/auth/\n  - type: SDK\n    url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: ChangeLog\n    url: https://docs.microsoft.com/en-us/graph/changelog\n- aid: azure-ad:azure-ad-b2c-api\n  name: Azure AD B2C API\n  description: Business-to-consumer identity management solution.\n  humanURL: https://docs.microsoft.com/en-us/azure/active-directory-b2c/\n  baseURL: https://login.microsoftonline.com\n  tags:\n  - Authentication\n  - B2C\n  - Consumer Identity\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/azure/active-directory-b2c/overview\ncommon:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n\
  \  url: https://learn.microsoft.com/en-us/azure/active-directory/\n- type: StatusPage\n  url: https://status.azure.com\n- type: Blog\n  url: \n    https://techcommunity.microsoft.com/t5/azure-active-directory-identity/bg-p/Identity\n- type: PrivacyPolicy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: TermsOfService\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Pricing\n  url: https://azure.microsoft.com/en-us/pricing/details/active-directory/\n- type: GettingStarted\n  url: \n    https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/get-started-azure-ad\n- type: Features\n  data:\n  - name: Single Sign-On\n    description: Enable users to sign in once and access all connected apps \n      without re-authenticating.\n  - name: Multi-Factor Authentication\n    description: Enforce MFA to add an extra layer of security beyond passwords.\n  - name: Conditional Access\n    description: Define access policies based on user, device, location,\
  \ and \n      risk signals.\n  - name: OAuth 2.0 and OpenID Connect\n    description: Industry-standard protocols for authorization and \n      authentication.\n  - name: SAML 2.0 Support\n    description: Federate with thousands of SAML-based SaaS applications.\n  - name: Identity Protection\n    description: Detect and respond to identity-based risks with AI-powered \n      signals.\n  - name: Privileged Identity Management\n    description: Just-in-time privileged access with approval workflows and \n      audit.\n  - name: B2B Collaboration\n    description: Invite external users from partner organizations to access your\n      resources.\n  - name: External Identities\n    description: Enable customer and partner identity management with Azure AD \n      B2C and B2B.\n- type: UseCases\n  data:\n  - name: Enterprise SSO\n    description: Provide single sign-on for employees across thousands of SaaS \n      applications.\n  - name: Zero Trust Security\n    description: Implement zero\
  \ trust architecture with identity as the control \n      plane.\n  - name: Consumer Identity\n    description: Build customer-facing login with Azure AD B2C supporting social\n      identities.\n  - name: API Security\n    description: Secure APIs with OAuth 2.0 tokens issued by Azure AD.\n  - name: Hybrid Identity\n    description: Extend on-premises Active Directory to the cloud with Azure AD \n      Connect.\n- type: Integrations\n  data:\n  - name: Microsoft 365\n    description: Provides identity and access management for all Microsoft 365 \n      applications.\n  - name: Salesforce\n    description: SAML-based SSO integration with Salesforce CRM and Platform.\n  - name: ServiceNow\n    description: Federated SSO and user provisioning for ServiceNow via SAML and\n      SCIM.\n  - name: GitHub Enterprise\n    description: SAML SSO and SCIM provisioning for GitHub Enterprise \n      organizations.\n  - name: AWS\n    description: Federate Azure AD with AWS IAM Identity Center for cross-cloud\
  \ \n      SSO.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-ad/refs/heads/main/apis.yml
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
