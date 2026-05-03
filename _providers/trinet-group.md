---
api_count: 5
apis:
- description: The TriNet Company API provides access to company-level HR data including organizational structure, departments, holiday schedules, workers compensation codes, and company configuration. Used by HR ad
  name: TriNet Company API
  slug: company-api
- description: The TriNet Employees API provides full lifecycle employee data management including retrieving all employee details, adding new employees (onboarding), and managing employee records. Supports HR workf
  name: TriNet Employees API
  slug: employees-api
- description: 'The TriNet Payroll API provides access to employee payroll and compensation data including pay rates, pay frequency, bonuses, and additional pay components. Enables integration with financial systems '
  name: TriNet Payroll API
  slug: payroll-api
- description: The TriNet Identity API provides access to employee identity and sensitive personally identifiable information (PII) such as Social Security Numbers for authorized systems. Access is strictly scoped a
  name: TriNet Identity API
  slug: identity-api
- description: The TriNet Manage Employee API enables management of employee roles and access permissions within the TriNet platform. Supports HR administrators in assigning, updating, and auditing employee roles fo
  name: TriNet Manage Employee API
  slug: manage-employee-api
common:
- title: ''
  type: Website
  url: https://www.trinet.com
- title: ''
  type: DeveloperPortal
  url: https://apidocs.trinet.com/home
- title: ''
  type: Documentation
  url: https://apidocs.trinet.com/home
- title: ''
  type: Authentication
  url: https://apidocs.trinet.com/oauth-scopes
- title: ''
  type: PartnerProgram
  url: https://www.trinet.com/hr-services/technology-platform/integration-center
- title: ''
  type: PrivacyPolicy
  url: https://www.trinet.com/privacy-policy
created: '2026-03-24'
description: TriNet Group is a professional employer organization (PEO) providing small and midsize businesses with full-service human resources solutions including payroll processing, employee benefits administration, risk management, compliance, and HR technology. TriNet serves over 16,000 companies and 340,000 worksite employees across verticals including technology, financial services, life sciences, professional services, and nonprofits.
features:
- name: Payroll Processing
- name: Benefits Administration
- name: Risk Management
- name: Compliance Support
- name: HR Technology Platform
- name: Employee Onboarding
- name: Time and Attendance
- name: Workers Compensation
- name: Expense Management
- name: Performance Management
- name: Learning and Development
- name: QuickBooks Online Integration
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: QuickBooks Online
- name: Salesforce
- name: Slack
- name: Microsoft Teams
- name: Google Workspace
- name: Okta
- name: Finch
- name: Merge
- name: Apideck
layout: provider
modified: '2026-05-03'
name: TriNet Group
skills: []
slug: trinet-group
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trinet-group\nurl: https://raw.githubusercontent.com/api-evangelist/trinet-group/refs/heads/main/apis.yml\nname: TriNet Group\ndescription: >-\n  TriNet Group is a professional employer organization (PEO) providing small and midsize\n  businesses with full-service human resources solutions including payroll processing,\n  employee benefits administration, risk management, compliance, and HR technology.\n  TriNet serves over 16,000 companies and 340,000 worksite employees across verticals\n  including technology, financial services, life sciences, professional services, and\n  nonprofits.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Benefits\n  - Compliance\n  - Human Resources\n  - Payroll\n  - Professional Employer Organization\n  - Risk Management\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trinet-group:company-api\n    name: TriNet Company API\n    tags:\n      - Company\n\
  \      - Departments\n      - Human Resources\n      - Holidays\n      - Workers Compensation\n    humanURL: https://apidocs.trinet.com/home\n    baseURL: https://api.trinet.com\n    properties:\n      - type: Documentation\n        url: https://apidocs.trinet.com/home\n    description: >-\n      The TriNet Company API provides access to company-level HR data including\n      organizational structure, departments, holiday schedules, workers compensation\n      codes, and company configuration. Used by HR administrators to retrieve\n      organizational metadata and policy information.\n\n  - aid: trinet-group:employees-api\n    name: TriNet Employees API\n    tags:\n      - Employees\n      - Human Resources\n      - Onboarding\n      - Workforce Management\n    humanURL: https://apidocs.trinet.com/home\n    baseURL: https://api.trinet.com\n    properties:\n      - type: Documentation\n        url: https://apidocs.trinet.com/home\n    description: >-\n      The TriNet Employees API provides\
  \ full lifecycle employee data management\n      including retrieving all employee details, adding new employees (onboarding),\n      and managing employee records. Supports HR workflows for workforce visibility\n      and headcount reporting.\n\n  - aid: trinet-group:payroll-api\n    name: TriNet Payroll API\n    tags:\n      - Compensation\n      - Human Resources\n      - Pay\n      - Payroll\n    humanURL: https://apidocs.trinet.com/home\n    baseURL: https://api.trinet.com\n    properties:\n      - type: Documentation\n        url: https://apidocs.trinet.com/home\n    description: >-\n      The TriNet Payroll API provides access to employee payroll and compensation data\n      including pay rates, pay frequency, bonuses, and additional pay components.\n      Enables integration with financial systems and compensation analytics platforms.\n\n  - aid: trinet-group:identity-api\n    name: TriNet Identity API\n    tags:\n      - Authentication\n      - Identity\n      - Security\n   \
  \ humanURL: https://apidocs.trinet.com/home\n    baseURL: https://api.trinet.com\n    properties:\n      - type: Documentation\n        url: https://apidocs.trinet.com/home\n    description: >-\n      The TriNet Identity API provides access to employee identity and sensitive\n      personally identifiable information (PII) such as Social Security Numbers\n      for authorized systems. Access is strictly scoped and requires elevated\n      permissions for compliance with data privacy regulations.\n\n  - aid: trinet-group:manage-employee-api\n    name: TriNet Manage Employee API\n    tags:\n      - Employee Management\n      - Human Resources\n      - Roles\n      - Workforce Management\n    humanURL: https://apidocs.trinet.com/home\n    baseURL: https://api.trinet.com\n    properties:\n      - type: Documentation\n        url: https://apidocs.trinet.com/home\n    description: >-\n      The TriNet Manage Employee API enables management of employee roles and\n      access permissions within\
  \ the TriNet platform. Supports HR administrators\n      in assigning, updating, and auditing employee roles for system access control.\n\ncommon:\n  - type: Website\n    url: https://www.trinet.com\n    name: TriNet\n  - type: DeveloperPortal\n    url: https://apidocs.trinet.com/home\n    name: TriNet API Portal\n  - type: Documentation\n    url: https://apidocs.trinet.com/home\n    name: TriNet API Documentation\n  - type: Authentication\n    url: https://apidocs.trinet.com/oauth-scopes\n    name: TriNet OAuth Scopes\n  - type: PartnerProgram\n    url: https://www.trinet.com/hr-services/technology-platform/integration-center\n    name: TriNet Integration Center\n  - type: Integrations\n    url: https://www.trinet.com/hr-services/technology-platform/integration-center/api\n    name: TriNet API Integrations\n  - type: PrivacyPolicy\n    url: https://www.trinet.com/privacy-policy\n    name: TriNet Privacy Policy\n  - name: Features\n    type: Features\n    data:\n      - name: Payroll Processing\n\
  \      - name: Benefits Administration\n      - name: Risk Management\n      - name: Compliance Support\n      - name: HR Technology Platform\n      - name: Employee Onboarding\n      - name: Time and Attendance\n      - name: Workers Compensation\n      - name: Expense Management\n      - name: Performance Management\n      - name: Learning and Development\n      - name: QuickBooks Online Integration\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: QuickBooks Online\n      - name: Salesforce\n      - name: Slack\n      - name: Microsoft Teams\n      - name: Google Workspace\n      - name: Okta\n      - name: Finch\n      - name: Merge\n      - name: Apideck\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Employee Data Sync\n      - name: Payroll Integration\n      - name: Benefits Enrollment Automation\n      - name: HR System Integration\n      - name: Compliance Reporting\n      - name: Onboarding Automation\n      - name: Headcount Reporting\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trinet-group/refs/heads/main/apis.yml
tags:
- Benefits
- Compliance
- Human Resources
- Payroll
- Professional Employer Organization
- Risk Management
url: https://raw.githubusercontent.com/api-evangelist/trinet-group/refs/heads/main/apis.yml
use_cases:
- name: Employee Data Sync
- name: Payroll Integration
- name: Benefits Enrollment Automation
- name: HR System Integration
- name: Compliance Reporting
- name: Onboarding Automation
- name: Headcount Reporting
---
