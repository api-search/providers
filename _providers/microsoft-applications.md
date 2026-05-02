---
api_count: 9
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
apis:
- description: Unified API endpoint for accessing Microsoft 365, Windows 10, and Enterprise Mobility + Security services.
  name: Microsoft Graph API
  slug: ''
- description: APIs for Office 365 services including Outlook, OneDrive, and SharePoint.
  name: Office 365 API
  slug: ''
- description: Build apps and bots for Microsoft Teams collaboration platform.
  name: Microsoft Teams API
  slug: ''
- description: Access and manage files stored in OneDrive and SharePoint.
  name: OneDrive API
  slug: ''
- description: Access and manage email, calendar, and contacts in Outlook.
  name: Outlook Mail API
  slug: ''
- description: Programmatic access to SharePoint sites, lists, and content.
  name: SharePoint REST API
  slug: ''
- description: Embed Power BI content and manage Power BI resources.
  name: Power BI REST API
  slug: ''
- description: Manage tasks and to-do lists via Microsoft To Do.
  name: Microsoft To Do API
  slug: ''
- description: Create and manage plans, tasks, and team collaboration.
  name: Microsoft Planner API
  slug: ''
common: []
created: '2024-01-15'
description: A collection of APIs for Microsoft's suite of applications and services.
features: []
image: https://www.microsoft.com/favicon.ico
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Applications
skills: []
slug: microsoft-applications
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Applications\ndescription: >-\n  A collection of APIs for Microsoft's suite of applications and services.\nimage: https://www.microsoft.com/favicon.ico\nurl: https://www.microsoft.com/apis\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365, Windows 10, and Enterprise\n      Mobility + Security services.\n    image: https://learn.microsoft.com/favicon.ico\n    humanUrl: https://developer.microsoft.com/en-us/graph\n    baseUrl: https://graph.microsoft.com\n    tags:\n      - Calendar\n      - Files\n      - Groups\n      - Mail\n      - Teams\n      - Users\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n\
  \        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: GraphExplorer\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n  - name: Office 365 API\n    description: >-\n      APIs for Office 365 services including Outlook, OneDrive, and SharePoint.\n    humanUrl: https://developer.microsoft.com/en-us/office\n    baseUrl: https://outlook.office.com/api\n    tags:\n      - Calendar\n      - Contacts\n      - Email\n      - OneDrive\n      - SharePoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/\n      - type: GettingStarted\n        url: https://developer.microsoft.com/en-us/office/getting-started\n  - name: Microsoft Teams API\n    description: >-\n      Build apps and bots for Microsoft Teams collaboration platform.\n    humanUrl: https://developer.microsoft.com/en-us/microsoft-teams\n\
  \    baseUrl: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Bots\n      - Channels\n      - Chat\n      - Messaging\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/\n      - type: Samples\n        url: https://github.com/OfficeDev/Microsoft-Teams-Samples\n      - type: BotFramework\n        url: https://dev.botframework.com/\n  - name: OneDrive API\n    description: >-\n      Access and manage files stored in OneDrive and SharePoint.\n    humanUrl: https://developer.microsoft.com/en-us/onedrive\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Files\n      - Sharing\n      - Storage\n      - Sync\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/onedrive/developer/\n      - type: REST-API\n        url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/\n  - name: Outlook Mail API\n    description: >-\n      Access\
  \ and manage email, calendar, and contacts in Outlook.\n    humanUrl: https://developer.microsoft.com/en-us/outlook\n    baseUrl: https://graph.microsoft.com/v1.0/me/messages\n    tags:\n      - Calendar\n      - Contacts\n      - Email\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/outlook/rest/\n  - name: SharePoint REST API\n    description: >-\n      Programmatic access to SharePoint sites, lists, and content.\n    humanUrl: https://developer.microsoft.com/en-us/sharepoint\n    baseUrl: https://[tenant].sharepoint.com/_api\n    tags:\n      - Collaboration\n      - Documents\n      - Lists\n      - SharePoint\n      - Sites\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service\n      - type: Samples\n      \
  \  url: https://github.com/SharePoint/sp-dev-samples\n  - name: Power BI REST API\n    description: >-\n      Embed Power BI content and manage Power BI resources.\n    humanUrl: https://powerbi.microsoft.com/en-us/developers/\n    baseUrl: https://api.powerbi.com\n    tags:\n      - Analytics\n      - Dashboards\n      - Datasets\n      - Embedding\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-bi/\n      - type: Playground\n        url: https://playground.powerbi.com/\n  - name: Microsoft To Do API\n    description: >-\n      Manage tasks and to-do lists via Microsoft To Do.\n    humanUrl: https://developer.microsoft.com/en-us/to-do\n    baseUrl: https://graph.microsoft.com/v1.0/me/todo\n    tags:\n      - Lists\n      - Productivity\n      - Tasks\n      - ToDo\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/todo-overview\n  - name: Microsoft\
  \ Planner API\n    description: >-\n      Create and manage plans, tasks, and team collaboration.\n    humanUrl: https://developer.microsoft.com/en-us/planner\n    baseUrl: https://graph.microsoft.com/v1.0/planner\n    tags:\n      - Planning\n      - Projects\n      - Tasks\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/planner-overview\nmaintainers:\n  - name: Microsoft Developer Relations\n    email: developer@microsoft.com\n    url: https://developer.microsoft.com\ntags:\n  - Cloud\n  - Collaboration\n  - Enterprise\n  - Microsoft\n  - Office 365\n  - Productivity\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-applications/refs/heads/main/apis.yml
tags:
- Cloud
- Collaboration
- Enterprise
- Microsoft
- Office 365
- Productivity
url: https://www.microsoft.com/apis
use_cases: []
---
