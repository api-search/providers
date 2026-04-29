---
api_count: 10
api_specs:
- filename: microsoft-graph-identity-api.yml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-active-directory/refs/heads/main/openapi/microsoft-graph-identity-api.yml
- filename: microsoft-graph-identity-api.yml
  format: yaml
  label: Microsoft Graph Identity and Access API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-active-directory/refs/heads/main/openapi/microsoft-graph-identity-api.yml
apis:
- description: The Microsoft Graph API offers a single endpoint to access Azure AD data and other Microsoft 365 services.
  name: Microsoft Graph API
  slug: ''
- description: Microsoft Graph APIs for managing Microsoft Entra identity and network access capabilities, including user management, group management, application registration, conditional access policies, authenti
  name: Microsoft Graph Identity and Access API
  slug: ''
- description: Legacy API for accessing Azure AD (deprecated in favor of Microsoft Graph).
  name: Azure AD Graph API (Deprecated)
  slug: ''
- description: Authentication library for Azure AD (being replaced by MSAL).
  name: Azure AD Authentication Library (ADAL)
  slug: ''
- description: Modern authentication library for Microsoft identity platform.
  name: Microsoft Authentication Library (MSAL)
  slug: ''
- description: 'The Microsoft identity platform provides authentication and authorization services using standards-compliant implementations of OAuth 2.0 and OpenID Connect, enabling developers to build applications '
  name: Microsoft Identity Platform
  slug: ''
- description: Microsoft Entra Verified ID is a managed verifiable credentials service that enables organizations to issue, manage, and verify decentralized identity credentials based on W3C standards.
  name: Microsoft Entra Verified ID API
  slug: ''
- description: Microsoft Entra ID Governance APIs in Microsoft Graph enable automated access reviews, entitlement management, lifecycle workflows, and privileged identity management for identity governance scenarios
  name: Microsoft Entra ID Governance API
  slug: ''
- description: Microsoft Entra ID supports SCIM 2.0 protocol for automatic user and group provisioning to cloud applications, enabling automated identity lifecycle management through standardized REST APIs.
  name: Microsoft Entra SCIM Provisioning API
  slug: ''
- description: The Microsoft Entra PowerShell module provides cmdlets for managing Microsoft Entra resources programmatically, built on the Microsoft Graph PowerShell SDK.
  name: Microsoft Entra PowerShell
  slug: ''
capabilities:
- description: Unified identity and access management workflow combining user lifecycle, group management, application registration, and service principal operations. Used by IT administrators and identity engineers
  name: Azure AD Identity and Access Management
  slug: identity-and-access
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/azure-active-directory/bg-p/Azure-Active-Directory
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/active-directory/
- title: ''
  type: Training
  url: https://docs.microsoft.com/en-us/learn/azure/
- title: Entra Admin Center
  type: Portal
  url: https://entra.microsoft.com
- title: ''
  type: DeveloperPortal
  url: https://developer.microsoft.com/en-us/graph
- title: Identity Developer Blog
  type: Blog
  url: https://devblogs.microsoft.com/identity/
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/entra/fundamentals/whats-new
- title: Entra Documentation
  type: Documentation
  url: https://learn.microsoft.com/en-us/entra/identity/
- title: Graph Explorer
  type: Console
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- title: ''
  type: GitHubOrganization
  url: https://github.com/AzureAD
- title: ''
  type: OpenAPI
  url: openapi/microsoft-graph-identity-api.yml
- title: ''
  type: JSONSchema
  url: json-schema/azure-active-directory-user-schema.json
- title: ''
  type: JSONLD
  url: json-ld/azure-active-directory-context.jsonld
created: '2024-01-15'
description: Microsoft Azure Active Directory (Azure AD), now Microsoft Entra ID, is Microsoft's cloud-based identity and access management service, which helps employees sign in and access resources.
features:
- description: Enable users to sign in once and access all connected applications without re-authenticating.
  name: Single Sign-On
- description: Enforce granular access policies based on user, device, location, and risk signals for zero trust security.
  name: Conditional Access
- description: Add a second layer of security with phone, app, or hardware token verification for identity protection.
  name: Multi-Factor Authentication
- description: Automate user and group lifecycle management across cloud applications using SCIM 2.0 standard.
  name: SCIM User Provisioning
- description: Issue and verify decentralized identity credentials based on W3C standards for privacy-preserving identity verification.
  name: Verifiable Credentials
- description: Automate access reviews, entitlement management, and lifecycle workflows for identity governance at scale.
  name: Identity Governance
- description: Publish on-premises web applications externally with secure remote access without VPN infrastructure.
  name: Application Proxy
image: https://docs.microsoft.com/azure/media/index/active-directory.svg
integrations:
- description: Native identity provider for all Microsoft 365 applications including Teams, Outlook, SharePoint, and OneDrive.
  name: Microsoft 365
- description: Single sign-on and automated user provisioning for Salesforce CRM using SAML and SCIM protocols.
  name: Salesforce
- description: Federated authentication and automated user lifecycle management for ServiceNow ITSM platform.
  name: ServiceNow
- description: Cross-cloud identity federation enabling Azure AD users to access AWS resources with single sign-on.
  name: AWS
- description: HR-driven identity provisioning with automated user creation and attribute synchronization from Workday.
  name: Workday
jsonld:
- class_count: 1
  name: Azure Active Directory Context
  property_count: 6
  slug: azure-active-directory-context
- class_count: 0
  name: Microsoft Graph Identity Context
  property_count: 0
  slug: microsoft-graph-identity-context
layout: provider
modified: '2026-04-18'
name: Azure Active Directory
rules:
- name: Azure Active Directory API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: azure-active-directory-spectral-rules
skills: []
slug: azure-active-directory
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Active Directory\ndescription: Microsoft Azure Active Directory (Azure AD), now Microsoft Entra ID, is Microsoft's cloud-based identity and access management service, which helps employees sign in and access resources.\nimage: https://docs.microsoft.com/azure/media/index/active-directory.svg\nurl: https://azure.microsoft.com/en-us/services/active-directory/\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntags:\n  - Authentication\n  - Authorization\n  - Identity\n  - Microsoft\n  - Microsoft Entra\n  - OAuth\n  - OpenID Connect\n  - SAML\n  - SCIM\n  - Single Sign-On\n  - Zero Trust\napis:\n  - name: Microsoft Graph API\n    description: >-\n      The Microsoft Graph API offers a single endpoint to access Azure AD data and\n      other Microsoft 365 services.\n    image: https://docs.microsoft.com/graph/images/microsoft-graph.png\n    humanURL: https://docs.microsoft.com/en-us/graph/overview\n    baseURL: https://graph.microsoft.com\n\
  \    tags:\n      - Graph\n      - Groups\n      - Identity\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: OpenAPI\n        url: openapi/microsoft-graph-identity-api.yml\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: SDK\n        url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/active-directory/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/use-the-api\n      - type: Console\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n        title: Graph Explorer\n      - type: ChangeLog\n        url: https://learn.microsoft.com/en-us/graph/changelog\n\
  \  - name: Microsoft Graph Identity and Access API\n    description: Microsoft Graph APIs for managing Microsoft Entra identity and network access capabilities, including user management, group management, application registration, conditional access policies, authentication methods, and identity governance.\n    humanURL: https://learn.microsoft.com/en-us/graph/identity-network-access-overview\n    baseURL: https://graph.microsoft.com\n    tags:\n      - Access Management\n      - Authentication Methods\n      - Conditional Access\n      - Identity\n      - Identity Governance\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identity-network-access-overview?view=graph-rest-1.0\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/conditionalaccesspolicy?view=graph-rest-1.0\n        title: Conditional Access Documentation\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identitygovernance-overview?view=graph-rest-1.0\n\
  \        title: Identity Governance Documentation\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/v2-conditional-access-dev-guide\n        title: Developer Guide\n      - type: OpenAPI\n        url: openapi/microsoft-graph-identity-api.yml\n      - type: JSONSchema\n        url: json-schema/azure-active-directory-user-schema.json\n      - type: JSONLD\n        url: json-ld/azure-active-directory-context.jsonld\n  - name: Azure AD Graph API (Deprecated)\n    description: >-\n      Legacy API for accessing Azure AD (deprecated in favor of Microsoft Graph).\n    humanURL: https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-graph-api\n    baseURL: https://graph.windows.net\n    tags:\n      - Deprecated\n      - Identity\n      - Legacy\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/previous-versions/azure/ad/graph/api/api-catalog\n      - type: Documentation\n  \
  \      url: https://docs.microsoft.com/en-us/graph/migrate-azure-ad-graph-overview\n        title: Migration Guide\n  - name: Azure AD Authentication Library (ADAL)\n    description: >-\n      Authentication library for Azure AD (being replaced by MSAL).\n    humanURL: https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-authentication-libraries\n    tags:\n      - Authentication\n      - Legacy\n      - Library\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-authentication-libraries\n      - type: GitHubRepository\n        url: https://github.com/AzureAD/azure-activedirectory-library-for-dotnet\n  - name: Microsoft Authentication Library (MSAL)\n    description: >-\n      Modern authentication library for Microsoft identity platform.\n    humanURL: https://docs.microsoft.com/en-us/azure/active-directory/develop/msal-overview\n    tags:\n      - Authentication\n    \
  \  - Library\n      - OAuth\n      - OpenID Connect\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/msal-overview\n      - type: GitHubRepository\n        url: https://github.com/AzureAD/microsoft-authentication-library-for-js\n        title: JavaScript SDK\n      - type: CodeExamples\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/sample-v2-code\n      - type: GitHubRepository\n        url: https://github.com/AzureAD/microsoft-authentication-library-for-dotnet\n        title: .NET SDK\n      - type: GitHubRepository\n        url: https://github.com/AzureAD/microsoft-authentication-library-for-python\n        title: Python SDK\n      - type: GitHubRepository\n        url: https://github.com/AzureAD/microsoft-authentication-library-for-java\n        title: Java SDK\n      - type: GitHubRepository\n        url: https://github.com/AzureAD/microsoft-authentication-library-for-objc\n  \
  \      title: iOS SDK\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/msal/\n        title: MSAL Documentation\n  - name: Microsoft Identity Platform\n    description: The Microsoft identity platform provides authentication and authorization services using standards-compliant implementations of OAuth 2.0 and OpenID Connect, enabling developers to build applications that sign in users and access secured APIs.\n    humanURL: https://learn.microsoft.com/en-us/entra/identity-platform/\n    baseURL: https://login.microsoftonline.com\n    tags:\n      - App Registration\n      - Authentication\n      - Authorization\n      - OAuth\n      - OpenID Connect\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/v2-protocols\n        title: OAuth Documentation\n      - type: Documentation\n        url:\
  \ https://learn.microsoft.com/en-us/entra/identity-platform/v2-protocols-oidc\n        title: OpenID Connect Documentation\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/v2-oauth2-auth-code-flow\n        title: Authorization Code Flow\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/quickstart-register-app\n        title: App Registration Guide\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/scopes-oidc\n        title: Scopes and Permissions\n      - type: CodeExamples\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/quickstart-web-app-sign-in\n  - name: Microsoft Entra Verified ID API\n    description: Microsoft Entra Verified ID is a managed verifiable credentials service that enables organizations to issue, manage, and verify decentralized identity credentials based on W3C standards.\n    humanURL: https://learn.microsoft.com/en-us/entra/verified-id/\n\
  \    baseURL: https://verifiedid.did.msidentity.com\n    tags:\n      - Decentralized Identity\n      - Identity Verification\n      - Verifiable Credentials\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/verified-id/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/entra/verified-id/admin-api\n        title: Admin API\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/entra/verified-id/vc-network-api\n        title: Network API\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/verified-id/decentralized-identifier-overview\n        title: Overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/entra/verified-id/verifiable-credentials-configure-tenant\n  - name: Microsoft Entra ID Governance API\n    description: Microsoft Entra ID Governance APIs in Microsoft Graph enable automated access reviews, entitlement\
  \ management, lifecycle workflows, and privileged identity management for identity governance scenarios.\n    humanURL: https://learn.microsoft.com/en-us/entra/id-governance/identity-governance-overview\n    baseURL: https://graph.microsoft.com\n    tags:\n      - Access Reviews\n      - Entitlement Management\n      - Governance\n      - Lifecycle Workflows\n      - Privileged Identity Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/id-governance/identity-governance-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identitygovernance-overview?view=graph-rest-1.0\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/id-governance/deploy-access-reviews\n        title: Access Reviews\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/id-governance/lifecycle-workflows-deployment\n        title: Lifecycle Workflows\n\
  \      - type: Pricing\n        url: https://learn.microsoft.com/en-us/entra/id-governance/licensing-fundamentals\n  - name: Microsoft Entra SCIM Provisioning API\n    description: Microsoft Entra ID supports SCIM 2.0 protocol for automatic user and group provisioning to cloud applications, enabling automated identity lifecycle management through standardized REST APIs.\n    humanURL: https://learn.microsoft.com/en-us/entra/identity/app-provisioning/use-scim-to-provision-users-and-groups\n    tags:\n      - Automation\n      - Group Management\n      - Provisioning\n      - SCIM\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity/app-provisioning/use-scim-to-provision-users-and-groups\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/architecture/sync-scim\n        title: Architecture Guide\n      - type: GitHubRepository\n        url: https://github.com/azure-ad-b2c/rest-api\n\
  \  - name: Microsoft Entra PowerShell\n    description: The Microsoft Entra PowerShell module provides cmdlets for managing Microsoft Entra resources programmatically, built on the Microsoft Graph PowerShell SDK.\n    humanURL: https://learn.microsoft.com/en-us/powershell/entra-powershell/overview?view=entra-powershell\n    tags:\n      - Automation\n      - CLI\n      - PowerShell\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/powershell/entra-powershell/?view=entra-powershell\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/powershell/entra-powershell/installation?view=entra-powershell\n        title: Installation\n      - type: GitHubRepository\n        url: https://github.com/microsoftgraph/entra-powershell\nmaintainers:\n  - name: Microsoft\n    email: azuread@microsoft.com\n    url: https://azure.microsoft.com/en-us/services/active-directory/\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\
  \    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/azure-active-directory/bg-p/Azure-Active-Directory\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/active-directory/\n  - type: Training\n    url: https://docs.microsoft.com/en-us/learn/azure/\n  - type: Portal\n    url: https://entra.microsoft.com\n    title: Entra Admin Center\n  - type: DeveloperPortal\n    url: https://developer.microsoft.com/en-us/graph\n  - type: Blog\n    url: https://devblogs.microsoft.com/identity/\n    title: Identity Developer Blog\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/entra/fundamentals/whats-new\n\
  \  - type: Documentation\n    url: https://learn.microsoft.com/en-us/entra/identity/\n    title: Entra Documentation\n  - type: Console\n    url: https://developer.microsoft.com/en-us/graph/graph-explorer\n    title: Graph Explorer\n  - type: GitHubOrganization\n    url: https://github.com/AzureAD\n  - type: OpenAPI\n    url: openapi/microsoft-graph-identity-api.yml\n  - type: JSONSchema\n    url: json-schema/azure-active-directory-user-schema.json\n  - type: JSONLD\n    url: json-ld/azure-active-directory-context.jsonld\n  - type: Features\n    data:\n      - name: Single Sign-On\n        description: Enable users to sign in once and access all connected applications without re-authenticating.\n      - name: Conditional Access\n        description: Enforce granular access policies based on user, device, location, and risk signals for zero trust security.\n      - name: Multi-Factor Authentication\n        description: Add a second layer of security with phone, app, or hardware token verification\
  \ for identity protection.\n      - name: SCIM User Provisioning\n        description: Automate user and group lifecycle management across cloud applications using SCIM 2.0 standard.\n      - name: Verifiable Credentials\n        description: Issue and verify decentralized identity credentials based on W3C standards for privacy-preserving identity verification.\n      - name: Identity Governance\n        description: Automate access reviews, entitlement management, and lifecycle workflows for identity governance at scale.\n      - name: Application Proxy\n        description: Publish on-premises web applications externally with secure remote access without VPN infrastructure.\n  - type: UseCases\n    data:\n      - name: Enterprise SSO\n        description: Implement single sign-on across SaaS and on-premises applications for seamless employee access management.\n      - name: B2B Collaboration\n        description: Enable secure collaboration with external partners and guests using Azure\
  \ AD B2B identity federation.\n      - name: Customer Identity\n        description: Build customer-facing applications with self-service sign-up, social identity providers, and branded login experiences.\n      - name: Zero Trust Security\n        description: Implement zero trust architecture with conditional access policies, continuous access evaluation, and risk-based authentication.\n      - name: Automated User Provisioning\n        description: Automate user account creation, updates, and deprovisioning across connected SaaS applications using SCIM.\n  - type: Integrations\n    data:\n      - name: Microsoft 365\n        description: Native identity provider for all Microsoft 365 applications including Teams, Outlook, SharePoint, and OneDrive.\n      - name: Salesforce\n        description: Single sign-on and automated user provisioning for Salesforce CRM using SAML and SCIM protocols.\n      - name: ServiceNow\n        description: Federated authentication and automated user lifecycle\
  \ management for ServiceNow ITSM platform.\n      - name: AWS\n        description: Cross-cloud identity federation enabling Azure AD users to access AWS resources with single sign-on.\n      - name: Workday\n        description: HR-driven identity provisioning with automated user creation and attribute synchronization from Workday.\ninclude:\n  - name: Microsoft Identity Platform\n    url: https://docs.microsoft.com/en-us/azure/active-directory/develop/\n  - name: Azure AD B2C\n    url: https://azure.microsoft.com/en-us/services/active-directory/external-identities/b2c/\n  - name: Azure AD B2B\n    url: https://docs.microsoft.com/en-us/azure/active-directory/external-identities/\n  - name: Microsoft Entra External ID\n    url: https://learn.microsoft.com/en-us/entra/external-id/self-service-sign-up-secure-api-connector\n  - name: Microsoft Entra ID Protection\n    url: https://learn.microsoft.com/en-us/entra/id-protection/howto-identity-protection-graph-api\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-active-directory/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Identity
- Microsoft
- Microsoft Entra
- OAuth
- OpenID Connect
- SAML
- SCIM
- Single Sign-On
- Zero Trust
url: https://azure.microsoft.com/en-us/services/active-directory/
use_cases:
- description: Implement single sign-on across SaaS and on-premises applications for seamless employee access management.
  name: Enterprise SSO
- description: Enable secure collaboration with external partners and guests using Azure AD B2B identity federation.
  name: B2B Collaboration
- description: Build customer-facing applications with self-service sign-up, social identity providers, and branded login experiences.
  name: Customer Identity
- description: Implement zero trust architecture with conditional access policies, continuous access evaluation, and risk-based authentication.
  name: Zero Trust Security
- description: Automate user account creation, updates, and deprovisioning across connected SaaS applications using SCIM.
  name: Automated User Provisioning
---
