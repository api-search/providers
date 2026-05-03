---
api_count: 5
apis:
- description: Calendar Overlay is Cloudwell's flagship SharePoint app for combining SharePoint lists and libraries, Outlook and Exchange calendars, Planner plans, and iCalendar feeds into a unified calendar surface
  name: Cloudwell Calendar Overlay
  slug: calendar-overlay
- description: Org Chart for SharePoint and Microsoft Teams renders an interactive organization hierarchy from Entra ID/Azure AD reporting structure. Distributed as an SPFx solution; no public REST API.
  name: Cloudwell Org Chart
  slug: org-chart
- description: Staff Directory provides searchable, filterable employee directories across SharePoint and Teams, sourced from Microsoft Graph and Entra ID. Distributed as an SPFx solution; no public REST API.
  name: Cloudwell Staff Directory
  slug: staff-directory
- description: Team Members consolidates Microsoft 365 groups and Teams, SharePoint groups, and Azure AD groups and departments into a single view inside SharePoint. Distributed as an SPFx solution; no public REST A
  name: Cloudwell Team Members
  slug: team-members
- description: Viva Announcements lets users view Viva Connections announcements anywhere in SharePoint via an SPFx web part. No public REST API.
  name: Cloudwell Viva Announcements
  slug: viva-announcements
common:
- title: ''
  type: Website
  url: https://cloudwell.io/
- title: ''
  type: AppSource
  url: https://appsource.microsoft.com/en-us/marketplace/apps?search=cloudwell
- title: ''
  type: Support
  url: https://cloudwell.io/support/
- title: ''
  type: Privacy Policy
  url: https://cloudwell.io/privacy-policy/
created: '2024-01-01'
description: 'Cloudwell (cloudwell.io) is a Microsoft 365 and Azure-focused software partner founded in 2012, offering a suite of SharePoint and Teams apps: Calendar Overlay, Org Chart, Staff Directory, Team Members, and Viva Announcements - all distributed via Microsoft AppSource. Cloudwell does not publish a public REST API; their products are consumed inside SharePoint Online, Microsoft Teams, and Viva Connections via SharePoint Framework (SPFx) web parts and the Microsoft Graph API. The "opal" suffix in this repository name is preserved for index continuity but Cloudwell does not currently ship a product named Opal.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-25'
name: Cloudwell
skills: []
slug: cloudwell-opal
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudwell-opal\nname: Cloudwell\ndescription: >-\n  Cloudwell (cloudwell.io) is a Microsoft 365 and Azure-focused software\n  partner founded in 2012, offering a suite of SharePoint and Teams apps:\n  Calendar Overlay, Org Chart, Staff Directory, Team Members, and Viva\n  Announcements - all distributed via Microsoft AppSource. Cloudwell does\n  not publish a public REST API; their products are consumed inside\n  SharePoint Online, Microsoft Teams, and Viva Connections via SharePoint\n  Framework (SPFx) web parts and the Microsoft Graph API. The \"opal\"\n  suffix in this repository name is preserved for index continuity but\n  Cloudwell does not currently ship a product named Opal.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloudwell-opal/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-25'\nspecificationVersion: '0.19'\nx-type: company\ntags:\n\
  \  - AppSource\n  - Calendar Overlay\n  - Microsoft 365\n  - Microsoft Partner\n  - Org Chart\n  - SharePoint\n  - SPFx\n  - Staff Directory\n  - Teams\n  - Viva Connections\napis:\n  - aid: cloudwell-opal:calendar-overlay\n    name: Cloudwell Calendar Overlay\n    tags:\n      - Calendar\n      - SharePoint\n      - SPFx\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://appsource.microsoft.com/en-us/product/web-apps/cloudwell.cloudwell_calendar_overlay\n    properties:\n      - url: https://appsource.microsoft.com/en-us/product/web-apps/cloudwell.cloudwell_calendar_overlay\n        type: AppSource Listing\n      - url: https://learn.microsoft.com/en-us/microsoft-365-app-certification/sharepoint/cloudwell-calendar-overlay\n        type: Microsoft 365 App Certification\n    description: >-\n      Calendar Overlay is Cloudwell's flagship SharePoint app for combining\n      SharePoint lists and libraries, Outlook and Exchange calendars,\n\
  \      Planner plans, and iCalendar feeds into a unified calendar surface.\n      Configured inside SharePoint Online; no public REST API.\n  - aid: cloudwell-opal:org-chart\n    name: Cloudwell Org Chart\n    tags:\n      - Directory\n      - Org Chart\n      - SharePoint\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloudwell.io/products/org-chart/\n    properties:\n      - url: https://cloudwell.io/products/org-chart/\n        type: Product Page\n    description: >-\n      Org Chart for SharePoint and Microsoft Teams renders an interactive\n      organization hierarchy from Entra ID/Azure AD reporting structure.\n      Distributed as an SPFx solution; no public REST API.\n  - aid: cloudwell-opal:staff-directory\n    name: Cloudwell Staff Directory\n    tags:\n      - Directory\n      - SharePoint\n      - Teams\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloudwell.io/products/staff-directory/\n\
  \    properties:\n      - url: https://cloudwell.io/products/staff-directory/\n        type: Product Page\n    description: >-\n      Staff Directory provides searchable, filterable employee directories\n      across SharePoint and Teams, sourced from Microsoft Graph and Entra\n      ID. Distributed as an SPFx solution; no public REST API.\n  - aid: cloudwell-opal:team-members\n    name: Cloudwell Team Members\n    tags:\n      - Groups\n      - SharePoint\n      - Teams\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/microsoft-365-app-certification/sharepoint/cloudwell-team-members\n    properties:\n      - url: https://learn.microsoft.com/en-us/microsoft-365-app-certification/sharepoint/cloudwell-team-members\n        type: Microsoft 365 App Certification\n    description: >-\n      Team Members consolidates Microsoft 365 groups and Teams, SharePoint\n      groups, and Azure AD groups and departments\
  \ into a single view inside\n      SharePoint. Distributed as an SPFx solution; no public REST API.\n  - aid: cloudwell-opal:viva-announcements\n    name: Cloudwell Viva Announcements\n    tags:\n      - SharePoint\n      - Viva Connections\n      - Announcements\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloudwell.io/products/viva-announcements/\n    properties:\n      - url: https://cloudwell.io/products/viva-announcements/\n        type: Product Page\n    description: >-\n      Viva Announcements lets users view Viva Connections announcements\n      anywhere in SharePoint via an SPFx web part. No public REST API.\ncommon:\n  - type: Website\n    url: https://cloudwell.io/\n  - type: AppSource\n    url: https://appsource.microsoft.com/en-us/marketplace/apps?search=cloudwell\n  - type: Support\n    url: https://cloudwell.io/support/\n  - type: Privacy Policy\n    url: https://cloudwell.io/privacy-policy/\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudwell-opal/refs/heads/main/apis.yml
tags:
- AppSource
- Calendar Overlay
- Microsoft 365
- Microsoft Partner
- Org Chart
- SharePoint
- SPFx
- Staff Directory
- Teams
- Viva Connections
url: https://raw.githubusercontent.com/api-evangelist/cloudwell-opal/refs/heads/main/apis.yml
use_cases: []
---
