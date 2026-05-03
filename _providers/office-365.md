---
api_count: 5
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API
  slug: microsoft-graph-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
apis:
- description: The primary API for Office 365, providing access to data and intelligence in Microsoft 365, Windows 10, and Enterprise Mobility + Security.
  name: Microsoft Graph API
  slug: microsoft-graph-api
- description: Access email, manage folders, send mail, and manage mail settings via Microsoft Graph.
  name: Outlook Mail API
  slug: outlook-mail-api
- description: Access and manage calendar events, meeting requests, and calendar groups.
  name: Outlook Calendar API
  slug: outlook-calendar-api
- description: Access and manage files stored in OneDrive and SharePoint.
  name: OneDrive API
  slug: onedrive-api
- description: Integrate with Microsoft Teams for chat, channels, meetings, and collaboration.
  name: Microsoft Teams API
  slug: microsoft-teams-api
common:
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-365
- title: ''
  type: Documentation
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/
- title: ''
  type: Status
  url: https://status.office365.com/
- title: ''
  type: Support
  url: https://learn.microsoft.com/en-us/answers/products/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/microsoft365dev/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/servicesagreement
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
created: '2024-01-15'
description: Microsoft Office 365 is a cloud-based suite of productivity and collaboration applications that integrates all Microsoft's existing online applications into a single platform including email, calendar, files, Teams, and SharePoint.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Office 365
skills: []
slug: office-365
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: office-365\nname: Office 365\ndescription: >-\n  Microsoft Office 365 is a cloud-based suite of productivity and collaboration\n  applications that integrates all Microsoft's existing online applications into\n  a single platform including email, calendar, files, Teams, and SharePoint.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud\n  - Collaboration\n  - Documents\n  - Email\n  - Enterprise\n  - Productivity\nurl: https://raw.githubusercontent.com/api-evangelist/office-365/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: office-365:microsoft-graph-api\n    name: Microsoft Graph API\n    description: >-\n      The primary API for Office 365, providing access to data and intelligence\n      in Microsoft 365, Windows 10, and Enterprise Mobility + Security.\n    humanURL: https://developer.microsoft.com/en-us/graph\n    baseURL: https://graph.microsoft.com/v1.0\n\
  \    tags:\n      - Calendar\n      - Graph\n      - Mail\n      - SharePoint\n      - Teams\n      - Users\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Change Log\n        url: https://developer.microsoft.com/en-us/graph/changelog\n  - aid: office-365:outlook-mail-api\n    name: Outlook Mail API\n    description: >-\n      Access email, manage folders, send mail, and manage mail settings via\n      Microsoft Graph.\n    humanURL: https://learn.microsoft.com/en-us/graph/outlook-mail-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/me/messages\n    tags:\n      - Email\n      - Mail\n\
  \      - Outlook\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview\n  - aid: office-365:outlook-calendar-api\n    name: Outlook Calendar API\n    description: Access and manage calendar events, meeting requests, and calendar groups.\n    humanURL: https://learn.microsoft.com/en-us/graph/outlook-calendar-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/me/calendar\n    tags:\n      - Calendar\n      - Events\n      - Meetings\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/calendar\n  - aid: office-365:onedrive-api\n    name: OneDrive API\n    description: Access and manage files stored in OneDrive and SharePoint.\n    humanURL: https://learn.microsoft.com/en-us/onedrive/developer/\n    baseURL: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Files\n      - OneDrive\n      - Storage\n    properties:\n      - type:\
  \ Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/onedrive\n  - aid: office-365:microsoft-teams-api\n    name: Microsoft Teams API\n    description: >-\n      Integrate with Microsoft Teams for chat, channels, meetings, and collaboration.\n    humanURL: https://learn.microsoft.com/en-us/graph/teams-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Chat\n      - Collaboration\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview\ncommon:\n  - type: Website\n    url: https://www.microsoft.com/en-us/microsoft-365\n  - type: Documentation\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/\n  - type: Status\n    url: https://status.office365.com/\n  - type: Support\n    url: https://learn.microsoft.com/en-us/answers/products/\n\
  \  - type: Blog\n    url: https://devblogs.microsoft.com/microsoft365dev/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/servicesagreement\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/office-365/refs/heads/main/apis.yml
tags:
- Cloud
- Collaboration
- Documents
- Email
- Enterprise
- Productivity
url: https://raw.githubusercontent.com/api-evangelist/office-365/refs/heads/main/apis.yml
use_cases: []
---
