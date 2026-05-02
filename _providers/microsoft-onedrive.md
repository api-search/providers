---
api_count: 2
apis:
- description: 'The Microsoft Graph OneDrive API provides programmatic access to OneDrive personal and OneDrive for Business file storage. Developers can upload, download, search, and share files and folders, manage '
  name: Microsoft Graph OneDrive API
  slug: graph-drive-api
- description: 'The OneDrive File Picker is a JavaScript SDK that provides a pre-built UI component for selecting files from OneDrive within web applications. It handles authentication, file browsing, and selection, '
  name: OneDrive File Picker
  slug: file-picker
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-365/onedrive/online-cloud-storage
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/onedrive/developer/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
created: '2024-01-01'
description: Microsoft OneDrive is a cloud-based file storage and synchronization service. It provides APIs through Microsoft Graph for accessing, managing, and sharing files and folders stored in OneDrive personal and OneDrive for Business.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft OneDrive
skills: []
slug: microsoft-onedrive
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-onedrive\nname: Microsoft OneDrive\ndescription: >-\n  Microsoft OneDrive is a cloud-based file storage and synchronization service.\n  It provides APIs through Microsoft Graph for accessing, managing, and sharing\n  files and folders stored in OneDrive personal and OneDrive for Business.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Storage\n  - File Storage\n  - Files\n  - Microsoft\n  - Microsoft 365\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-onedrive/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-onedrive:graph-drive-api\n    name: Microsoft Graph OneDrive API\n    tags:\n      - Cloud Storage\n      - File Storage\n      - Files\n      - Microsoft Graph\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://graph.microsoft.com/v1.0/\n\
  \    humanURL: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/\n    properties:\n      - url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/graph/api/resources/onedrive\n        type: Reference\n    description: >-\n      The Microsoft Graph OneDrive API provides programmatic access to\n      OneDrive personal and OneDrive for Business file storage. Developers\n      can upload, download, search, and share files and folders, manage\n      permissions, track changes with delta queries, and create sharing\n      links. The API supports large file uploads with resumable sessions\n      and real-time notifications via webhooks.\n  - aid: microsoft-onedrive:file-picker\n    name: OneDrive File Picker\n    tags:\n      - File Picker\n      - Files\n      - UI Component\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/onedrive/developer/controls/file-pickers/\n\
  \    properties:\n      - url: https://learn.microsoft.com/en-us/onedrive/developer/controls/file-pickers/\n        type: Documentation\n    description: >-\n      The OneDrive File Picker is a JavaScript SDK that provides a\n      pre-built UI component for selecting files from OneDrive within\n      web applications. It handles authentication, file browsing, and\n      selection, returning file metadata and download URLs to the\n      calling application without requiring direct API integration.\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Website\n    url: https://www.microsoft.com/en-us/microsoft-365/onedrive/online-cloud-storage\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/onedrive/developer/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n\
  \  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-onedrive/refs/heads/main/apis.yml
tags:
- Cloud Storage
- File Storage
- Files
- Microsoft
- Microsoft 365
url: https://raw.githubusercontent.com/api-evangelist/microsoft-onedrive/refs/heads/main/apis.yml
use_cases: []
---
