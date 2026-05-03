---
api_count: 4
api_specs:
- filename: workday-report-writer-raas-openapi.yml
  format: yaml
  label: Workday Report-as-a-Service (RaaS) REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/openapi/workday-report-writer-raas-openapi.yml
- filename: workday-report-writer-wql-openapi.yml
  format: yaml
  label: Workday WQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/openapi/workday-report-writer-wql-openapi.yml
- filename: workday-report-writer-prism-analytics-openapi.yml
  format: yaml
  label: Workday Prism Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/openapi/workday-report-writer-prism-analytics-openapi.yml
apis:
- description: SOAP web service API for creating, managing, and executing custom reports in Workday using Report Writer functionality. Provides programmatic access to report definitions, calculated fields, and repor
  name: Workday Report Writer API
  slug: ''
- description: 'REST API that exposes custom Workday reports as web service endpoints. Advanced-type reports enabled as web services can be consumed via RESTful endpoints, returning data in JSON, CSV, XML, and other '
  name: Workday Report-as-a-Service (RaaS) REST API
  slug: ''
- description: Workday Query Language (WQL) API enabling SQL-like querying of Workday data through REST endpoints. Allows developers to construct queries using SELECT, FROM, WHERE, ORDER BY, and LIMIT syntax to retr
  name: Workday WQL API
  slug: ''
- description: 'REST API for working with Workday Prism Analytics tables, datasets, and data change tasks. Enables programmatic loading of external data into Prism Analytics for advanced reporting and analytics that '
  name: Workday Prism Analytics API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.workday.com/about
- title: ''
  type: GettingStarted
  url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/KfHiRHLBJB0O63TxIyZCFA
- title: ''
  type: Documentation
  url: https://community.workday.com/api
- title: ''
  type: Authentication
  url: https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html
- title: ''
  type: Sandbox
  url: https://community.workday.com/articles/6394
- title: ''
  type: Hub
  url: https://community.workday.com/
- title: ''
  type: RateLimits
  url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/a3a_TL5Tde61ZFJKLtycjg
- title: ''
  type: TermsOfService
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: PrivacyPolicy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: StatusPage
  url: https://community.workday.com/trust/status
- title: ''
  type: Support
  url: https://www.workday.com/en-us/services/support.html
- title: ''
  type: Blog
  url: https://blog.workday.com/en-us/technology.html
- title: ''
  type: SignUp
  url: https://resourcecenter.workday.com/
- title: ''
  type: Console
  url: https://developer.workday.com/about
- title: ''
  type: GitHubOrganization
  url: https://github.com/Workday
- title: ''
  type: APIReference
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html
created: '2024-01-01'
description: APIs for Workday Report Writer - a tool for creating custom reports and data extracts from Workday HCM and Financial systems.
features:
- description: Build custom reports using Report Writer with calculated fields, subfilters, and grouping across HCM and Financial Management data.
  name: Custom Report Authoring
- description: Expose any advanced custom report as a REST or SOAP web service returning JSON, CSV, XML, or RSS for programmatic consumption.
  name: Report-as-a-Service Web Endpoints
- description: Query Workday data with SQL-like SELECT/FROM/WHERE/ORDER BY/LIMIT syntax against governed data sources for high-performance retrieval.
  name: SQL-Like Data Access via WQL
- description: Programmatically create tables, upload compressed files via buckets, and run data change tasks (insert, update, upsert, delete) in Prism.
  name: External Data Loading with Prism Analytics
- description: Secure access to REST endpoints using OAuth 2.0 client credentials, refresh tokens, and bearer tokens managed through API client setup.
  name: OAuth 2.0 Authentication
- description: Retrieve report data in JSON, CSV, XML, RSS, and other formats with query parameter control over filtering, prompts, and pagination.
  name: Multi-Format Output
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Land Workday RaaS and WQL extracts into Snowflake stages for use in enterprise data warehouse pipelines.
  name: Snowflake
- description: Ingest Workday report data into Databricks for analytics, ML feature engineering, and lakehouse modeling.
  name: Databricks
- description: Connect Tableau to RaaS endpoints or downstream warehouses to build interactive dashboards on Workday HCM and financial data.
  name: Tableau
- description: Use RaaS JSON or CSV outputs as data sources for Microsoft Power BI reports and semantic models.
  name: Power BI
- description: Orchestrate Workday API calls in iPaaS workflows that move data between Workday and third-party SaaS applications.
  name: Workato
- description: Build integration pipelines using SnapLogic's Workday Snap Pack to read RaaS, WQL, and Prism endpoints.
  name: SnapLogic
- description: Connect Workday APIs to ERP, CRM, and HRIS systems through Boomi AtomSphere integration processes.
  name: Boomi
layout: provider
modified: '2026-05-03'
name: Workday Report Writer
skills: []
slug: workday-report-writer
solutions:
- description: End-to-end workforce and people analytics built on Report Writer, RaaS, and WQL across the Workday HCM suite.
  name: HCM Reporting
- description: Custom financial reporting and extracts spanning ledgers, projects, procurement, and revenue across Workday Financial Management.
  name: Financial Management Reporting
- description: Bring external data into Workday and combine with native data sets to deliver advanced analytics and self-service reporting.
  name: Prism Analytics
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-report-writer\nname: Workday Report Writer\ndescription: >-\n  APIs for Workday Report Writer - a tool for creating custom reports and data extracts\n  from Workday HCM and Financial systems.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Enterprise\n  - Erp\n  - Financials\n  - Hrms\n  - Reporting\n  - Saas\napis:\n  - name: Workday Report Writer API\n    description: >-\n      SOAP web service API for creating, managing, and executing custom reports in\n      Workday using Report Writer functionality. Provides programmatic access to\n      report definitions, calculated fields, and report output across HCM and\n      Financial Management modules.\n    image: https://www.workday.com/content/dam/web/images/logo.svg\n \
  \   humanURL: https://www.workday.com/en-us/products/financial-management/reporting-analytics.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service\n    tags:\n      - Analytics\n      - Custom Reports\n      - Data Extraction\n      - Reports\n      - SOAP\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: APIReference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v41.0/Report_as_a_Service.html\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://www.workday.com/en-us/company/contact-us.html\n  - name: Workday Report-as-a-Service (RaaS) REST API\n    description: >-\n      REST API that exposes custom Workday reports as web service\
  \ endpoints.\n      Advanced-type reports enabled as web services can be consumed via RESTful\n      endpoints, returning data in JSON, CSV, XML, and other formats. Supports\n      query parameters for report prompts and filtering.\n    image: https://www.workday.com/content/dam/web/images/logo.svg\n    humanURL: https://community.workday.com/api\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/customreport2\n    tags:\n      - Custom Reports\n      - Data Export\n      - Report as a Service\n      - Reports\n      - REST\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/api\n      - type: OpenAPI\n        url: openapi/workday-report-writer-raas-openapi.yml\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html\n      - type: SDK\n        url: https://github.com/Workday/raas-python\n        title: Python SDK\n      - type: CLI\n        url: https://github.com/Workday/raas-python\n\
  \        title: RaaS Python CLI\n      - type: GitHubRepository\n        url: https://github.com/Workday/raas-python\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://www.workday.com/en-us/company/contact-us.html\n  - name: Workday WQL API\n    description: >-\n      Workday Query Language (WQL) API enabling SQL-like querying of Workday data\n      through REST endpoints. Allows developers to construct queries using SELECT,\n      FROM, WHERE, ORDER BY, and LIMIT syntax to retrieve report data with high\n      performance, controlled via OAuth 2.0 tokens.\n    image: https://www.workday.com/content/dam/web/images/logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/wql\n    tags:\n      - Analytics\n      - Data Access\n      - Query Language\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n\
  \      - type: OpenAPI\n        url: openapi/workday-report-writer-wql-openapi.yml\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://www.workday.com/en-us/company/contact-us.html\n  - name: Workday Prism Analytics API\n    description: >-\n      REST API for working with Workday Prism Analytics tables, datasets, and data\n      change tasks. Enables programmatic loading of external data into Prism\n      Analytics for advanced reporting and analytics that combines internal Workday\n      data with external sources.\n    image: https://www.workday.com/content/dam/web/images/logo.svg\n    humanURL: https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/prismAnalytics\n    tags:\n      - Analytics\n      - Data Loading\n\
  \      - Datasets\n      - Prism Analytics\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html\n      - type: OpenAPI\n        url: openapi/workday-report-writer-prism-analytics-openapi.yml\n      - type: JSONSchema\n        url: json-schema/workday-report-writer-prism-table-schema.json\n        title: Prism Table Schema Definition\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html\n      - type: SDK\n        url: https://github.com/Workday/prism-python\n        title: Python SDK\n      - type: CLI\n        url: https://github.com/Workday/prism-python\n        title: Prism Python CLI\n      - type: GitHubRepository\n        url: https://github.com/Workday/prism-python\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://www.workday.com/en-us/company/contact-us.html\n\
  common:\n  - type: Portal\n    url: https://developer.workday.com/about\n  - type: GettingStarted\n    url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/KfHiRHLBJB0O63TxIyZCFA\n  - type: Documentation\n    url: https://community.workday.com/api\n  - type: Authentication\n    url: https://doc.workday.com/admin-guide/en-us/workday-api/authentication/index.html\n  - type: Sandbox\n    url: https://community.workday.com/articles/6394\n  - type: Hub\n    url: https://community.workday.com/\n  - type: RateLimits\n    url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/a3a_TL5Tde61ZFJKLtycjg\n  - type: TermsOfService\n    url: https://www.workday.com/en-us/legal.html\n  - type: PrivacyPolicy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: StatusPage\n    url: https://community.workday.com/trust/status\n  - type: Support\n    url: https://www.workday.com/en-us/services/support.html\n  - type: Blog\n    url: https://blog.workday.com/en-us/technology.html\n  - type:\
  \ SignUp\n    url: https://resourcecenter.workday.com/\n  - type: Console\n    url: https://developer.workday.com/about\n  - type: GitHubOrganization\n    url: https://github.com/Workday\n  - type: APIReference\n    url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n  - type: Features\n    data:\n      - name: Custom Report Authoring\n        description: >-\n          Build custom reports using Report Writer with calculated fields,\n          subfilters, and grouping across HCM and Financial Management data.\n      - name: Report-as-a-Service Web Endpoints\n        description: >-\n          Expose any advanced custom report as a REST or SOAP web service\n          returning JSON, CSV, XML, or RSS for programmatic consumption.\n      - name: SQL-Like Data Access via WQL\n        description: >-\n          Query Workday data with SQL-like SELECT/FROM/WHERE/ORDER BY/LIMIT\n          syntax against governed data sources for high-performance retrieval.\n\
  \      - name: External Data Loading with Prism Analytics\n        description: >-\n          Programmatically create tables, upload compressed files via buckets,\n          and run data change tasks (insert, update, upsert, delete) in Prism.\n      - name: OAuth 2.0 Authentication\n        description: >-\n          Secure access to REST endpoints using OAuth 2.0 client credentials,\n          refresh tokens, and bearer tokens managed through API client setup.\n      - name: Multi-Format Output\n        description: >-\n          Retrieve report data in JSON, CSV, XML, RSS, and other formats with\n          query parameter control over filtering, prompts, and pagination.\n  - type: UseCases\n    data:\n      - name: HR Analytics and Workforce Reporting\n        description: >-\n          Extract headcount, compensation, and turnover metrics from Workday\n          HCM for downstream analytics, dashboards, and board reporting.\n      - name: Financial Reporting and Close\n        description:\
  \ >-\n          Pull custom financial reports for general ledger, accounts payable,\n          and budget variance analysis in support of period close processes.\n      - name: Data Warehouse and Lake Hydration\n        description: >-\n          Schedule RaaS or WQL extracts to feed Snowflake, BigQuery, Redshift,\n          Databricks, or other downstream systems with Workday data.\n      - name: External Data Blending in Prism\n        description: >-\n          Load external CSV or Parquet datasets into Prism Analytics tables to\n          combine with native Workday data for cross-source reporting.\n      - name: Operational Integrations\n        description: >-\n          Drive payroll vendors, benefits providers, and identity systems with\n          scheduled report extracts derived from Workday source-of-truth data.\n      - name: Compliance and Audit Reporting\n        description: >-\n          Generate audit-ready extracts of personnel actions, journal entries,\n          and\
  \ security configurations for regulatory and SOX compliance.\n  - type: Integrations\n    data:\n      - name: Snowflake\n        description: >-\n          Land Workday RaaS and WQL extracts into Snowflake stages for use in\n          enterprise data warehouse pipelines.\n      - name: Databricks\n        description: >-\n          Ingest Workday report data into Databricks for analytics, ML feature\n          engineering, and lakehouse modeling.\n      - name: Tableau\n        description: >-\n          Connect Tableau to RaaS endpoints or downstream warehouses to build\n          interactive dashboards on Workday HCM and financial data.\n      - name: Power BI\n        description: >-\n          Use RaaS JSON or CSV outputs as data sources for Microsoft Power BI\n          reports and semantic models.\n      - name: Workato\n        description: >-\n          Orchestrate Workday API calls in iPaaS workflows that move data\n          between Workday and third-party SaaS applications.\n\
  \      - name: SnapLogic\n        description: >-\n          Build integration pipelines using SnapLogic's Workday Snap Pack to\n          read RaaS, WQL, and Prism endpoints.\n      - name: Boomi\n        description: >-\n          Connect Workday APIs to ERP, CRM, and HRIS systems through Boomi\n          AtomSphere integration processes.\n  - type: Solutions\n    data:\n      - name: HCM Reporting\n        description: >-\n          End-to-end workforce and people analytics built on Report Writer,\n          RaaS, and WQL across the Workday HCM suite.\n      - name: Financial Management Reporting\n        description: >-\n          Custom financial reporting and extracts spanning ledgers, projects,\n          procurement, and revenue across Workday Financial Management.\n      - name: Prism Analytics\n        description: >-\n          Bring external data into Workday and combine with native data sets\n          to deliver advanced analytics and self-service reporting.\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/apis.yml
tags:
- Analytics
- Enterprise
- Erp
- Financials
- Hrms
- Reporting
- Saas
url: https://raw.githubusercontent.com/api-evangelist/workday-report-writer/refs/heads/main/apis.yml
use_cases:
- description: Extract headcount, compensation, and turnover metrics from Workday HCM for downstream analytics, dashboards, and board reporting.
  name: HR Analytics and Workforce Reporting
- description: Pull custom financial reports for general ledger, accounts payable, and budget variance analysis in support of period close processes.
  name: Financial Reporting and Close
- description: Schedule RaaS or WQL extracts to feed Snowflake, BigQuery, Redshift, Databricks, or other downstream systems with Workday data.
  name: Data Warehouse and Lake Hydration
- description: Load external CSV or Parquet datasets into Prism Analytics tables to combine with native Workday data for cross-source reporting.
  name: External Data Blending in Prism
- description: Drive payroll vendors, benefits providers, and identity systems with scheduled report extracts derived from Workday source-of-truth data.
  name: Operational Integrations
- description: Generate audit-ready extracts of personnel actions, journal entries, and security configurations for regulatory and SOX compliance.
  name: Compliance and Audit Reporting
---
