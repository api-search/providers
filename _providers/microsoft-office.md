---
api_count: 7
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API
  slug: microsoft-graph-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/openapi.yaml
apis:
- description: Unified API endpoint for accessing Microsoft 365 services including Office applications, OneDrive, Outlook, and more.
  name: Microsoft Graph API
  slug: microsoft-graph-api
- description: API for interacting with Microsoft Word documents, including reading, writing, and formatting content.
  name: Word API
  slug: word-api
- description: API for working with Excel workbooks, worksheets, ranges, charts, and tables.
  name: Excel API
  slug: excel-api
- description: API for creating and manipulating PowerPoint presentations, slides, and content.
  name: PowerPoint API
  slug: powerpoint-api
- description: API for accessing and managing email, calendar, contacts, and tasks in Outlook.
  name: Outlook Mail API
  slug: outlook-mail-api
- description: API for accessing files and folders stored in OneDrive and SharePoint.
  name: OneDrive API
  slug: onedrive-api
- description: API for integrating with Microsoft Teams, including messaging, channels, and collaboration features.
  name: Teams API
  slug: teams-api
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-365
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/office/dev/add-ins/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/
- title: ''
  type: Blog
  url: https://developer.microsoft.com/en-us/microsoft-365/blogs/
- title: ''
  type: Support
  url: https://learn.microsoft.com/en-us/answers/products/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Status
  url: https://status.dev.microsoft.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/OfficeDev
created: '2024-01-01'
description: A collection of APIs for Microsoft Office applications and services, providing programmatic access to Word, Excel, PowerPoint, Outlook, OneDrive, and Teams through Microsoft Graph and Office JavaScript APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Office
skills: []
slug: microsoft-office
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-office\nname: Microsoft Office\ndescription: >-\n  A collection of APIs for Microsoft Office applications and services,\n  providing programmatic access to Word, Excel, PowerPoint, Outlook,\n  OneDrive, and Teams through Microsoft Graph and Office JavaScript APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Collaboration\n  - Documents\n  - Microsoft\n  - Office\n  - Productivity\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-office/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-office:microsoft-graph-api\n    name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365 services including Office applications,\n      OneDrive, Outlook, and more.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.microsoft.com/en-us/graph\n\
  \    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Microsoft Graph\n      - Office 365\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/active-directory/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - aid: microsoft-office:word-api\n    name: Word API\n    description: >-\n      API for interacting with Microsoft Word documents, including reading, writing,\n      and formatting content.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/javascript/api/word\n\
  \    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Documents\n      - Word\n      - Word Processing\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/word-add-ins-reference-overview\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/javascript/api/word\n  - aid: microsoft-office:excel-api\n    name: Excel API\n    description: >-\n      API for working with Excel workbooks, worksheets, ranges, charts, and tables.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/javascript/api/excel\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Data Analysis\n      - Excel\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview\n      - type: Reference\n\
  \        url: https://learn.microsoft.com/en-us/javascript/api/excel\n  - aid: microsoft-office:powerpoint-api\n    name: PowerPoint API\n    description: >-\n      API for creating and manipulating PowerPoint presentations, slides, and content.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/javascript/api/powerpoint\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - PowerPoint\n      - Presentations\n      - Slides\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/powerpoint-add-ins-reference-overview\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/javascript/api/powerpoint\n  - aid: microsoft-office:outlook-mail-api\n    name: Outlook Mail API\n    description: >-\n      API for accessing and managing email, calendar, contacts, and tasks in Outlook.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Calendar\n      - Contacts\n      - Email\n      - Outlook\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/graph/tutorials\n  - aid: microsoft-office:onedrive-api\n    name: OneDrive API\n    description: >-\n      API for accessing files and folders stored in OneDrive and SharePoint.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/onedrive\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud Storage\n      - Files\n      - OneDrive\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/onedrive\n\
  \      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/onedrive/developer/\n  - aid: microsoft-office:teams-api\n    name: Teams API\n    description: >-\n      API for integrating with Microsoft Teams, including messaging, channels, and\n      collaboration features.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Chat\n      - Collaboration\n      - Meetings\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: Website\n    url: https://www.microsoft.com/en-us/microsoft-365\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/office/dev/add-ins/\n  - type: Authentication\n\
  \    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/\n  - type: Blog\n    url: https://developer.microsoft.com/en-us/microsoft-365/blogs/\n  - type: Support\n    url: https://learn.microsoft.com/en-us/answers/products/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Status\n    url: https://status.dev.microsoft.com/\n  - type: GitHub Organization\n    url: https://github.com/OfficeDev\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office/refs/heads/main/apis.yml
tags:
- Collaboration
- Documents
- Microsoft
- Office
- Productivity
url: https://raw.githubusercontent.com/api-evangelist/microsoft-office/refs/heads/main/apis.yml
use_cases: []
---
