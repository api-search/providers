---
api_count: 2
apis:
- description: Microsoft Graph exposes PowerPoint presentation files (.pptx) stored in OneDrive and SharePoint as drive items, enabling upload, download, sharing, and metadata operations against presentations progra
  name: PowerPoint via Microsoft Graph
  slug: powerpoint-graph-api
- description: Office JavaScript API namespace for building PowerPoint Add-ins that read, write, and manipulate slides, shapes, text, and tables inside the running PowerPoint application.
  name: Office JavaScript API for PowerPoint
  slug: powerpoint-javascript-api
common:
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-365/powerpoint
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/graph/overview
- title: ''
  type: Developer
  url: https://learn.microsoft.com/en-us/office/dev/add-ins/
created: '2026-03-16'
description: Microsoft PowerPoint provides programmatic access through the Microsoft Graph API and the Office JavaScript API for creating, reading, and manipulating PowerPoint presentations. PowerPoint files stored in OneDrive and SharePoint are accessible as drive items via Microsoft Graph, while the Office JavaScript API enables in-document automation for Office Add-ins.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: PowerPoint
skills: []
slug: powerpoint
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: powerpoint\nname: PowerPoint\ndescription: >-\n  Microsoft PowerPoint provides programmatic access through the Microsoft\n  Graph API and the Office JavaScript API for creating, reading, and\n  manipulating PowerPoint presentations. PowerPoint files stored in\n  OneDrive and SharePoint are accessible as drive items via Microsoft\n  Graph, while the Office JavaScript API enables in-document automation\n  for Office Add-ins.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Microsoft Office\n  - Microsoft 365\n  - Presentations\n  - Productivity\n  - Documents\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/powerpoint/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: powerpoint:powerpoint-graph-api\n    name: PowerPoint via Microsoft Graph\n    description: >-\n      Microsoft Graph exposes PowerPoint presentation files (.pptx)\n    \
  \  stored in OneDrive and SharePoint as drive items, enabling upload,\n      download, sharing, and metadata operations against presentations\n      programmatically.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/driveitem\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Microsoft Graph\n      - Files\n      - Presentations\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/driveitem\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n  - aid: powerpoint:powerpoint-javascript-api\n    name: Office JavaScript API for PowerPoint\n    description: >-\n      Office JavaScript API namespace for building PowerPoint Add-ins\n      that read, write, and manipulate slides, shapes, text, and tables\n      inside the running PowerPoint application.\n    humanURL: https://learn.microsoft.com/en-us/javascript/api/powerpoint\n    tags:\n      - Office Add-ins\n\
  \      - JavaScript\n      - Presentations\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/powerpoint\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/powerpoint-quickstart\ncommon:\n  - type: Website\n    url: https://www.microsoft.com/en-us/microsoft-365/powerpoint\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/graph/overview\n  - type: Developer\n    url: https://learn.microsoft.com/en-us/office/dev/add-ins/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/powerpoint/refs/heads/main/apis.yml
tags:
- Microsoft Office
- Microsoft 365
- Presentations
- Productivity
- Documents
url: https://raw.githubusercontent.com/api-evangelist/powerpoint/refs/heads/main/apis.yml
use_cases: []
---
