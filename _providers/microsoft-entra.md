---
api_count: 14
api_specs:
- filename: microsoft-entra-graph-identity-openapi.yml
  format: yaml
  label: Microsoft Entra ID (Azure AD) API
  slug: graph-identity
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-entra/refs/heads/main/openapi/microsoft-entra-graph-identity-openapi.yml
apis:
- description: Core identity and access management API for user authentication, authorization, and directory management.
  name: Microsoft Entra ID (Azure AD) API
  slug: graph-identity
- description: API for identity risk detection, investigation, and remediation.
  name: Microsoft Entra ID Protection API
  slug: id-protection
- description: API for managing conditional access policies and controls.
  name: Microsoft Entra Conditional Access API
  slug: conditional-access
- description: API for managing privileged access and just-in-time administration.
  name: Microsoft Entra Privileged Identity Management API
  slug: pim
- description: API for issuing and verifying decentralized identity credentials.
  name: Microsoft Entra Verified ID API
  slug: verified-id
- description: API for managing customer and partner identity and access management.
  name: Microsoft Entra External ID API
  slug: external-id
- description: API for managing identity governance including access reviews, entitlement management, and lifecycle workflows to ensure the right people have the right access at the right time.
  name: Microsoft Entra ID Governance API
  slug: id-governance
- description: API for registering, configuring, and managing applications and service principals in Microsoft Entra ID.
  name: Microsoft Entra Application Management API
  slug: application-management
- description: API for managing user authentication methods including FIDO2 security keys, passwordless phone sign-in, Microsoft Authenticator, and MFA registration.
  name: Microsoft Entra Authentication Methods API
  slug: authentication-methods
- description: API for managing and securing identities for software workloads such as applications, services, scripts, and containers.
  name: Microsoft Entra Workload ID API
  slug: workload-id
- description: API for automating user provisioning and deprovisioning using SCIM protocol, including API-driven inbound provisioning from any system of record.
  name: Microsoft Entra Provisioning API
  slug: provisioning
- description: API for managing Microsoft Entra Internet Access and Microsoft Entra Private Access, providing identity-centric secure web gateway and zero-trust network access.
  name: Microsoft Entra Global Secure Access API
  slug: global-secure-access
- description: API endpoints for OAuth 2.0, OpenID Connect, and SAML authentication protocols enabling application integration with Microsoft Entra ID.
  name: Microsoft Identity Platform API
  slug: identity-platform
- description: API for creating, securing, and monitoring AI agent identities, providing authentication, authorization, and lifecycle management for AI agents.
  name: Microsoft Entra Agent ID API
  slug: agent-id
capabilities:
- description: Unified workflow for managing identity and access including users, groups, applications, and service principals in Microsoft Entra ID. Used by IT administrators and identity engineers.
  name: Microsoft Entra Identity and Access Management
  slug: identity-and-access
common:
- title: ''
  type: Portal
  url: https://entra.microsoft.com/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/entra/fundamentals/
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/bg-p/Identity
- title: ''
  type: Support
  url: https://learn.microsoft.com/en-us/entra/fundamentals/how-to-get-support
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/licensing/terms/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/entra/fundamentals/whats-new
- title: ''
  type: SDK
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoftgraph
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing
- title: ''
  type: JSONLD
  url: json-ld/microsoft-entra-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/microsoft-entra-user-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/microsoft-entra-application-schema.json
- title: Graph Identity API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/graph-identity.yaml
- title: Identity and Access Management Workflow
  type: NaftikoCapability
  url: capabilities/identity-and-access.yaml
created: '2024-01-01'
description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management services including authentication, authorization, and directory services.
features:
- description: Manage user identities, authentication, and authorization across cloud and hybrid environments with single sign-on.
  name: Identity and Access Management
- description: Enforce adaptive access policies based on user, device, location, and risk signals for zero trust security.
  name: Conditional Access
- description: Automate access reviews, entitlement management, and lifecycle workflows to ensure proper access controls.
  name: Identity Governance
- description: Manage, control, and monitor privileged access with just-in-time and approval-based activation.
  name: Privileged Identity Management
- description: Issue and verify decentralized identity credentials using open standards for portable, self-sovereign identity.
  name: Verified ID
- description: Enable secure collaboration with external partners and customers through B2B and B2C identity management.
  name: External Identities
- description: Provide identity-centric secure web gateway and zero-trust network access for internet and private resources.
  name: Global Secure Access
- description: Secure and manage identities for applications, services, scripts, and containers running as software workloads.
  name: Workload Identities
image: https://www.microsoft.com/en-us/security/content/dam/microsoft/final/security/includes/microsoft-entra-logo.svg
integrations:
- description: Deep integration for identity and access management across all Microsoft 365 applications and services.
  name: Microsoft 365
- description: Native identity provider for Azure resources including VMs, databases, storage, and managed identities.
  name: Azure Services
- description: Hybrid identity synchronization with on-premises Active Directory using Azure AD Connect.
  name: Active Directory
- description: SAML and SCIM integration for single sign-on and automated user provisioning with Salesforce.
  name: Salesforce
- description: SSO and automated provisioning integration with ServiceNow ITSM platform.
  name: ServiceNow
- description: Inbound provisioning from Workday HR to automate user lifecycle management.
  name: Workday
- description: SSO and provisioning integration with SAP applications and S/4HANA.
  name: SAP
- description: Cross-platform identity federation and migration support with Okta identity provider.
  name: Okta
jsonld:
- class_count: 0
  name: Microsoft Entra Context
  property_count: 5
  slug: microsoft-entra-context
- class_count: 0
  name: Microsoft Entra Graph Identity Context
  property_count: 0
  slug: microsoft-entra-graph-identity-context
layout: provider
modified: '2026-04-18'
name: Microsoft Entra
rules:
- name: Microsoft Entra API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: microsoft-entra-spectral-rules
skills: []
slug: microsoft-entra
solutions: []
source_filename: apis.yml
source_yaml: "aid: microsoft-entra\nname: Microsoft Entra\ndescription: Microsoft Entra (formerly Azure Active Directory) provides identity and access management services including authentication, authorization, and directory services.\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-entra/refs/heads/main/apis.yml\nimage: https://www.microsoft.com/en-us/security/content/dam/microsoft/final/security/includes/microsoft-entra-logo.svg\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\ntags:\n  - Access Management\n  - Authentication\n  - Azure AD\n  - Entra\n  - Identity\n  - Identity Governance\n  - Microsoft\n  - Network Security\n  - Security\n  - Zero Trust\napis:\n  - aid: microsoft-entra:graph-identity\n    name: Microsoft Entra ID (Azure AD) API\n    description: >-\n      Core identity and access management API for user authentication, authorization,\n      and directory management.\n    image: https://www.microsoft.com/en-us/security/content/dam/microsoft/final/security/includes/microsoft-entra-logo.svg\n\
  \    humanURL: https://learn.microsoft.com/en-us/graph/azuread-identity-access-management-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Authentication\n      - Authorization\n      - Directory\n      - Groups\n      - Identity\n      - Users\n    properties:\n      - type: OpenAPI\n        url: openapi/microsoft-entra-graph-identity-openapi.yml\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Pricing\n        url: https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/tutorial-applications-basics\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identity-network-access-overview\n\
  \  - aid: microsoft-entra:id-protection\n    name: Microsoft Entra ID Protection API\n    description: >-\n      API for identity risk detection, investigation, and remediation.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/identityprotection-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Identity Protection\n      - Risk Detection\n      - Security\n      - Threat Protection\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/id-protection/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identityprotectionroot\n  - aid: microsoft-entra:conditional-access\n    name: Microsoft Entra Conditional Access API\n    description: >-\n      API for managing conditional access policies and controls.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/conditionalaccessroot\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n  \
  \    - Access Control\n      - Conditional Access\n      - Policies\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity/conditional-access/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/conditionalaccessroot\n  - aid: microsoft-entra:pim\n    name: Microsoft Entra Privileged Identity Management API\n    description: >-\n      API for managing privileged access and just-in-time administration.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/privilegedidentitymanagementv3-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Just-In-Time\n      - PIM\n      - Privileged Access\n      - Role Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/id-governance/privileged-identity-management/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/privilegedidentitymanagementv3-overview\n\
  \  - aid: microsoft-entra:verified-id\n    name: Microsoft Entra Verified ID API\n    description: >-\n      API for issuing and verifying decentralized identity credentials.\n    humanURL: https://learn.microsoft.com/en-us/entra/verified-id/\n    baseURL: https://verifiedid.did.msidentity.com/v1.0\n    tags:\n      - Decentralized Identity\n      - DID\n      - SSI\n      - Verifiable Credentials\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/verified-id/verifiable-credentials-configure-tenant\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/entra/verified-id/get-started-request-api\n  - aid: microsoft-entra:external-id\n    name: Microsoft Entra External ID API\n    description: >-\n      API for managing customer and partner identity and access management.\n    humanURL: https://learn.microsoft.com/en-us/entra/external-id/\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - B2B\n      - B2C\n\
  \      - Customer Identity\n      - External Identities\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/external-id/external-identities-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identity-network-access-overview\n  - aid: microsoft-entra:id-governance\n    name: Microsoft Entra ID Governance API\n    description: >-\n      API for managing identity governance including access reviews, entitlement management,\n      and lifecycle workflows to ensure the right people have the right access at\n      the right time.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/identitygovernance-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Access Reviews\n      - Compliance\n      - Entitlement Management\n      - Identity Governance\n      - Lifecycle Workflows\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/id-governance/identity-governance-overview\n\
  \      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identitygovernance-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/tutorial-access-package-api\n  - aid: microsoft-entra:application-management\n    name: Microsoft Entra Application Management API\n    description: >-\n      API for registering, configuring, and managing applications and service principals\n      in Microsoft Entra ID.\n    humanURL: https://learn.microsoft.com/en-us/graph/applications-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - App Registration\n      - Applications\n      - Credentials\n      - OAuth\n      - Service Principals\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/applications-api-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/applications-api-overview\n \
  \     - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/tutorial-applications-basics\n  - aid: microsoft-entra:authentication-methods\n    name: Microsoft Entra Authentication Methods API\n    description: >-\n      API for managing user authentication methods including FIDO2 security keys,\n      passwordless phone sign-in, Microsoft Authenticator, and MFA registration.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/authenticationmethods-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Authentication Methods\n      - FIDO2\n      - MFA\n      - Passkeys\n      - Passwordless\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/authenticationmethods-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/authenticationmethods-get-started\n\
  \  - aid: microsoft-entra:workload-id\n    name: Microsoft Entra Workload ID API\n    description: >-\n      API for managing and securing identities for software workloads such as applications,\n      services, scripts, and containers.\n    humanURL: https://learn.microsoft.com/en-us/entra/workload-id/\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Managed Identities\n      - Service Principals\n      - Workload Identities\n      - Workload Identity Federation\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/workload-id/workload-identities-overview\n  - aid: microsoft-entra:provisioning\n    name: Microsoft Entra Provisioning API\n    description: >-\n      API for automating user provisioning and deprovisioning using SCIM protocol,\n      including API-driven inbound provisioning from any system of record.\n    humanURL: https://learn.microsoft.com/en-us/entra/identity/app-provisioning/inbound-provisioning-api-concepts\n\
  \    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Inbound Provisioning\n      - Provisioning\n      - SCIM\n      - Synchronization\n      - User Lifecycle\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity/app-provisioning/how-provisioning-works\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/synchronization-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/entra/identity/app-provisioning/inbound-provisioning-api-configure-app\n  - aid: microsoft-entra:global-secure-access\n    name: Microsoft Entra Global Secure Access API\n    description: >-\n      API for managing Microsoft Entra Internet Access and Microsoft Entra Private\n      Access, providing identity-centric secure web gateway and zero-trust network\n      access.\n    humanURL: https://learn.microsoft.com/en-us/entra/global-secure-access/overview-what-is-global-secure-access\n\
  \    baseURL: https://graph.microsoft.com/beta\n    tags:\n      - Internet Access\n      - Network Security\n      - Private Access\n      - Secure Web Gateway\n      - Zero Trust\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/global-secure-access/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/networkaccess-global-secure-access-api-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/tutorial-entra-private-access\n  - aid: microsoft-entra:identity-platform\n    name: Microsoft Identity Platform API\n    description: >-\n      API endpoints for OAuth 2.0, OpenID Connect, and SAML authentication protocols\n      enabling application integration with Microsoft Entra ID.\n    humanURL: https://learn.microsoft.com/en-us/entra/identity-platform/\n    baseURL: https://login.microsoftonline.com\n    tags:\n      - Identity Platform\n    \
  \  - OAuth 2.0\n      - OpenID Connect\n      - SAML\n      - Token Service\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/entra/identity-platform/v2-protocols\n  - aid: microsoft-entra:agent-id\n    name: Microsoft Entra Agent ID API\n    description: >-\n      API for creating, securing, and monitoring AI agent identities, providing authentication,\n      authorization, and lifecycle management for AI agents.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/agentid-platform-overview\n    baseURL: https://graph.microsoft.com/beta\n    tags:\n      - Agent Identity\n      - Agent Registry\n      - AI Agents\n      - Machine Identity\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/agentid-platform-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/entra/agent-id/identity-platform/interactive-agent-request-user-tokens\n\
  common:\n  - type: Portal\n    url: https://entra.microsoft.com/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/entra/fundamentals/\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/bg-p/Identity\n  - type: Support\n    url: https://learn.microsoft.com/en-us/entra/fundamentals/how-to-get-support\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: TermsOfService\n    url: https://www.microsoft.com/licensing/terms/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/entra/fundamentals/whats-new\n  - type: SDK\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: GitHubOrganization\n    url: https://github.com/microsoftgraph\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing\n\
  \  - type: JSONLD\n    url: json-ld/microsoft-entra-context.jsonld\n  - type: JSONSchema\n    url: json-schema/microsoft-entra-user-schema.json\n  - type: JSONSchema\n    url: json-schema/microsoft-entra-application-schema.json\n  - type: NaftikoCapability\n    url: capabilities/shared/graph-identity.yaml\n    title: Graph Identity API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/identity-and-access.yaml\n    title: Identity and Access Management Workflow\n  - type: Features\n    data:\n      - name: Identity and Access Management\n        description: Manage user identities, authentication, and authorization across cloud and hybrid environments with single sign-on.\n      - name: Conditional Access\n        description: Enforce adaptive access policies based on user, device, location, and risk signals for zero trust security.\n      - name: Identity Governance\n        description: Automate access reviews, entitlement management, and lifecycle workflows to ensure\
  \ proper access controls.\n      - name: Privileged Identity Management\n        description: Manage, control, and monitor privileged access with just-in-time and approval-based activation.\n      - name: Verified ID\n        description: Issue and verify decentralized identity credentials using open standards for portable, self-sovereign identity.\n      - name: External Identities\n        description: Enable secure collaboration with external partners and customers through B2B and B2C identity management.\n      - name: Global Secure Access\n        description: Provide identity-centric secure web gateway and zero-trust network access for internet and private resources.\n      - name: Workload Identities\n        description: Secure and manage identities for applications, services, scripts, and containers running as software workloads.\n  - type: UseCases\n    data:\n      - name: Zero Trust Implementation\n        description: Implement zero trust architecture with identity-based access\
  \ controls, conditional access policies, and continuous verification.\n      - name: Hybrid Identity Management\n        description: Synchronize and manage identities across on-premises Active Directory and cloud environments.\n      - name: Application Single Sign-On\n        description: Enable SSO for thousands of SaaS and on-premises applications with SAML, OIDC, and password-based authentication.\n      - name: Automated User Provisioning\n        description: Automate user lifecycle management with SCIM-based provisioning and deprovisioning across integrated applications.\n      - name: AI Agent Identity Management\n        description: Create, secure, and monitor identities for AI agents with authentication, authorization, and lifecycle management.\n  - type: Integrations\n    data:\n      - name: Microsoft 365\n        description: Deep integration for identity and access management across all Microsoft 365 applications and services.\n      - name: Azure Services\n        description:\
  \ Native identity provider for Azure resources including VMs, databases, storage, and managed identities.\n      - name: Active Directory\n        description: Hybrid identity synchronization with on-premises Active Directory using Azure AD Connect.\n      - name: Salesforce\n        description: SAML and SCIM integration for single sign-on and automated user provisioning with Salesforce.\n      - name: ServiceNow\n        description: SSO and automated provisioning integration with ServiceNow ITSM platform.\n      - name: Workday\n        description: Inbound provisioning from Workday HR to automate user lifecycle management.\n      - name: SAP\n        description: SSO and provisioning integration with SAP applications and S/4HANA.\n      - name: Okta\n        description: Cross-platform identity federation and migration support with Okta identity provider.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-entra/refs/heads/main/apis.yml
tags:
- Access Management
- Authentication
- Azure AD
- Entra
- Identity
- Identity Governance
- Microsoft
- Network Security
- Security
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/microsoft-entra/refs/heads/main/apis.yml
use_cases:
- description: Implement zero trust architecture with identity-based access controls, conditional access policies, and continuous verification.
  name: Zero Trust Implementation
- description: Synchronize and manage identities across on-premises Active Directory and cloud environments.
  name: Hybrid Identity Management
- description: Enable SSO for thousands of SaaS and on-premises applications with SAML, OIDC, and password-based authentication.
  name: Application Single Sign-On
- description: Automate user lifecycle management with SCIM-based provisioning and deprovisioning across integrated applications.
  name: Automated User Provisioning
- description: Create, secure, and monitor identities for AI agents with authentication, authorization, and lifecycle management.
  name: AI Agent Identity Management
---
