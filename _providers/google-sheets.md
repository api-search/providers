---
api_count: 2
apis:
- description: The Google Sheets API lets you read, write, and format Google Sheets data.
  name: Google Sheets API v4
  slug: ''
- description: The built-in Google Apps Script Spreadsheet Service allows creation, access, and modification of Google Sheets files directly from Apps Script with performance bundling and numerous classes for format
  name: Google Apps Script Spreadsheet Service
  slug: ''
capabilities:
- description: Workflow for managing spreadsheet data including creating spreadsheets, reading and writing cell values, batch operations, and metadata management. Used by data analysts, developers, and automation en
  name: Google Sheets Spreadsheet Data Management
  slug: spreadsheet-data-management
common:
- title: ''
  type: Portal
  url: https://developers.google.com/workspace/sheets/api
- title: ''
  type: Documentation
  url: https://developers.google.com/workspace/sheets/api/reference/rest
- title: ''
  type: Blog
  url: https://workspace.google.com/blog/developers-practitioners
- title: ''
  type: GitHubOrganization
  url: https://github.com/googleapis
- title: ''
  type: Support
  url: https://developers.google.com/sheets/api/support
- title: ''
  type: StatusPage
  url: https://www.google.com/appsstatus/dashboard/
- title: ''
  type: TermsOfService
  url: https://developers.google.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: SignUp
  url: https://console.cloud.google.com/
- title: ''
  type: Login
  url: https://console.cloud.google.com/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/google-sheets-api
- title: ''
  type: YouTube
  url: https://developers.google.com/workspace/sheets/api/videos
- title: ''
  type: GettingStarted
  url: https://developers.google.com/workspace/sheets/api/guides/concepts
- title: ''
  type: Authentication
  url: https://developers.google.com/sheets/api/guides/authorizing
- title: ''
  type: SDK
  url: https://developers.google.com/workspace/sheets/api/guides/libraries
- title: ''
  type: ReleaseNotes
  url: https://developers.google.com/workspace/sheets/release-notes
- title: ''
  type: Pricing
  url: https://developers.google.com/workspace/sheets/api/limits
- title: ''
  type: RateLimits
  url: https://developers.google.com/workspace/sheets/api/limits
- title: ''
  type: SpectralRules
  url: rules/google-sheets-spectral-rules.yml
- title: Google Sheets API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/google-sheets.yaml
- title: Spreadsheet Data Management Workflow
  type: NaftikoCapability
  url: capabilities/spreadsheet-data-management.yaml
created: '2024-01-01'
description: API for reading, writing, and formatting data in Google Sheets.
features:
- description: Create, read, update, and delete spreadsheets programmatically with full control over properties and metadata.
  name: Spreadsheet Management
- description: Read and write individual cell values, ranges, and batch operations across multiple ranges.
  name: Cell Value Operations
- description: Apply rich formatting to cells including fonts, colors, borders, alignment, and number formats.
  name: Formatting
- description: Add, remove, copy, and configure individual sheets within a spreadsheet.
  name: Sheet Management
- description: Attach custom metadata to spreadsheets, sheets, rows, and columns for application-specific data.
  name: Developer Metadata
- description: Set validation rules on cells to enforce data quality and consistency.
  name: Data Validation
- description: Apply conditional formatting rules based on cell values and formulas.
  name: Conditional Formatting
- description: Create and manage embedded charts within spreadsheets.
  name: Charts and Graphs
- description: Define and manage named ranges for easier formula references.
  name: Named Ranges
- description: Execute multiple read and write operations in a single API call for efficiency.
  name: Batch Operations
image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png
integrations:
- description: Deep integration with Google Docs, Slides, Forms, and other Workspace applications.
  name: Google Workspace
- description: Extend Sheets functionality with custom functions, menus, and automation scripts.
  name: Google Apps Script
- description: Connect to BigQuery, Cloud Functions, and other GCP services for advanced data processing.
  name: Google Cloud Platform
- description: Connect Google Sheets to thousands of apps through Zapier automation workflows.
  name: Zapier
- description: Send notifications and updates to Slack channels based on spreadsheet changes.
  name: Slack
jsonld:
- class_count: 0
  name: Google Sheets Context
  property_count: 0
  slug: google-sheets-context
layout: provider
modified: '2026-04-18'
name: Google Sheets
rules:
- name: Google Sheets API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: google-sheets-spectral-rules
skills: []
slug: google-sheets
solutions: []
source_yaml: "aid: google-sheets\nname: Google Sheets\ndescription: >-\n  API for reading, writing, and formatting data in Google Sheets.\nimage: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png\nurl: https://developers.google.com/sheets/api\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - name: Google Sheets API v4\n    description: >-\n      The Google Sheets API lets you read, write, and format Google Sheets data.\n    image: https://www.gstatic.com/images/branding/product/2x/sheets_2020q4_48dp.png\n    humanURL: https://developers.google.com/sheets/api\n    baseURL: https://sheets.googleapis.com/v4\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/sheets/api/reference/rest\n      - type: OpenAPI\n        url: openapi/google-sheets-openapi.yml\n      - type: Authentication\n        url: https://developers.google.com/sheets/api/guides/authorizing\n      - type:\
  \ Quickstart\n        url: https://developers.google.com/sheets/api/quickstart/python\n      - type: GettingStarted\n        url: https://developers.google.com/workspace/sheets/api/guides/concepts\n      - type: APIReference\n        url: https://developers.google.com/workspace/sheets/api/reference/rest\n      - type: SDK\n        url: https://developers.google.com/workspace/sheets/api/guides/libraries\n      - type: ChangeLog\n        url: https://developers.google.com/workspace/sheets/release-notes\n      - type: CodeExamples\n        url: https://developers.google.com/workspace/sheets/api/samples\n      - type: RateLimits\n        url: https://developers.google.com/workspace/sheets/api/limits\n      - type: Errors\n        url: https://developers.google.com/workspace/sheets/api/troubleshoot-api-errors\n      - type: JSONSchema\n        url: json-schema/google-sheets-spreadsheet-schema.json\n      - type: JSONLD\n        url: json-ld/google-sheets-context.jsonld\n    contact:\n     \
  \ - type: Support\n        url: https://support.google.com/developers/\n      - type: StackOverflow\n        url: https://stackoverflow.com/questions/tagged/google-sheets-api\n    tags:\n      - Collaboration\n      - Data\n      - Google\n      - Productivity\n      - Spreadsheets\n  - name: Google Apps Script Spreadsheet Service\n    description: >-\n      The built-in Google Apps Script Spreadsheet Service allows creation, access,\n      and modification of Google Sheets files directly from Apps Script with\n      performance bundling and numerous classes for formatting, data sources,\n      structure, and content.\n    image: https://www.gstatic.com/images/branding/product/2x/apps_script_48dp.png\n    humanURL: https://developers.google.com/apps-script/reference/spreadsheet\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/apps-script/reference/spreadsheet\n      - type: GettingStarted\n        url: https://developers.google.com/apps-script\n\
  \      - type: APIReference\n        url: https://developers.google.com/apps-script/reference\n      - type: ReleaseNotes\n        url: https://developers.google.com/apps-script/release-notes\n    contact:\n      - type: StackOverflow\n        url: https://stackoverflow.com/questions/tagged/google-apps-script\n    tags:\n      - Apps Script\n      - Automation\n      - Google\n      - Scripting\n      - Spreadsheets\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developers.google.com/workspace/sheets/api\n  - type: Documentation\n    url: https://developers.google.com/workspace/sheets/api/reference/rest\n  - type: Blog\n    url: https://workspace.google.com/blog/developers-practitioners\n  - type: GitHubOrganization\n    url: https://github.com/googleapis\n  - type: Support\n    url: https://developers.google.com/sheets/api/support\n  - type: StatusPage\n    url: https://www.google.com/appsstatus/dashboard/\n\
  \  - type: TermsOfService\n    url: https://developers.google.com/terms\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: SignUp\n    url: https://console.cloud.google.com/\n  - type: Login\n    url: https://console.cloud.google.com/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/google-sheets-api\n  - type: YouTube\n    url: https://developers.google.com/workspace/sheets/api/videos\n  - type: GettingStarted\n    url: https://developers.google.com/workspace/sheets/api/guides/concepts\n  - type: Authentication\n    url: https://developers.google.com/sheets/api/guides/authorizing\n  - type: SDK\n    url: https://developers.google.com/workspace/sheets/api/guides/libraries\n  - type: ReleaseNotes\n    url: https://developers.google.com/workspace/sheets/release-notes\n  - type: Pricing\n    url: https://developers.google.com/workspace/sheets/api/limits\n  - type: RateLimits\n    url: https://developers.google.com/workspace/sheets/api/limits\n\
  \  - type: SpectralRules\n    url: rules/google-sheets-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/google-sheets.yaml\n    title: Google Sheets API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/spreadsheet-data-management.yaml\n    title: Spreadsheet Data Management Workflow\n  - type: Features\n    data:\n      - name: Spreadsheet Management\n        description: Create, read, update, and delete spreadsheets programmatically with full control over properties and metadata.\n      - name: Cell Value Operations\n        description: Read and write individual cell values, ranges, and batch operations across multiple ranges.\n      - name: Formatting\n        description: Apply rich formatting to cells including fonts, colors, borders, alignment, and number formats.\n      - name: Sheet Management\n        description: Add, remove, copy, and configure individual sheets within a spreadsheet.\n      - name: Developer Metadata\n      \
  \  description: Attach custom metadata to spreadsheets, sheets, rows, and columns for application-specific data.\n      - name: Data Validation\n        description: Set validation rules on cells to enforce data quality and consistency.\n      - name: Conditional Formatting\n        description: Apply conditional formatting rules based on cell values and formulas.\n      - name: Charts and Graphs\n        description: Create and manage embedded charts within spreadsheets.\n      - name: Named Ranges\n        description: Define and manage named ranges for easier formula references.\n      - name: Batch Operations\n        description: Execute multiple read and write operations in a single API call for efficiency.\n  - type: UseCases\n    data:\n      - name: Data Collection and Reporting\n        description: Collect data from various sources and generate automated reports in Google Sheets.\n      - name: Database Backend\n        description: Use Google Sheets as a lightweight database\
  \ for web applications and prototypes.\n      - name: Workflow Automation\n        description: Automate data entry, processing, and distribution workflows using the API.\n      - name: Data Integration\n        description: Synchronize data between Google Sheets and other business applications.\n      - name: Dashboard Creation\n        description: Build interactive dashboards and visualizations from spreadsheet data.\n  - type: Integrations\n    data:\n      - name: Google Workspace\n        description: Deep integration with Google Docs, Slides, Forms, and other Workspace applications.\n      - name: Google Apps Script\n        description: Extend Sheets functionality with custom functions, menus, and automation scripts.\n      - name: Google Cloud Platform\n        description: Connect to BigQuery, Cloud Functions, and other GCP services for advanced data processing.\n      - name: Zapier\n        description: Connect Google Sheets to thousands of apps through Zapier automation workflows.\n\
  \      - name: Slack\n        description: Send notifications and updates to Slack channels based on spreadsheet changes.\ntags:\n  - Google Workspace\n  - Productivity\n  - Spreadsheets\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-sheets/refs/heads/main/apis.yml
tags:
- Google Workspace
- Productivity
- Spreadsheets
url: https://developers.google.com/sheets/api
use_cases:
- description: Collect data from various sources and generate automated reports in Google Sheets.
  name: Data Collection and Reporting
- description: Use Google Sheets as a lightweight database for web applications and prototypes.
  name: Database Backend
- description: Automate data entry, processing, and distribution workflows using the API.
  name: Workflow Automation
- description: Synchronize data between Google Sheets and other business applications.
  name: Data Integration
- description: Build interactive dashboards and visualizations from spreadsheet data.
  name: Dashboard Creation
---
