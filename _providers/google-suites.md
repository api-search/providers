---
api_count: 8
apis:
- description: Access Gmail mailboxes and send mail.
  name: Gmail API
  slug: ''
- description: Manage calendars and events.
  name: Google Calendar API
  slug: ''
- description: Store and share files in the cloud.
  name: Google Drive API
  slug: ''
- description: Create and edit documents programmatically.
  name: Google Docs API
  slug: ''
- description: Read and write spreadsheet data.
  name: Google Sheets API
  slug: ''
- description: Create and edit presentations.
  name: Google Slides API
  slug: ''
- description: Manage video conferencing.
  name: Google Meet API
  slug: ''
- description: Manage users, groups, and organizational units.
  name: Admin SDK Directory API
  slug: ''
common:
- title: ''
  type: Authentication
  url: https://developers.google.com/workspace/guides/auth-overview
- title: ''
  type: Console
  url: https://console.cloud.google.com
- title: ''
  type: Pricing
  url: https://workspace.google.com/pricing
- title: ''
  type: Support
  url: https://workspace.google.com/support
- title: ''
  type: Terms of Service
  url: https://workspace.google.com/terms
- title: ''
  type: SDKs
  url: https://developers.google.com/workspace/guides/client-libraries
created: '2024-01-01'
description: Collection of APIs for Google Workspace (formerly G Suite) services including Gmail, Calendar, Drive, Docs, Sheets, and more.
features: []
image: https://workspace.google.com/static/img/logo-workspace.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Workspace APIs
skills: []
slug: google-suites
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-suites\nname: Google Workspace APIs\ndescription: >-\n  Collection of APIs for Google Workspace (formerly G Suite) services including Gmail,\n  Calendar, Drive, Docs, Sheets, and more.\nimage: https://workspace.google.com/static/img/logo-workspace.svg\nurl: https://workspace.google.com/\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Cloud Storage\n  - Collaboration\n  - Email\n  - Office Suite\n  - Productivity\napis:\n  - name: Gmail API\n    description: >-\n      Access Gmail mailboxes and send mail.\n    image: https://www.gstatic.com/images/branding/product/1x/gmail_48dp.png\n    humanURL: https://developers.google.com/gmail/api\n    baseURL: https://gmail.googleapis.com\n    tags:\n      - Email\n      - Messaging\n    properties:\n      - type: OpenAPI\n        url: https://gmail.googleapis.com/$discovery/rest?version=v1\n      - type: Documentation\n        url: https://developers.google.com/gmail/api/guides\n\
  \      - type: Authentication\n        url: https://developers.google.com/gmail/api/auth/about-auth\n  - name: Google Calendar API\n    description: >-\n      Manage calendars and events.\n    image: https://www.gstatic.com/images/branding/product/1x/calendar_48dp.png\n    humanURL: https://developers.google.com/calendar\n    baseURL: https://www.googleapis.com/calendar/v3\n    tags:\n      - Calendar\n      - Events\n      - Scheduling\n    properties:\n      - type: OpenAPI\n        url: https://www.googleapis.com/discovery/v1/apis/calendar/v3/rest\n      - type: Documentation\n        url: https://developers.google.com/calendar/api/guides/overview\n      - type: Quickstart\n        url: https://developers.google.com/calendar/api/quickstart\n  - name: Google Drive API\n    description: >-\n      Store and share files in the cloud.\n    image: https://www.gstatic.com/images/branding/product/1x/drive_48dp.png\n    humanURL: https://developers.google.com/drive\n    baseURL: https://www.googleapis.com/drive/v3\n\
  \    tags:\n      - Cloud\n      - Files\n      - Storage\n    properties:\n      - type: OpenAPI\n        url: https://www.googleapis.com/discovery/v1/apis/drive/v3/rest\n      - type: Documentation\n        url: https://developers.google.com/drive/api/guides/about-sdk\n      - type: Pricing\n        url: https://workspace.google.com/pricing\n  - name: Google Docs API\n    description: >-\n      Create and edit documents programmatically.\n    image: https://www.gstatic.com/images/branding/product/1x/docs_48dp.png\n    humanURL: https://developers.google.com/docs/api\n    baseURL: https://docs.googleapis.com\n    tags:\n      - Documents\n      - Word Processing\n    properties:\n      - type: OpenAPI\n        url: https://docs.googleapis.com/$discovery/rest?version=v1\n      - type: Documentation\n        url: https://developers.google.com/docs/api/how-tos/overview\n      - type: Samples\n        url: https://developers.google.com/docs/api/samples\n  - name: Google Sheets API\n    description:\
  \ >-\n      Read and write spreadsheet data.\n    image: https://www.gstatic.com/images/branding/product/1x/sheets_48dp.png\n    humanURL: https://developers.google.com/sheets/api\n    baseURL: https://sheets.googleapis.com\n    tags:\n      - Data\n      - Spreadsheets\n    properties:\n      - type: OpenAPI\n        url: https://sheets.googleapis.com/$discovery/rest?version=v4\n      - type: Documentation\n        url: https://developers.google.com/sheets/api/guides/concepts\n      - type: Quickstart\n        url: https://developers.google.com/sheets/api/quickstart\n  - name: Google Slides API\n    description: >-\n      Create and edit presentations.\n    image: https://www.gstatic.com/images/branding/product/1x/slides_48dp.png\n    humanURL: https://developers.google.com/slides\n    baseURL: https://slides.googleapis.com\n    tags:\n      - Presentations\n      - Slides\n    properties:\n      - type: OpenAPI\n        url: https://slides.googleapis.com/$discovery/rest?version=v1\n\
  \      - type: Documentation\n        url: https://developers.google.com/slides/how-tos/overview\n  - name: Google Meet API\n    description: >-\n      Manage video conferencing.\n    image: https://www.gstatic.com/images/branding/product/1x/meet_48dp.png\n    humanURL: https://developers.google.com/meet\n    baseURL: https://meet.googleapis.com\n    tags:\n      - Meetings\n      - Video Conferencing\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/meet/api\n  - name: Admin SDK Directory API\n    description: >-\n      Manage users, groups, and organizational units.\n    humanURL: https://developers.google.com/admin-sdk/directory\n    baseURL: https://admin.googleapis.com\n    tags:\n      - Administration\n      - Groups\n      - Users\n    properties:\n      - type: OpenAPI\n        url: https://admin.googleapis.com/$discovery/rest?version=directory_v1\n      - type: Documentation\n        url: https://developers.google.com/admin-sdk/directory/reference/rest\n\
  common:\n  - type: Authentication\n    url: https://developers.google.com/workspace/guides/auth-overview\n  - type: Console\n    url: https://console.cloud.google.com\n  - type: Pricing\n    url: https://workspace.google.com/pricing\n  - type: Support\n    url: https://workspace.google.com/support\n  - type: Terms of Service\n    url: https://workspace.google.com/terms\n  - type: SDKs\n    url: https://developers.google.com/workspace/guides/client-libraries\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-suites/refs/heads/main/apis.yml
tags:
- Cloud Storage
- Collaboration
- Email
- Office Suite
- Productivity
url: https://workspace.google.com/
use_cases: []
---
