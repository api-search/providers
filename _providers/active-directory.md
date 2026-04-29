---
api_count: 10
apis:
- description: Manage the entire lifecycle of users in Microsoft Entra ID, including creating, reading, updating, and deleting user accounts, managing licenses, group memberships, authentication methods, and profile
  name: Microsoft Graph Users API
  slug: ''
- description: Create and manage Microsoft Entra security groups, Microsoft 365 groups, and distribution lists. Manage group memberships, owners, and settings. Groups enable efficient entitlement management for user
  name: Microsoft Graph Groups API
  slug: ''
- description: Register and manage Microsoft Entra applications and their associated service principals programmatically. Configure app permissions, OAuth2 permission grants, app role assignments, certificates, fede
  name: Microsoft Graph Applications and Service Principals API
  slug: ''
- description: Manage devices registered or joined to Microsoft Entra ID, including Entra joined, Entra registered, and hybrid Azure AD joined devices. Retrieve BitLocker recovery keys and Local Admin Password Solut
  name: Microsoft Graph Devices API
  slug: ''
- description: Manage Microsoft Entra built-in and custom directory roles, role assignments, and role-scoped administrative units. Assign administrator roles to users, groups, or service principals, and create scope
  name: Microsoft Graph Directory Roles and Administrative Units API
  slug: ''
- description: Create and manage Microsoft Entra Conditional Access policies that enforce access controls based on user, location, device, and risk signals. Configure named locations, authentication context class re
  name: Microsoft Graph Conditional Access API
  slug: ''
- description: Manage Microsoft Entra ID Governance features including access reviews, entitlement management (access packages, catalogs, and policies), Privileged Identity Management (PIM) for just-in-time role act
  name: Microsoft Graph Identity Governance API
  slug: ''
- description: Detect, investigate, and remediate identity-based risks using Microsoft Entra ID Protection. Access risk detections, risky users, risky service principals, and risk events, and feed data into SIEM too
  name: Microsoft Graph Identity Protection API
  slug: ''
- description: Manage authentication methods registered for users in Microsoft Entra ID, including FIDO2 security keys, Microsoft Authenticator, phone (SMS/voice call), email OTP, Windows Hello for Business, and tem
  name: Microsoft Graph Authentication Methods API
  slug: ''
- description: 'Access audit logs, sign-in logs, provisioning logs, and identity-related reports for monitoring, compliance, and troubleshooting. Stream logs to Azure Monitor and Log Analytics or to third-party SIEM '
  name: Microsoft Graph Identity and Access Reports API
  slug: ''
capabilities:
- description: Unified workflow for managing Microsoft Entra ID (Active Directory) identity and access operations including user lifecycle management, group management, and application registration. Used by IT admin
  name: Microsoft Active Directory Identity Management Operations
  slug: identity-management-operations
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/graph
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/graph/get-started
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/graph/overview
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/auth-concepts
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/en-us/graph/api/overview
- title: ''
  type: RateLimits
  url: https://learn.microsoft.com/en-us/graph/throttling
- title: ''
  type: SDK
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: CLI
  url: https://learn.microsoft.com/en-us/cli/azure/ad
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/microsoft365dev/
- title: ''
  type: StatusPage
  url: https://azure.status.microsoft.com/
- title: ''
  type: Support
  url: https://developer.microsoft.com/en-us/graph/support
- title: ''
  type: TermsOfService
  url: https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/privacystatement
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/graph/changelog
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoftgraph
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoftgraph/microsoft-graph-openapi
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/microsoft-graph
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/paths/m365-msgraph-associate/
- title: ''
  type: SpectralRules
  url: rules/active-directory-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/identity-management-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/active-directory-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/active-directory-context.jsonld
created: '2024-01-01'
description: Microsoft Active Directory and Microsoft Entra ID provide identity and access management for organizations of all sizes. Microsoft Graph API is the unified REST API gateway for accessing and managing Microsoft Entra ID (formerly Azure Active Directory), including users, groups, applications, devices, conditional access policies, identity governance, and directory administration. Legacy on-premises Active Directory is managed through LDAP, Kerberos, and PowerShell protocols; cloud identity is managed through Microsoft Graph.
features:
- description: Single REST endpoint (graph.microsoft.com) for all Microsoft Entra identity and directory operations.
  name: Unified Identity API
- description: Full CRUD operations for user accounts including bulk operations, license assignment, and guest management.
  name: User Lifecycle Management
- description: Create and manage security groups, Microsoft 365 groups, and dynamic membership groups.
  name: Group Management
- description: Programmatic app registration, permission configuration, and service principal management.
  name: Application Registration
- description: Create, update, and evaluate Conditional Access policies via API for Zero Trust enforcement.
  name: Conditional Access Automation
- description: Just-in-time role activation, time-bound access, and PIM policy management via API.
  name: Privileged Identity Management
- description: Access risk signals, risky users, and risk detections for automated threat response.
  name: Identity Protection
- description: Manage MFA and passwordless authentication methods registered for users.
  name: Authentication Method Management
- description: Programmatic access to audit logs, sign-in logs, and provisioning logs for SIEM integration.
  name: Audit and Sign-in Logs
- description: Access reviews, entitlement management, and lifecycle workflows for automated IAM.
  name: Identity Governance
image: https://learn.microsoft.com/en-us/entra/media/index/active-directory.svg
integrations:
- description: Microsoft Entra ID (formerly Azure AD) is the cloud identity backbone accessed via Microsoft Graph.
  name: Azure Active Directory
- description: Microsoft Graph provides unified access to Microsoft 365 user data alongside identity operations.
  name: Microsoft 365
- description: Stream Microsoft Entra sign-in and audit logs to Azure Monitor Log Analytics for analysis.
  name: Azure Monitor
- description: Feed identity risk signals and audit logs into Microsoft Sentinel SIEM for threat hunting.
  name: Microsoft Sentinel
- description: Microsoft Graph Intune APIs integrate device management with identity policies.
  name: Intune
- description: Automate user provisioning to SaaS applications using Microsoft Entra SCIM provisioning.
  name: SCIM Providers
- description: Register and manage federated applications using SAML 2.0 and OpenID Connect via Microsoft Graph.
  name: SAML and OIDC Applications
jsonld:
- class_count: 1
  name: Active Directory Context
  property_count: 69
  slug: active-directory-context
layout: provider
modified: '2026-04-19'
name: Microsoft Active Directory
rules:
- name: Microsoft Active Directory API Rules
  rule_count: 33
  severity_counts:
    error: 14
    hint: 0
    info: 4
    warn: 15
  slug: active-directory-spectral-rules
skills: []
slug: active-directory
solutions: []
source_yaml: "name: Microsoft Active Directory\ndescription: >-\n  Microsoft Active Directory and Microsoft Entra ID provide identity and access management\n  for organizations of all sizes. Microsoft Graph API is the unified REST API gateway\n  for accessing and managing Microsoft Entra ID (formerly Azure Active Directory), including\n  users, groups, applications, devices, conditional access policies, identity governance,\n  and directory administration. Legacy on-premises Active Directory is managed through LDAP,\n  Kerberos, and PowerShell protocols; cloud identity is managed through Microsoft Graph.\nimage: https://learn.microsoft.com/en-us/entra/media/index/active-directory.svg\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n  - Active Directory\n  - Authentication\n  - Authorization\n  - Directory Services\n  - Identity Management\n  - Microsoft Entra\n  - Zero Trust\napis:\n  - name: Microsoft Graph Users API\n    description: >-\n      Manage\
  \ the entire lifecycle of users in Microsoft Entra ID, including creating,\n      reading, updating, and deleting user accounts, managing licenses, group memberships,\n      authentication methods, and profile photos. Supports both v1.0 and beta endpoints.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/users\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Directory Services\n      - Identity Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/users\n      - type: OpenAPI\n        url: openapi/active-directory-users-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/users-user-schema.json\n      - type: JSONSchema\n        url: json-schema/users-password-profile-schema.json\n      - type: JSONStructure\n        url: json-structure/users-user-structure.json\n      - type: Example\n        url: examples/users-user-example.json\n      - type: NaftikoCapability\n\
  \        url: capabilities/shared/active-directory-users.yaml\n\n  - name: Microsoft Graph Groups API\n    description: >-\n      Create and manage Microsoft Entra security groups, Microsoft 365 groups, and\n      distribution lists. Manage group memberships, owners, and settings. Groups\n      enable efficient entitlement management for users, licensing, and resource access.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/groups-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Directory Services\n      - Groups\n      - Identity Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/groups-overview\n      - type: OpenAPI\n        url: openapi/active-directory-groups-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/groups-group-schema.json\n      - type: JSONStructure\n        url: json-structure/groups-group-structure.json\n      - type: Example\n     \
  \   url: examples/groups-group-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/active-directory-groups.yaml\n\n  - name: Microsoft Graph Applications and Service Principals API\n    description: >-\n      Register and manage Microsoft Entra applications and their associated service principals\n      programmatically. Configure app permissions, OAuth2 permission grants, app role assignments,\n      certificates, federated identity credentials, and app consent policies.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/applications-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Applications\n      - Identity Management\n      - OAuth2\n      - Service Principals\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/applications-api-overview\n      - type: OpenAPI\n        url: openapi/active-directory-applications-openapi.yaml\n      - type: JSONSchema\n\
  \        url: json-schema/applications-application-schema.json\n      - type: JSONSchema\n        url: json-schema/applications-service-principal-schema.json\n      - type: JSONStructure\n        url: json-structure/applications-application-structure.json\n      - type: Example\n        url: examples/applications-application-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/active-directory-applications.yaml\n\n  - name: Microsoft Graph Devices API\n    description: >-\n      Manage devices registered or joined to Microsoft Entra ID, including Entra joined,\n      Entra registered, and hybrid Azure AD joined devices. Retrieve BitLocker recovery keys\n      and Local Admin Password Solution (LAPS) credentials for managed devices.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/device\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Devices\n      - Endpoint Management\n      - Identity Management\n    properties:\n   \
  \   - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/device\n\n  - name: Microsoft Graph Directory Roles and Administrative Units API\n    description: >-\n      Manage Microsoft Entra built-in and custom directory roles, role assignments,\n      and role-scoped administrative units. Assign administrator roles to users, groups,\n      or service principals, and create scoped role assignments via administrative units.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/directoryrole\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Authorization\n      - Directory Services\n      - Role Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/directoryrole\n\n  - name: Microsoft Graph Conditional Access API\n    description: >-\n      Create and manage Microsoft Entra Conditional Access policies that enforce\n      access controls based on user,\
  \ location, device, and risk signals. Configure\n      named locations, authentication context class references, and evaluate policy\n      impact using what-if analysis.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/conditionalaccesspolicy\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Authorization\n      - Conditional Access\n      - Security\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/conditionalaccesspolicy\n\n  - name: Microsoft Graph Identity Governance API\n    description: >-\n      Manage Microsoft Entra ID Governance features including access reviews, entitlement\n      management (access packages, catalogs, and policies), Privileged Identity Management\n      (PIM) for just-in-time role activation, and lifecycle workflows for joiner/mover/leaver\n      employee identity lifecycle automation.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/identitygovernance-overview\n\
  \    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Governance\n      - Identity Management\n      - Lifecycle Management\n      - Privileged Identity Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identitygovernance-overview\n\n  - name: Microsoft Graph Identity Protection API\n    description: >-\n      Detect, investigate, and remediate identity-based risks using Microsoft Entra ID Protection.\n      Access risk detections, risky users, risky service principals, and risk events, and feed\n      data into SIEM tools for security correlation and incident response.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/identityprotection-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Identity Protection\n      - Risk Management\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/identityprotection-overview\n\
  \n  - name: Microsoft Graph Authentication Methods API\n    description: >-\n      Manage authentication methods registered for users in Microsoft Entra ID, including\n      FIDO2 security keys, Microsoft Authenticator, phone (SMS/voice call), email OTP,\n      Windows Hello for Business, and temporary access passes. Configure authentication\n      method policies and authentication strength requirements.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/authenticationmethods-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Authentication\n      - MFA\n      - Passwordless\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/authenticationmethods-overview\n\n  - name: Microsoft Graph Identity and Access Reports API\n    description: >-\n      Access audit logs, sign-in logs, provisioning logs, and identity-related reports for\n      monitoring, compliance, and troubleshooting.\
  \ Stream logs to Azure Monitor and Log Analytics\n      or to third-party SIEM tools for security operations.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/report-identity-access\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Audit Logs\n      - Compliance\n      - Monitoring\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/report-identity-access\n\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/graph\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/graph/get-started\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/graph/overview\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/auth-concepts\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/graph/api/overview\n  - type: RateLimits\n    url: https://learn.microsoft.com/en-us/graph/throttling\n  - type:\
  \ SDK\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/cli/azure/ad\n  - type: Blog\n    url: https://devblogs.microsoft.com/microsoft365dev/\n  - type: StatusPage\n    url: https://azure.status.microsoft.com/\n  - type: Support\n    url: https://developer.microsoft.com/en-us/graph/support\n  - type: TermsOfService\n    url: https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/privacystatement\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/graph/changelog\n  - type: GitHubOrganization\n    url: https://github.com/microsoftgraph\n  - type: GitHubRepository\n    url: https://github.com/microsoftgraph/microsoft-graph-openapi\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/microsoft-graph\n\
  \  - type: Training\n    url: https://learn.microsoft.com/en-us/training/paths/m365-msgraph-associate/\n  - type: SpectralRules\n    url: rules/active-directory-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/identity-management-operations.yaml\n  - type: Vocabulary\n    url: vocabulary/active-directory-vocabulary.yaml\n  - type: JSON-LD\n    url: json-ld/active-directory-context.jsonld\n  - type: Features\n    data:\n      - name: Unified Identity API\n        description: Single REST endpoint (graph.microsoft.com) for all Microsoft Entra identity and directory operations.\n      - name: User Lifecycle Management\n        description: Full CRUD operations for user accounts including bulk operations, license assignment, and guest management.\n      - name: Group Management\n        description: Create and manage security groups, Microsoft 365 groups, and dynamic membership groups.\n      - name: Application Registration\n        description: Programmatic app registration,\
  \ permission configuration, and service principal management.\n      - name: Conditional Access Automation\n        description: Create, update, and evaluate Conditional Access policies via API for Zero Trust enforcement.\n      - name: Privileged Identity Management\n        description: Just-in-time role activation, time-bound access, and PIM policy management via API.\n      - name: Identity Protection\n        description: Access risk signals, risky users, and risk detections for automated threat response.\n      - name: Authentication Method Management\n        description: Manage MFA and passwordless authentication methods registered for users.\n      - name: Audit and Sign-in Logs\n        description: Programmatic access to audit logs, sign-in logs, and provisioning logs for SIEM integration.\n      - name: Identity Governance\n        description: Access reviews, entitlement management, and lifecycle workflows for automated IAM.\n  - type: UseCases\n    data:\n      - name: User\
  \ Provisioning Automation\n        description: Automate user account creation, attribute updates, and deprovisioning for HR-driven identity lifecycle.\n      - name: Zero Trust Policy Enforcement\n        description: Programmatically deploy and manage Conditional Access policies across the organization.\n      - name: SIEM Integration\n        description: Stream audit logs and sign-in events to security information and event management systems.\n      - name: Application Access Management\n        description: Automate app registration, permission grants, and app role assignments for developer self-service.\n      - name: Identity Risk Remediation\n        description: Detect and respond to risky sign-ins and compromised accounts via Identity Protection APIs.\n      - name: Compliance Reporting\n        description: Generate access reviews, entitlement reports, and audit logs for regulatory compliance.\n      - name: Privileged Access Governance\n        description: Enforce just-in-time\
  \ privileged access and audit role assignments via PIM APIs.\n  - type: Integrations\n    data:\n      - name: Azure Active Directory\n        description: Microsoft Entra ID (formerly Azure AD) is the cloud identity backbone accessed via Microsoft Graph.\n      - name: Microsoft 365\n        description: Microsoft Graph provides unified access to Microsoft 365 user data alongside identity operations.\n      - name: Azure Monitor\n        description: Stream Microsoft Entra sign-in and audit logs to Azure Monitor Log Analytics for analysis.\n      - name: Microsoft Sentinel\n        description: Feed identity risk signals and audit logs into Microsoft Sentinel SIEM for threat hunting.\n      - name: Intune\n        description: Microsoft Graph Intune APIs integrate device management with identity policies.\n      - name: SCIM Providers\n        description: Automate user provisioning to SaaS applications using Microsoft Entra SCIM provisioning.\n      - name: SAML and OIDC Applications\n\
  \        description: Register and manage federated applications using SAML 2.0 and OpenID Connect via Microsoft Graph.\n\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/active-directory/refs/heads/main/apis.yml
tags:
- Active Directory
- Authentication
- Authorization
- Directory Services
- Identity Management
- Microsoft Entra
- Zero Trust
url: ''
use_cases:
- description: Automate user account creation, attribute updates, and deprovisioning for HR-driven identity lifecycle.
  name: User Provisioning Automation
- description: Programmatically deploy and manage Conditional Access policies across the organization.
  name: Zero Trust Policy Enforcement
- description: Stream audit logs and sign-in events to security information and event management systems.
  name: SIEM Integration
- description: Automate app registration, permission grants, and app role assignments for developer self-service.
  name: Application Access Management
- description: Detect and respond to risky sign-ins and compromised accounts via Identity Protection APIs.
  name: Identity Risk Remediation
- description: Generate access reviews, entitlement reports, and audit logs for regulatory compliance.
  name: Compliance Reporting
- description: Enforce just-in-time privileged access and audit role assignments via PIM APIs.
  name: Privileged Access Governance
---
