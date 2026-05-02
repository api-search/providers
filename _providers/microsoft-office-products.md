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
- description: API for building add-ins and automating Microsoft Word.
  name: Word JavaScript API
  slug: ''
- description: API for creating Excel add-ins and automating spreadsheet operations.
  name: Excel JavaScript API
  slug: ''
- description: API for developing PowerPoint add-ins and presentation automation.
  name: PowerPoint JavaScript API
  slug: ''
- description: API for building Outlook add-ins for email, calendar, and contacts.
  name: Outlook JavaScript API
  slug: ''
- description: API for building apps, bots, and integrations for Microsoft Teams.
  name: Microsoft Teams API
  slug: ''
- description: API for accessing and managing files in OneDrive and SharePoint.
  name: OneDrive API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/
- title: ''
  type: Terms of Service
  url: https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/microsoft365dev/
- title: ''
  type: Status
  url: https://status.dev.microsoft.com/
created: '2024-01-15'
description: API catalog for Microsoft Office product suite including Word, Excel, PowerPoint, Outlook, and Teams.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Office Products
skills: []
slug: microsoft-office-products
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-office-products\nname: Microsoft Office Products\ndescription: >-\n  API catalog for Microsoft Office product suite including Word, Excel, PowerPoint,\n  Outlook, and Teams.\nimage: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365.png\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-office-products/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365 services including Office applications.\n    image: https://learn.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanUrl: https://learn.microsoft.com/en-us/graph/overview\n    baseUrl: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud\n      - Microsoft 365\n      - Office\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/overview\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Changelog\n        url: https://learn.microsoft.com/en-us/graph/changelog\n    contact:\n      - type: Support\n        url: https://developer.microsoft.com/en-us/graph/support\n  - name: Word JavaScript API\n    description: >-\n      API for building add-ins and automating Microsoft Word.\n    humanUrl: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/word-add-ins-reference-overview\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive/items/{id}/workbook\n    tags:\n      - Documents\n      - Office Add-Ins\n      - Word\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/word\n\
  \      - type: Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n      - type: Quick Start\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/word-quickstart\n  - name: Excel JavaScript API\n    description: >-\n      API for creating Excel add-ins and automating spreadsheet operations.\n    humanUrl: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive/items/{id}/workbook\n    tags:\n      - Data Analysis\n      - Excel\n      - Office Add-Ins\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/excel\n      - type: REST API\n        url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n      - type: Samples\n        url: https://github.com/OfficeDev/Excel-Add-in-samples\n      - type: Tutorial\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/tutorials/excel-tutorial\n\
  \  - name: PowerPoint JavaScript API\n    description: >-\n      API for developing PowerPoint add-ins and presentation automation.\n    humanUrl: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/powerpoint-add-ins-reference-overview\n    tags:\n      - Office Add-Ins\n      - PowerPoint\n      - Presentations\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/powerpoint\n      - type: Samples\n        url: https://github.com/OfficeDev/PowerPoint-Add-in-samples\n      - type: Quick Start\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/powerpoint-quickstart\n  - name: Outlook JavaScript API\n    description: >-\n      API for building Outlook add-ins for email, calendar, and contacts.\n    humanUrl: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/outlook-add-ins-reference-overview\n    tags:\n      - Calendar\n      - Email\n      - Office Add-Ins\n   \
  \   - Outlook\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/outlook\n      - type: REST API\n        url: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview\n      - type: Samples\n        url: https://github.com/OfficeDev/Outlook-Add-in-samples\n      - type: Patterns\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/outlook-addin-design\n  - name: Microsoft Teams API\n    description: >-\n      API for building apps, bots, and integrations for Microsoft Teams.\n    humanUrl: https://learn.microsoft.com/en-us/microsoftteams/platform/\n    baseUrl: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Chat\n      - Collaboration\n      - Meetings\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview\n      - type: Bot Framework\n        url: https://dev.botframework.com/\n      - type:\
  \ App Samples\n        url: https://github.com/OfficeDev/Microsoft-Teams-Samples\n      - type: Toolkit\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/toolkit/teams-toolkit-fundamentals\n  - name: OneDrive API\n    description: >-\n      API for accessing and managing files in OneDrive and SharePoint.\n    humanUrl: https://learn.microsoft.com/en-us/onedrive/developer/\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Files\n      - OneDrive\n      - SharePoint\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/onedrive\n      - type: File Picker\n        url: https://learn.microsoft.com/en-us/onedrive/developer/controls/file-pickers/\n      - type: Webhooks\n        url: https://learn.microsoft.com/en-us/graph/api/resources/webhooks\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: Authentication\n    url:\
  \ https://learn.microsoft.com/en-us/azure/active-directory/develop/\n  - type: Terms of Service\n    url: https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\n  - type: Blog\n    url: https://devblogs.microsoft.com/microsoft365dev/\n  - type: Status\n    url: https://status.dev.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Enterprise\n  - Microsoft\n  - Office\n  - Productivity\n  - SaaS\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-products/refs/heads/main/apis.yml
tags:
- Cloud
- Enterprise
- Microsoft
- Office
- Productivity
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-products/refs/heads/main/apis.yml
use_cases: []
---
