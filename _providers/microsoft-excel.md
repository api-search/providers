---
api_count: 3
apis:
- description: REST API for accessing and manipulating Excel workbooks stored in OneDrive for Business, SharePoint sites, or Group drives through Microsoft Graph. Supports worksheet, table, chart, range, named item,
  name: Microsoft Graph Excel API
  slug: ''
- description: Office Add-ins API for building custom functionality within Excel using JavaScript and TypeScript.
  name: Excel JavaScript API
  slug: ''
- description: TypeScript-based automation for Excel on the web, enabling Power Automate integration for business process automation.
  name: Office Scripts API
  slug: ''
capabilities:
- description: Workflow capability for automating Excel spreadsheet operations including worksheet management, data manipulation, table operations, and chart generation via Microsoft Graph.
  name: Microsoft Excel Spreadsheet Automation
  slug: spreadsheet-automation
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: Support
  url: https://support.microsoft.com/excel
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-365/excel
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/excel-blog/bg-p/ExcelBlog
- title: ''
  type: GitHubOrganization
  url: https://github.com/OfficeDev
- title: ''
  type: SpectralRules
  url: rules/microsoft-excel-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/spreadsheet-automation.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-excel-vocabulary.yaml
created: '2024'
description: APIs for automating, integrating, and extending Microsoft Excel functionality including workbook management, data manipulation, charting, and formula execution through Microsoft Graph REST APIs.
features:
- description: Persistent and non-persistent sessions for efficient API operations.
  name: Workbook Sessions
- description: Read, write, and format individual cells or ranges of cells.
  name: Cell Range Operations
- description: Create, update, sort, and filter structured tables.
  name: Table Management
- description: Create and manage charts with customizable source data.
  name: Chart Generation
- description: Invoke Excel functions programmatically via the API.
  name: Workbook Functions
- description: Define and manage named ranges for reusable cell references.
  name: Named Ranges
image: https://learn.microsoft.com/en-us/graph/images/excel-logo.png
integrations:
- description: Automate Excel workflows using Power Automate connectors.
  name: Microsoft Power Automate
- description: Access and modify Excel files stored in SharePoint sites.
  name: SharePoint
- description: Work with Excel workbooks stored in OneDrive for Business.
  name: OneDrive
- description: Share and collaborate on Excel workbooks within Teams.
  name: Microsoft Teams
jsonld:
- class_count: 9
  name: Microsoft Excel Graph Api Context
  property_count: 20
  slug: microsoft-excel-graph-api-context
layout: provider
modified: '2026-04-18'
name: Microsoft Excel
rules:
- name: Microsoft Excel API Rules
  rule_count: 24
  severity_counts:
    error: 16
    hint: 0
    info: 2
    warn: 6
  slug: microsoft-excel-spectral-rules
skills: []
slug: microsoft-excel
solutions: []
source_yaml: "aid: microsoft-excel\nname: Microsoft Excel\ndescription: >-\n  APIs for automating, integrating, and extending Microsoft Excel functionality\n  including workbook management, data manipulation, charting, and formula\n  execution through Microsoft Graph REST APIs.\nimage: https://learn.microsoft.com/en-us/graph/images/excel-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-excel/refs/heads/main/apis.yml\nhumanURL: https://www.microsoft.com/excel\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Automation\n  - Data Analysis\n  - Microsoft\n  - Microsoft 365\n  - Office\n  - Spreadsheets\napis:\n  - name: Microsoft Graph Excel API\n    description: >-\n      REST API for accessing and manipulating Excel workbooks stored in OneDrive\n      for Business, SharePoint sites, or Group drives through Microsoft Graph.\n      Supports worksheet, table, chart, range, named item, and function operations.\n    humanURL:\
  \ https://learn.microsoft.com/en-us/graph/api/resources/excel\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud\n      - Microsoft Graph\n      - OneDrive\n      - REST API\n      - SharePoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n      - type: OpenAPI\n        url: openapi/microsoft-excel-graph-api.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: JSONSchema\n        url: json-schema/excel-graph-api-worksheet-schema.json\n      - type: JSONSchema\n        url: json-schema/excel-graph-api-table-schema.json\n      - type: JSONSchema\n        url: json-schema/excel-graph-api-table-row-schema.json\n      - type: JSONSchema\n        url:\
  \ json-schema/excel-graph-api-table-column-schema.json\n      - type: JSONSchema\n        url: json-schema/excel-graph-api-chart-schema.json\n      - type: JSONSchema\n        url: json-schema/excel-graph-api-range-schema.json\n      - type: JSONSchema\n        url: json-schema/excel-graph-api-named-item-schema.json\n      - type: JSONStructure\n        url: json-structure/excel-graph-api-worksheet-structure.json\n      - type: JSON-LD\n        url: json-ld/microsoft-excel-graph-api-context.jsonld\n      - type: Example\n        url: examples/excel-graph-api-worksheet-example.json\n      - type: Example\n        url: examples/excel-graph-api-table-example.json\n      - type: Example\n        url: examples/excel-graph-api-range-example.json\n  - name: Excel JavaScript API\n    description: >-\n      Office Add-ins API for building custom functionality within Excel using\n      JavaScript and TypeScript.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview\n\
  \    baseURL: https://excel.office.com\n    tags:\n      - Client-Side\n      - JavaScript\n      - Office Add-Ins\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/excel\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/excel-quickstart-jquery\n  - name: Office Scripts API\n    description: >-\n      TypeScript-based automation for Excel on the web, enabling Power Automate\n      integration for business process automation.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/scripts/overview/excel\n    baseURL: https://excel.office.com\n    tags:\n      - Automation\n      - Excel Online\n      - Power Automate\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/scripts/develop/scripting-fundamentals\n      - type: CodeExamples\n        url: https://learn.microsoft.com/en-us/office/dev/scripts/resources/samples/samples-overview\n\
  \      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/office/dev/scripts/tutorials/excel-tutorial\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: Support\n    url: https://support.microsoft.com/excel\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/microsoft-365/excel\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/excel-blog/bg-p/ExcelBlog\n  - type: GitHubOrganization\n    url: https://github.com/OfficeDev\n  - type: SpectralRules\n    url: rules/microsoft-excel-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/spreadsheet-automation.yaml\n  - type: Vocabulary\n    url: vocabulary/microsoft-excel-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Workbook Sessions\n        description: Persistent\
  \ and non-persistent sessions for efficient API operations.\n      - name: Cell Range Operations\n        description: Read, write, and format individual cells or ranges of cells.\n      - name: Table Management\n        description: Create, update, sort, and filter structured tables.\n      - name: Chart Generation\n        description: Create and manage charts with customizable source data.\n      - name: Workbook Functions\n        description: Invoke Excel functions programmatically via the API.\n      - name: Named Ranges\n        description: Define and manage named ranges for reusable cell references.\n  - type: UseCases\n    data:\n      - name: Automated Reporting\n        description: Generate and update Excel reports from external data sources.\n      - name: Data Entry Automation\n        description: Programmatically insert and update data in spreadsheets.\n      - name: Financial Modeling\n        description: Use Excel functions API for financial calculations.\n      - name:\
  \ Dashboard Generation\n        description: Create charts and visualizations from data.\n  - type: Integrations\n    data:\n      - name: Microsoft Power Automate\n        description: Automate Excel workflows using Power Automate connectors.\n      - name: SharePoint\n        description: Access and modify Excel files stored in SharePoint sites.\n      - name: OneDrive\n        description: Work with Excel workbooks stored in OneDrive for Business.\n      - name: Microsoft Teams\n        description: Share and collaborate on Excel workbooks within Teams.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-excel/refs/heads/main/apis.yml
tags:
- Automation
- Data Analysis
- Microsoft
- Microsoft 365
- Office
- Spreadsheets
url: https://raw.githubusercontent.com/api-evangelist/microsoft-excel/refs/heads/main/apis.yml
use_cases:
- description: Generate and update Excel reports from external data sources.
  name: Automated Reporting
- description: Programmatically insert and update data in spreadsheets.
  name: Data Entry Automation
- description: Use Excel functions API for financial calculations.
  name: Financial Modeling
- description: Create charts and visualizations from data.
  name: Dashboard Generation
---
