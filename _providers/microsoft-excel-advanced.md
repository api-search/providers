---
api_count: 6
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Excel API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
apis:
- description: REST API for reading and writing Excel workbook data through Microsoft Graph.
  name: Microsoft Graph Excel API
  slug: ''
- description: TypeScript-based automation API for Excel on the web and desktop.
  name: Office Scripts API
  slug: ''
- description: JavaScript API for building Excel add-ins and extensions.
  name: Excel JavaScript API
  slug: ''
- description: API for creating custom functions in Excel using JavaScript.
  name: Excel Custom Functions API
  slug: ''
- description: REST API for accessing Excel files stored in OneDrive and SharePoint.
  name: Excel REST API (OneDrive)
  slug: ''
- description: Pre-built connector for automating Excel workflows in Power Automate.
  name: Power Automate Excel Connector
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: Authentication Guide
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: Status Page
  url: https://status.cloud.microsoft/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
created: '2024-01-01'
description: Advanced automation and integration APIs for Microsoft Excel, enabling programmatic access to spreadsheet data, formulas, charts, and automation capabilities through Microsoft Graph, Office Scripts, JavaScript add-ins, custom functions, OneDrive REST endpoints, and Power Automate connectors.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Excel (Advanced)
skills: []
slug: microsoft-excel-advanced
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-excel-advanced\nname: Microsoft Excel (Advanced)\ndescription: >-\n  Advanced automation and integration APIs for Microsoft Excel, enabling programmatic\n  access to spreadsheet data, formulas, charts, and automation capabilities through\n  Microsoft Graph, Office Scripts, JavaScript add-ins, custom functions, OneDrive\n  REST endpoints, and Power Automate connectors.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Business Intelligence\n  - Data Analysis\n  - Office\n  - Spreadsheets\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-excel-advanced/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph Excel API\n    description: >-\n      REST API for reading and writing Excel workbook data through Microsoft Graph.\n    image: https://learn.microsoft.com/graph/images/graph-logo.png\n    humanURL:\
  \ https://learn.microsoft.com/en-us/graph/api/resources/excel\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud\n      - REST\n      - Workbooks\n      - Worksheets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: QuickStart\n        url: https://learn.microsoft.com/en-us/graph/api/resources/excel#get-started\n    contact:\n      - FN: Microsoft Graph Support\n        email: graphsdksupport@microsoft.com\n  - name: Office Scripts API\n    description: >-\n      TypeScript-based automation API for Excel on the web and desktop.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/scripts/\n    baseURL: https://script.office.com\n    tags:\n      - Automation\n\
  \      - Power-Automate\n      - Scripting\n      - Typescript\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/scripts/overview/excel\n      - type: Samples\n        url: https://learn.microsoft.com/en-us/office/dev/scripts/resources/samples/\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/javascript/api/office-scripts/overview\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/office/dev/scripts/tutorials/excel-tutorial\n  - name: Excel JavaScript API\n    description: >-\n      JavaScript API for building Excel add-ins and extensions.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview\n    baseURL: https://appsforoffice.microsoft.com\n    tags:\n      - Add-Ins\n      - Extensions\n      - Javascript\n      - Office-Js\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/excel/\n\
  \      - type: API Reference\n        url: https://learn.microsoft.com/en-us/javascript/api/excel\n      - type: Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n      - type: Quick Start\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/excel-quickstart-jquery\n      - type: CDN\n        url: https://appsforoffice.microsoft.com/lib/1/hosted/office.js\n  - name: Excel Custom Functions API\n    description: >-\n      API for creating custom functions in Excel using JavaScript.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/excel/custom-functions-overview\n    tags:\n      - Calculations\n      - Custom-Functions\n      - Formulas\n      - Udf\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/excel/custom-functions-overview\n      - type: Tutorial\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/tutorials/excel-tutorial-create-custom-functions\n\
  \      - type: Best Practices\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/excel/custom-functions-best-practices\n  - name: Excel REST API (OneDrive)\n    description: >-\n      REST API for accessing Excel files stored in OneDrive and SharePoint.\n    humanURL: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/\n    baseURL: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Cloud-Storage\n      - Onedrive\n      - REST\n      - Sharepoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/api/driveitem_get\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/driveitem\n  - name: Power Automate Excel Connector\n    description: >-\n      Pre-built connector for automating Excel workflows in Power Automate.\n    humanURL: https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/\n    tags:\n      - Connector\n      - Low-Code\n\
  \      - Power-Automate\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/\n      - type: Actions Reference\n        url: https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/#actions\n      - type: Triggers Reference\n        url: https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/#triggers\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: Authentication Guide\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: Status Page\n    url: https://status.cloud.microsoft/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-excel-advanced/refs/heads/main/apis.yml
tags:
- Automation
- Business Intelligence
- Data Analysis
- Office
- Spreadsheets
url: https://raw.githubusercontent.com/api-evangelist/microsoft-excel-advanced/refs/heads/main/apis.yml
use_cases: []
---
