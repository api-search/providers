---
api_count: 3
apis:
- description: RESTful API for managing and generating Crystal Reports programmatically.
  name: Crystal Reports REST API
  slug: rest-api
- description: Software Development Kit for embedding Crystal Reports into applications.
  name: Crystal Reports SDK
  slug: sdk
- description: API for Crystal Reports Server administration and report management.
  name: Crystal Reports Server REST API
  slug: server-rest-api
capabilities:
- description: Unified workflow for managing Crystal Reports including authentication, repository browsing, report viewing, data access, and export. Used by report developers, BI analysts, and application developers
  name: Crystal Reports Report Management
  slug: report-management
common:
- title: ''
  type: Portal
  url: https://api.sap.com
- title: ''
  type: Blog
  url: https://blogs.sap.com/tags/73554900100800000134/
- title: ''
  type: Community
  url: https://community.sap.com/topics/crystal-reports
- title: ''
  type: Support
  url: https://support.sap.com/crystal-reports
- title: ''
  type: TermsOfService
  url: https://www.sap.com/about/legal/terms-of-use.html
- title: ''
  type: PrivacyPolicy
  url: https://www.sap.com/about/legal/privacy.html
created: '2024-01-01'
description: APIs and resources for Crystal Reports, a business intelligence application for designing and generating reports from various data sources.
features:
- description: Generate formatted reports from relational databases, spreadsheets, and XML data sources.
  name: Report Generation
- description: Embed report viewers in web and desktop applications for interactive report consumption.
  name: Report Viewing
- description: Schedule automated report generation and delivery via email or file system.
  name: Report Scheduling
- description: Pass dynamic parameters to filter and customize report content at runtime.
  name: Parameter Prompts
- description: Export reports to PDF, Excel, Word, CSV, XML, and other formats programmatically.
  name: Export Formats
- description: Embed linked sub-reports within parent reports for drill-down capabilities.
  name: Sub-Reports
- description: Generate pivot-table style cross-tabulation reports from data.
  name: Cross-Tab Reports
- description: Create charts and graphs within reports for data visualization.
  name: Charting
- description: Connect to SQL Server, Oracle, SAP HANA, ODBC, JDBC, and other data sources.
  name: Data Source Connectivity
- description: Manage report server instances, folders, users, and security via REST API.
  name: Report Server Management
image: /assets/icons/crystal-reports.png
integrations: []
jsonld:
- class_count: 22
  name: Crystal Reports Context
  property_count: 54
  slug: crystal-reports-context
layout: provider
modified: '2026-04-17'
name: Crystal Reports
rules:
- name: Crystal Reports API Rules
  rule_count: 16
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 1
  slug: crystal-reports-spectral-rules
skills: []
slug: crystal-reports
solutions:
- description: Desktop report designer for creating and editing report templates.
  name: SAP Crystal Reports
- description: Server platform for scheduling, managing, and distributing reports.
  name: SAP Crystal Reports Server
- description: Enterprise BI platform with Crystal Reports integration.
  name: SAP BusinessObjects BI
source_filename: apis.yml
source_yaml: "aid: crystal-reports\nname: Crystal Reports\ndescription: APIs and resources for Crystal Reports, a business intelligence application\n  for designing and generating reports from various data sources.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/crystal-reports/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-17'\napis:\n- name: Crystal Reports REST API\n  description: RESTful API for managing and generating Crystal Reports programmatically.\n  image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n  humanURL: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS\n  baseURL: https://api.sap.com/crystal/v1\n  tags:\n  - Business Intelligence\n  - Data Visualization\n  - Enterprise\n  - Reports\n  properties:\n  - type: Documentation\n    url: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/api\n  - type: OpenAPI\n    url: https://api.sap.com/crystal/openapi.json\n\
  \  - type: Authentication\n    url: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/authentication\n  contact:\n  - FN: SAP Support\n    email: support@sap.com\n    url: https://support.sap.com\n  aid: crystal-reports:rest-api\n- name: Crystal Reports SDK\n  description: Software Development Kit for embedding Crystal Reports into applications.\n  humanURL: https://help.sap.com/docs/CRYSTAL_REPORTS_SDK\n  baseURL: https://www.sap.com/sdk/crystal\n  tags:\n  - .NET\n  - Embedding\n  - Java\n  - SDK\n  properties:\n  - type: Documentation\n    url: https://help.sap.com/docs/CRYSTAL_REPORTS_SDK\n  - type: Download\n    url: https://www.sap.com/products/technology-platform/crystal-reports/downloads.html\n  - type: Code Samples\n    url: https://github.com/SAP-samples/crystal-reports\n  aid: crystal-reports:sdk\n- name: Crystal Reports Server REST API\n  description: API for Crystal Reports Server administration and report management.\n  humanURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM\n\
  \  baseURL: https://server:port/biprws\n  tags:\n  - Administration\n  - BI Platform\n  - Report Management\n  - Server\n  properties:\n  - type: Documentation\n    url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/rest-api\n  - type: API Reference\n    url: https://help.sap.com/doc/rest-api-reference\n  aid: crystal-reports:server-rest-api\ncommon:\n- type: Portal\n  url: https://api.sap.com\n- type: Blog\n  url: https://blogs.sap.com/tags/73554900100800000134/\n- type: Community\n  url: https://community.sap.com/topics/crystal-reports\n- type: Support\n  url: https://support.sap.com/crystal-reports\n- type: TermsOfService\n  url: https://www.sap.com/about/legal/terms-of-use.html\n- type: PrivacyPolicy\n  url: https://www.sap.com/about/legal/privacy.html\n- type: Features\n  data:\n  - name: Report Generation\n    description: Generate formatted reports from relational databases, spreadsheets,\n      and XML data sources.\n  - name: Report Viewing\n   \
  \ description: Embed report viewers in web and desktop applications for interactive\n      report consumption.\n  - name: Report Scheduling\n    description: Schedule automated report generation and delivery via email or file\n      system.\n  - name: Parameter Prompts\n    description: Pass dynamic parameters to filter and customize report content at\n      runtime.\n  - name: Export Formats\n    description: Export reports to PDF, Excel, Word, CSV, XML, and other formats programmatically.\n  - name: Sub-Reports\n    description: Embed linked sub-reports within parent reports for drill-down capabilities.\n  - name: Cross-Tab Reports\n    description: Generate pivot-table style cross-tabulation reports from data.\n  - name: Charting\n    description: Create charts and graphs within reports for data visualization.\n  - name: Data Source Connectivity\n    description: Connect to SQL Server, Oracle, SAP HANA, ODBC, JDBC, and other data\n      sources.\n  - name: Report Server Management\n\
  \    description: Manage report server instances, folders, users, and security via\n      REST API.\n- type: UseCases\n  data:\n  - name: Financial Reporting\n    description: Generate financial statements, balance sheets, and P&L reports from\n      ERP data.\n  - name: Operational Dashboards\n    description: Create operational reports for manufacturing, logistics, and supply\n      chain.\n  - name: Compliance Reports\n    description: Generate regulatory compliance reports for auditing and governance.\n  - name: Customer Invoicing\n    description: Produce formatted invoices and statements from billing data.\n  - name: HR Analytics\n    description: Generate employee reports, headcount analytics, and compensation\n      summaries.\n  - name: Embedded Reporting\n    description: Embed Crystal Reports viewer into custom applications for end-user\n      reporting.\n- type: Solutions\n  data:\n  - name: SAP Crystal Reports\n    description: Desktop report designer for creating and editing\
  \ report templates.\n  - name: SAP Crystal Reports Server\n    description: Server platform for scheduling, managing, and distributing reports.\n  - name: SAP BusinessObjects BI\n    description: Enterprise BI platform with Crystal Reports integration.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ntags:\n- Business Intelligence\n- Crystal Reports\n- Data Analytics\n- Enterprise Software\n- Reporting\n- SAP\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/crystal-reports/refs/heads/main/apis.yml
tags:
- Business Intelligence
- Crystal Reports
- Data Analytics
- Enterprise Software
- Reporting
- SAP
url: https://raw.githubusercontent.com/api-evangelist/crystal-reports/refs/heads/main/apis.yml
use_cases:
- description: Generate financial statements, balance sheets, and P&L reports from ERP data.
  name: Financial Reporting
- description: Create operational reports for manufacturing, logistics, and supply chain.
  name: Operational Dashboards
- description: Generate regulatory compliance reports for auditing and governance.
  name: Compliance Reports
- description: Produce formatted invoices and statements from billing data.
  name: Customer Invoicing
- description: Generate employee reports, headcount analytics, and compensation summaries.
  name: HR Analytics
- description: Embed Crystal Reports viewer into custom applications for end-user reporting.
  name: Embedded Reporting
---
