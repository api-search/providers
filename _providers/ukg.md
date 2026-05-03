---
api_count: 3
api_specs:
- filename: ukg-pro-hcm-openapi.yml
  format: yaml
  label: UKG Pro HCM API
  slug: ukg-pro-hcm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/openapi/ukg-pro-hcm-openapi.yml
- filename: ukg-pro-wfm-openapi.yml
  format: yaml
  label: UKG Pro Workforce Management API
  slug: ukg-pro-wfm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/openapi/ukg-pro-wfm-openapi.yml
apis:
- description: The UKG Pro HCM API provides programmatic access to human capital management data including employees, personnel actions, benefits, payroll, performance, and organizational structure. Uses Basic Authe
  name: UKG Pro HCM API
  slug: ukg-pro-hcm-api
- description: The UKG Pro WFM API provides programmatic access to time and labor management data including punches, shifts, schedules, accruals, and attendance. Supports timekeeping, scheduling, and compliance work
  name: UKG Pro Workforce Management API
  slug: ukg-pro-wfm-api
- description: 'The UKG HR Service Delivery API (formerly People Doc) provides access to employee request management, knowledge portal content, process automation, document storage, and compliance workflows. Enables '
  name: UKG HR Service Delivery API
  slug: ukg-hr-service-delivery-api
capabilities:
- description: HR administration workflow combining employee records, benefits, payroll, and organizational management capabilities.
  name: UKG HR Administration
  slug: hr-administration
- description: Workforce management workflow combining timekeeping, scheduling, and accrual capabilities for hourly and salaried employees.
  name: UKG Workforce Management
  slug: workforce-management
common:
- title: ''
  type: Website
  url: https://www.ukg.com
- title: ''
  type: Documentation
  url: https://developer.ukg.com
- title: ''
  type: Portal
  url: https://developer.ukg.com
- title: ''
  type: Blog
  url: https://www.ukg.com/blog
- title: ''
  type: Pricing
  url: https://www.ukg.com/pricing
- title: ''
  type: TermsOfService
  url: https://www.ukg.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.ukg.com/legal/privacy-policy
- title: ''
  type: Support
  url: https://support.ukg.com
- title: ''
  type: GettingStarted
  url: https://developer.ukg.com/general/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.ukg.com/hcm/docs/authentication
- title: ''
  type: Signup
  url: https://www.ukg.com/contact-us
- title: ''
  type: SpectralRules
  url: rules/ukg-spectral-rules.yml
- title: Workforce Management
  type: NaftikoCapability
  url: capabilities/workforce-management.yaml
- title: HR Administration
  type: NaftikoCapability
  url: capabilities/hr-administration.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/ukg-vocabulary.yaml
created: '2025-02-08'
description: UKG (Ultimate Kronos Group) is an enterprise human capital management (HCM) and workforce management platform serving over 80,000 organizations worldwide. The UKG Pro suite includes HCM APIs for employee data, payroll, benefits, and personnel actions, plus WFM APIs for time and labor management, scheduling, accruals, and attendance. The UKG Developer Hub provides REST APIs, webhook subscriptions, and People Fabric APIs for building HR integrations, payroll connectors, and workforce analytics applications.
features:
- description: Comprehensive HCM covering employee records, org management, talent, and compliance for enterprise organizations.
  name: Human Capital Management
- description: Full-service payroll with tax compliance, direct deposit, pay statements, and multi-state support.
  name: Payroll Processing
- description: Benefits enrollment, plan management, life event processing, and ACA compliance tracking.
  name: Benefits Administration
- description: Automated timekeeping with punch clocks, mobile entry, approval workflows, and FLSA compliance.
  name: Time and Attendance
- description: AI-powered scheduling with demand forecasting, shift management, and coverage optimization.
  name: Workforce Scheduling
- description: Configurable vacation, sick, and PTO accrual policies with automated balance tracking.
  name: Accrual Management
- description: Employee case management, knowledge portal, HR document management, and process automation.
  name: HR Service Delivery
- description: Unified data platform connecting HCM and WFM data across all UKG products via modern APIs.
  name: People Fabric
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sync employee data between UKG and Salesforce for HR-CRM alignment.
  name: Salesforce
- description: Integrate with SAP ERP for GL posting, cost center management, and financial reconciliation.
  name: SAP
- description: Single sign-on and user provisioning integration with Microsoft Entra ID.
  name: Microsoft Azure AD
- description: Employee data exchange for organizations using both platforms during migration or hybrid scenarios.
  name: Workday
- description: Payroll data exchange with ADP for organizations using both HCM and payroll platforms.
  name: ADP
- description: Applicant tracking system integration for recruiting and onboarding handoff.
  name: Greenhouse
jsonld:
- class_count: 13
  name: Ukg Pro Hcm Context
  property_count: 62
  slug: ukg-pro-hcm-context
- class_count: 6
  name: Ukg Pro Wfm Context
  property_count: 28
  slug: ukg-pro-wfm-context
layout: provider
modified: '2026-05-03'
name: UKG
rules:
- name: UKG API Rules
  rule_count: 30
  severity_counts:
    error: 14
    hint: 0
    info: 4
    warn: 12
  slug: ukg-spectral-rules
skills: []
slug: ukg
solutions:
- description: Enterprise HCM platform for mid-market and enterprise organizations with full HR, payroll, and talent capabilities.
  name: UKG Pro
- description: Workforce management platform for hourly and complex workforce scheduling, timekeeping, and compliance.
  name: UKG Pro WFM
- description: Simplified HCM solution for small and medium businesses with combined HR, payroll, and time management.
  name: UKG Ready
- description: Employee experience platform for HR case management, knowledge delivery, and document compliance.
  name: UKG HR Service Delivery
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ukg\nname: UKG\ndescription: >-\n  UKG (Ultimate Kronos Group) is an enterprise human capital management (HCM)\n  and workforce management platform serving over 80,000 organizations worldwide.\n  The UKG Pro suite includes HCM APIs for employee data, payroll, benefits, and\n  personnel actions, plus WFM APIs for time and labor management, scheduling,\n  accruals, and attendance. The UKG Developer Hub provides REST APIs, webhook\n  subscriptions, and People Fabric APIs for building HR integrations, payroll\n  connectors, and workforce analytics applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Human Capital Management\n  - HCM\n  - Workforce Management\n  - HR\n  - Payroll\n  - Time and Attendance\n  - Benefits\n  - Scheduling\nurl: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/apis.yml\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ ukg:ukg-pro-hcm-api\n    name: UKG Pro HCM API\n    description: >-\n      The UKG Pro HCM API provides programmatic access to human capital\n      management data including employees, personnel actions, benefits, payroll,\n      performance, and organizational structure. Uses Basic Authentication with\n      service account credentials and tenant-specific API keys. Enables\n      integrations with HR systems, payroll processors, benefits administrators,\n      and workforce analytics platforms.\n    humanURL: https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api\n    baseURL: https://service.ultipro.com\n    tags:\n      - HCM\n      - Employees\n      - Payroll\n      - Benefits\n      - Personnel Actions\n    properties:\n      - type: Documentation\n        url: https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api\n      - type: OpenAPI\n        url: openapi/ukg-pro-hcm-openapi.yml\n      - type: JSONSchema\n        url: json-schema/pro-hcm-employee-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/pro-hcm-employee-job-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-pay-rate-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-benefits-election-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-department-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-location-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-pay-statement-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-direct-deposit-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-personnel-change-request-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-personnel-change-response-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-employee-list-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-hcm-employee-id-list-schema.json\n      - type: JSONStructure\n      \
  \  url: json-structure/pro-hcm-employee-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-employee-job-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-pay-rate-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-benefits-election-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-department-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-location-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-pay-statement-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-direct-deposit-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-personnel-change-request-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-personnel-change-response-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-hcm-employee-list-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/pro-hcm-employee-id-list-structure.json\n      - type: JSONLDContext\n        url: json-ld/ukg-pro-hcm-context.jsonld\n      - type: Example\n        url: examples/pro-hcm-employee-example.json\n      - type: Example\n        url: examples/pro-hcm-employee-job-example.json\n      - type: Example\n        url: examples/pro-hcm-pay-rate-example.json\n      - type: Example\n        url: examples/pro-hcm-benefits-election-example.json\n      - type: Example\n        url: examples/pro-hcm-department-example.json\n      - type: Example\n        url: examples/pro-hcm-location-example.json\n      - type: Example\n        url: examples/pro-hcm-pay-statement-example.json\n      - type: Example\n        url: examples/pro-hcm-direct-deposit-example.json\n      - type: Example\n        url: examples/pro-hcm-personnel-change-request-example.json\n      - type: Example\n        url: examples/pro-hcm-personnel-change-response-example.json\n   \
  \   - type: Example\n        url: examples/pro-hcm-employee-list-example.json\n      - type: Example\n        url: examples/pro-hcm-employee-id-list-example.json\n  - aid: ukg:ukg-pro-wfm-api\n    name: UKG Pro Workforce Management API\n    description: >-\n      The UKG Pro WFM API provides programmatic access to time and labor\n      management data including punches, shifts, schedules, accruals, and\n      attendance. Supports timekeeping, scheduling, and compliance workflows\n      for hourly and salaried employees. Uses OAuth 2.0 with tenant API keys.\n    humanURL: https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api\n    baseURL: https://api.ultipro.com/workforce/v1\n    tags:\n      - Workforce Management\n      - Time and Attendance\n      - Scheduling\n      - Accruals\n      - Timekeeping\n    properties:\n      - type: Documentation\n        url: https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api\n    \
  \  - type: OpenAPI\n        url: openapi/ukg-pro-wfm-openapi.yml\n      - type: JSONSchema\n        url: json-schema/pro-wfm-wfm-employee-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-wfm-timecard-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-wfm-punch-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-wfm-punch-request-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-wfm-accrual-balance-schema.json\n      - type: JSONSchema\n        url: json-schema/pro-wfm-shift-schema.json\n      - type: JSONStructure\n        url: json-structure/pro-wfm-wfm-employee-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-wfm-timecard-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-wfm-punch-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-wfm-punch-request-structure.json\n      - type: JSONStructure\n        url: json-structure/pro-wfm-accrual-balance-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/pro-wfm-shift-structure.json\n      - type: JSONLDContext\n        url: json-ld/ukg-pro-wfm-context.jsonld\n      - type: Example\n        url: examples/pro-wfm-wfm-employee-example.json\n      - type: Example\n        url: examples/pro-wfm-timecard-example.json\n      - type: Example\n        url: examples/pro-wfm-punch-example.json\n      - type: Example\n        url: examples/pro-wfm-punch-request-example.json\n      - type: Example\n        url: examples/pro-wfm-accrual-balance-example.json\n      - type: Example\n        url: examples/pro-wfm-shift-example.json\n  - aid: ukg:ukg-hr-service-delivery-api\n    name: UKG HR Service Delivery API\n    description: >-\n      The UKG HR Service Delivery API (formerly People Doc) provides access to\n      employee request management, knowledge portal content, process automation,\n      document storage, and compliance workflows. Enables HR case management\n      integrations and employee\
  \ self-service applications.\n    humanURL: https://doc.people-doc.com/api/?urls.primaryName=Client\n    baseURL: https://api.people-doc.com\n    tags:\n      - HR Service Delivery\n      - Case Management\n      - Document Management\n      - Employee Requests\n    properties:\n      - type: Documentation\n        url: https://doc.people-doc.com/api/?urls.primaryName=Client\n      - type: APIReference\n        url: https://doc.people-doc.com/client/api/index-v2.html\ncommon:\n  - type: Website\n    url: https://www.ukg.com\n  - type: Documentation\n    url: https://developer.ukg.com\n  - type: Portal\n    url: https://developer.ukg.com\n  - type: Blog\n    url: https://www.ukg.com/blog\n  - type: Pricing\n    url: https://www.ukg.com/pricing\n  - type: TermsOfService\n    url: https://www.ukg.com/legal/terms\n  - type: PrivacyPolicy\n    url: https://www.ukg.com/legal/privacy-policy\n  - type: Support\n    url: https://support.ukg.com\n  - type: GettingStarted\n    url: https://developer.ukg.com/general/docs/getting-started\n\
  \  - type: Authentication\n    url: https://developer.ukg.com/hcm/docs/authentication\n  - type: Signup\n    url: https://www.ukg.com/contact-us\n  - type: SpectralRules\n    url: rules/ukg-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/workforce-management.yaml\n    title: Workforce Management\n  - type: NaftikoCapability\n    url: capabilities/hr-administration.yaml\n    title: HR Administration\n  - type: Vocabulary\n    url: vocabulary/ukg-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Human Capital Management\n        description: Comprehensive HCM covering employee records, org management, talent, and compliance for enterprise organizations.\n      - name: Payroll Processing\n        description: Full-service payroll with tax compliance, direct deposit, pay statements, and multi-state support.\n      - name: Benefits Administration\n        description: Benefits enrollment, plan management, life event processing, and ACA compliance tracking.\n\
  \      - name: Time and Attendance\n        description: Automated timekeeping with punch clocks, mobile entry, approval workflows, and FLSA compliance.\n      - name: Workforce Scheduling\n        description: AI-powered scheduling with demand forecasting, shift management, and coverage optimization.\n      - name: Accrual Management\n        description: Configurable vacation, sick, and PTO accrual policies with automated balance tracking.\n      - name: HR Service Delivery\n        description: Employee case management, knowledge portal, HR document management, and process automation.\n      - name: People Fabric\n        description: Unified data platform connecting HCM and WFM data across all UKG products via modern APIs.\n  - type: UseCases\n    data:\n      - name: Payroll Integration\n        description: Sync employee pay data, deductions, and tax information with third-party payroll processors and ERP systems.\n      - name: Benefits Connector\n        description: Exchange enrollment\
  \ data and eligibility with benefits carriers, insurance providers, and benefits administration systems.\n      - name: Time and Labor Integration\n        description: Import punch data, approved timecards, and schedule information into payroll and workforce analytics platforms.\n      - name: HRIS Data Sync\n        description: Keep employee demographic, job, and organizational data synchronized between UKG and downstream business systems.\n      - name: Analytics and Reporting\n        description: Export workforce data to business intelligence tools and data warehouses for advanced analytics and reporting.\n      - name: Onboarding Automation\n        description: Automate new hire provisioning by triggering downstream system access and equipment setup from UKG hire events.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Sync employee data between UKG and Salesforce for HR-CRM alignment.\n      - name: SAP\n        description: Integrate with SAP\
  \ ERP for GL posting, cost center management, and financial reconciliation.\n      - name: Microsoft Azure AD\n        description: Single sign-on and user provisioning integration with Microsoft Entra ID.\n      - name: Workday\n        description: Employee data exchange for organizations using both platforms during migration or hybrid scenarios.\n      - name: ADP\n        description: Payroll data exchange with ADP for organizations using both HCM and payroll platforms.\n      - name: Greenhouse\n        description: Applicant tracking system integration for recruiting and onboarding handoff.\n  - type: Solutions\n    data:\n      - name: UKG Pro\n        description: Enterprise HCM platform for mid-market and enterprise organizations with full HR, payroll, and talent capabilities.\n      - name: UKG Pro WFM\n        description: Workforce management platform for hourly and complex workforce scheduling, timekeeping, and compliance.\n      - name: UKG Ready\n        description: Simplified\
  \ HCM solution for small and medium businesses with combined HR, payroll, and time management.\n      - name: UKG HR Service Delivery\n        description: Employee experience platform for HR case management, knowledge delivery, and document compliance.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/apis.yml
tags:
- Human Capital Management
- HCM
- Workforce Management
- HR
- Payroll
- Time and Attendance
- Benefits
- Scheduling
url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/apis.yml
use_cases:
- description: Sync employee pay data, deductions, and tax information with third-party payroll processors and ERP systems.
  name: Payroll Integration
- description: Exchange enrollment data and eligibility with benefits carriers, insurance providers, and benefits administration systems.
  name: Benefits Connector
- description: Import punch data, approved timecards, and schedule information into payroll and workforce analytics platforms.
  name: Time and Labor Integration
- description: Keep employee demographic, job, and organizational data synchronized between UKG and downstream business systems.
  name: HRIS Data Sync
- description: Export workforce data to business intelligence tools and data warehouses for advanced analytics and reporting.
  name: Analytics and Reporting
- description: Automate new hire provisioning by triggering downstream system access and equipment setup from UKG hire events.
  name: Onboarding Automation
---
