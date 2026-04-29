---
api_count: 6
api_specs:
- filename: power-bi-rest-api-openapi.yml
  format: yaml
  label: Power BI REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/power-bi/refs/heads/main/openapi/power-bi-rest-api-openapi.yml
apis:
- description: The Power BI REST API provides service endpoints for embedding, administration, governance, and user resources.
  name: Power BI REST API
  slug: ''
- description: Azure service that enables ISVs and developers to embed Power BI visuals, reports, and dashboards into their applications.
  name: Power BI Embedded
  slug: ''
- description: API for managing Power BI capacity, workspaces, and tenant settings.
  name: Power BI Management API
  slug: ''
- description: The Push Datasets API enables real-time data streaming by allowing applications to create push datasets and post rows of data directly into Power BI datasets.
  name: Power BI Push Datasets API
  slug: ''
- description: The Power BI Report Server REST API provides programmatic access to report server catalog objects such as folders, reports, KPIs, data sources, datasets, refresh plans, and subscriptions.
  name: Power BI Report Server REST API
  slug: ''
- description: The Power BI Visuals API enables developers to create custom visuals that can be used in Power BI reports and dashboards, extending the built-in visualization capabilities.
  name: Power BI Visuals API
  slug: ''
capabilities:
- description: Unified workflow for Power BI analytics operations including dataset management, report creation and distribution, dashboard monitoring, workspace administration, and gateway configuration. Used by BI
  name: Power BI Analytics and Reporting
  slug: analytics-and-reporting
common:
- title: ''
  type: Portal
  url: https://app.powerbi.com
- title: ''
  type: DeveloperPortal
  url: https://powerbi.microsoft.com/en-us/developers/
- title: ''
  type: Blog
  url: https://powerbi.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://powerbi.microsoft.com/en-us/support/
- title: ''
  type: StatusPage
  url: https://powerbi.microsoft.com/en-us/status/
- title: ''
  type: TermsOfService
  url: https://powerbi.microsoft.com/en-us/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHubRepository
  url: https://github.com/Microsoft/PowerBI-JavaScript
- title: Developer Samples
  type: GitHubRepository
  url: https://github.com/microsoft/PowerBI-Developer-Samples
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/showcase/microsoft-power-bi/
- title: ''
  type: X
  url: https://twitter.com/MSPowerBI
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/mspowerbi
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-bi/
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/power-platform/products/power-bi/pricing
- title: ''
  type: SignUp
  url: https://app.powerbi.com/signupredirect?pbi_source=web
- title: ''
  type: Login
  url: https://app.powerbi.com/signin
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/power-bi/fundamentals/whats-new
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/powerbi
- title: ''
  type: JSONLD
  url: json-ld/power-bi-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/power-bi-dataset-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/power-bi-report-schema.json
- title: .NET SDK
  type: SDK
  url: https://github.com/microsoft/PowerBI-CSharp
created: '2024'
description: Microsoft Power BI is a business analytics service that delivers insights to enable fast, informed decisions. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards.
features:
- description: Create and share interactive dashboards with real-time data visualizations and drill-down capabilities.
  name: Interactive Dashboards
- description: Ask questions about your data in plain English and get instant visualizations with Q&A.
  name: Natural Language Queries
- description: Connect to hundreds of data sources including databases, cloud services, files, and streaming data.
  name: Data Connectivity
- description: Embed Power BI reports and dashboards into custom applications using REST APIs and JavaScript SDK.
  name: Embedded Analytics
- description: Create pixel-perfect, print-ready reports designed for printing or PDF generation.
  name: Paginated Reports
- description: Push real-time data to dashboards with streaming datasets and live tile updates.
  name: Real-Time Streaming
- description: Control data access at the row level based on user identity and roles.
  name: Row-Level Security
- description: Self-service data preparation with Power Query Online for creating reusable data transformation logic.
  name: Dataflows
image: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png
integrations:
- description: View and interact with Power BI reports directly within Microsoft Teams channels and chats.
  name: Microsoft Teams
- description: Analyze Power BI datasets in Excel with connected tables and PivotTables.
  name: Excel
- description: Embed Power BI reports in SharePoint Online pages for enterprise-wide distribution.
  name: SharePoint
- description: Connect to Azure Synapse workspaces for big data analytics and data warehousing.
  name: Azure Synapse Analytics
- description: Pre-built analytics templates and data connectors for Dynamics 365 business applications.
  name: Dynamics 365
- description: Trigger automated workflows based on Power BI data alerts and refresh events.
  name: Power Automate
- description: Enterprise authentication and authorization with Azure AD for secure API access.
  name: Azure Active Directory
- description: Connect to Salesforce data with native connectors for CRM analytics and reporting.
  name: Salesforce
jsonld:
- class_count: 0
  name: Power Bi Context
  property_count: 15
  slug: power-bi-context
- class_count: 0
  name: Power Bi Rest Context
  property_count: 0
  slug: power-bi-rest-context
layout: provider
modified: '2026-04-18'
name: Power BI
rules:
- name: Power BI API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: power-bi-spectral-rules
skills: []
slug: power-bi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Power BI\ndescription: Microsoft Power BI is a business analytics service that delivers insights to enable fast, informed decisions. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards.\nimage: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png\nurl: https://powerbi.microsoft.com\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Analytics\n  - Business Intelligence\n  - Dashboards\n  - Data Analysis\n  - Reporting\n  - Visualization\napis:\n  - name: Power BI REST API\n    description: The Power BI REST API provides service endpoints for embedding, administration, governance, and user resources.\n    image: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png\n    humanURL: https://docs.microsoft.com/en-us/rest/api/power-bi/\n\
  \    baseURL: https://api.powerbi.com\n    tags:\n      - Dashboards\n      - Datasets\n      - Embeddings\n      - Reports\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/power-bi/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/powerbi/data-plane/Microsoft.PowerBI/stable/v1.0/powerbi.json\n      - type: OpenAPI\n        url: openapi/power-bi-rest-api-openapi.yml\n      - type: JSONLD\n        url: json-ld/power-bi-rest-context.jsonld\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/power-bi/developer/embedded/get-azuread-access-token\n      - type: GettingStarted\n        url: https://docs.microsoft.com/en-us/power-bi/developer/embedded/embedding-content\n      - type: RateLimits\n        url: https://docs.microsoft.com/en-us/power-bi/developer/automation/api-rest-api-limitations\n      - type: SDK\n        url: https://docs.microsoft.com/en-us/javascript/api/overview/powerbi/\n\
  \        title: JavaScript SDK\n      - type: ChangeLog\n        url: https://docs.microsoft.com/en-us/power-bi/developer/embedded/embedded-analytics-power-bi-changelog\n      - type: Troubleshooting\n        url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/troubleshoot-rest-api\n  - name: Power BI Embedded\n    description: Azure service that enables ISVs and developers to embed Power BI visuals, reports, and dashboards into their applications.\n    image: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png\n    humanURL: https://azure.microsoft.com/en-us/services/power-bi-embedded/\n    baseURL: https://api.powerbi.com\n    tags:\n      - Azure\n      - Embedded\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-bi/developer/embedded/\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/power-bi-embedded/\n      - type: Sandbox\n        url:\
  \ https://playground.powerbi.com/\n      - type: CodeExamples\n        url: https://github.com/Microsoft/PowerBI-Developer-Samples\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/power-bi-embedded/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/embed-organization-app\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/embed-tokens\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/javascript/api/overview/powerbi/embedded-analytics-client-api\n        title: JavaScript SDK\n      - type: SDK\n        url: https://github.com/microsoft/PowerBI-CSharp\n        title: .NET SDK\n  - name: Power BI Management API\n    description: API for managing Power BI capacity, workspaces, and tenant settings.\n    image: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png\n    humanURL: https://docs.microsoft.com/en-us/rest/api/power-bi/admin\n\
  \    baseURL: https://api.powerbi.com/v1.0/myorg/admin\n    tags:\n      - Administration\n      - Governance\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/power-bi/admin\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/power-bi/admin/service-admin-reference\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-bi/admin/service-admin-health\n  - name: Power BI Push Datasets API\n    description: The Push Datasets API enables real-time data streaming by allowing applications to create push datasets and post rows of data directly into Power BI datasets.\n    image: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/power-bi/push-datasets\n    baseURL: https://api.powerbi.com\n    tags:\n      - Datasets\n      - Push\n      - Real-Time\n      - Streaming\n    properties:\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-bi/push-datasets\n      - type: RateLimits\n        url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/push-datasets-limitations\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/get-azuread-access-token\n  - name: Power BI Report Server REST API\n    description: The Power BI Report Server REST API provides programmatic access to report server catalog objects such as folders, reports, KPIs, data sources, datasets, refresh plans, and subscriptions.\n    image: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/power-bi-report/\n    baseURL: https://api.powerbi.com\n    tags:\n      - On-Premises\n      - Report Server\n      - Reports\n      - SSRS\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-bi-report/\n\
  \      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-bi/report-server/rest-api\n      - type: ChangeLog\n        url: https://learn.microsoft.com/en-us/power-bi/report-server/changelog\n      - type: ReleaseNotes\n        url: https://learn.microsoft.com/en-us/power-bi/report-server/whats-new\n  - name: Power BI Visuals API\n    description: The Power BI Visuals API enables developers to create custom visuals that can be used in Power BI reports and dashboards, extending the built-in visualization capabilities.\n    image: https://powerbi.microsoft.com/pictures/shared/social/social-default-image.png\n    humanURL: https://learn.microsoft.com/en-us/power-bi/developer/visuals/\n    baseURL: https://api.powerbi.com\n    tags:\n      - Charts\n      - Custom Visuals\n      - Visualization\n      - Visuals\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-bi/developer/visuals/\n      - type: APIReference\n    \
  \    url: https://learn.microsoft.com/en-us/power-bi/developer/visuals/visual-api\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-bi/developer/visuals/develop-power-bi-visuals\n      - type: ChangeLog\n        url: https://learn.microsoft.com/en-us/power-bi/developer/visuals/changelog\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-bi/developer/visuals/authentication-api\ncommon:\n  - type: Portal\n    url: https://app.powerbi.com\n  - type: DeveloperPortal\n    url: https://powerbi.microsoft.com/en-us/developers/\n  - type: Blog\n    url: https://powerbi.microsoft.com/en-us/blog/\n  - type: Support\n    url: https://powerbi.microsoft.com/en-us/support/\n  - type: StatusPage\n    url: https://powerbi.microsoft.com/en-us/status/\n  - type: TermsOfService\n    url: https://powerbi.microsoft.com/en-us/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GitHubRepository\n\
  \    url: https://github.com/Microsoft/PowerBI-JavaScript\n  - type: GitHubRepository\n    url: https://github.com/microsoft/PowerBI-Developer-Samples\n    title: Developer Samples\n  - type: LinkedIn\n    url: https://www.linkedin.com/showcase/microsoft-power-bi/\n  - type: X\n    url: https://twitter.com/MSPowerBI\n  - type: YouTube\n    url: https://www.youtube.com/user/mspowerbi\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-bi/\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/power-platform/products/power-bi/pricing\n  - type: SignUp\n    url: https://app.powerbi.com/signupredirect?pbi_source=web\n  - type: Login\n    url: https://app.powerbi.com/signin\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/power-bi/fundamentals/whats-new\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/powerbi\n  - type: JSONLD\n    url: json-ld/power-bi-context.jsonld\n  - type: JSONSchema\n    url: json-schema/power-bi-dataset-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/power-bi-report-schema.json\n  - type: SDK\n    url: https://github.com/microsoft/PowerBI-CSharp\n    title: .NET SDK\n  - type: Features\n    data:\n      - name: Interactive Dashboards\n        description: Create and share interactive dashboards with real-time data visualizations and drill-down capabilities.\n      - name: Natural Language Queries\n        description: Ask questions about your data in plain English and get instant visualizations with Q&A.\n      - name: Data Connectivity\n        description: Connect to hundreds of data sources including databases, cloud services, files, and streaming data.\n      - name: Embedded Analytics\n        description: Embed Power BI reports and dashboards into custom applications using REST APIs and JavaScript SDK.\n      - name: Paginated Reports\n        description: Create pixel-perfect, print-ready reports designed for printing or PDF generation.\n      - name: Real-Time Streaming\n        description:\
  \ Push real-time data to dashboards with streaming datasets and live tile updates.\n      - name: Row-Level Security\n        description: Control data access at the row level based on user identity and roles.\n      - name: Dataflows\n        description: Self-service data preparation with Power Query Online for creating reusable data transformation logic.\n  - type: UseCases\n    data:\n      - name: Executive Dashboards\n        description: Provide C-suite executives with real-time KPI dashboards for data-driven decision making.\n      - name: Sales Analytics\n        description: Track sales performance, pipeline metrics, and revenue forecasting with interactive reports.\n      - name: Financial Reporting\n        description: Automate financial reporting with scheduled refreshes and pixel-perfect paginated reports.\n      - name: Embedded Analytics for ISVs\n        description: Embed Power BI visualizations into SaaS applications to provide analytics to end customers.\n      - name:\
  \ IoT Monitoring\n        description: Visualize real-time IoT sensor data with streaming datasets and live dashboard tiles.\n      - name: HR Analytics\n        description: Analyze workforce metrics, retention rates, and employee engagement across the organization.\n  - type: Integrations\n    data:\n      - name: Microsoft Teams\n        description: View and interact with Power BI reports directly within Microsoft Teams channels and chats.\n      - name: Excel\n        description: Analyze Power BI datasets in Excel with connected tables and PivotTables.\n      - name: SharePoint\n        description: Embed Power BI reports in SharePoint Online pages for enterprise-wide distribution.\n      - name: Azure Synapse Analytics\n        description: Connect to Azure Synapse workspaces for big data analytics and data warehousing.\n      - name: Dynamics 365\n        description: Pre-built analytics templates and data connectors for Dynamics 365 business applications.\n      - name: Power\
  \ Automate\n        description: Trigger automated workflows based on Power BI data alerts and refresh events.\n      - name: Azure Active Directory\n        description: Enterprise authentication and authorization with Azure AD for secure API access.\n      - name: Salesforce\n        description: Connect to Salesforce data with native connectors for CRM analytics and reporting.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/power-bi/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Analysis
- Reporting
- Visualization
url: https://powerbi.microsoft.com
use_cases:
- description: Provide C-suite executives with real-time KPI dashboards for data-driven decision making.
  name: Executive Dashboards
- description: Track sales performance, pipeline metrics, and revenue forecasting with interactive reports.
  name: Sales Analytics
- description: Automate financial reporting with scheduled refreshes and pixel-perfect paginated reports.
  name: Financial Reporting
- description: Embed Power BI visualizations into SaaS applications to provide analytics to end customers.
  name: Embedded Analytics for ISVs
- description: Visualize real-time IoT sensor data with streaming datasets and live dashboard tiles.
  name: IoT Monitoring
- description: Analyze workforce metrics, retention rates, and employee engagement across the organization.
  name: HR Analytics
---
