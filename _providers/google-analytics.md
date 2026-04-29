---
api_count: 6
api_specs:
- filename: google-analytics-data-api.yaml
  format: yaml
  label: Google Analytics Data API (GA4)
  slug: google-analytics-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-data-api.yaml
- filename: google-analytics-admin-api.yaml
  format: yaml
  label: Google Analytics Admin API
  slug: google-analytics-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-admin-api.yaml
- filename: google-analytics-measurement-protocol.yaml
  format: yaml
  label: Google Analytics Measurement Protocol (GA4)
  slug: google-analytics-measurement-protocol
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-measurement-protocol.yaml
- filename: google-analytics-user-deletion-api.yaml
  format: yaml
  label: Google Analytics User Deletion API
  slug: google-analytics-user-deletion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-user-deletion-api.yaml
- filename: google-analytics-reporting-api-v4.yaml
  format: yaml
  label: Google Analytics Reporting API v4 (Universal Analytics)
  slug: google-analytics-reporting-api-v4
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-reporting-api-v4.yaml
- filename: google-analytics-management-api-v3.yaml
  format: yaml
  label: Google Analytics Management API v3
  slug: google-analytics-management-api-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/openapi/google-analytics-management-api-v3.yaml
apis:
- description: The Google Analytics Data API provides programmatic access to Google Analytics 4 (GA4) report data including standard reports, pivot reports, real-time reports, funnel reports, and audience exports.
  name: Google Analytics Data API (GA4)
  slug: google-analytics-data-api
- description: 'The Analytics Admin API allows programmatic access to configuration data for Google Analytics 4 properties including account management, data streams, custom dimensions, key events, user permissions, '
  name: Google Analytics Admin API
  slug: google-analytics-admin-api
- description: The Measurement Protocol lets you send events directly to Google Analytics servers via HTTP requests to augment existing GA4 data with server-to-server and offline interactions.
  name: Google Analytics Measurement Protocol (GA4)
  slug: google-analytics-measurement-protocol
- description: The User Deletion API enables removal of data linked to specific user identifiers in Google Analytics, supporting compliance with data protection and privacy requirements.
  name: Google Analytics User Deletion API
  slug: google-analytics-user-deletion-api
- description: The Analytics Reporting API v4 provides programmatic access to Universal Analytics report data. Universal Analytics was sunset on July 1, 2023 and users should migrate to GA4.
  name: Google Analytics Reporting API v4 (Universal Analytics)
  slug: google-analytics-reporting-api-v4
- description: The Analytics Management API allows access to configuration data for Universal Analytics accounts, properties, and views. Deprecated with Universal Analytics sunset.
  name: Google Analytics Management API v3
  slug: google-analytics-management-api-v3
capabilities:
- description: Unified workflow for creating, exporting, and analyzing GA4 audiences. Combines the Data API audience export capabilities with Admin API property configuration. Used by marketing teams and data analys
  name: Google Analytics Audience Management
  slug: audience-management
- description: 'Unified workflow for managing data privacy and compliance across Google Analytics. Combines the User Deletion API for GDPR/privacy compliance with the Admin API for data access auditing and user data '
  name: Google Analytics Compliance and Privacy
  slug: compliance
- description: Unified workflow for managing GA4 property configuration including accounts, properties, data streams, custom dimensions and metrics, conversion events, and integration links. Used by analytics admini
  name: Google Analytics Configuration Management
  slug: configuration-management
- description: Unified workflow for server-side event tracking combining the Measurement Protocol for sending events with the Admin API for managing measurement protocol secrets and data streams. Used by backend eng
  name: Google Analytics Event Collection
  slug: event-collection
- description: 'Unified workflow for managing GA4 integration links with Firebase, Google Ads, and measurement protocol secrets. Used by platform engineers and marketing ops teams to connect GA4 with advertising and '
  name: Google Analytics Integrations and Linking
  slug: integrations-and-linking
- description: 'Unified reporting workflow combining the Data API for running standard, realtime, and pivot reports with the Admin API for accessing data access audit reports. Used by data analysts, marketing teams, '
  name: Google Analytics Reporting and Insights
  slug: reporting-and-insights
common:
- title: ''
  type: GettingStarted
  url: https://developers.google.com/analytics/get-started
- title: ''
  type: Portal
  url: https://developers.google.com/analytics
- title: ''
  type: Console
  url: https://console.cloud.google.com/apis/library/analytics.googleapis.com
- title: ''
  type: SignUp
  url: https://analytics.google.com/analytics/
- title: ''
  type: Authentication
  url: https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries
- title: ''
  type: SDK
  url: https://developers.google.com/analytics/devguides/config/admin/v1/client-libraries
- title: MCP Server
  type: Tools
  url: https://github.com/googleanalytics/google-analytics-mcp
- title: GA Dev Tools
  type: Tools
  url: https://ga-dev-tools.google/ga4/
- title: E-commerce Migration Helper
  type: Tools
  url: https://github.com/googleanalytics/ecommerce-migration-helper
- title: GA4 Tutorials
  type: Tutorials
  url: https://github.com/googleanalytics/ga4-tutorials
- title: Consent Mode Examples
  type: CodeExamples
  url: https://github.com/googleanalytics/gtm-consent-mode-examples
- title: ''
  type: Pricing
  url: https://marketingplatform.google.com/about/analytics/
- title: ''
  type: TermsOfService
  url: https://developers.google.com/analytics/terms
- title: ''
  type: PrivacyPolicy
  url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/policy
- title: ''
  type: Blog
  url: https://analytics.googleblog.com/
- title: ''
  type: StatusPage
  url: https://status.cloud.google.com/
- title: ''
  type: Support
  url: https://developers.google.com/analytics/support
- title: ''
  type: FAQ
  url: https://support.google.com/analytics
- title: ''
  type: ReleaseNotes
  url: https://support.google.com/analytics/answer/9164320
- title: ''
  type: ChangeLog
  url: https://groups.google.com/forum/#!forum/google-analytics-api-notify
- title: ''
  type: GitHubOrganization
  url: https://github.com/googleanalytics/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/google-analytics
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/googleanalytics
- title: ''
  type: Training
  url: https://goo.gle/ga-courses
- title: ''
  type: Academy
  url: https://marketingplatformacademy.withgoogle.com/google-analytics-360
created: '2024-01-01'
description: Google Analytics provides data and insights about website and app usage, enabling businesses to understand their audience and optimize their digital properties through customer-centric measurement, machine learning insights, and cross-platform attribution.
features:
- description: Machine learning models that predict future actions users may take, like purchasing or churning.
  name: Predictive Capabilities
- description: Automatically detects and surfaces actionable insights from your data.
  name: Proactive Insights
- description: Monitor user activity on your site or app as it happens.
  name: Real-Time Reporting
- description: Machine learning to understand how each touchpoint contributes to conversions.
  name: Data-Driven Attribution
- description: Drag-and-drop analysis with instant visualizations for custom reporting.
  name: Free-Form Exploration
- description: Visualize user steps through conversion funnels and identify optimization opportunities.
  name: Funnel Exploration
- description: Visualize user navigation paths to understand how users reach conversions.
  name: Path Exploration
- description: Analyze behavior of users grouped by common attributes over time.
  name: Cohort Exploration
- description: Export raw event data to BigQuery for advanced analysis and data warehousing.
  name: BigQuery Export
- description: Customer-centric measurement across websites and apps throughout the entire customer lifecycle.
  name: Cross-Platform Measurement
- description: Machine learning models that provide a complete picture of the customer journey while respecting privacy.
  name: Privacy-Safe Modeling
- description: Define custom dimensions and metrics to capture data specific to your business needs.
  name: Custom Dimensions and Metrics
image: https://www.google.com/analytics/images/google-analytics-logo.png
integrations:
- description: Link Google Ads accounts to analyze campaign performance and optimize ad spend with Analytics data.
  name: Google Ads
- description: Export raw Analytics data to BigQuery for advanced SQL-based analysis and data warehousing.
  name: Google BigQuery
- description: Connect Search Console to see organic search queries, impressions, and click data alongside Analytics.
  name: Google Search Console
- description: Integrate with Firebase for comprehensive mobile and web app analytics and event tracking.
  name: Firebase
- description: Link DV360 for programmatic advertising measurement and attribution.
  name: Display & Video 360
- description: Connect SA360 for unified search advertising measurement across engines.
  name: Search Ads 360
- description: Use Tag Manager to deploy and manage Analytics tags without modifying website code.
  name: Google Tag Manager
- description: Integrate publisher ad serving data with Analytics for holistic content and ad performance analysis.
  name: Google Ad Manager
- description: Leverage Google Cloud services for advanced data processing, ML models, and storage with Analytics data.
  name: Google Cloud
- description: Connect Salesforce Marketing Cloud for cross-platform marketing measurement and audience activation.
  name: Salesforce Marketing Cloud
jsonld:
- class_count: 10
  name: Google Analytics Admin Api Context
  property_count: 48
  slug: google-analytics-admin-api-context
- class_count: 10
  name: Google Analytics Data Api Context
  property_count: 92
  slug: google-analytics-data-api-context
- class_count: 7
  name: Google Analytics Measurement Protocol Context
  property_count: 37
  slug: google-analytics-measurement-protocol-context
- class_count: 2
  name: Google Analytics User Deletion Api Context
  property_count: 8
  slug: google-analytics-user-deletion-api-context
layout: provider
modified: '2026-04-17'
name: Google Analytics
rules:
- name: Google Analytics API Rules
  rule_count: 66
  severity_counts:
    error: 18
    hint: 0
    info: 26
    warn: 22
  slug: google-analytics-spectral-rules
skills:
- name: Run Report
  url: skills/run-report/SKILL.md
- name: Run Realtime Report
  url: skills/run-realtime-report/SKILL.md
- name: Run Pivot Report
  url: skills/run-pivot-report/SKILL.md
- name: Batch Run Reports
  url: skills/batch-run-reports/SKILL.md
- name: Batch Run Pivot Reports
  url: skills/batch-run-pivot-reports/SKILL.md
- name: Check Compatibility
  url: skills/check-compatibility/SKILL.md
- name: Create Audience Export
  url: skills/create-audience-export/SKILL.md
- name: Get Audience Export
  url: skills/get-audience-export/SKILL.md
- name: List Audience Exports
  url: skills/list-audience-exports/SKILL.md
- name: Query Audience Export
  url: skills/query-audience-export/SKILL.md
- name: List Account Summaries
  url: skills/list-account-summaries/SKILL.md
- name: List Accounts
  url: skills/list-accounts/SKILL.md
- name: Provision Account Ticket
  url: skills/provision-account-ticket/SKILL.md
- name: List Properties
  url: skills/list-properties/SKILL.md
- name: Create Property
  url: skills/create-property/SKILL.md
- name: Search Change History Events
  url: skills/search-change-history-events/SKILL.md
- name: Run Access Report
  url: skills/run-access-report/SKILL.md
- name: Delete Google Ads Link
  url: skills/delete-google-ads-link/SKILL.md
- name: Get Measurement Protocol Secret
  url: skills/get-measurement-protocol-secret/SKILL.md
- name: Update Google Ads Link
  url: skills/update-google-ads-link/SKILL.md
- name: Archive Custom Metric
  url: skills/archive-custom-metric/SKILL.md
- name: List Conversion Events
  url: skills/list-conversion-events/SKILL.md
- name: Create Conversion Event
  url: skills/create-conversion-event/SKILL.md
- name: List Custom Dimensions
  url: skills/list-custom-dimensions/SKILL.md
- name: Create Custom Dimension
  url: skills/create-custom-dimension/SKILL.md
- name: List Custom Metrics
  url: skills/list-custom-metrics/SKILL.md
- name: Create Custom Metric
  url: skills/create-custom-metric/SKILL.md
- name: List Data Streams
  url: skills/list-data-streams/SKILL.md
- name: Create Data Stream
  url: skills/create-data-stream/SKILL.md
- name: List Firebase Links
  url: skills/list-firebase-links/SKILL.md
- name: Create Firebase Link
  url: skills/create-firebase-link/SKILL.md
- name: List Google Ads Links
  url: skills/list-google-ads-links/SKILL.md
- name: Create Google Ads Link
  url: skills/create-google-ads-link/SKILL.md
- name: List Measurement Protocol Secrets
  url: skills/list-measurement-protocol-secrets/SKILL.md
- name: Create Measurement Protocol Secret
  url: skills/create-measurement-protocol-secret/SKILL.md
- name: Acknowledge User Data Collection
  url: skills/acknowledge-user-data-collection/SKILL.md
- name: Send Events
  url: skills/send-events/SKILL.md
- name: Validate Events
  url: skills/validate-events/SKILL.md
- name: Upsert User Deletion Request
  url: skills/upsert-user-deletion-request/SKILL.md
slug: google-analytics
solutions:
- description: Full-featured web and app analytics solution available at no charge for businesses of all sizes.
  name: Google Analytics Free
- description: Enterprise-grade analytics with advanced features including intraday data, sub-properties, roll-up reporting, and higher limits.
  name: Analytics 360
- description: Integrated advertising and analytics platform combining Analytics 360 with advertising products for enterprise marketing.
  name: Google Marketing Platform
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-analytics\nname: Google Analytics\ndescription: Google Analytics provides data and insights about website and app usage, enabling businesses to understand their audience and optimize their digital properties through customer-centric measurement, machine learning insights, and cross-platform attribution.\ntype: Index\nimage: https://www.google.com/analytics/images/google-analytics-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Data\n  - Google\n  - Metrics\n  - Reporting\n  - Web Analytics\n  - Machine Learning\n  - Attribution\napis:\n  - aid: google-analytics:google-analytics-data-api\n    name: Google Analytics Data API (GA4)\n    description: The Google Analytics Data API provides programmatic access to Google Analytics 4 (GA4) report data including standard reports, pivot reports, real-time reports,\
  \ funnel reports, and audience exports.\n    image: https://www.google.com/analytics/images/google-analytics-logo.png\n    humanURL: https://developers.google.com/analytics/devguides/reporting/data/v1\n    baseURL: https://analyticsdata.googleapis.com\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1\n      - type: OpenAPI\n        url: openapi/google-analytics-data-api.yaml\n      - type: APIReference\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1/rest\n      - type: Quickstart\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart\n      - type: Authentication\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries\n      - type: RateLimits\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1/quotas\n      - type: SDK\n        url: https://pypi.org/project/google-analytics-data/\n\
  \        title: Python SDK\n      - type: SDK\n        url: https://www.npmjs.com/package/@google-analytics/data\n        title: Node.js SDK\n      - type: SDK\n        url: https://central.sonatype.com/artifact/com.google.analytics/google-analytics-data\n        title: Java SDK\n      - type: SDK\n        url: https://www.nuget.org/packages/Google.Analytics.Data.V1Beta\n        title: .NET SDK\n      - type: SDK\n        url: https://packagist.org/packages/google/analytics-data\n        title: PHP SDK\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/python-docs-samples\n        title: Python Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/java-docs-samples\n        title: Java Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/nodejs-docs-samples\n        title: Node.js Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/dotnet-docs-samples\n        title:\
  \ .NET Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/php-docs-samples\n        title: PHP Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/analytics-data-curl-examples\n        title: Curl Examples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/analytics-data-javascript-examples\n        title: JavaScript Examples\n    tags:\n      - Analytics\n      - Data API\n      - GA4\n      - Reporting\n      - Real-Time\n      - Funnels\n  - aid: google-analytics:google-analytics-admin-api\n    name: Google Analytics Admin API\n    description: The Analytics Admin API allows programmatic access to configuration data for Google Analytics 4 properties including account management, data streams, custom dimensions, key events, user permissions, and integration linking.\n    image: https://www.google.com/analytics/images/google-analytics-logo.png\n    humanURL: https://developers.google.com/analytics/devguides/config/admin/v1\n\
  \    baseURL: https://analyticsadmin.googleapis.com\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/config/admin/v1\n      - type: OpenAPI\n        url: openapi/google-analytics-admin-api.yaml\n      - type: APIReference\n        url: https://developers.google.com/analytics/devguides/config/admin/v1/rest\n      - type: Quickstart\n        url: https://developers.google.com/analytics/devguides/config/admin/v1/quickstart\n      - type: SDK\n        url: https://developers.google.com/analytics/devguides/config/admin/v1/client-libraries\n      - type: SDK\n        url: https://pypi.org/project/google-analytics-admin/\n        title: Python SDK\n      - type: SDK\n        url: https://www.npmjs.com/package/@google-analytics/admin\n        title: Node.js SDK\n      - type: SDK\n        url: https://central.sonatype.com/artifact/com.google.analytics/google-analytics-admin\n        title: Java SDK\n      - type: SDK\n        url: https://www.nuget.org/packages/Google.Analytics.Admin.V1Beta\n\
  \        title: .NET SDK\n      - type: SDK\n        url: https://packagist.org/packages/google/analytics-admin\n        title: PHP SDK\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/python-docs-samples\n        title: Python Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/java-docs-samples\n        title: Java Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/nodejs-docs-samples\n        title: Node.js Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/dotnet-docs-samples\n        title: .NET Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/php-docs-samples\n        title: PHP Samples\n      - type: CodeExamples\n        url: https://github.com/googleanalytics/analytics-samples-config\n        title: Configuration Samples\n    tags:\n      - Admin\n      - Configuration\n      - GA4\n      - Management\n      - Permissions\n\
  \  - aid: google-analytics:google-analytics-measurement-protocol\n    name: Google Analytics Measurement Protocol (GA4)\n    description: The Measurement Protocol lets you send events directly to Google Analytics servers via HTTP requests to augment existing GA4 data with server-to-server and offline interactions.\n    image: https://www.google.com/analytics/images/google-analytics-logo.png\n    humanURL: https://developers.google.com/analytics/devguides/collection/protocol/ga4\n    baseURL: https://www.google-analytics.com\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4\n      - type: APIReference\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/reference\n      - type: Quickstart\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/sending-events\n      - type: OpenAPI\n        url: openapi/google-analytics-measurement-protocol.yaml\n\
  \      - type: Troubleshooting\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/troubleshooting\n    tags:\n      - Events\n      - Measurement\n      - Server-Side\n      - Tracking\n  - aid: google-analytics:google-analytics-user-deletion-api\n    name: Google Analytics User Deletion API\n    description: The User Deletion API enables removal of data linked to specific user identifiers in Google Analytics, supporting compliance with data protection and privacy requirements.\n    image: https://www.google.com/analytics/images/google-analytics-logo.png\n    humanURL: https://developers.google.com/analytics/devguides/config/userdeletion/v3\n    baseURL: https://www.googleapis.com/analytics/v3\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/config/userdeletion/v3\n      - type: APIReference\n        url: https://developers.google.com/analytics/devguides/config/userdeletion/v3/reference\n\
  \      - type: OpenAPI\n        url: openapi/google-analytics-user-deletion-api.yaml\n      - type: Authentication\n        url: https://developers.google.com/analytics/devguides/config/userdeletion/v3/authorization\n    tags:\n      - Compliance\n      - Data Privacy\n      - GDPR\n      - User Deletion\n  - aid: google-analytics:google-analytics-reporting-api-v4\n    name: Google Analytics Reporting API v4 (Universal Analytics)\n    description: The Analytics Reporting API v4 provides programmatic access to Universal Analytics report data. Universal Analytics was sunset on July 1, 2023 and users should migrate to GA4.\n    image: https://www.google.com/analytics/images/google-analytics-logo.png\n    humanURL: https://developers.google.com/analytics/devguides/reporting/core/v4\n    baseURL: https://analyticsreporting.googleapis.com\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/reporting/core/v4\n      - type: OpenAPI\n  \
  \      url: openapi/google-analytics-reporting-api-v4.yaml\n      - type: GettingStarted\n        url: https://developers.google.com/analytics/devguides/migration/api/reporting-ua-to-ga4\n    tags:\n      - Analytics\n      - Deprecated\n      - Legacy\n      - Reporting\n      - Universal Analytics\n  - aid: google-analytics:google-analytics-management-api-v3\n    name: Google Analytics Management API v3\n    description: The Analytics Management API allows access to configuration data for Universal Analytics accounts, properties, and views. Deprecated with Universal Analytics sunset.\n    image: https://www.google.com/analytics/images/google-analytics-logo.png\n    humanURL: https://developers.google.com/analytics/devguides/config/mgmt/v3\n    baseURL: https://www.googleapis.com/analytics/v3\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/config/mgmt/v3\n      - type: OpenAPI\n        url: openapi/google-analytics-management-api-v3.yaml\n\
  \      - type: APIReference\n        url: https://developers.google.com/analytics/devguides/config/mgmt/v3/mgmtReference\n    tags:\n      - Configuration\n      - Deprecated\n      - Legacy\n      - Management\n      - Universal Analytics\ncommon:\n  - type: GettingStarted\n    url: https://developers.google.com/analytics/get-started\n  - type: Portal\n    url: https://developers.google.com/analytics\n  - type: Console\n    url: https://console.cloud.google.com/apis/library/analytics.googleapis.com\n  - type: SignUp\n    url: https://analytics.google.com/analytics/\n  - type: Authentication\n    url: https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries\n  - type: SDK\n    url: https://developers.google.com/analytics/devguides/config/admin/v1/client-libraries\n  - type: Tools\n    url: https://github.com/googleanalytics/google-analytics-mcp\n    title: MCP Server\n  - type: Tools\n    url: https://ga-dev-tools.google/ga4/\n    title: GA Dev Tools\n\
  \  - type: Tools\n    url: https://github.com/googleanalytics/ecommerce-migration-helper\n    title: E-commerce Migration Helper\n  - type: Tutorials\n    url: https://github.com/googleanalytics/ga4-tutorials\n    title: GA4 Tutorials\n  - type: CodeExamples\n    url: https://github.com/googleanalytics/gtm-consent-mode-examples\n    title: Consent Mode Examples\n  - type: Pricing\n    url: https://marketingplatform.google.com/about/analytics/\n  - type: TermsOfService\n    url: https://developers.google.com/analytics/terms\n  - type: PrivacyPolicy\n    url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/policy\n  - type: Blog\n    url: https://analytics.googleblog.com/\n  - type: StatusPage\n    url: https://status.cloud.google.com/\n  - type: Support\n    url: https://developers.google.com/analytics/support\n  - type: FAQ\n    url: https://support.google.com/analytics\n  - type: ReleaseNotes\n    url: https://support.google.com/analytics/answer/9164320\n  -\
  \ type: ChangeLog\n    url: https://groups.google.com/forum/#!forum/google-analytics-api-notify\n  - type: Skills\n    data:\n      - name: Run Report\n        url: skills/run-report/SKILL.md\n      - name: Run Realtime Report\n        url: skills/run-realtime-report/SKILL.md\n      - name: Run Pivot Report\n        url: skills/run-pivot-report/SKILL.md\n      - name: Batch Run Reports\n        url: skills/batch-run-reports/SKILL.md\n      - name: Batch Run Pivot Reports\n        url: skills/batch-run-pivot-reports/SKILL.md\n      - name: Check Compatibility\n        url: skills/check-compatibility/SKILL.md\n      - name: Create Audience Export\n        url: skills/create-audience-export/SKILL.md\n      - name: Get Audience Export\n        url: skills/get-audience-export/SKILL.md\n      - name: List Audience Exports\n        url: skills/list-audience-exports/SKILL.md\n      - name: Query Audience Export\n        url: skills/query-audience-export/SKILL.md\n      - name: List Account Summaries\n\
  \        url: skills/list-account-summaries/SKILL.md\n      - name: List Accounts\n        url: skills/list-accounts/SKILL.md\n      - name: Provision Account Ticket\n        url: skills/provision-account-ticket/SKILL.md\n      - name: List Properties\n        url: skills/list-properties/SKILL.md\n      - name: Create Property\n        url: skills/create-property/SKILL.md\n      - name: Search Change History Events\n        url: skills/search-change-history-events/SKILL.md\n      - name: Run Access Report\n        url: skills/run-access-report/SKILL.md\n      - name: Delete Google Ads Link\n        url: skills/delete-google-ads-link/SKILL.md\n      - name: Get Measurement Protocol Secret\n        url: skills/get-measurement-protocol-secret/SKILL.md\n      - name: Update Google Ads Link\n        url: skills/update-google-ads-link/SKILL.md\n      - name: Archive Custom Metric\n        url: skills/archive-custom-metric/SKILL.md\n      - name: List Conversion Events\n        url: skills/list-conversion-events/SKILL.md\n\
  \      - name: Create Conversion Event\n        url: skills/create-conversion-event/SKILL.md\n      - name: List Custom Dimensions\n        url: skills/list-custom-dimensions/SKILL.md\n      - name: Create Custom Dimension\n        url: skills/create-custom-dimension/SKILL.md\n      - name: List Custom Metrics\n        url: skills/list-custom-metrics/SKILL.md\n      - name: Create Custom Metric\n        url: skills/create-custom-metric/SKILL.md\n      - name: List Data Streams\n        url: skills/list-data-streams/SKILL.md\n      - name: Create Data Stream\n        url: skills/create-data-stream/SKILL.md\n      - name: List Firebase Links\n        url: skills/list-firebase-links/SKILL.md\n      - name: Create Firebase Link\n        url: skills/create-firebase-link/SKILL.md\n      - name: List Google Ads Links\n        url: skills/list-google-ads-links/SKILL.md\n      - name: Create Google Ads Link\n        url: skills/create-google-ads-link/SKILL.md\n      - name: List Measurement Protocol\
  \ Secrets\n        url: skills/list-measurement-protocol-secrets/SKILL.md\n      - name: Create Measurement Protocol Secret\n        url: skills/create-measurement-protocol-secret/SKILL.md\n      - name: Acknowledge User Data Collection\n        url: skills/acknowledge-user-data-collection/SKILL.md\n      - name: Send Events\n        url: skills/send-events/SKILL.md\n      - name: Validate Events\n        url: skills/validate-events/SKILL.md\n      - name: Upsert User Deletion Request\n        url: skills/upsert-user-deletion-request/SKILL.md\n  - type: GitHubOrganization\n    url: https://github.com/googleanalytics/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/google-analytics\n  - type: YouTube\n    url: https://www.youtube.com/user/googleanalytics\n  - type: Training\n    url: https://goo.gle/ga-courses\n  - type: Academy\n    url: https://marketingplatformacademy.withgoogle.com/google-analytics-360\n  - type: Features\n    data:\n      - name: Predictive\
  \ Capabilities\n        description: Machine learning models that predict future actions users may take, like purchasing or churning.\n      - name: Proactive Insights\n        description: Automatically detects and surfaces actionable insights from your data.\n      - name: Real-Time Reporting\n        description: Monitor user activity on your site or app as it happens.\n      - name: Data-Driven Attribution\n        description: Machine learning to understand how each touchpoint contributes to conversions.\n      - name: Free-Form Exploration\n        description: Drag-and-drop analysis with instant visualizations for custom reporting.\n      - name: Funnel Exploration\n        description: Visualize user steps through conversion funnels and identify optimization opportunities.\n      - name: Path Exploration\n        description: Visualize user navigation paths to understand how users reach conversions.\n      - name: Cohort Exploration\n        description: Analyze behavior of users\
  \ grouped by common attributes over time.\n      - name: BigQuery Export\n        description: Export raw event data to BigQuery for advanced analysis and data warehousing.\n      - name: Cross-Platform Measurement\n        description: Customer-centric measurement across websites and apps throughout the entire customer lifecycle.\n      - name: Privacy-Safe Modeling\n        description: Machine learning models that provide a complete picture of the customer journey while respecting privacy.\n      - name: Custom Dimensions and Metrics\n        description: Define custom dimensions and metrics to capture data specific to your business needs.\n  - type: UseCases\n    data:\n      - name: Website Traffic Analysis\n        description: Understand where visitors come from, what pages they view, and how they interact with your website.\n      - name: Conversion Optimization\n        description: Track conversion events, analyze funnels, and identify drop-off points to improve conversion rates.\n\
  \      - name: Audience Segmentation\n        description: Segment users by demographics, behavior, technology, and custom attributes for targeted analysis.\n      - name: Marketing Campaign Measurement\n        description: Measure the effectiveness of advertising campaigns across channels with attribution modeling.\n      - name: E-commerce Analytics\n        description: Track purchase activity, revenue, product performance, and shopping behavior.\n      - name: App Analytics\n        description: Measure user engagement, retention, and in-app actions for mobile and web applications.\n      - name: Server-Side Event Tracking\n        description: Send events from your server using the Measurement Protocol for offline and backend interactions.\n      - name: Compliance and Data Privacy\n        description: Manage user data deletion requests and privacy compliance using the User Deletion API.\n      - name: Custom Reporting and Dashboards\n        description: Build custom reports and\
  \ dashboards programmatically using the Data API.\n      - name: Real-Time Monitoring\n        description: Monitor live user activity for time-sensitive campaigns, launches, and events.\n  - type: Integrations\n    data:\n      - name: Google Ads\n        description: Link Google Ads accounts to analyze campaign performance and optimize ad spend with Analytics data.\n      - name: Google BigQuery\n        description: Export raw Analytics data to BigQuery for advanced SQL-based analysis and data warehousing.\n      - name: Google Search Console\n        description: Connect Search Console to see organic search queries, impressions, and click data alongside Analytics.\n      - name: Firebase\n        description: Integrate with Firebase for comprehensive mobile and web app analytics and event tracking.\n      - name: Display & Video 360\n        description: Link DV360 for programmatic advertising measurement and attribution.\n      - name: Search Ads 360\n        description: Connect\
  \ SA360 for unified search advertising measurement across engines.\n      - name: Google Tag Manager\n        description: Use Tag Manager to deploy and manage Analytics tags without modifying website code.\n      - name: Google Ad Manager\n        description: Integrate publisher ad serving data with Analytics for holistic content and ad performance analysis.\n      - name: Google Cloud\n        description: Leverage Google Cloud services for advanced data processing, ML models, and storage with Analytics data.\n      - name: Salesforce Marketing Cloud\n        description: Connect Salesforce Marketing Cloud for cross-platform marketing measurement and audience activation.\n  - type: Solutions\n    data:\n      - name: Google Analytics Free\n        description: Full-featured web and app analytics solution available at no charge for businesses of all sizes.\n      - name: Analytics 360\n        description: Enterprise-grade analytics with advanced features including intraday data, sub-properties,\
  \ roll-up reporting, and higher limits.\n      - name: Google Marketing Platform\n        description: Integrated advertising and analytics platform combining Analytics 360 with advertising products for enterprise marketing.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/apis.yml
tags:
- Analytics
- Data
- Google
- Metrics
- Reporting
- Web Analytics
- Machine Learning
- Attribution
url: https://raw.githubusercontent.com/api-evangelist/google-analytics/refs/heads/main/apis.yml
use_cases:
- description: Understand where visitors come from, what pages they view, and how they interact with your website.
  name: Website Traffic Analysis
- description: Track conversion events, analyze funnels, and identify drop-off points to improve conversion rates.
  name: Conversion Optimization
- description: Segment users by demographics, behavior, technology, and custom attributes for targeted analysis.
  name: Audience Segmentation
- description: Measure the effectiveness of advertising campaigns across channels with attribution modeling.
  name: Marketing Campaign Measurement
- description: Track purchase activity, revenue, product performance, and shopping behavior.
  name: E-commerce Analytics
- description: Measure user engagement, retention, and in-app actions for mobile and web applications.
  name: App Analytics
- description: Send events from your server using the Measurement Protocol for offline and backend interactions.
  name: Server-Side Event Tracking
- description: Manage user data deletion requests and privacy compliance using the User Deletion API.
  name: Compliance and Data Privacy
- description: Build custom reports and dashboards programmatically using the Data API.
  name: Custom Reporting and Dashboards
- description: Monitor live user activity for time-sensitive campaigns, launches, and events.
  name: Real-Time Monitoring
---
