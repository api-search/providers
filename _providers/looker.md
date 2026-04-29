---
api_count: 6
apis:
- description: The Looker API provides programmatic access to Looker functionality including running queries, managing users, creating dashboards, and administering the platform.
  name: Looker API
  slug: api
- description: API for programmatically managing LookML projects, models, and views.
  name: LookML API
  slug: lookml
- description: The Looker Action API enables developers to define custom actions, or destinations, to which Looker can send query results, dashboard results, or user interactions via a webhook-like API.
  name: Looker Action API
  slug: action
- description: The Looker Embed SDK is a JavaScript library for embedding Looker content such as dashboards, Looks, Explores, reports, and extensions into web applications, with support for signed SSO and cookieless
  name: Looker Embed SDK
  slug: embed-sdk
- description: The Looker Extension Framework provides APIs and SDKs for building custom extensions that run inside the Looker UI, with access to the Looker API, Looker components library, and the Embed SDK.
  name: Looker Extension Framework API
  slug: extension-framework
- description: The Looker (Google Cloud core) REST API provides management capabilities for Looker instances running on Google Cloud, including instance lifecycle management, backups, and operations.
  name: Looker (Google Cloud core) API
  slug: google-cloud-core
capabilities:
- description: Unified workflow for business intelligence analytics including dashboards, looks, queries, and user management. Used by data analysts and BI administrators.
  name: Looker Analytics and Reporting
  slug: analytics-and-reporting
common:
- title: ''
  type: DeveloperPortal
  url: https://developers.looker.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/looker-open-source
- title: ''
  type: Support
  url: https://cloud.google.com/looker/docs/support
- title: ''
  type: StatusPage
  url: https://status.looker.com/
- title: ''
  type: PrivacyPolicy
  url: https://looker.com/privacy
- title: ''
  type: TermsOfService
  url: https://looker.com/terms
- title: ''
  type: SDK
  url: https://docs.cloud.google.com/looker/docs/api-sdk
- title: ''
  type: ChangeLog
  url: https://github.com/looker-open-source/sdk-codegen/blob/main/CHANGELOG.md
- title: ''
  type: ReleaseNotes
  url: https://docs.cloud.google.com/looker/docs/release-notes
- title: ''
  type: Pricing
  url: https://cloud.google.com/looker/pricing
- title: ''
  type: GettingStarted
  url: https://docs.cloud.google.com/looker/docs/api-getting-started
- title: ''
  type: Authentication
  url: https://docs.cloud.google.com/looker/docs/api-auth
- title: ''
  type: Tutorials
  url: https://developers.looker.com/api/tutorials/interactive-api-docs-whats-next/
- title: ''
  type: JSONSchema
  url: json-schema/looker-dashboard-schema.json
- title: ''
  type: JSONLD
  url: json-ld/looker-context.jsonld
- title: Looker API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/looker-api.yaml
- title: Analytics and Reporting Workflow
  type: NaftikoCapability
  url: capabilities/analytics-and-reporting.yaml
created: '2024-01-01'
description: Looker is a business intelligence and data analytics platform that enables organizations to explore, analyze, and share real-time business analytics.
features:
- description: Enable business users to explore data, build visualizations, and create dashboards without SQL knowledge using LookML models.
  name: Self-Service Analytics
- description: Define reusable data models in LookML that provide a semantic layer between databases and end-user analytics.
  name: Data Modeling with LookML
- description: Embed interactive dashboards, reports, and data explorations directly into web applications using SSO and cookieless authentication.
  name: Embedded Analytics
- description: Schedule and deliver reports and dashboards via email, Slack, S3, or custom action destinations.
  name: Scheduled Reports
- description: Build webhook-based actions to send query results to any external destination or trigger workflows.
  name: Custom Actions
- description: Programmatically manage users, roles, dashboards, queries, and platform settings through the Looker API.
  name: API-Driven Administration
image: https://looker.com/assets/img/images/logos/looker-logo.png
integrations:
- description: Native optimized connector for querying and analyzing data in Google BigQuery data warehouse.
  name: Google BigQuery
- description: High-performance connector for Snowflake cloud data warehouse with push-down query optimization.
  name: Snowflake
- description: Native connector for querying and visualizing data in Amazon Redshift data warehouse.
  name: Amazon Redshift
- description: Deliver scheduled reports and dashboard snapshots to Slack channels with interactive query capabilities.
  name: Slack
- description: Export query results and dashboard data directly to Google Sheets for collaborative analysis.
  name: Google Sheets
- description: Connect to Salesforce data for CRM analytics and combine with other data sources for unified views.
  name: Salesforce
jsonld:
- class_count: 0
  name: Looker Context
  property_count: 0
  slug: looker-context
layout: provider
modified: '2026-04-18'
name: Looker
rules:
- name: Looker API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: looker-spectral-rules
skills: []
slug: looker
solutions: []
source_yaml: "aid: looker\nname: Looker\ndescription: Looker is a business intelligence and data analytics platform that enables organizations to explore, analyze, and share real-time business analytics.\nimage: https://looker.com/assets/img/images/logos/looker-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/looker/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\ntags:\n  - Analytics\n  - BI Platform\n  - Business Intelligence\n  - Data Analytics\n  - Data Visualization\napis:\n  - aid: looker:api\n    name: Looker API\n    description: The Looker API provides programmatic access to Looker functionality including running queries, managing users, creating dashboards, and administering the platform.\n    image: https://looker.com/assets/img/images/logos/looker-logo.png\n    humanURL: https://developers.looker.com/api/explorer/4.0\n    baseURL: https://your-instance.looker.com:19999/api/4.0\n\
  \    tags:\n      - Analytics\n      - Dashboards\n      - Queries\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developers.looker.com/api/getting-started\n      - type: OpenAPI\n        url: openapi/looker-api-openapi.yml\n      - type: Authentication\n        url: https://developers.looker.com/api/getting-started#authentication\n      - type: SDK\n        url: https://developers.looker.com/api/sdks\n      - type: Console\n        url: https://developers.looker.com/api/explorer/4.0\n      - type: RateLimits\n        url: https://cloud.google.com/looker/docs/api-rate-limits\n      - type: APIReference\n        url: https://docs.cloud.google.com/looker/docs/reference/looker-api/latest\n      - type: GettingStarted\n        url: https://docs.cloud.google.com/looker/docs/api-getting-started\n      - type: Versioning\n        url: https://docs.cloud.google.com/looker/docs/api-versioning\n  - aid: looker:lookml\n    name: LookML API\n    description:\
  \ API for programmatically managing LookML projects, models, and views.\n    humanURL: https://developers.looker.com/api/explorer/4.0/methods/Project\n    baseURL: https://your-instance.looker.com:19999/api/4.0\n    tags:\n      - Data Modeling\n      - LookML\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://developers.looker.com/api/explorer/4.0/methods/Project\n      - type: Tutorials\n        url: https://developers.looker.com/api/lookml-validation\n  - aid: looker:action\n    name: Looker Action API\n    description: The Looker Action API enables developers to define custom actions, or destinations, to which Looker can send query results, dashboard results, or user interactions via a webhook-like API.\n    humanURL: https://docs.cloud.google.com/looker/docs/actions-overview\n    baseURL: https://your-instance.looker.com:19999/api/4.0\n    tags:\n      - Actions\n      - Data Delivery\n      - Integrations\n      - Webhooks\n    properties:\n   \
  \   - type: Documentation\n        url: https://docs.cloud.google.com/looker/docs/actions-overview\n      - type: GitHubRepository\n        url: https://github.com/looker-open-source/actions\n  - aid: looker:embed-sdk\n    name: Looker Embed SDK\n    description: The Looker Embed SDK is a JavaScript library for embedding Looker content such as dashboards, Looks, Explores, reports, and extensions into web applications, with support for signed SSO and cookieless authentication.\n    humanURL: https://docs.cloud.google.com/looker/docs/embed-sdk-intro\n    baseURL: https://your-instance.looker.com:19999/api/4.0\n    tags:\n      - Dashboards\n      - Embedding\n      - JavaScript SDK\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://docs.cloud.google.com/looker/docs/embed-sdk-intro\n      - type: GitHubRepository\n        url: https://github.com/looker-open-source/embed-sdk\n      - type: APIReference\n        url: https://looker-open-source.github.io/embed-sdk/\n\
  \  - aid: looker:extension-framework\n    name: Looker Extension Framework API\n    description: The Looker Extension Framework provides APIs and SDKs for building custom extensions that run inside the Looker UI, with access to the Looker API, Looker components library, and the Embed SDK.\n    humanURL: https://developers.looker.com/extensions/overview/\n    baseURL: https://your-instance.looker.com:19999/api/4.0\n    tags:\n      - Extensions\n      - JavaScript\n      - React\n      - UI Components\n    properties:\n      - type: Documentation\n        url: https://docs.cloud.google.com/looker/docs/intro-to-extension-framework\n      - type: CodeExamples\n        url: https://docs.cloud.google.com/looker/docs/extension-framework-react-and-js-code-examples\n  - aid: looker:google-cloud-core\n    name: Looker (Google Cloud core) API\n    description: The Looker (Google Cloud core) REST API provides management capabilities for Looker instances running on Google Cloud, including instance\
  \ lifecycle management, backups, and operations.\n    humanURL: https://cloud.google.com/looker/docs/reference/rest\n    baseURL: https://looker.googleapis.com/v1\n    tags:\n      - Backups\n      - Google Cloud\n      - Infrastructure\n      - Instance Management\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/looker/docs/reference/rest\n      - type: Console\n        url: https://console.cloud.google.com/apis/library/looker.googleapis.com\ncommon:\n  - type: DeveloperPortal\n    url: https://developers.looker.com/\n  - type: GitHubOrganization\n    url: https://github.com/looker-open-source\n  - type: Support\n    url: https://cloud.google.com/looker/docs/support\n  - type: StatusPage\n    url: https://status.looker.com/\n  - type: PrivacyPolicy\n    url: https://looker.com/privacy\n  - type: TermsOfService\n    url: https://looker.com/terms\n  - type: SDK\n    url: https://docs.cloud.google.com/looker/docs/api-sdk\n  - type: ChangeLog\n    url:\
  \ https://github.com/looker-open-source/sdk-codegen/blob/main/CHANGELOG.md\n  - type: ReleaseNotes\n    url: https://docs.cloud.google.com/looker/docs/release-notes\n  - type: Pricing\n    url: https://cloud.google.com/looker/pricing\n  - type: GettingStarted\n    url: https://docs.cloud.google.com/looker/docs/api-getting-started\n  - type: Authentication\n    url: https://docs.cloud.google.com/looker/docs/api-auth\n  - type: Tutorials\n    url: https://developers.looker.com/api/tutorials/interactive-api-docs-whats-next/\n  - type: JSONSchema\n    url: json-schema/looker-dashboard-schema.json\n  - type: JSONLD\n    url: json-ld/looker-context.jsonld\n  - type: NaftikoCapability\n    url: capabilities/shared/looker-api.yaml\n    title: Looker API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/analytics-and-reporting.yaml\n    title: Analytics and Reporting Workflow\n  - type: Features\n    data:\n      - name: Self-Service Analytics\n        description: Enable business\
  \ users to explore data, build visualizations, and create dashboards without SQL knowledge using LookML models.\n      - name: Data Modeling with LookML\n        description: Define reusable data models in LookML that provide a semantic layer between databases and end-user analytics.\n      - name: Embedded Analytics\n        description: Embed interactive dashboards, reports, and data explorations directly into web applications using SSO and cookieless authentication.\n      - name: Scheduled Reports\n        description: Schedule and deliver reports and dashboards via email, Slack, S3, or custom action destinations.\n      - name: Custom Actions\n        description: Build webhook-based actions to send query results to any external destination or trigger workflows.\n      - name: API-Driven Administration\n        description: Programmatically manage users, roles, dashboards, queries, and platform settings through the Looker API.\n  - type: UseCases\n    data:\n      - name: Executive\
  \ Dashboards\n        description: Build real-time executive dashboards aggregating KPIs from multiple data sources for leadership visibility.\n      - name: Customer-Facing Analytics\n        description: Embed analytics into SaaS products to provide customers with self-service reporting and data exploration.\n      - name: Data Governance Reporting\n        description: Monitor data quality, usage patterns, and access controls across the organization through audit reports.\n      - name: Marketing Performance Analytics\n        description: Analyze campaign performance, attribution, and ROI across marketing channels with unified data models.\n      - name: Operational Monitoring\n        description: Track operational metrics and KPIs in real time with automated alerting and scheduled report delivery.\n  - type: Integrations\n    data:\n      - name: Google BigQuery\n        description: Native optimized connector for querying and analyzing data in Google BigQuery data warehouse.\n \
  \     - name: Snowflake\n        description: High-performance connector for Snowflake cloud data warehouse with push-down query optimization.\n      - name: Amazon Redshift\n        description: Native connector for querying and visualizing data in Amazon Redshift data warehouse.\n      - name: Slack\n        description: Deliver scheduled reports and dashboard snapshots to Slack channels with interactive query capabilities.\n      - name: Google Sheets\n        description: Export query results and dashboard data directly to Google Sheets for collaborative analysis.\n      - name: Salesforce\n        description: Connect to Salesforce data for CRM analytics and combine with other data sources for unified views.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/looker/refs/heads/main/apis.yml
tags:
- Analytics
- BI Platform
- Business Intelligence
- Data Analytics
- Data Visualization
url: https://raw.githubusercontent.com/api-evangelist/looker/refs/heads/main/apis.yml
use_cases:
- description: Build real-time executive dashboards aggregating KPIs from multiple data sources for leadership visibility.
  name: Executive Dashboards
- description: Embed analytics into SaaS products to provide customers with self-service reporting and data exploration.
  name: Customer-Facing Analytics
- description: Monitor data quality, usage patterns, and access controls across the organization through audit reports.
  name: Data Governance Reporting
- description: Analyze campaign performance, attribution, and ROI across marketing channels with unified data models.
  name: Marketing Performance Analytics
- description: Track operational metrics and KPIs in real time with automated alerting and scheduled report delivery.
  name: Operational Monitoring
---
