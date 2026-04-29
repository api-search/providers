---
api_count: 6
apis:
- description: The ADP Payroll API provides programmatic access to payroll processing capabilities including earnings, deductions, pay statements, and payroll runs for employees across ADP Workforce Now and ADP Vant
  name: ADP Payroll API
  slug: payroll-api
- description: The ADP Workers API provides access to employee demographic and employment data including personal information, job assignments, pay rates, reporting relationships, and employment status. Supports CRU
  name: ADP Worker Demographics API
  slug: worker-api
- description: The ADP Time and Labor API enables integration with ADP's timekeeping system for time entries, schedules, time off requests, accruals, and labor cost allocation. Supports both ADP Workforce Now and AD
  name: ADP Time and Labor API
  slug: time-labor-api
- description: The ADP Benefits API provides access to employee benefits enrollment, plan data, coverage elections, and life event processing. Enables HR system integrations with benefits carriers and third-party be
  name: ADP Benefits API
  slug: benefits-api
- description: The ADP Talent Management API provides access to performance reviews, goal management, succession planning, and learning management data within the ADP platform. Enables integration with third-party t
  name: ADP Talent Management API
  slug: talent-api
- description: 'The ADP Recruiting API enables integration with ADP''s applicant tracking system for job postings, candidate management, offer letters, and new hire onboarding workflows. Connects with third-party ATS '
  name: ADP Recruiting API
  slug: recruiting-api
common:
- title: ''
  type: Portal
  url: https://developers.adp.com
- title: ''
  type: Website
  url: https://www.adp.com
- title: ''
  type: Documentation
  url: https://developers.adp.com/articles/api/all
- title: ''
  type: GettingStarted
  url: https://developers.adp.com/articles/guide/adp-marketplace-app-intro
- title: ''
  type: Authentication
  url: https://developers.adp.com/articles/guide/auth-process-data-conn-mgr-mngd-oauth2
- title: ''
  type: SignUp
  url: https://developers.adp.com/articles/guide/registration
- title: ''
  type: Marketplace
  url: https://apps.adp.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/adplabs
- title: ''
  type: Support
  url: https://developers.adp.com/articles/guide/support
created: '2026-03-21'
description: Automatic Data Processing (ADP) is a global provider of cloud-based human capital management (HCM) solutions including payroll processing, benefits administration, talent management, time and attendance, workforce analytics, and tax compliance services. ADP serves over 1 million businesses worldwide and provides a comprehensive developer platform with REST APIs, SDKs, and marketplace integrations for HCM system connectivity.
features:
- description: ADP APIs use OAuth 2.0 with client credentials and authorization code flows for secure access. Mutual TLS (mTLS) is required for production connections.
  name: OAuth 2.0 Authentication
- description: ADP provides a developer sandbox environment with synthetic data for testing integrations before production deployment.
  name: Sandbox Environment
- description: ADP Marketplace allows ISVs to publish and monetize HCM integrations accessible to ADP's one million plus client base through the app store.
  name: Marketplace Integration
- description: Event-driven notifications for HR data changes including hire events, terminations, payroll completions, and benefits enrollment changes.
  name: Webhooks and Events
- description: ADP Data Connector provides managed OAuth2 connections and data sync for partner integrations without custom authentication management.
  name: Data Connector
image: ''
integrations:
- description: Sync ADP HR data with Salesforce for commission calculations, quota management, and employee-customer relationship tracking.
  name: Salesforce
- description: Bidirectional integration between ADP payroll and SAP SuccessFactors for HCM data synchronization across enterprise systems.
  name: SAP SuccessFactors
- description: Connect ADP employee data with Microsoft Teams, Active Directory, and SharePoint for identity management and org chart synchronization.
  name: Microsoft 365
- description: Integration between ADP payroll services and Workday HCM for organizations running split HCM/payroll configurations.
  name: Workday
- description: Sync ADP payroll data with QuickBooks for journal entry and labor cost posting in small business accounting workflows.
  name: QuickBooks
layout: provider
modified: '2026-04-19'
name: Automatic Data Processing (ADP)
skills: []
slug: automatic-data-processing
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: automatic-data-processing\nname: Automatic Data Processing (ADP)\ndescription: >-\n  Automatic Data Processing (ADP) is a global provider of cloud-based human capital\n  management (HCM) solutions including payroll processing, benefits administration,\n  talent management, time and attendance, workforce analytics, and tax compliance services.\n  ADP serves over 1 million businesses worldwide and provides a comprehensive developer\n  platform with REST APIs, SDKs, and marketplace integrations for HCM system connectivity.\nurl: https://raw.githubusercontent.com/api-evangelist/automatic-data-processing/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n  - HCM\n  - Human Capital Management\n  - HR\n  - Payroll\n  - Benefits\n  - Workforce Management\n  - Tax Compliance\n  - Enterprise\napis:\n  - aid: automatic-data-processing:payroll-api\n    name: ADP Payroll API\n    description: >-\n      The ADP Payroll API provides\
  \ programmatic access to payroll processing\n      capabilities including earnings, deductions, pay statements, and payroll\n      runs for employees across ADP Workforce Now and ADP Vantage HCM platforms.\n      Supports payroll input, calculation, and retrieval of pay data.\n    humanURL: https://developers.adp.com/articles/api/payroll\n    baseURL: https://api.adp.com\n    tags:\n      - Payroll\n      - Earnings\n      - Deductions\n      - Pay Statements\n      - Tax\n    properties:\n      - type: Documentation\n        url: https://developers.adp.com/articles/api/payroll\n      - type: Portal\n        url: https://developers.adp.com\n\n  - aid: automatic-data-processing:worker-api\n    name: ADP Worker Demographics API\n    description: >-\n      The ADP Workers API provides access to employee demographic and employment\n      data including personal information, job assignments, pay rates, reporting\n      relationships, and employment status. Supports CRUD operations on worker\n\
  \      records across ADP HCM platforms.\n    humanURL: https://developers.adp.com/articles/api/workers\n    baseURL: https://api.adp.com\n    tags:\n      - Worker Demographics\n      - Employee Data\n      - HR\n      - Workforce\n    properties:\n      - type: Documentation\n        url: https://developers.adp.com/articles/api/workers\n      - type: Portal\n        url: https://developers.adp.com\n\n  - aid: automatic-data-processing:time-labor-api\n    name: ADP Time and Labor API\n    description: >-\n      The ADP Time and Labor API enables integration with ADP's timekeeping\n      system for time entries, schedules, time off requests, accruals, and\n      labor cost allocation. Supports both ADP Workforce Now and ADP Vantage\n      time management modules.\n    humanURL: https://developers.adp.com/articles/api/time-labor-management\n    baseURL: https://api.adp.com\n    tags:\n      - Time and Attendance\n      - Scheduling\n      - Timekeeping\n      - Labor Management\n    properties:\n\
  \      - type: Documentation\n        url: https://developers.adp.com/articles/api/time-labor-management\n      - type: Portal\n        url: https://developers.adp.com\n\n  - aid: automatic-data-processing:benefits-api\n    name: ADP Benefits API\n    description: >-\n      The ADP Benefits API provides access to employee benefits enrollment,\n      plan data, coverage elections, and life event processing. Enables HR\n      system integrations with benefits carriers and third-party benefits\n      administration platforms.\n    humanURL: https://developers.adp.com/articles/api/benefits\n    baseURL: https://api.adp.com\n    tags:\n      - Benefits\n      - Enrollment\n      - Healthcare\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://developers.adp.com/articles/api/benefits\n      - type: Portal\n        url: https://developers.adp.com\n\n  - aid: automatic-data-processing:talent-api\n    name: ADP Talent Management API\n    description: >-\n    \
  \  The ADP Talent Management API provides access to performance reviews,\n      goal management, succession planning, and learning management data\n      within the ADP platform. Enables integration with third-party talent\n      and learning management systems.\n    humanURL: https://developers.adp.com/articles/api/talent-management\n    baseURL: https://api.adp.com\n    tags:\n      - Talent Management\n      - Performance Reviews\n      - Learning\n      - Succession Planning\n    properties:\n      - type: Documentation\n        url: https://developers.adp.com/articles/api/talent-management\n      - type: Portal\n        url: https://developers.adp.com\n\n  - aid: automatic-data-processing:recruiting-api\n    name: ADP Recruiting API\n    description: >-\n      The ADP Recruiting API enables integration with ADP's applicant tracking\n      system for job postings, candidate management, offer letters, and\n      new hire onboarding workflows. Connects with third-party ATS platforms\n\
  \      and job boards.\n    humanURL: https://developers.adp.com/articles/api/recruiting\n    baseURL: https://api.adp.com\n    tags:\n      - Recruiting\n      - Applicant Tracking\n      - Onboarding\n      - HR\n    properties:\n      - type: Documentation\n        url: https://developers.adp.com/articles/api/recruiting\n      - type: Portal\n        url: https://developers.adp.com\n\ncommon:\n  - type: Portal\n    url: https://developers.adp.com\n  - type: Website\n    url: https://www.adp.com\n  - type: Documentation\n    url: https://developers.adp.com/articles/api/all\n  - type: GettingStarted\n    url: https://developers.adp.com/articles/guide/adp-marketplace-app-intro\n  - type: Authentication\n    url: https://developers.adp.com/articles/guide/auth-process-data-conn-mgr-mngd-oauth2\n  - type: SignUp\n    url: https://developers.adp.com/articles/guide/registration\n  - type: Marketplace\n    url: https://apps.adp.com\n  - type: GitHubOrganization\n    url: https://github.com/adplabs\n\
  \  - type: Support\n    url: https://developers.adp.com/articles/guide/support\n  - type: Features\n    data:\n      - name: OAuth 2.0 Authentication\n        description: >-\n          ADP APIs use OAuth 2.0 with client credentials and authorization code\n          flows for secure access. Mutual TLS (mTLS) is required for production\n          connections.\n      - name: Sandbox Environment\n        description: >-\n          ADP provides a developer sandbox environment with synthetic data for\n          testing integrations before production deployment.\n      - name: Marketplace Integration\n        description: >-\n          ADP Marketplace allows ISVs to publish and monetize HCM integrations\n          accessible to ADP's one million plus client base through the app store.\n      - name: Webhooks and Events\n        description: >-\n          Event-driven notifications for HR data changes including hire events,\n          terminations, payroll completions, and benefits enrollment\
  \ changes.\n      - name: Data Connector\n        description: >-\n          ADP Data Connector provides managed OAuth2 connections and data sync\n          for partner integrations without custom authentication management.\n  - type: UseCases\n    data:\n      - name: Payroll Integration\n        description: >-\n          Connect HRIS, ERP, and time management systems to ADP payroll for\n          automated payroll input and pay statement distribution.\n      - name: HR Data Sync\n        description: >-\n          Synchronize employee records between ADP and third-party HRIS,\n          talent management, and workforce planning systems.\n      - name: Benefits Carrier Connectivity\n        description: >-\n          Connect benefits carriers and insurance providers with ADP enrollment\n          data for real-time eligibility and coverage updates.\n      - name: Onboarding Automation\n        description: >-\n          Automate new hire workflows from ATS to payroll including I-9, direct\n\
  \          deposit setup, and benefits enrollment using ADP APIs.\n      - name: Workforce Analytics\n        description: >-\n          Pull ADP workforce data into BI platforms for headcount, compensation,\n          turnover, and labor cost analysis.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: >-\n          Sync ADP HR data with Salesforce for commission calculations, quota\n          management, and employee-customer relationship tracking.\n      - name: SAP SuccessFactors\n        description: >-\n          Bidirectional integration between ADP payroll and SAP SuccessFactors\n          for HCM data synchronization across enterprise systems.\n      - name: Microsoft 365\n        description: >-\n          Connect ADP employee data with Microsoft Teams, Active Directory, and\n          SharePoint for identity management and org chart synchronization.\n      - name: Workday\n        description: >-\n          Integration between ADP payroll services\
  \ and Workday HCM for\n          organizations running split HCM/payroll configurations.\n      - name: QuickBooks\n        description: >-\n          Sync ADP payroll data with QuickBooks for journal entry and labor\n          cost posting in small business accounting workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/automatic-data-processing/refs/heads/main/apis.yml
tags:
- HCM
- Human Capital Management
- HR
- Payroll
- Benefits
- Workforce Management
- Tax Compliance
- Enterprise
url: https://raw.githubusercontent.com/api-evangelist/automatic-data-processing/refs/heads/main/apis.yml
use_cases:
- description: Connect HRIS, ERP, and time management systems to ADP payroll for automated payroll input and pay statement distribution.
  name: Payroll Integration
- description: Synchronize employee records between ADP and third-party HRIS, talent management, and workforce planning systems.
  name: HR Data Sync
- description: Connect benefits carriers and insurance providers with ADP enrollment data for real-time eligibility and coverage updates.
  name: Benefits Carrier Connectivity
- description: Automate new hire workflows from ATS to payroll including I-9, direct deposit setup, and benefits enrollment using ADP APIs.
  name: Onboarding Automation
- description: Pull ADP workforce data into BI platforms for headcount, compensation, turnover, and labor cost analysis.
  name: Workforce Analytics
---
