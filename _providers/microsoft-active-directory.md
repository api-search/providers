---
api_count: 4
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API (Azure AD)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/openapi.yaml
apis:
- description: REST API for accessing Azure Active Directory resources including users, groups, applications, and directory data.
  name: Microsoft Graph API (Azure AD)
  slug: ''
- description: Lightweight Directory Access Protocol interface for querying and modifying Active Directory.
  name: LDAP Protocol Interface
  slug: ''
- description: PowerShell cmdlets for managing Active Directory Domain Services.
  name: PowerShell Active Directory Module
  slug: ''
- description: Legacy REST API for Azure Active Directory (being replaced by Microsoft Graph).
  name: Azure AD Graph API (Deprecated)
  slug: ''
common:
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/servicesagreement
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Service Status
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/bg-p/Identity
- title: ''
  type: Support
  url: https://support.microsoft.com/en-us/windows-server
created: '2024'
description: Microsoft Active Directory (AD) is a directory service developed by Microsoft for Windows domain networks. It provides authentication and authorization services, centralized domain management, and directory services.
features: []
image: https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/media/active-directory-domain-services.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Active Directory
skills: []
slug: microsoft-active-directory
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Active Directory\ndescription: Microsoft Active Directory (AD) is a directory service developed by Microsoft for Windows domain networks. It provides authentication and authorization services, centralized domain management, and directory services.\nimage: https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/media/active-directory-domain-services.png\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\nurl: https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/\ntags:\n  - Authentication\n  - Authorization\n  - Directory Services\n  - Enterprise\n  - Identity\n  - Ldap\n  - Windows\napis:\n  - name: Microsoft Graph API (Azure AD)\n    description: >-\n      REST API for accessing Azure Active Directory resources including users, groups,\n      applications, and directory data.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://docs.microsoft.com/en-us/graph/overview\n    baseURL:\
  \ https://graph.microsoft.com\n    tags:\n      - Azure\n      - Groups\n      - Identity\n      - Rest\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/active-directory/\n    contact:\n      - FN: Microsoft Support\n        url: https://support.microsoft.com\n  - name: LDAP Protocol Interface\n    description: >-\n      Lightweight Directory Access Protocol interface for querying and modifying Active\n      Directory.\n    humanURL: https://docs.microsoft.com/en-us/previous-versions/windows/desktop/ldap/lightweight-directory-access-protocol-ldap-api\n\
  \    baseURL: ldap://[domain-controller]:389\n    tags:\n      - Directory\n      - Ldap\n      - Protocol\n      - Queries\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/windows/win32/ad/active-directory-ldap\n      - type: Protocol Specification\n        url: https://datatracker.ietf.org/doc/html/rfc4511\n      - type: Examples\n        url: https://docs.microsoft.com/en-us/windows/win32/ad/example-code-for-searching-active-directory\n  - name: PowerShell Active Directory Module\n    description: >-\n      PowerShell cmdlets for managing Active Directory Domain Services.\n    humanURL: https://docs.microsoft.com/en-us/powershell/module/activedirectory/\n    tags:\n      - Administration\n      - Automation\n      - Powershell\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/powershell/module/activedirectory/\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/powershell/module/activedirectory/get-aduser\n\
  \      - type: Examples\n        url: https://docs.microsoft.com/en-us/powershell/scripting/samples/sample-scripts-for-administration\n  - name: Azure AD Graph API (Deprecated)\n    description: >-\n      Legacy REST API for Azure Active Directory (being replaced by Microsoft Graph).\n    humanURL: https://docs.microsoft.com/en-us/previous-versions/azure/ad/graph/\n    baseURL: https://graph.windows.net\n    tags:\n      - Azure\n      - Deprecated\n      - Legacy\n      - Rest\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/previous-versions/azure/ad/graph/api/api-catalog\n      - type: Migration Guide\n        url: https://docs.microsoft.com/en-us/graph/migrate-azure-ad-graph-overview\n      - type: Deprecation Notice\n        url: https://docs.microsoft.com/en-us/graph/migrate-azure-ad-graph-overview\nmaintainers:\n  - FN: Microsoft Corporation\n    email: support@microsoft.com\n    url: https://www.microsoft.com\ncommon:\n  - type: Terms\
  \ of Service\n    url: https://www.microsoft.com/en-us/servicesagreement\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Service Status\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/bg-p/Identity\n  - type: Support\n    url: https://support.microsoft.com/en-us/windows-server\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-active-directory/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Directory Services
- Enterprise
- Identity
- Ldap
- Windows
url: https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/
use_cases: []
---
