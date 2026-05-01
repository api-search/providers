---
api_count: 4
api_specs:
- filename: rest
  format: yaml
  label: Google Docs API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Google Sheets API
  slug: ''
  spec_type: OpenAPI
  url: https://sheets.googleapis.com/$discovery/rest?version=v4
- filename: rest
  format: yaml
  label: Google Slides API
  slug: ''
  spec_type: OpenAPI
  url: https://slides.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Gmail API
  slug: ''
  spec_type: OpenAPI
  url: https://gmail.googleapis.com/$discovery/rest?version=v1
apis:
- description: API for creating, reading, and editing Google Docs documents.
  name: Google Docs API
  slug: ''
- description: API for reading and modifying Google Sheets spreadsheets.
  name: Google Sheets API
  slug: ''
- description: API for creating and modifying Google Slides presentations.
  name: Google Slides API
  slug: ''
- description: API for accessing Gmail mailboxes and sending mail.
  name: Gmail API
  slug: ''
common:
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: Console
  url: https://console.cloud.google.com
- title: ''
  type: Terms of Service
  url: https://developers.google.com/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Status
  url: https://www.google.com/appsstatus
created: '2024-01-01'
description: Collection of Google Workspace APIs including Docs, Sheets, Slides, and Gmail.
features: []
image: https://workspace.google.com/static/img/logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Workspace Suite
skills: []
slug: google-suite-docs-sheets-slides-gmail
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-suite-docs-sheets-slides-gmail\nname: Google Workspace Suite\ndescription: >-\n  Collection of Google Workspace APIs including Docs, Sheets, Slides, and Gmail.\nimage: https://workspace.google.com/static/img/logo.png\nurl: https://workspace.google.com\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - name: Google Docs API\n    description: >-\n      API for creating, reading, and editing Google Docs documents.\n    image: https://www.gstatic.com/images/branding/product/1x/docs_48dp.png\n    humanURL: https://developers.google.com/docs\n    baseURL: https://docs.googleapis.com\n    tags:\n      - Collaboration\n      - Documents\n      - Productivity\n      - Word Processing\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/docs/api\n      - type: OpenAPI\n        url: https://docs.googleapis.com/$discovery/rest?version=v1\n      - type: Authentication\n        url: https://developers.google.com/docs/api/how-tos/authorizing\n\
  \      - type: Pricing\n        url: https://developers.google.com/docs/api/limits\n    contact:\n      - FN: Google Workspace Support\n        email: workspace-apis@google.com\n        url: https://developers.google.com/docs/api/support\n  - name: Google Sheets API\n    description: >-\n      API for reading and modifying Google Sheets spreadsheets.\n    image: https://www.gstatic.com/images/branding/product/1x/sheets_48dp.png\n    humanURL: https://developers.google.com/sheets\n    baseURL: https://sheets.googleapis.com\n    tags:\n      - Analytics\n      - Data\n      - Productivity\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/sheets/api\n      - type: OpenAPI\n        url: https://sheets.googleapis.com/$discovery/rest?version=v4\n      - type: Authentication\n        url: https://developers.google.com/sheets/api/guides/authorizing\n      - type: Quickstart\n        url: https://developers.google.com/sheets/api/quickstart\n\
  \      - type: Pricing\n        url: https://developers.google.com/sheets/api/limits\n    contact:\n      - FN: Google Workspace Support\n        email: workspace-apis@google.com\n        url: https://developers.google.com/sheets/api/support\n  - name: Google Slides API\n    description: >-\n      API for creating and modifying Google Slides presentations.\n    image: https://www.gstatic.com/images/branding/product/1x/slides_48dp.png\n    humanURL: https://developers.google.com/slides\n    baseURL: https://slides.googleapis.com\n    tags:\n      - Collaboration\n      - Presentations\n      - Productivity\n      - Slides\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/slides/api\n      - type: OpenAPI\n        url: https://slides.googleapis.com/$discovery/rest?version=v1\n      - type: Authentication\n        url: https://developers.google.com/slides/api/guides/authorizing\n      - type: Samples\n        url: https://developers.google.com/slides/samples\n\
  \      - type: Pricing\n        url: https://developers.google.com/slides/api/limits\n    contact:\n      - FN: Google Workspace Support\n        email: workspace-apis@google.com\n        url: https://developers.google.com/slides/api/support\n  - name: Gmail API\n    description: >-\n      API for accessing Gmail mailboxes and sending mail.\n    image: https://www.gstatic.com/images/branding/product/1x/gmail_48dp.png\n    humanURL: https://developers.google.com/gmail\n    baseURL: https://gmail.googleapis.com\n    tags:\n      - Communication\n      - Email\n      - Messaging\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/gmail/api\n      - type: OpenAPI\n        url: https://gmail.googleapis.com/$discovery/rest?version=v1\n      - type: Authentication\n        url: https://developers.google.com/gmail/api/auth\n      - type: Guides\n        url: https://developers.google.com/gmail/api/guides\n      - type: Reference\n   \
  \     url: https://developers.google.com/gmail/api/reference/rest\n      - type: Pricing\n        url: https://developers.google.com/gmail/api/reference/quota\n    contact:\n      - FN: Google Workspace Support\n        email: workspace-apis@google.com\n        url: https://developers.google.com/gmail/api/support\ncommon:\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n  - type: Console\n    url: https://console.cloud.google.com\n  - type: Terms of Service\n    url: https://developers.google.com/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Status\n    url: https://www.google.com/appsstatus\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Collaboration\n  - Documents\n  - Google\n  - Productivity\n  - Workspace\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-suite-docs-sheets-slides-gmail/refs/heads/main/apis.yml
tags:
- Cloud
- Collaboration
- Documents
- Google
- Productivity
- Workspace
url: https://workspace.google.com
use_cases: []
---
