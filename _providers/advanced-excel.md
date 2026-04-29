---
api_count: 1
apis:
- description: The Microsoft Graph Excel API provides REST access to Excel workbooks stored in OneDrive, SharePoint, or Teams. Supports reading and writing cell values, executing formulas, managing worksheets, creat
  name: Microsoft Graph Excel API
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-365/excel
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/graph/excel-concept-overview
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/graph/api/resources/excel
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/servicesagreement
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHubOrganization
  url: https://github.com/OfficeDev
created: '2024-01-15'
description: Advanced Excel is a subject-matter topic encompassing Microsoft Excel's programmatic capabilities for data analysis, formula execution, workbook management, chart generation, and automation. This topic index covers REST APIs, open data schemas, and developer tools for working with Excel workbooks programmatically, including Microsoft Graph Excel API, open-source spreadsheet libraries, and data interchange formats used in business intelligence and automation workflows.
features:
- description: Create, read, update, and delete Excel workbooks and worksheets via REST API calls.
  name: Workbook and Worksheet Management
- description: Execute Excel formulas and retrieve computed values programmatically via the Microsoft Graph API.
  name: Formula Execution
- description: Read and write cell values, apply formatting, and manipulate named ranges and tables.
  name: Range and Cell Operations
- description: Create and configure charts from worksheet data including column, line, pie, and bar chart types.
  name: Chart Generation
- description: Create, query, and manipulate Excel tables and pivot tables via API.
  name: Table and PivotTable Operations
- description: Manage persistent workbook sessions for transactional multi-step operations on Excel files.
  name: Session Management
- description: Access named ranges, defined names, and custom functions within Excel workbooks.
  name: Named Items and Functions
- description: Apply and query conditional formatting rules on cell ranges via the REST API.
  name: Conditional Formatting
image: /assets/icons/advanced-excel.png
integrations:
- description: No-code automation flows that read and write Excel data using the Excel Online Business connector.
  name: Microsoft Power Automate
- description: Publish Excel workbooks to Power BI for interactive dashboards and data visualization.
  name: Microsoft Power BI
- description: Enterprise workflow automation that connects Excel data to Azure services and external APIs.
  name: Azure Logic Apps
- description: Open-source Python library for reading and writing Excel 2010+ files without Microsoft Office.
  name: Python openpyxl
- description: Java library for reading and writing Microsoft Office formats including Excel XLSX files.
  name: Apache POI
- description: Node.js library for reading, manipulating, and writing Excel workbook files.
  name: ExcelJS
- description: Google's spreadsheet REST API offering similar capabilities for Sheets-based workflows.
  name: Google Sheets API
jsonld:
- class_count: 33
  name: Microsoft Graph Excel Api Context
  property_count: 0
  slug: microsoft-graph-excel-api-context
layout: provider
modified: '2026-04-19'
name: Advanced Excel
skills: []
slug: advanced-excel
solutions: []
source_yaml: "aid: advanced-excel\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/advanced-excel/refs/heads/main/apis.yml\nname: Advanced Excel\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Automation\n- Business Intelligence\n- Data Analysis\n- Data Processing\n- Excel\n- Microsoft\n- Spreadsheets\ndescription: >-\n  Advanced Excel is a subject-matter topic encompassing Microsoft Excel's programmatic capabilities for data analysis, formula execution, workbook management, chart generation, and automation. This topic index covers REST APIs, open data schemas, and developer tools for working with Excel workbooks programmatically, including Microsoft Graph Excel API, open-source spreadsheet libraries, and data interchange formats used in business intelligence and automation workflows.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- name: Microsoft Graph Excel API\n  description: The\
  \ Microsoft Graph Excel API provides REST access to Excel workbooks stored in OneDrive, SharePoint, or Teams. Supports reading and writing cell values, executing formulas, managing worksheets, creating charts and tables, and running workbook sessions for transactional batch operations.\n  humanURL: https://learn.microsoft.com/en-us/graph/api/resources/excel\n  baseURL: https://graph.microsoft.com/v1.0\n  tags:\n  - Excel\n  - Microsoft\n  - OneDrive\n  - REST API\n  - Spreadsheets\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n  - type: OpenAPI\n    url: openapi/microsoft-graph-excel-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/\n  - type: JSONStructure\n    url: json-structure/\n  - type: JSONLD\n    url: json-ld/microsoft-graph-excel-api-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/advanced-excel-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Website\n\
  \  url: https://www.microsoft.com/en-us/microsoft-365/excel\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/graph/excel-concept-overview\n- type: GettingStarted\n  url: https://learn.microsoft.com/en-us/graph/api/resources/excel\n- type: TermsOfService\n  url: https://www.microsoft.com/en-us/servicesagreement\n- type: PrivacyPolicy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: GitHubOrganization\n  url: https://github.com/OfficeDev\n- type: Features\n  data:\n  - name: Workbook and Worksheet Management\n    description: Create, read, update, and delete Excel workbooks and worksheets via REST API calls.\n  - name: Formula Execution\n    description: Execute Excel formulas and retrieve computed values programmatically via the Microsoft Graph API.\n  - name: Range and Cell Operations\n    description: Read and write cell values, apply formatting, and manipulate named ranges and tables.\n  - name: Chart Generation\n    description: Create and configure\
  \ charts from worksheet data including column, line, pie, and bar chart types.\n  - name: Table and PivotTable Operations\n    description: Create, query, and manipulate Excel tables and pivot tables via API.\n  - name: Session Management\n    description: Manage persistent workbook sessions for transactional multi-step operations on Excel files.\n  - name: Named Items and Functions\n    description: Access named ranges, defined names, and custom functions within Excel workbooks.\n  - name: Conditional Formatting\n    description: Apply and query conditional formatting rules on cell ranges via the REST API.\n- type: UseCases\n  data:\n  - name: Automated Reporting\n    description: Generate Excel-based financial, operational, or analytical reports programmatically from business data.\n  - name: Data Import and Export\n    description: Read data from Excel workbooks into business applications or write application data into Excel formats.\n  - name: Spreadsheet Automation\n    description:\
  \ Automate repetitive Excel tasks such as data cleanup, formula recalculation, and sheet formatting.\n  - name: Business Intelligence Pipelines\n    description: Extract and transform Excel data for loading into data warehouses and BI tools.\n  - name: Financial Modeling\n    description: Execute complex financial models stored in Excel and retrieve results via API for application integration.\n  - name: Form and Survey Data Collection\n    description: Use Excel as a data store for forms and survey responses collected via web or mobile applications.\n- type: Integrations\n  data:\n  - name: Microsoft Power Automate\n    description: No-code automation flows that read and write Excel data using the Excel Online Business connector.\n  - name: Microsoft Power BI\n    description: Publish Excel workbooks to Power BI for interactive dashboards and data visualization.\n  - name: Azure Logic Apps\n    description: Enterprise workflow automation that connects Excel data to Azure services and\
  \ external APIs.\n  - name: Python openpyxl\n    description: Open-source Python library for reading and writing Excel 2010+ files without Microsoft Office.\n  - name: Apache POI\n    description: Java library for reading and writing Microsoft Office formats including Excel XLSX files.\n  - name: ExcelJS\n    description: Node.js library for reading, manipulating, and writing Excel workbook files.\n  - name: Google Sheets API\n    description: Google's spreadsheet REST API offering similar capabilities for Sheets-based workflows.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/advanced-excel/refs/heads/main/apis.yml
tags:
- Automation
- Business Intelligence
- Data Analysis
- Data Processing
- Excel
- Microsoft
- Spreadsheets
url: https://raw.githubusercontent.com/api-evangelist/advanced-excel/refs/heads/main/apis.yml
use_cases:
- description: Generate Excel-based financial, operational, or analytical reports programmatically from business data.
  name: Automated Reporting
- description: Read data from Excel workbooks into business applications or write application data into Excel formats.
  name: Data Import and Export
- description: Automate repetitive Excel tasks such as data cleanup, formula recalculation, and sheet formatting.
  name: Spreadsheet Automation
- description: Extract and transform Excel data for loading into data warehouses and BI tools.
  name: Business Intelligence Pipelines
- description: Execute complex financial models stored in Excel and retrieve results via API for application integration.
  name: Financial Modeling
- description: Use Excel as a data store for forms and survey responses collected via web or mobile applications.
  name: Form and Survey Data Collection
---
