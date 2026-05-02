---
api_count: 8
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
apis:
- description: Unified API endpoint for accessing Microsoft 365 services including users, mail, calendar, contacts, files, and more.
  name: Microsoft Graph API
  slug: ''
- description: API for building apps and bots that integrate with Microsoft Teams.
  name: Microsoft Teams API
  slug: ''
- description: API for accessing and managing email messages through Microsoft Outlook.
  name: Outlook Mail API
  slug: ''
- description: API for accessing and managing files stored in OneDrive and SharePoint.
  name: OneDrive API
  slug: ''
- description: API for accessing SharePoint sites, lists, and content.
  name: SharePoint API
  slug: ''
- description: API for identity and access management in Azure AD.
  name: Azure Active Directory API
  slug: ''
- description: API for managing tasks and to-do lists.
  name: Microsoft To Do API
  slug: ''
- description: API for creating and managing plans, tasks, and team collaboration.
  name: Microsoft Planner API
  slug: ''
common: []
created: '2024-01-15'
description: Collection of Microsoft application APIs for productivity, collaboration, and enterprise services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Applications APIs
skills: []
slug: ms-applications
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ms-applications\nname: Microsoft Applications APIs\ndescription: >-\n  Collection of Microsoft application APIs for productivity, collaboration, and enterprise\n  services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://developer.microsoft.com\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365 services including users, mail,\n      calendar, contacts, files, and more.\n    image: https://developer.microsoft.com/graph/images/graph-logo.png\n    humanURL: https://developer.microsoft.com/graph\n    baseURL: https://graph.microsoft.com\n    tags:\n      - Cloud\n      - Collaboration\n      - Identity\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/graph/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n\
  \      - type: Authentication\n        url: https://docs.microsoft.com/graph/auth/\n      - type: SDKs\n        url: https://docs.microsoft.com/graph/sdks/sdks-overview\n      - type: Pricing\n        url: https://azure.microsoft.com/pricing/details/active-directory/\n  - name: Microsoft Teams API\n    description: >-\n      API for building apps and bots that integrate with Microsoft Teams.\n    image: https://developer.microsoft.com/teams/images/teams-logo.png\n    humanURL: https://developer.microsoft.com/microsoft-teams\n    baseURL: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Chat\n      - Collaboration\n      - Meetings\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/microsoftteams/platform/\n      - type: Getting Started\n        url: https://docs.microsoft.com/microsoftteams/platform/get-started/get-started-overview\n      - type: Bot Framework\n        url: https://docs.microsoft.com/microsoftteams/platform/bots/what-are-bots\n\
  \      - type: Sample Apps\n        url: https://github.com/OfficeDev/Microsoft-Teams-Samples\n  - name: Outlook Mail API\n    description: >-\n      API for accessing and managing email messages through Microsoft Outlook.\n    image: https://www.microsoft.com/outlook/favicon.ico\n    humanURL: https://developer.microsoft.com/outlook\n    baseURL: https://graph.microsoft.com/v1.0/me/messages\n    tags:\n      - Email\n      - Messaging\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/graph/api/resources/mail-api-overview\n      - type: API Reference\n        url: https://docs.microsoft.com/graph/api/resources/message\n      - type: Quick Start\n        url: https://developer.microsoft.com/graph/quick-start\n  - name: OneDrive API\n    description: >-\n      API for accessing and managing files stored in OneDrive and SharePoint.\n    image: https://www.microsoft.com/onedrive/favicon.ico\n    humanURL: https://developer.microsoft.com/onedrive\n\
  \    baseURL: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Cloud\n      - Collaboration\n      - Files\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/onedrive/developer/\n      - type: API Reference\n        url: https://docs.microsoft.com/graph/api/resources/onedrive\n      - type: File Picker\n        url: https://docs.microsoft.com/onedrive/developer/controls/file-pickers/\n  - name: SharePoint API\n    description: >-\n      API for accessing SharePoint sites, lists, and content.\n    image: https://www.microsoft.com/sharepoint/favicon.ico\n    humanURL: https://developer.microsoft.com/sharepoint\n    baseURL: https://graph.microsoft.com/v1.0/sites\n    tags:\n      - Collaboration\n      - Content Management\n      - Enterprise\n      - Intranet\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/sharepoint/dev/\n      - type: REST API Reference\n        url: https://docs.microsoft.com/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service\n\
  \      - type: Framework\n        url: https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview\n  - name: Azure Active Directory API\n    description: >-\n      API for identity and access management in Azure AD.\n    image: https://azure.microsoft.com/favicon.ico\n    humanURL: https://developer.microsoft.com/identity\n    baseURL: https://graph.microsoft.com/v1.0/users\n    tags:\n      - Authentication\n      - Authorization\n      - Identity\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/azure/active-directory/develop/\n      - type: Authentication Flows\n        url: https://docs.microsoft.com/azure/active-directory/develop/authentication-flows-app-scenarios\n      - type: Microsoft Identity Platform\n        url: https://docs.microsoft.com/azure/active-directory/develop/v2-overview\n  - name: Microsoft To Do API\n    description: >-\n      API for managing tasks and to-do lists.\n    image: https://www.microsoft.com/microsoft-365/favicon.ico\n\
  \    humanURL: https://developer.microsoft.com/graph\n    baseURL: https://graph.microsoft.com/v1.0/me/todo\n    tags:\n      - Planning\n      - Productivity\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/graph/api/resources/todo-overview\n      - type: API Reference\n        url: https://docs.microsoft.com/graph/api/resources/todotask\n  - name: Microsoft Planner API\n    description: >-\n      API for creating and managing plans, tasks, and team collaboration.\n    image: https://www.microsoft.com/microsoft-365/favicon.ico\n    humanURL: https://developer.microsoft.com/graph\n    baseURL: https://graph.microsoft.com/v1.0/planner\n    tags:\n      - Collaboration\n      - Productivity\n      - Project Management\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/graph/api/resources/planner-overview\n      - type: API Reference\n        url: https://docs.microsoft.com/graph/api/resources/plannertask\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Enterprise\n  - Microsoft\n  - Microsoft-365\n  - Office\n  - Productivity\n  - Saas\ninclude:\n  - name: Microsoft Developer Network\n    url: https://developer.microsoft.com\n  - name: Microsoft Learn\n    url: https://docs.microsoft.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ms-applications/refs/heads/main/apis.yml
tags:
- Cloud
- Enterprise
- Microsoft
- Microsoft-365
- Office
- Productivity
- Saas
url: https://developer.microsoft.com
use_cases: []
---
