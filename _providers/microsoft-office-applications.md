---
api_count: 8
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/openapi.yaml
apis:
- description: Unified API endpoint for accessing Microsoft 365 services including Office applications.
  name: Microsoft Graph API
  slug: ''
- description: API for creating, editing, and managing Word documents.
  name: Word API
  slug: ''
- description: API for creating, editing, and managing Excel spreadsheets.
  name: Excel API
  slug: ''
- description: API for creating, editing, and managing PowerPoint presentations.
  name: PowerPoint API
  slug: ''
- description: API for accessing and managing email in Outlook.
  name: Outlook Mail API
  slug: ''
- description: API for creating and managing OneNote notebooks, sections, and pages.
  name: OneNote API
  slug: ''
- description: API for accessing and managing files in OneDrive.
  name: OneDrive API
  slug: ''
- description: API for Microsoft Teams collaboration and communication.
  name: Teams API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: Authentication
  url: https://docs.microsoft.com/en-us/azure/active-directory/develop/
- title: ''
  type: Blog
  url: https://developer.microsoft.com/en-us/microsoft-365/blogs/
- title: ''
  type: Support
  url: https://docs.microsoft.com/en-us/answers/products/m365
- title: ''
  type: Terms of Service
  url: https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
created: '2024'
description: APIs for Microsoft Office suite including Word, Excel, PowerPoint, Outlook, and other Office applications.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Office Applications
skills: []
slug: microsoft-office-applications
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-office-applications\nname: Microsoft Office Applications\ndescription: >-\n  APIs for Microsoft Office suite including Word, Excel, PowerPoint, Outlook, and\n  other Office applications.\nimage: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365-logo.png\ntags:\n  - Documents\n  - Office\n  - Presentations\n  - Productivity\n  - Spreadsheets\ncreated: '2024'\nmodified: '2026-04-28'\nurl: https://www.microsoft.com/en-us/microsoft-365\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365 services including Office applications.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://developer.microsoft.com/en-us/graph\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Graph\n      - Microsoft 365\n      - Office\n    properties:\n      - type: Documentation\n     \
  \   url: https://docs.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n  - name: Word API\n    description: >-\n      API for creating, editing, and managing Word documents.\n    humanURL: https://docs.microsoft.com/en-us/javascript/api/word\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Documents\n      - Word\n      - Word Processing\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/office/dev/add-ins/word/\n      - type: Reference\n        url: https://docs.microsoft.com/en-us/javascript/api/word\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/office/dev/add-ins/quickstarts/word-quickstart\n\
  \  - name: Excel API\n    description: >-\n      API for creating, editing, and managing Excel spreadsheets.\n    humanURL: https://docs.microsoft.com/en-us/javascript/api/excel\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Data Analysis\n      - Excel\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/office/dev/add-ins/excel/\n      - type: Reference\n        url: https://docs.microsoft.com/en-us/javascript/api/excel\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/office/dev/add-ins/quickstarts/excel-quickstart-jquery\n  - name: PowerPoint API\n    description: >-\n      API for creating, editing, and managing PowerPoint presentations.\n    humanURL: https://docs.microsoft.com/en-us/javascript/api/powerpoint\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - PowerPoint\n      - Presentations\n      - Slides\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.microsoft.com/en-us/office/dev/add-ins/powerpoint/\n      - type: Reference\n        url: https://docs.microsoft.com/en-us/javascript/api/powerpoint\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/office/dev/add-ins/quickstarts/powerpoint-quickstart\n  - name: Outlook Mail API\n    description: >-\n      API for accessing and managing email in Outlook.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/mail-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Email\n      - Mail\n      - Outlook\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/mail-api-overview\n      - type: Reference\n        url: https://docs.microsoft.com/en-us/graph/api/resources/message\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/office/dev/add-ins/quickstarts/outlook-quickstart\n  - name: OneNote API\n    description:\
  \ >-\n      API for creating and managing OneNote notebooks, sections, and pages.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/onenote-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Notebooks\n      - Notes\n      - OneNote\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/onenote-api-overview\n      - type: Reference\n        url: https://docs.microsoft.com/en-us/graph/api/resources/onenote\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/graph/onenote-get-started\n  - name: OneDrive API\n    description: >-\n      API for accessing and managing files in OneDrive.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/onedrive\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Files\n      - OneDrive\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/onedrive/developer/\n\
  \      - type: Reference\n        url: https://docs.microsoft.com/en-us/graph/api/resources/onedrive\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/onedrive/developer/rest-api/getting-started/\n  - name: Teams API\n    description: >-\n      API for Microsoft Teams collaboration and communication.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/teams-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Chat\n      - Collaboration\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/teams-api-overview\n      - type: Reference\n        url: https://docs.microsoft.com/en-us/graph/api/resources/team\n      - type: Getting Started\n        url: https://docs.microsoft.com/en-us/microsoftteams/platform/\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: Authentication\n    url: https://docs.microsoft.com/en-us/azure/active-directory/develop/\n\
  \  - type: Blog\n    url: https://developer.microsoft.com/en-us/microsoft-365/blogs/\n  - type: Support\n    url: https://docs.microsoft.com/en-us/answers/products/m365\n  - type: Terms of Service\n    url: https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-applications/refs/heads/main/apis.yml
tags:
- Documents
- Office
- Presentations
- Productivity
- Spreadsheets
url: https://www.microsoft.com/en-us/microsoft-365
use_cases: []
---
