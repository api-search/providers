---
api_count: 3
apis:
- description: OData-based REST API for querying SAP BW data, executing BEx queries, and accessing InfoProviders. Supports analytical queries with filtering, aggregation, and hierarchical navigation.
  name: SAP BW OData API
  slug: odata-api
- description: Business Application Programming Interfaces (BAPIs) and Remote Function Call (RFC) interfaces for SAP BW providing access to metadata management, data loading, process chain execution, and administrat
  name: SAP BW BAPI/RFC API
  slug: bapi-api
- description: API for SAP Analysis for Microsoft Office providing programmatic control of analytical workbooks, data source connections, and report automation within Excel and PowerPoint.
  name: SAP Analysis for Office API
  slug: analysis-office-api
common:
- title: ''
  type: Portal
  url: https://help.sap.com/docs/SAP_BW4HANA
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/SAP_BW4HANA
- title: ''
  type: GettingStarted
  url: https://learning.sap.com/
- title: ''
  type: Support
  url: https://support.sap.com/
- title: ''
  type: Blog
  url: https://community.sap.com/topics/bw
- title: ''
  type: TermsOfService
  url: https://www.sap.com/about/legal/terms-of-use.html
- title: ''
  type: PrivacyPolicy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: Training
  url: https://learning.sap.com/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/sap-bw
created: '2024-01-01'
description: SAP Business Warehouse (SAP BW) and SAP BW/4HANA provide enterprise data warehousing capabilities with APIs for data extraction, query execution, metadata management, and integration with SAP and non-SAP systems. The platform offers OData services, BAPI/RFC interfaces, and Analysis Office APIs for programmatic access to data warehouse operations.
features:
- description: Centralized data warehousing with support for structured and unstructured data across SAP and non-SAP sources.
  name: Enterprise Data Warehousing
- description: Execute Business Explorer queries programmatically with filtering, hierarchies, and key figure calculations.
  name: BEx Query Execution
- description: Access SAP BW data through standard OData REST services for modern application integration.
  name: OData Query Access
- description: Automate and monitor ETL process chains for scheduled data loading and transformation.
  name: Process Chain Management
- description: Programmatic access to InfoProvider metadata, hierarchies, and data model definitions.
  name: Metadata Services
image: /assets/icons/sap-bw.png
integrations:
- description: Integration with SAP Analytics Cloud for modern analytics and planning on BW data.
  name: SAP Analytics Cloud
- description: Native HANA optimization for SAP BW/4HANA with in-memory data processing.
  name: SAP HANA
- description: Analysis for Office integration for enterprise reporting directly in Excel.
  name: Microsoft Excel
- description: Data pipeline integration for connecting BW with data lakes and machine learning workloads.
  name: SAP Data Intelligence
layout: provider
modified: '2026-04-18'
name: SAP BW
skills: []
slug: sap-bw
solutions: []
source_yaml: "aid: sap-bw\nname: SAP BW\ndescription: >-\n  SAP Business Warehouse (SAP BW) and SAP BW/4HANA provide enterprise data\n  warehousing capabilities with APIs for data extraction, query execution,\n  metadata management, and integration with SAP and non-SAP systems. The\n  platform offers OData services, BAPI/RFC interfaces, and Analysis Office\n  APIs for programmatic access to data warehouse operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sap-bw/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Business Intelligence\n  - Data Warehousing\n  - Enterprise\n  - ETL\n  - SAP\napis:\n  - aid: sap-bw:odata-api\n    name: SAP BW OData API\n    description: >-\n      OData-based REST API for querying SAP BW data, executing BEx queries,\n      and accessing InfoProviders. Supports analytical queries with\
  \ filtering,\n      aggregation, and hierarchical navigation.\n    humanURL: https://help.sap.com/docs/SAP_BW4HANA\n    baseURL: https://sap-host/sap/opu/odata/sap/\n    tags:\n      - Analytics\n      - OData\n      - Queries\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BW4HANA\n  - aid: sap-bw:bapi-api\n    name: SAP BW BAPI/RFC API\n    description: >-\n      Business Application Programming Interfaces (BAPIs) and Remote Function\n      Call (RFC) interfaces for SAP BW providing access to metadata management,\n      data loading, process chain execution, and administrative operations.\n    humanURL: https://help.sap.com/docs/SAP_BW4HANA\n    baseURL: https://sap-host/sap/bc/\n    tags:\n      - BAPI\n      - Enterprise\n      - Metadata\n      - RFC\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BW4HANA\n  - aid: sap-bw:analysis-office-api\n    name: SAP Analysis for Office API\n  \
  \  description: >-\n      API for SAP Analysis for Microsoft Office providing programmatic control\n      of analytical workbooks, data source connections, and report automation\n      within Excel and PowerPoint.\n    humanURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_ANALYSIS_OFFICE\n    baseURL: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_ANALYSIS_OFFICE\n    tags:\n      - Analysis\n      - Excel\n      - Office Integration\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_ANALYSIS_OFFICE\ncommon:\n  - type: Portal\n    url: https://help.sap.com/docs/SAP_BW4HANA\n  - type: Documentation\n    url: https://help.sap.com/docs/SAP_BW4HANA\n  - type: GettingStarted\n    url: https://learning.sap.com/\n  - type: Support\n    url: https://support.sap.com/\n  - type: Blog\n    url: https://community.sap.com/topics/bw\n  - type: TermsOfService\n    url: https://www.sap.com/about/legal/terms-of-use.html\n  - type:\
  \ PrivacyPolicy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: Training\n    url: https://learning.sap.com/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/sap-bw\n  - type: Features\n    data:\n      - name: Enterprise Data Warehousing\n        description: Centralized data warehousing with support for structured and unstructured data across SAP and non-SAP sources.\n      - name: BEx Query Execution\n        description: Execute Business Explorer queries programmatically with filtering, hierarchies, and key figure calculations.\n      - name: OData Query Access\n        description: Access SAP BW data through standard OData REST services for modern application integration.\n      - name: Process Chain Management\n        description: Automate and monitor ETL process chains for scheduled data loading and transformation.\n      - name: Metadata Services\n        description: Programmatic access to InfoProvider metadata, hierarchies, and\
  \ data model definitions.\n  - type: UseCases\n    data:\n      - name: Enterprise Reporting\n        description: Build enterprise reports and dashboards connecting to SAP BW data through OData and BAPI interfaces.\n      - name: Data Integration\n        description: Extract and load data between SAP BW and external systems using API-based integration.\n      - name: Automated ETL Workflows\n        description: Automate data warehouse loading processes with API-triggered process chain execution.\n      - name: Self-Service Analytics\n        description: Enable business users to access BW data through Analysis for Office API integrations.\n  - type: Integrations\n    data:\n      - name: SAP Analytics Cloud\n        description: Integration with SAP Analytics Cloud for modern analytics and planning on BW data.\n      - name: SAP HANA\n        description: Native HANA optimization for SAP BW/4HANA with in-memory data processing.\n      - name: Microsoft Excel\n        description: Analysis\
  \ for Office integration for enterprise reporting directly in Excel.\n      - name: SAP Data Intelligence\n        description: Data pipeline integration for connecting BW with data lakes and machine learning workloads.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-bw/refs/heads/main/apis.yml
tags:
- Business Intelligence
- Data Warehousing
- Enterprise
- ETL
- SAP
url: https://raw.githubusercontent.com/api-evangelist/sap-bw/refs/heads/main/apis.yml
use_cases:
- description: Build enterprise reports and dashboards connecting to SAP BW data through OData and BAPI interfaces.
  name: Enterprise Reporting
- description: Extract and load data between SAP BW and external systems using API-based integration.
  name: Data Integration
- description: Automate data warehouse loading processes with API-triggered process chain execution.
  name: Automated ETL Workflows
- description: Enable business users to access BW data through Analysis for Office API integrations.
  name: Self-Service Analytics
---
