---
api_count: 10
apis:
- description: The Gmail API lets you view and manage Gmail mailbox data like threads, messages, and labels.
  name: Gmail API
  slug: ''
- description: The Google Calendar API lets you integrate your app with Google Calendar, creating new ways for users to engage with their calendars.
  name: Google Calendar API
  slug: ''
- description: The Google Drive API allows you to create apps that leverage Google Drive cloud storage.
  name: Google Drive API
  slug: ''
- description: The Google Docs API lets you create and modify documents programmatically.
  name: Google Docs API
  slug: ''
- description: The Google Sheets API lets you read, write, and format Google Sheets data with your preferred programming language.
  name: Google Sheets API
  slug: ''
- description: The Google Slides API lets you create and modify Google Slides presentations programmatically.
  name: Google Slides API
  slug: ''
- description: The Google Meet API allows developers to build applications that integrate with Google Meet.
  name: Google Meet API
  slug: ''
- description: The Google Chat API allows you to build Chat apps that bring your services into Google Chat.
  name: Google Chat API
  slug: ''
- description: The Admin SDK lets administrators of Google Workspace domains programmatically manage users, groups, and resources.
  name: Google Admin SDK
  slug: ''
- description: The Google Forms API provides programmatic access to create, modify, and retrieve form content and responses.
  name: Google Forms API
  slug: ''
common:
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: Console
  url: https://console.cloud.google.com/
- title: ''
  type: Terms of Service
  url: https://developers.google.com/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Status
  url: https://www.google.com/appsstatus/dashboard/
created: '2024-01-15'
description: Google Workspace (formerly G Suite) is a collection of cloud computing, productivity and collaboration tools, software and products developed and marketed by Google.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Workspace (G Suite)
skills: []
slug: google-suite
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-suite\nname: Google Workspace (G Suite)\ndescription: Google Workspace (formerly G Suite) is a collection of cloud computing, productivity and collaboration tools, software and products developed and marketed by Google.\nurl: https://workspace.google.com/\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - name: Gmail API\n    description: The Gmail API lets you view and manage Gmail mailbox data like threads, messages, and labels.\n    image: https://www.gstatic.com/images/branding/product/2x/gmail_64dp.png\n    humanURL: https://developers.google.com/gmail/api\n    baseURL: https://gmail.googleapis.com\n    tags:\n      - Email\n      - Messaging\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/gmail/api/guides\n      - type: OpenAPI\n        url: https://gmail.googleapis.com/$discovery/rest?version=v1\n      - type: Authentication\n        url: https://developers.google.com/gmail/api/auth/about-auth\n\
  \      - type: Pricing\n        url: https://developers.google.com/gmail/api/reference/quota\n    contact:\n      - type: Support\n        url: https://developers.google.com/gmail/api/support\n  - name: Google Calendar API\n    description: The Google Calendar API lets you integrate your app with Google Calendar, creating new ways for users to engage with their calendars.\n    image: https://www.gstatic.com/images/branding/product/2x/calendar_64dp.png\n    humanURL: https://developers.google.com/calendar\n    baseURL: https://www.googleapis.com/calendar/v3\n    tags:\n      - Calendar\n      - Events\n      - Productivity\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/calendar/api/guides/overview\n      - type: OpenAPI\n        url: https://www.googleapis.com/discovery/v1/apis/calendar/v3/rest\n      - type: Authentication\n        url: https://developers.google.com/calendar/api/guides/auth\n      - type: Quickstart\n     \
  \   url: https://developers.google.com/calendar/api/quickstart/python\n  - name: Google Drive API\n    description: The Google Drive API allows you to create apps that leverage Google Drive cloud storage.\n    image: https://www.gstatic.com/images/branding/product/2x/drive_64dp.png\n    humanURL: https://developers.google.com/drive\n    baseURL: https://www.googleapis.com/drive/v3\n    tags:\n      - Cloud\n      - Collaboration\n      - Files\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/drive/api/guides/about-sdk\n      - type: OpenAPI\n        url: https://www.googleapis.com/discovery/v1/apis/drive/v3/rest\n      - type: Authentication\n        url: https://developers.google.com/drive/api/guides/about-auth\n      - type: Pricing\n        url: https://developers.google.com/drive/api/guides/limits\n  - name: Google Docs API\n    description: The Google Docs API lets you create and modify documents programmatically.\n    image:\
  \ https://www.gstatic.com/images/branding/product/2x/docs_64dp.png\n    humanURL: https://developers.google.com/docs/api\n    baseURL: https://docs.googleapis.com/v1\n    tags:\n      - Collaboration\n      - Documents\n      - Productivity\n      - Word-Processing\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/docs/api/how-tos/overview\n      - type: OpenAPI\n        url: https://docs.googleapis.com/$discovery/rest?version=v1\n      - type: Quickstart\n        url: https://developers.google.com/docs/api/quickstart/python\n  - name: Google Sheets API\n    description: The Google Sheets API lets you read, write, and format Google Sheets data with your preferred programming language.\n    image: https://www.gstatic.com/images/branding/product/2x/sheets_64dp.png\n    humanURL: https://developers.google.com/sheets/api\n    baseURL: https://sheets.googleapis.com/v4\n    tags:\n      - Collaboration\n      - Data\n      - Productivity\n      - Spreadsheets\n\
  \    properties:\n      - type: Documentation\n        url: https://developers.google.com/sheets/api/guides/concepts\n      - type: OpenAPI\n        url: https://sheets.googleapis.com/$discovery/rest?version=v4\n      - type: Authentication\n        url: https://developers.google.com/sheets/api/guides/authorizing\n      - type: Samples\n        url: https://developers.google.com/sheets/api/samples\n  - name: Google Slides API\n    description: The Google Slides API lets you create and modify Google Slides presentations programmatically.\n    image: https://www.gstatic.com/images/branding/product/2x/slides_64dp.png\n    humanURL: https://developers.google.com/slides\n    baseURL: https://slides.googleapis.com/v1\n    tags:\n      - Collaboration\n      - Presentations\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/slides/how-tos/overview\n      - type: OpenAPI\n        url: https://slides.googleapis.com/$discovery/rest?version=v1\n\
  \      - type: Samples\n        url: https://developers.google.com/slides/samples\n  - name: Google Meet API\n    description: The Google Meet API allows developers to build applications that integrate with Google Meet.\n    image: https://www.gstatic.com/images/branding/product/2x/meet_64dp.png\n    humanURL: https://developers.google.com/meet\n    baseURL: https://meet.googleapis.com/v2\n    tags:\n      - Collaboration\n      - Communication\n      - Meetings\n      - Video-Conferencing\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/meet/api/guides/overview\n      - type: Reference\n        url: https://developers.google.com/meet/api/reference/rest\n  - name: Google Chat API\n    description: The Google Chat API allows you to build Chat apps that bring your services into Google Chat.\n    image: https://www.gstatic.com/images/branding/product/2x/chat_64dp.png\n    humanURL: https://developers.google.com/chat\n    baseURL: https://chat.googleapis.com/v1\n\
  \    tags:\n      - Bots\n      - Collaboration\n      - Communication\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/chat/api/guides/overview\n      - type: OpenAPI\n        url: https://chat.googleapis.com/$discovery/rest?version=v1\n      - type: Concepts\n        url: https://developers.google.com/chat/api/guides/concepts\n  - name: Google Admin SDK\n    description: The Admin SDK lets administrators of Google Workspace domains programmatically manage users, groups, and resources.\n    image: https://www.gstatic.com/images/branding/product/2x/admin_64dp.png\n    humanURL: https://developers.google.com/admin-sdk\n    baseURL: https://admin.googleapis.com\n    tags:\n      - Administration\n      - Groups\n      - Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/admin-sdk/directory/v1/guides\n      - type: Directory API\n        url: https://developers.google.com/admin-sdk/directory\n\
  \      - type: Reports API\n        url: https://developers.google.com/admin-sdk/reports\n      - type: OpenAPI\n        url: https://admin.googleapis.com/$discovery/rest?version=directory_v1\n  - name: Google Forms API\n    description: The Google Forms API provides programmatic access to create, modify, and retrieve form content and responses.\n    image: https://www.gstatic.com/images/branding/product/2x/forms_64dp.png\n    humanURL: https://developers.google.com/forms/api\n    baseURL: https://forms.googleapis.com/v1\n    tags:\n      - Data-Collection\n      - Forms\n      - Productivity\n      - Surveys\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/forms/api/guides\n      - type: Reference\n        url: https://developers.google.com/forms/api/reference/rest\ncommon:\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n  - type: Console\n    url: https://console.cloud.google.com/\n  - type: Terms of\
  \ Service\n    url: https://developers.google.com/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Status\n    url: https://www.google.com/appsstatus/dashboard/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Collaboration\n  - Enterprise\n  - Google\n  - Productivity\n  - Workspace\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-suite/refs/heads/main/apis.yml
tags:
- Cloud
- Collaboration
- Enterprise
- Google
- Productivity
- Workspace
url: https://workspace.google.com/
use_cases: []
---
