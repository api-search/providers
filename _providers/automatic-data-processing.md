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
