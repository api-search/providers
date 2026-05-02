---
api_count: 7
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
apis:
- description: Unified API endpoint for accessing Microsoft 365 services including Office applications.
  name: Microsoft Graph API
  slug: ''
- description: API for creating, reading, and modifying Word documents.
  name: Word API
  slug: ''
- description: API for working with Excel workbooks, worksheets, charts, and tables.
  name: Excel API
  slug: ''
- description: API for creating and modifying PowerPoint presentations.
  name: PowerPoint API
  slug: ''
- description: API for accessing and managing email messages, calendars, and contacts.
  name: Outlook Mail API
  slug: ''
- description: API for accessing files and folders stored in OneDrive.
  name: OneDrive API
  slug: ''
- description: API for accessing SharePoint sites, lists, and content.
  name: SharePoint API
  slug: ''
common:
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/servicesagreement
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/privacystatement
- title: ''
  type: Developer Portal
  url: https://developer.microsoft.com/microsoft-365
- title: ''
  type: Status
  url: https://status.dev.microsoft.com/
- title: ''
  type: Blog
  url: https://developer.microsoft.com/microsoft-365/blogs/
created: '2024'
description: A collection of APIs for Microsoft Office productivity applications including Word, Excel, PowerPoint, Outlook, and OneDrive.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Office Pack
skills: []
slug: microsoft-office-pack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-office-pack\nname: Microsoft Office Pack\ndescription: >-\n  A collection of APIs for Microsoft Office productivity applications including Word,\n  Excel, PowerPoint, Outlook, and OneDrive.\nimage: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365-logo.png\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-office-pack/refs/heads/main/apis.yml\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365 services including Office applications.\n    image: https://learn.microsoft.com/graph/images/microsoft-graph.png\n    humanUrl: https://developer.microsoft.com/graph\n    baseUrl: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud\n      - Microsoft 365\n      - Office\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/graph/api/overview\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/graph/sdks/sdks-overview\n      - type: Pricing\n        url: https://www.microsoft.com/microsoft-365/enterprise/compare-office-365-plans\n    contact:\n      - type: Support\n        url: https://developer.microsoft.com/graph/support\n  - name: Word API\n    description: >-\n      API for creating, reading, and modifying Word documents.\n    humanUrl: https://learn.microsoft.com/graph/api/resources/word\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive/items/{id}/workbook\n    tags:\n      - Documents\n      - Text Processing\n      - Word\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/office/dev/add-ins/word/word-add-ins-programming-overview\n      - type: QuickStart\n\
  \        url: https://learn.microsoft.com/office/dev/add-ins/quickstarts/word-quickstart\n  - name: Excel API\n    description: >-\n      API for working with Excel workbooks, worksheets, charts, and tables.\n    humanUrl: https://learn.microsoft.com/graph/api/resources/excel\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive/items/{id}/workbook\n    tags:\n      - Data Analysis\n      - Excel\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/graph/api/resources/excel\n      - type: QuickStart\n        url: https://learn.microsoft.com/office/dev/add-ins/quickstarts/excel-quickstart-jquery\n      - type: Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n  - name: PowerPoint API\n    description: >-\n      API for creating and modifying PowerPoint presentations.\n    humanUrl: https://learn.microsoft.com/office/dev/add-ins/powerpoint/powerpoint-add-ins\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive/items/{id}\n\
  \    tags:\n      - PowerPoint\n      - Presentations\n      - Slides\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/office/dev/add-ins/powerpoint/powerpoint-add-ins\n      - type: QuickStart\n        url: https://learn.microsoft.com/office/dev/add-ins/quickstarts/powerpoint-quickstart\n  - name: Outlook Mail API\n    description: >-\n      API for accessing and managing email messages, calendars, and contacts.\n    humanUrl: https://learn.microsoft.com/graph/api/resources/mail-api-overview\n    baseUrl: https://graph.microsoft.com/v1.0/me/messages\n    tags:\n      - Calendar\n      - Contacts\n      - Email\n      - Outlook\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/graph/api/resources/mail-api-overview\n      - type: Permissions\n        url: https://learn.microsoft.com/graph/permissions-reference#mail-permissions\n  - name: OneDrive API\n    description: >-\n      API for accessing files and folders\
  \ stored in OneDrive.\n    humanUrl: https://learn.microsoft.com/graph/api/resources/onedrive\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Cloud Storage\n      - Files\n      - OneDrive\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/graph/api/resources/onedrive\n      - type: Upload\n        url: https://learn.microsoft.com/graph/api/driveitem-put-content\n  - name: SharePoint API\n    description: >-\n      API for accessing SharePoint sites, lists, and content.\n    humanUrl: https://learn.microsoft.com/graph/api/resources/sharepoint\n    baseUrl: https://graph.microsoft.com/v1.0/sites\n    tags:\n      - Collaboration\n      - Content Management\n      - SharePoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/graph/api/resources/sharepoint\ncommon:\n  - type: Terms of Service\n    url: https://www.microsoft.com/servicesagreement\n  - type: Privacy Policy\n\
  \    url: https://privacy.microsoft.com/privacystatement\n  - type: Developer Portal\n    url: https://developer.microsoft.com/microsoft-365\n  - type: Status\n    url: https://status.dev.microsoft.com/\n  - type: Blog\n    url: https://developer.microsoft.com/microsoft-365/blogs/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-pack/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-pack/refs/heads/main/apis.yml
use_cases: []
---
