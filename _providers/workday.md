---
api_count: 20
apis:
- description: Human Capital Management API for managing workforce data, recruiting, talent management, and payroll. Provides RESTful endpoints for core HR operations.
  name: Workday HCM API
  slug: hcm-api
- description: Financial Management API for accounting, procurement, expenses, and financial reporting. Enables programmatic access to financial data and workflows.
  name: Workday Financial Management API
  slug: financial-management-api
- description: Recruiting API for managing job postings, candidates, applications, and hiring workflows. Supports interview feedback and prospect management.
  name: Workday Recruiting API
  slug: recruiting-api
- description: Time Tracking API for managing employee time entry, timesheets, time clock events, and time validations.
  name: Workday Time Tracking API
  slug: time-tracking-api
- description: Benefits API for managing employee benefits, enrollments, and coverage. Provides endpoints for benefits administration workflows.
  name: Workday Benefits API
  slug: benefits-api
- description: Absence Management API for managing leave balances, time-off requests, leaves of absence, and eligible absence types for workers.
  name: Workday Absence Management API
  slug: absence-management-api
- description: Compensation API for managing employee compensation plans, scorecards, scorecard results, and one-time payment requests.
  name: Workday Compensation API
  slug: compensation-api
- description: Payroll API for managing pay groups, pay group details, tax rates, payroll inputs, and pay components.
  name: Workday Payroll API
  slug: payroll-api
- description: Person API for managing worker person data including personal information, contact details, and organizational relationships.
  name: Workday Person API
  slug: person-api
- description: Performance Management API for managing performance reviews, feedback badges, goals, and employee performance evaluations.
  name: Workday Performance Management API
  slug: performance-management-api
- description: Talent Management API for managing mentorships, talent profiles, career development, and succession planning.
  name: Workday Talent Management API
  slug: talent-management-api
- description: Common API providing shared reference data, lookup values, and utility endpoints used across other Workday REST API services.
  name: Workday Common API
  slug: common-api
- description: Staffing API for managing organizational assignments, job profiles, positions, supervisory organizations, and worker staffing events.
  name: Workday Staffing API
  slug: staffing-api
- description: Strategic Sourcing API for managing sourcing events, awards, contracts, suppliers, spend categories, and procurement workflows.
  name: Workday Strategic Sourcing API
  slug: strategic-sourcing-api
- description: Standards-based SOAP API providing programmatic access to Workday business management services with WSDL and XML Schema definitions. Covers 55 service areas including Human Resources, Payroll, Benefit
  name: Workday SOAP Web Services API
  slug: soap-web-services-api
- description: Prism Analytics REST API for working with Workday Prism Analytics tables, data change tasks, and datasets. Enables programmatic creation and management of analytics data.
  name: Workday Prism Analytics API
  slug: prism-analytics-api
- description: Workday Extend platform for building custom applications that integrate with Workday. Provides low-code and no-code developer tools for creating business solutions.
  name: Workday Extend API
  slug: extend-api
- description: Report-as-a-Service (RaaS) exposes custom reports as RESTful web services, enabling programmatic access to report data. Supports query parameters for filtering and returns data in multiple formats.
  name: Workday Report-as-a-Service API
  slug: raas-api
- description: Adaptive Planning REST and XML APIs for managing planning data, accounts, dimensions, and custom reports. Supports integration with enterprise planning and budgeting workflows.
  name: Workday Adaptive Planning API
  slug: adaptive-planning-api
- description: Workday Query Language (WQL) API enabling SQL-like querying of Workday data through REST endpoints. Provides high-performance data access controlled via OAuth 2.0 tokens.
  name: Workday WQL API
  slug: wql-api
capabilities:
- description: Unified analytics and reporting combining Prism Analytics, WQL, and Report-as-a-Service APIs for business analysts to query data, manage datasets, and access custom reports.
  name: Workday Analytics and Reporting
  slug: analytics-and-reporting
- description: Unified compensation and payroll management combining Compensation, Payroll, and Benefits APIs for payroll administrators to manage pay plans, benefits enrollment, and payroll processing.
  name: Workday Compensation and Payroll
  slug: compensation-and-payroll
- description: Unified financial operations combining Financial Management and procurement data for finance teams to manage accounting, suppliers, expenses, and invoices.
  name: Workday Finance and Procurement
  slug: finance-and-procurement
- description: Unified talent and performance management combining Recruiting, Talent, and Performance Management APIs for HR and talent leads to manage hiring pipelines, career development, and performance evaluati
  name: Workday Talent and Performance
  slug: talent-and-performance
- description: Unified time and absence management combining Time Tracking and Absence Management APIs for HR operations to manage timesheets, time-off requests, and leave balances.
  name: Workday Time and Absence
  slug: time-and-absence
- description: Unified workforce management combining HCM, Person, Staffing, and Common APIs for HR administrators to manage workers, organizations, positions, and reference data.
  name: Workday Workforce Management
  slug: workforce-management
common:
- title: ''
  type: GettingStarted
  url: https://community.workday.com/api-start
- title: ''
  type: Authentication
  url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication
- title: ''
  type: RateLimits
  url: https://community.workday.com/articles/16827
- title: ''
  type: StatusPage
  url: https://community.workday.com/trust/status
- title: ''
  type: TermsOfService
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: PrivacyPolicy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Documentation
  url: https://community.workday.com/api
- title: ''
  type: Console
  url: https://developer.workday.com/about
- title: ''
  type: Blog
  url: https://blog.workday.com/en-us/application-development.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/workday
- title: ''
  type: SignUp
  url: https://resourcecenter.workday.com/
- title: ''
  type: Support
  url: https://www.workday.com/en-us/services/support.html
- title: ''
  type: Marketplace
  url: https://marketplace.workday.com/en-US/home
- title: ''
  type: Partners
  url: https://www.workday.com/en-us/company/partners/overview.html
- title: ''
  type: APIReference
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html
- title: ''
  type: JSONLD
  url: json-ld/context.jsonld
- title: ''
  type: SpectralRules
  url: rules/workday-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/workday-vocabulary.yaml
created: '2024-01-15'
description: Collection of Workday REST and SOAP APIs for human capital management, financial management, enterprise planning, analytics, and platform extensibility.
features:
- description: Comprehensive HCM suite for managing the entire employee lifecycle from hiring to retirement with global compliance.
  name: Human Capital Management
- description: Cloud-native financial management with real-time accounting, procurement, expenses, and revenue management.
  name: Financial Management
- description: Enterprise planning and budgeting with collaborative forecasting, scenario modeling, and rolling forecasts.
  name: Adaptive Planning
- description: Augmented analytics platform combining Workday and third-party data for actionable business intelligence.
  name: Prism Analytics
- description: End-to-end recruiting solution with job requisitions, candidate management, and interview scheduling.
  name: Recruiting
- description: Skills-based talent optimization with performance reviews, succession planning, and career development.
  name: Talent Management
- description: Global payroll processing with automated calculations, tax compliance, and pay slip generation.
  name: Payroll
- description: Automated time entry, timesheet management, leave balances, and absence request workflows.
  name: Time and Absence Tracking
- description: Low-code platform for building custom applications that integrate natively with the Workday ecosystem.
  name: Workday Extend
- description: Expose custom Workday reports as RESTful web services for programmatic data access and integration.
  name: Report-as-a-Service
image: /assets/icons/workday.png
integrations:
- description: Sync workforce and customer data between Workday HCM and Salesforce CRM for unified employee and customer insights.
  name: Salesforce
- description: Integrate Workday with Microsoft Teams, Outlook, and Azure AD for single sign-on and productivity workflows.
  name: Microsoft 365
- description: Connect Workday HR processes with ServiceNow ITSM for automated employee service delivery and ticket management.
  name: ServiceNow
- description: Enable Workday notifications, approvals, and time-off requests directly within Slack channels and DMs.
  name: Slack
- description: Integrate Workday payroll with ADP for third-party payroll processing and tax filing services.
  name: ADP
- description: Connect Workday financial management with SAP ERP for cross-system accounting and procurement workflows.
  name: SAP
- description: Integrate Workday with Greenhouse recruiting for seamless candidate pipeline management and hiring workflows.
  name: Greenhouse
- description: Connect Workday with Okta for identity management, single sign-on, and automated user provisioning.
  name: Okta
jsonld:
- class_count: 0
  name: Absencemanagement Context
  property_count: 0
  slug: absenceManagement-context
- class_count: 0
  name: Benefits Context
  property_count: 0
  slug: benefits-context
- class_count: 0
  name: Common Context
  property_count: 0
  slug: common-context
- class_count: 0
  name: Compensation Context
  property_count: 0
  slug: compensation-context
- class_count: 3
  name: context Context
  property_count: 19
  slug: context
- class_count: 0
  name: Financialmanagement Context
  property_count: 0
  slug: financialManagement-context
- class_count: 0
  name: Hcm Context
  property_count: 0
  slug: hcm-context
- class_count: 0
  name: Payroll Context
  property_count: 0
  slug: payroll-context
- class_count: 0
  name: Performancemanagement Context
  property_count: 0
  slug: performanceManagement-context
- class_count: 0
  name: Person Context
  property_count: 0
  slug: person-context
- class_count: 0
  name: Prismanalytics Context
  property_count: 0
  slug: prismAnalytics-context
- class_count: 0
  name: Raas Context
  property_count: 0
  slug: raas-context
- class_count: 0
  name: Recruiting Context
  property_count: 0
  slug: recruiting-context
- class_count: 0
  name: Staffing Context
  property_count: 0
  slug: staffing-context
- class_count: 0
  name: Talent Context
  property_count: 0
  slug: talent-context
- class_count: 0
  name: Timetracking Context
  property_count: 0
  slug: timeTracking-context
- class_count: 0
  name: Wql Context
  property_count: 0
  slug: wql-context
layout: provider
modified: '2026-04-18'
name: Workday
rules:
- name: Workday API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: workday-spectral-rules
skills: []
slug: workday
solutions: []
source_yaml: "aid: workday\nspecificationVersion: '0.19'\ntype: Index\nname: Workday\ndescription: >-\n  Collection of Workday REST and SOAP APIs for human capital management,\n  financial management, enterprise planning, analytics, and platform\n  extensibility.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-18'\ntags:\n  - Cloud Computing\n  - Enterprise Software\n  - Financial Management\n  - HCM\n  - SaaS\napis:\n  - aid: workday:hcm-api\n    name: Workday HCM API\n    description: >-\n      Human Capital Management API for managing workforce data, recruiting,\n      talent management, and payroll. Provides RESTful endpoints for core HR\n      operations.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n\
  \    baseURL: https://wd2-impl-services1.workday.com/ccx/api/\n    tags:\n      - Human Capital Management\n      - Human Resources\n      - Payroll\n      - Talent Management\n      - Workforce\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/hcm.yml\n      - type: JSONSchema\n        url: json-schema/worker.json\n      - type: JSONSchema\n        url: json-schema/organization.json\n      - type: JSONLD\n        url: json-ld/hcm-context.jsonld\n      - type: Authentication\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://www.workday.com/en-us/customer-service/support.html\n  - aid: workday:financial-management-api\n    name: Workday Financial Management API\n    description: >-\n      Financial\
  \ Management API for accounting, procurement, expenses, and\n      financial reporting. Enables programmatic access to financial data and\n      workflows.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/financialManagement/\n    tags:\n      - Accounting\n      - Expenses\n      - Financial Management\n      - Procurement\n      - Revenue\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/financialManagement.yml\n      - type: JSONLD\n        url: json-ld/financialManagement-context.jsonld\n  - aid: workday:recruiting-api\n    name: Workday Recruiting API\n    description: >-\n      Recruiting API for managing job postings, candidates, applications, and\n      hiring\
  \ workflows. Supports interview feedback and prospect management.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/recruiting/\n    tags:\n      - Applications\n      - Candidates\n      - Hiring\n      - Job Postings\n      - Recruiting\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/recruiting.yml\n      - type: JSONLD\n        url: json-ld/recruiting-context.jsonld\n  - aid: workday:time-tracking-api\n    name: Workday Time Tracking API\n    description: >-\n      Time Tracking API for managing employee time entry, timesheets, time clock\n      events, and time validations.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL:\
  \ https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/timeTracking/\n    tags:\n      - Absence\n      - Leave Management\n      - Time Tracking\n      - Timesheets\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/timeTracking.yml\n      - type: JSONLD\n        url: json-ld/timeTracking-context.jsonld\n  - aid: workday:benefits-api\n    name: Workday Benefits API\n    description: >-\n      Benefits API for managing employee benefits, enrollments, and coverage.\n      Provides endpoints for benefits administration workflows.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/benefits/\n\
  \    tags:\n      - Benefits\n      - Coverage\n      - Enrollments\n      - Health Insurance\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/benefits.yml\n      - type: JSONLD\n        url: json-ld/benefits-context.jsonld\n  - aid: workday:absence-management-api\n    name: Workday Absence Management API\n    description: >-\n      Absence Management API for managing leave balances, time-off requests,\n      leaves of absence, and eligible absence types for workers.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/absenceManagement/\n    tags:\n      - Absence Management\n      - Leave Balances\n      - Leave of Absence\n      - Time Off\n    properties:\n      -\
  \ type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/absenceManagement.yml\n      - type: JSONSchema\n        url: json-schema/time-off.json\n      - type: JSONLD\n        url: json-ld/absenceManagement-context.jsonld\n  - aid: workday:compensation-api\n    name: Workday Compensation API\n    description: >-\n      Compensation API for managing employee compensation plans, scorecards,\n      scorecard results, and one-time payment requests.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/compensation/\n    tags:\n      - Compensation\n      - One-Time Payments\n      - Pay Plans\n      - Scorecards\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n\
  \      - type: OpenAPI\n        url: openapi/compensation.yml\n      - type: JSONSchema\n        url: json-schema/compensation.json\n      - type: JSONLD\n        url: json-ld/compensation-context.jsonld\n  - aid: workday:payroll-api\n    name: Workday Payroll API\n    description: >-\n      Payroll API for managing pay groups, pay group details, tax rates, payroll\n      inputs, and pay components.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/payroll/\n    tags:\n      - Pay Components\n      - Pay Groups\n      - Payroll\n      - Tax Rates\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/payroll.yml\n      - type: JSONLD\n        url: json-ld/payroll-context.jsonld\n\
  \  - aid: workday:person-api\n    name: Workday Person API\n    description: >-\n      Person API for managing worker person data including personal information,\n      contact details, and organizational relationships.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/person/\n    tags:\n      - Contact Information\n      - Employee Data\n      - Person\n      - Workers\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/person.yml\n      - type: JSONSchema\n        url: json-schema/worker.json\n      - type: JSONLD\n        url: json-ld/person-context.jsonld\n  - aid: workday:performance-management-api\n    name: Workday Performance Management API\n    description:\
  \ >-\n      Performance Management API for managing performance reviews, feedback\n      badges, goals, and employee performance evaluations.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/performanceManagement/\n    tags:\n      - Feedback\n      - Goals\n      - Performance Management\n      - Reviews\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/performanceManagement.yml\n      - type: JSONLD\n        url: json-ld/performanceManagement-context.jsonld\n  - aid: workday:talent-management-api\n    name: Workday Talent Management API\n    description: >-\n      Talent Management API for managing mentorships, talent profiles, career\n      development, and succession\
  \ planning.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/talent/\n    tags:\n      - Career Development\n      - Mentorships\n      - Succession Planning\n      - Talent Management\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/talent.yml\n      - type: JSONLD\n        url: json-ld/talent-context.jsonld\n  - aid: workday:common-api\n    name: Workday Common API\n    description: >-\n      Common API providing shared reference data, lookup values, and utility\n      endpoints used across other Workday REST API services.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n\
  \    baseURL: https://wd2-impl-services1.workday.com/ccx/api/common/\n    tags:\n      - Common\n      - Lookup Values\n      - Reference Data\n      - Shared Services\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/common.yml\n      - type: JSONLD\n        url: json-ld/common-context.jsonld\n  - aid: workday:staffing-api\n    name: Workday Staffing API\n    description: >-\n      Staffing API for managing organizational assignments, job profiles,\n      positions, supervisory organizations, and worker staffing events.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/staffing/\n    tags:\n      - Job Profiles\n      - Organizations\n      - Positions\n      - Staffing\n\
  \    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/staffing.yml\n      - type: JSONSchema\n        url: json-schema/position.json\n      - type: JSONSchema\n        url: json-schema/organization.json\n      - type: JSONLD\n        url: json-ld/staffing-context.jsonld\n  - aid: workday:strategic-sourcing-api\n    name: Workday Strategic Sourcing API\n    description: >-\n      Strategic Sourcing API for managing sourcing events, awards, contracts,\n      suppliers, spend categories, and procurement workflows.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://apidocs.workdayspend.com/\n    baseURL: https://api.workdayspend.com/services/\n    tags:\n      - Awards\n      - Contracts\n      - Procurement\n      - Strategic Sourcing\n      - Suppliers\n    properties:\n      - type: Documentation\n     \
  \   url: https://apidocs.workdayspend.com/\n      - type: Authentication\n        url: https://apidocs.workdayspend.com/services/events/v1.html\n  - aid: workday:soap-web-services-api\n    name: Workday SOAP Web Services API\n    description: >-\n      Standards-based SOAP API providing programmatic access to Workday business\n      management services with WSDL and XML Schema definitions. Covers 55 service\n      areas including Human Resources, Payroll, Benefits, and Financial Management.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/api\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Enterprise Integration\n      - SOAP API\n      - Web Services\n      - WSDL\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/api\n      - type: APIReference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n\
  \  - aid: workday:prism-analytics-api\n    name: Workday Prism Analytics API\n    description: >-\n      Prism Analytics REST API for working with Workday Prism Analytics tables,\n      data change tasks, and datasets. Enables programmatic creation and\n      management of analytics data.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/prismAnalytics/\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Datasets\n      - Prism Analytics\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/prismAnalytics.yml\n      - type: JSONLD\n        url: json-ld/prismAnalytics-context.jsonld\n  - aid: workday:extend-api\n    name: Workday Extend API\n    description:\
  \ >-\n      Workday Extend platform for building custom applications that integrate\n      with Workday. Provides low-code and no-code developer tools for creating\n      business solutions.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/platform-product-extensions/app-development.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/\n    tags:\n      - App Development\n      - Custom Applications\n      - Low Code\n      - Platform Extensibility\n    properties:\n      - type: Documentation\n        url: https://www.workday.com/en-us/products/platform-product-extensions/app-development.html\n      - type: GettingStarted\n        url: https://developer.workday.com/about\n  - aid: workday:raas-api\n    name: Workday Report-as-a-Service API\n    description: >-\n      Report-as-a-Service (RaaS) exposes custom reports as RESTful web services,\n      enabling programmatic access to report data.\
  \ Supports query parameters for\n      filtering and returns data in multiple formats.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://community.workday.com/api\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Custom Reports\n      - Data Export\n      - Report as a Service\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/api\n      - type: OpenAPI\n        url: openapi/raas.yml\n      - type: JSONLD\n        url: json-ld/raas-context.jsonld\n  - aid: workday:adaptive-planning-api\n    name: Workday Adaptive Planning API\n    description: >-\n      Adaptive Planning REST and XML APIs for managing planning data, accounts,\n      dimensions, and custom reports. Supports integration with enterprise\n      planning and budgeting workflows.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n    humanURL: https://doc.workday.com/adaptive-planning/en-us/integration/managing-data-integration/api-documentation/understanding-the-adaptive-planning-rest-api/api-methods/brk1623709249507.html\n\
  \    baseURL: https://api.adaptiveinsights.com/api/\n    tags:\n      - Adaptive Planning\n      - Budgeting\n      - Financial Planning\n      - Forecasting\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/adaptive-planning/en-us/integration/managing-data-integration/api-documentation/understanding-the-adaptive-planning-rest-api/api-methods/brk1623709249507.html\n      - type: ChangeLog\n        url: https://doc.workday.com/adaptive-planning/en-us/workday-adaptive-planning-documentation/integration/managing-data-integration/api-documentation/understanding-the-adaptive-planning-rest-api/vmo1623708512342.html\n  - aid: workday:wql-api\n    name: Workday WQL API\n    description: >-\n      Workday Query Language (WQL) API enabling SQL-like querying of Workday data\n      through REST endpoints. Provides high-performance data access controlled\n      via OAuth 2.0 tokens.\n    image: https://www.workday.com/content/dam/web/images/logo/workday-logo.svg\n\
  \    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/wql/\n    tags:\n      - Analytics\n      - Data Access\n      - Query Language\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: openapi/wql.yml\n      - type: JSONLD\n        url: json-ld/wql-context.jsonld\ncommon:\n  - type: GettingStarted\n    url: https://community.workday.com/api-start\n  - type: Authentication\n    url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n  - type: RateLimits\n    url: https://community.workday.com/articles/16827\n  - type: StatusPage\n    url: https://community.workday.com/trust/status\n  - type: TermsOfService\n    url: https://www.workday.com/en-us/legal.html\n  - type: PrivacyPolicy\n    url: https://www.workday.com/en-us/privacy.html\n\
  \  - type: Documentation\n    url: https://community.workday.com/api\n  - type: Console\n    url: https://developer.workday.com/about\n  - type: Blog\n    url: https://blog.workday.com/en-us/application-development.html\n  - type: GitHubOrganization\n    url: https://github.com/workday\n  - type: SignUp\n    url: https://resourcecenter.workday.com/\n  - type: Support\n    url: https://www.workday.com/en-us/services/support.html\n  - type: Marketplace\n    url: https://marketplace.workday.com/en-US/home\n  - type: Partners\n    url: https://www.workday.com/en-us/company/partners/overview.html\n  - type: APIReference\n    url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n  - type: JSONLD\n    url: json-ld/context.jsonld\n  - type: SpectralRules\n    url: rules/workday-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/workday-vocabulary.yaml\n  - type: Features\n    url: https://www.workday.com/en-us/products.html\n    data:\n      -\
  \ name: Human Capital Management\n        description: Comprehensive HCM suite for managing the entire employee lifecycle from hiring to retirement with global compliance.\n      - name: Financial Management\n        description: Cloud-native financial management with real-time accounting, procurement, expenses, and revenue management.\n      - name: Adaptive Planning\n        description: Enterprise planning and budgeting with collaborative forecasting, scenario modeling, and rolling forecasts.\n      - name: Prism Analytics\n        description: Augmented analytics platform combining Workday and third-party data for actionable business intelligence.\n      - name: Recruiting\n        description: End-to-end recruiting solution with job requisitions, candidate management, and interview scheduling.\n      - name: Talent Management\n        description: Skills-based talent optimization with performance reviews, succession planning, and career development.\n      - name: Payroll\n      \
  \  description: Global payroll processing with automated calculations, tax compliance, and pay slip generation.\n      - name: Time and Absence Tracking\n        description: Automated time entry, timesheet management, leave balances, and absence request workflows.\n      - name: Workday Extend\n        description: Low-code platform for building custom applications that integrate natively with the Workday ecosystem.\n      - name: Report-as-a-Service\n        description: Expose custom Workday reports as RESTful web services for programmatic data access and integration.\n  - type: UseCases\n    url: https://www.workday.com/en-us/solutions.html\n    data:\n      - name: Employee Onboarding\n        description: Automate new hire onboarding workflows including position assignment, benefits enrollment, and system provisioning.\n      - name: Workforce Planning\n        description: Model headcount scenarios, track open positions, and align workforce supply with business demand.\n      -\
  \ name: Expense Management\n        description: Streamline employee expense reporting with automated policy enforcement, approval workflows, and reimbursement.\n      - name: Compliance Reporting\n        description: Generate regulatory compliance reports for labor laws, tax requirements, and industry-specific mandates.\n      - name: Performance Reviews\n        description: Conduct structured performance evaluations with goal tracking, feedback collection, and calibration.\n      - name: Payroll Integration\n        description: Integrate payroll data with third-party systems for tax filing, benefits administration, and general ledger posting.\n  - type: Integrations\n    url: https://marketplace.workday.com/en-US/home\n    data:\n      - name: Salesforce\n        description: Sync workforce and customer data between Workday HCM and Salesforce CRM for unified employee and customer insights.\n      - name: Microsoft 365\n        description: Integrate Workday with Microsoft Teams, Outlook,\
  \ and Azure AD for single sign-on and productivity workflows.\n      - name: ServiceNow\n        description: Connect Workday HR processes with ServiceNow ITSM for automated employee service delivery and ticket management.\n      - name: Slack\n        description: Enable Workday notifications, approvals, and time-off requests directly within Slack channels and DMs.\n      - name: ADP\n        description: Integrate Workday payroll with ADP for third-party payroll processing and tax filing services.\n      - name: SAP\n        description: Connect Workday financial management with SAP ERP for cross-system accounting and procurement workflows.\n      - name: Greenhouse\n        description: Integrate Workday with Greenhouse recruiting for seamless candidate pipeline management and hiring workflows.\n      - name: Okta\n        description: Connect Workday with Okta for identity management, single sign-on, and automated user provisioning.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  \    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/apis.yml
tags:
- Cloud Computing
- Enterprise Software
- Financial Management
- HCM
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/workday/refs/heads/main/apis.yml
use_cases:
- description: Automate new hire onboarding workflows including position assignment, benefits enrollment, and system provisioning.
  name: Employee Onboarding
- description: Model headcount scenarios, track open positions, and align workforce supply with business demand.
  name: Workforce Planning
- description: Streamline employee expense reporting with automated policy enforcement, approval workflows, and reimbursement.
  name: Expense Management
- description: Generate regulatory compliance reports for labor laws, tax requirements, and industry-specific mandates.
  name: Compliance Reporting
- description: Conduct structured performance evaluations with goal tracking, feedback collection, and calibration.
  name: Performance Reviews
- description: Integrate payroll data with third-party systems for tax filing, benefits administration, and general ledger posting.
  name: Payroll Integration
---
