---
api_count: 8
api_specs:
- filename: overview
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://learn.microsoft.com/en-us/graph/api/overview
apis:
- description: Unified API endpoint for accessing Microsoft 365 services including Office applications, users, and data.
  name: Microsoft Graph API
  slug: ''
- description: JavaScript API for building add-ins and automating Microsoft Word.
  name: Word API (Office.js)
  slug: ''
- description: JavaScript API for building add-ins and automating Microsoft Excel.
  name: Excel API (Office.js)
  slug: ''
- description: JavaScript API for building add-ins and automating Microsoft PowerPoint.
  name: PowerPoint API (Office.js)
  slug: ''
- description: JavaScript API for building add-ins and automating Microsoft Outlook.
  name: Outlook API (Office.js)
  slug: ''
- description: API for accessing and managing files stored in OneDrive.
  name: OneDrive API
  slug: ''
- description: API for accessing and managing SharePoint sites, lists, and documents.
  name: SharePoint REST API
  slug: ''
- description: API for building apps and bots integrated with Microsoft Teams.
  name: Microsoft Teams API
  slug: ''
common:
- title: ''
  type: Developer Portal
  url: https://developer.microsoft.com/
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: Status
  url: https://status.office.com/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/servicesagreement
created: '2024-01-15'
description: Collection of APIs for Microsoft Office Suite applications and services.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft365.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Office Suite
skills: []
slug: microsoft-office-suite
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-office-suite\nname: Microsoft Office Suite\ndescription: >-\n  Collection of APIs for Microsoft Office Suite applications and services.\nimage: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft365.png\nurl: https://www.microsoft.com/en-us/microsoft-365\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365 services including Office applications,\n      users, and data.\n    image: https://learn.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://developer.microsoft.com/en-us/graph\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Graph\n      - Microsoft 365\n      - Office\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url:\
  \ https://learn.microsoft.com/en-us/graph/api/overview\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Sandbox\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n  - name: Word API (Office.js)\n    description: >-\n      JavaScript API for building add-ins and automating Microsoft Word.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/word-add-ins-reference-overview\n    baseURL: https://officejs.org\n    tags:\n      - Documents\n      - Office Add-Ins\n      - Word\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/word\n      - type: Quick Start\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/word-quickstart\n      - type: Code Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n\
  \  - name: Excel API (Office.js)\n    description: >-\n      JavaScript API for building add-ins and automating Microsoft Excel.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview\n    baseURL: https://officejs.org\n    tags:\n      - Excel\n      - Office Add-Ins\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/excel\n      - type: Quick Start\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/excel-quickstart-jquery\n      - type: Code Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n  - name: PowerPoint API (Office.js)\n    description: >-\n      JavaScript API for building add-ins and automating Microsoft PowerPoint.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/powerpoint-add-ins-reference-overview\n    baseURL: https://officejs.org\n    tags:\n\
  \      - Office Add-Ins\n      - PowerPoint\n      - Presentations\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/powerpoint\n      - type: Quick Start\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/powerpoint-quickstart\n      - type: Code Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n  - name: Outlook API (Office.js)\n    description: >-\n      JavaScript API for building add-ins and automating Microsoft Outlook.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/outlook-add-ins-reference-overview\n    baseURL: https://officejs.org\n    tags:\n      - Calendar\n      - Email\n      - Office Add-Ins\n      - Outlook\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/outlook\n      - type: Quick Start\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/outlook-quickstart\n\
  \      - type: Code Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n  - name: OneDrive API\n    description: >-\n      API for accessing and managing files stored in OneDrive.\n    humanURL: https://learn.microsoft.com/en-us/onedrive/developer/\n    baseURL: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Cloud\n      - Files\n      - OneDrive\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/getting-started/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/getting-started/sdk\n  - name: SharePoint REST API\n    description: >-\n      API for accessing and managing SharePoint sites, lists, and documents.\n    humanURL: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service\n\
  \    baseURL: https://{site-url}/_api/\n    tags:\n      - Collaboration\n      - Documents\n      - Lists\n      - SharePoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-rest-endpoints\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/sharepoint-net-server-csom-jsom-and-rest-api-index\n      - type: Code Samples\n        url: https://github.com/SharePoint/sp-dev-samples\n  - name: Microsoft Teams API\n    description: >-\n      API for building apps and bots integrated with Microsoft Teams.\n    humanURL: https://learn.microsoft.com/en-us/microsoftteams/platform/\n    baseURL: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Chat\n      - Collaboration\n      - Meetings\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview\n\
  \      - type: Bot Framework\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots\n      - type: App Manifest\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/resources/schema/manifest-schema\n      - type: Developer Portal\n        url: https://dev.teams.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Collaboration\n  - Documents\n  - Microsoft 365\n  - Office\n  - Productivity\ncommon:\n  - type: Developer Portal\n    url: https://developer.microsoft.com/\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: Status\n    url: https://status.office.com/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/servicesagreement\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-suite/refs/heads/main/apis.yml
tags:
- Cloud
- Collaboration
- Documents
- Microsoft 365
- Office
- Productivity
url: https://www.microsoft.com/en-us/microsoft-365
use_cases: []
---
