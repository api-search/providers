---
api_count: 4
api_specs:
- filename: google-sheets-openapi.yml
  format: yaml
  label: Google Sheets API
  slug: google-sheets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/openapi/google-sheets-openapi.yml
apis:
- description: The Google Sheets API v4 is a RESTful interface that lets developers read and modify Google Spreadsheet data programmatically. The API supports creating spreadsheets, reading and writing cell values b
  name: Google Sheets API
  slug: google-sheets-api
- description: The Microsoft Graph Excel API enables reading and writing Excel workbooks (.xlsx format) stored in OneDrive for Business, SharePoint, or Group drives via the Microsoft Graph REST API. Supports workshe
  name: Microsoft Graph Excel API
  slug: microsoft-graph-excel-api
- description: SheetDB is a service that turns any Google Sheet into a JSON REST API. Provides GET, POST, PUT, PATCH, and DELETE endpoints against spreadsheet data, supporting full CRUD operations without code. Used
  name: SheetDB
  slug: sheetdb
- description: Sheety converts Google Spreadsheets into RESTful JSON APIs, providing simple HTTP endpoints for reading and writing spreadsheet data. Supports GET, POST, PUT, PATCH, and DELETE operations with optiona
  name: Sheety
  slug: sheety
capabilities:
- description: Workflow capability for spreadsheet data automation using Google Sheets API. Enables AI assistants and applications to read data from sheets, write and append new rows, batch update multiple ranges, c
  name: Spreadsheet Automation
  slug: spreadsheet-automation
common:
- title: ''
  type: Website
  url: https://developers.google.com/workspace/sheets/api
- title: ''
  type: Reference
  url: https://learn.microsoft.com/en-us/graph/api/resources/excel
- title: ''
  type: OpenAPI
  url: openapi/google-sheets-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/spreadsheet-range-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/spreadsheet-value-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/spreadsheet-range-structure.json
- title: ''
  type: JSONLD
  url: json-ld/spreadsheets-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/spreadsheets-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/spreadsheet-automation.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/spreadsheets-vocabulary.yml
created: '2026-03-16'
description: Spreadsheets covers the APIs, tools, and services for programmatic access to spreadsheet data across major platforms including Google Sheets and Microsoft Excel. The Google Sheets API v4 provides RESTful access to read, write, format, and manage Google Spreadsheets. The Microsoft Graph Excel API enables reading and writing Excel workbooks stored in OneDrive for Business and SharePoint. Third-party services like SheetDB, Sheety, Sheet Best, and Sheet2API convert spreadsheets into REST APIs for use as lightweight backends. Spreadsheet APIs are widely used for data import/export, automated reporting, form submissions, lightweight CMS, and business process automation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 32
  name: Spreadsheets Context
  property_count: 1
  slug: spreadsheets-context
layout: provider
modified: '2026-05-02'
name: Spreadsheets
rules:
- name: Spreadsheets API Rules
  rule_count: 13
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 6
  slug: spreadsheets-rules
skills: []
slug: spreadsheets
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spreadsheets\nname: Spreadsheets\ndescription: >-\n  Spreadsheets covers the APIs, tools, and services for programmatic access to spreadsheet\n  data across major platforms including Google Sheets and Microsoft Excel. The Google Sheets\n  API v4 provides RESTful access to read, write, format, and manage Google Spreadsheets.\n  The Microsoft Graph Excel API enables reading and writing Excel workbooks stored in\n  OneDrive for Business and SharePoint. Third-party services like SheetDB, Sheety, Sheet Best,\n  and Sheet2API convert spreadsheets into REST APIs for use as lightweight backends. Spreadsheet\n  APIs are widely used for data import/export, automated reporting, form submissions,\n  lightweight CMS, and business process automation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Spreadsheets\n  - Data\n  - Google Sheets\n  - Excel\n  - Productivity\n  - Automation\ncreated:\
  \ '2026-03-16'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: spreadsheets:google-sheets-api\n    name: Google Sheets API\n    description: >-\n      The Google Sheets API v4 is a RESTful interface that lets developers read and modify\n      Google Spreadsheet data programmatically. The API supports creating spreadsheets, reading\n      and writing cell values by range (A1 notation), batch operations for efficiency, managing\n      sheet structure and formatting, and accessing developer metadata. Authentication uses\n      Google OAuth 2.0. The API is widely used for data pipelines, automated reporting,\n      form data collection, and spreadsheet-powered applications.\n    humanURL: https://developers.google.com/workspace/sheets/api\n    baseURL: https://sheets.googleapis.com/v4\n    tags:\n      - Google Sheets\n      - Spreadsheets\n      - Data\n      - Productivity\n\
  \      - Google Workspace\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/sheets/api/guides/concepts\n      - type: Reference\n        url: https://developers.google.com/workspace/sheets/api/reference/rest\n      - type: OpenAPI\n        url: openapi/google-sheets-openapi.yml\n      - type: Getting Started\n        url: https://developers.google.com/workspace/sheets/api/quickstart/python\n      - type: Discovery\n        url: https://sheets.googleapis.com/$discovery/rest?version=v4\n    features:\n      - type: SpreadsheetCRUD\n        description: Create, read, and batch-update entire spreadsheets\n      - type: ValueReadWrite\n        description: Read and write cell values by range using A1 notation (e.g., Sheet1!A1:B2)\n      - type: BatchOperations\n        description: Batch read/write multiple ranges in a single API call for efficiency\n      - type: SheetFormatting\n        description: Apply number formats, text formatting, conditional\
  \ formatting, and cell styles\n      - type: DataValidation\n        description: Set and enforce data validation rules on cell ranges\n      - type: PivotTables\n        description: Create and manage pivot tables programmatically\n      - type: Charts\n        description: Create, update, and embed charts in spreadsheets\n      - type: DeveloperMetadata\n        description: Attach custom metadata to spreadsheets for application use\n    useCases:\n      - type: DataPipeline\n        description: Import and export data between databases and spreadsheets\n      - type: AutomatedReporting\n        description: Generate weekly/monthly reports directly into Google Sheets\n      - type: FormDataCollection\n        description: Write form submission data to spreadsheets as a lightweight backend\n      - type: FinancialModeling\n        description: Programmatically update financial models with live data\n      - type: ContentManagement\n        description: Use Sheets as a lightweight CMS\
  \ for websites and apps\n\n  - aid: spreadsheets:microsoft-graph-excel-api\n    name: Microsoft Graph Excel API\n    description: >-\n      The Microsoft Graph Excel API enables reading and writing Excel workbooks (.xlsx format)\n      stored in OneDrive for Business, SharePoint, or Group drives via the Microsoft Graph\n      REST API. Supports worksheets, ranges, tables, charts, named items, and Excel worksheet\n      functions. Uses session-based access for efficient multi-step operations. Authentication\n      requires Microsoft identity platform (OAuth 2.0) with Files.Read or Files.ReadWrite scopes.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/excel\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Excel\n      - Microsoft Graph\n      - Microsoft 365\n      - Spreadsheets\n      - OneDrive\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n      - type: Reference\n      \
  \  url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/graph/excel-use-functions\n    features:\n      - type: WorkbookAccess\n        description: Read and modify .xlsx workbooks stored in OneDrive for Business and SharePoint\n      - type: Sessions\n        description: Persistent and non-persistent session management for efficient operations\n      - type: WorksheetManagement\n        description: Create, rename, delete, and reorder worksheets within a workbook\n      - type: RangeOperations\n        description: Read, write, format, and sort cell ranges using A1-style addressing\n      - type: TableOperations\n        description: Create tables, manage rows/columns, sort, filter, and convert to range\n      - type: ChartOperations\n        description: Create, update, and retrieve chart images from workbooks\n      - type: NamedItems\n        description: Work with named ranges and named expressions\n\
  \      - type: WorkbookFunctions\n        description: Execute Excel worksheet functions (PMT, SUM, VLOOKUP, etc.) via API\n\n  - aid: spreadsheets:sheetdb\n    name: SheetDB\n    description: >-\n      SheetDB is a service that turns any Google Sheet into a JSON REST API. Provides GET,\n      POST, PUT, PATCH, and DELETE endpoints against spreadsheet data, supporting full CRUD\n      operations without code. Used for prototyping, simple backends, and content management.\n    humanURL: https://sheetdb.io/\n    baseURL: https://sheetdb.io/api/v1\n    tags:\n      - Spreadsheets\n      - No Code\n      - REST API\n      - Google Sheets\n    properties:\n      - type: Documentation\n        url: https://docs.sheetdb.io/\n      - type: Website\n        url: https://sheetdb.io/\n\n  - aid: spreadsheets:sheety\n    name: Sheety\n    description: >-\n      Sheety converts Google Spreadsheets into RESTful JSON APIs, providing simple HTTP\n      endpoints for reading and writing spreadsheet data.\
  \ Supports GET, POST, PUT, PATCH,\n      and DELETE operations with optional API key authentication.\n    humanURL: https://sheety.co/\n    baseURL: https://api.sheety.co\n    tags:\n      - Spreadsheets\n      - No Code\n      - REST API\n      - Google Sheets\n    properties:\n      - type: Documentation\n        url: https://sheety.co/docs\n      - type: Website\n        url: https://sheety.co/\n\ncommon:\n  - type: Website\n    url: https://developers.google.com/workspace/sheets/api\n  - type: Reference\n    url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n  - type: OpenAPI\n    url: openapi/google-sheets-openapi.yml\n  - type: JSONSchema\n    url: json-schema/spreadsheet-range-schema.json\n  - type: JSONSchema\n    url: json-schema/spreadsheet-value-schema.json\n  - type: JSONStructure\n    url: json-structure/spreadsheet-range-structure.json\n  - type: JSONLD\n    url: json-ld/spreadsheets-context.jsonld\n  - type: SpectralRules\n    url: rules/spreadsheets-rules.yml\n\
  \  - type: Capabilities\n    url: capabilities/spreadsheet-automation.yaml\n  - type: Vocabulary\n    url: vocabulary/spreadsheets-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/apis.yml
tags:
- Spreadsheets
- Data
- Google Sheets
- Excel
- Productivity
- Automation
url: https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/apis.yml
use_cases: []
---
