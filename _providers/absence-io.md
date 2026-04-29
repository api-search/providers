---
api_count: 1
apis:
- description: Absence.io REST API v2 allows seamless integration of absence management features into software applications. Retrieve, create, update, and delete records for absences, users, allowances, departments,
  name: Absence.io API
  slug: absence-io
capabilities:
- description: 'Unified workflow for managing employee absences, tracking leave balances, and administering organizational structure in Absence.io. Designed for HR managers, payroll teams, and integration developers '
  name: Absence.io Absence Management
  slug: absence-management
common:
- title: ''
  type: Pricing
  url: https://www.absence.io/pricing/pricing-packages/
- title: ''
  type: Authentication
  url: https://docs.absence.io/#authentication
- title: ''
  type: Blog
  url: https://blog.absence.io/en/
- title: ''
  type: Partners
  url: https://promo.absence.io/partner-program
- title: ''
  type: TermsOfService
  url: https://www.absence.io/terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.absence.io/privacy-notice/
- title: ''
  type: SpectralRules
  url: rules/absence-io-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/absence-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/absence-io.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/absence-io-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/absence-io-context.jsonld
created: '2025-02-17'
description: Absence.io is an innovative and efficient leave management software that simplifies the process of tracking and managing employee absences. It provides a centralized platform for both employees and managers to easily request, approve, and track time-off requests. Absence.io helps streamline communication and ensure transparency within an organization by providing real-time updates on employee availability and leave balances. The REST API v2 allows integration with absences, users, allowances, departments, locations, reason types, and timespans using Hawk authentication.
features:
- description: Create, approve, and track employee vacation, sick leave, and other absence types through a centralized platform.
  name: Absence Management
- description: Configure and track annual leave allowances per employee, including carryover management.
  name: Leave Allowances
- description: Configurable approval workflows for absence requests with manager notifications and audit trail.
  name: Approval Workflows
- description: Support for departments, locations, and teams to reflect your organization's hierarchy.
  name: Organizational Structure
- description: Customizable absence reason types (vacation, sick leave, parental leave, etc.) with color coding.
  name: Reason Types
- description: Define timespans with hours per day and days per week for accurate absence calculation.
  name: Working Time Configurations
- description: Full REST API for integrating absence management with ERP, HRIS, and other business systems using Hawk authentication.
  name: REST API v2
image: /assets/icons/absence-io.png
integrations:
- description: Integration with Slack for absence request notifications and team visibility.
  name: Slack
- description: Integration with Jira for project planning with awareness of team availability.
  name: Atlassian Jira
- description: Integration with SharePoint for absence calendar sharing and team visibility.
  name: SharePoint
- description: Sync absence records to Google Calendar for team scheduling visibility.
  name: Google Calendar
- description: Integration with Redmine project management for resource planning.
  name: Redmine
jsonld:
- class_count: 9
  name: Absence Io Context
  property_count: 28
  slug: absence-io-context
layout: provider
modified: '2026-04-19'
name: Absence.io
rules:
- name: Absence.io API Rules
  rule_count: 30
  severity_counts:
    error: 14
    hint: 0
    info: 5
    warn: 11
  slug: absence-io-spectral-rules
skills: []
slug: absence-io
solutions: []
source_yaml: "aid: absence-io\nurl: https://raw.githubusercontent.com/api-evangelist/absence-io/refs/heads/main/apis.yml\nname: Absence.io\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Absences\n  - Employees\n  - Leave Management\n  - HR\ndescription: >-\n  Absence.io is an innovative and efficient leave management software that simplifies\n  the process of tracking and managing employee absences. It provides a centralized\n  platform for both employees and managers to easily request, approve, and track time-off\n  requests. Absence.io helps streamline communication and ensure transparency within\n  an organization by providing real-time updates on employee availability and leave\n  balances. The REST API v2 allows integration with absences, users, allowances,\n  departments, locations, reason types, and timespans using Hawk authentication.\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n \
  \ - aid: absence-io:absence-io\n    name: Absence.io API\n    tags:\n      - Absences\n      - Employees\n      - Leave Management\n    humanURL: https://www.absence.io/\n    properties:\n      - type: Documentation\n        url: https://docs.absence.io/\n      - type: Authentication\n        url: https://docs.absence.io/#authentication\n      - type: OpenAPI\n        url: openapi/absence-io-openapi.yml\n      - type: SDK\n        url: https://www.npmjs.com/package/absence.io\n        title: Node.js SDK\n      - type: JSONSchema\n        url: json-schema/absence-schema.json\n        title: Absence Schema\n      - type: JSONSchema\n        url: json-schema/user-schema.json\n        title: User Schema\n      - type: JSONSchema\n        url: json-schema/allowance-schema.json\n        title: Allowance Schema\n    description: >-\n      Absence.io REST API v2 allows seamless integration of absence management features\n      into software applications. Retrieve, create, update, and delete records\
  \ for absences,\n      users, allowances, departments, locations, reason types, and timespans. All requests\n      and responses use JSON format with Hawk authentication.\ncommon:\n  - type: Pricing\n    url: https://www.absence.io/pricing/pricing-packages/\n  - type: Authentication\n    url: https://docs.absence.io/#authentication\n  - type: Blog\n    url: https://blog.absence.io/en/\n  - type: Partners\n    url: https://promo.absence.io/partner-program\n  - type: TermsOfService\n    url: https://www.absence.io/terms-and-conditions/\n  - type: PrivacyPolicy\n    url: https://www.absence.io/privacy-notice/\n  - type: Features\n    data:\n      - name: Absence Management\n        description: Create, approve, and track employee vacation, sick leave, and other absence types through a centralized platform.\n      - name: Leave Allowances\n        description: Configure and track annual leave allowances per employee, including carryover management.\n      - name: Approval Workflows\n     \
  \   description: Configurable approval workflows for absence requests with manager notifications and audit trail.\n      - name: Organizational Structure\n        description: Support for departments, locations, and teams to reflect your organization's hierarchy.\n      - name: Reason Types\n        description: Customizable absence reason types (vacation, sick leave, parental leave, etc.) with color coding.\n      - name: Working Time Configurations\n        description: Define timespans with hours per day and days per week for accurate absence calculation.\n      - name: REST API v2\n        description: Full REST API for integrating absence management with ERP, HRIS, and other business systems using Hawk authentication.\n  - type: UseCases\n    data:\n      - name: ERP Integration\n        description: Integrate absence data with ERP systems to automatically reflect employee availability and costs.\n      - name: HRIS Sync\n        description: Sync employee records between Absence.io\
  \ and HR information systems to maintain a single source of truth.\n      - name: Payroll Processing\n        description: Use absence and allowance data to calculate accurate payroll deductions and entitlements.\n      - name: Capacity Planning\n        description: Query team absence data to plan project staffing and identify scheduling conflicts.\n      - name: Absence Reporting\n        description: Generate custom reports on absence patterns, allowance usage, and team availability.\n      - name: Custom Dashboards\n        description: Pull absence and allowance data into custom HR dashboards and analytics tools.\n  - type: Integrations\n    data:\n      - name: Slack\n        description: Integration with Slack for absence request notifications and team visibility.\n      - name: Atlassian Jira\n        description: Integration with Jira for project planning with awareness of team availability.\n      - name: SharePoint\n        description: Integration with SharePoint for absence\
  \ calendar sharing and team visibility.\n      - name: Google Calendar\n        description: Sync absence records to Google Calendar for team scheduling visibility.\n      - name: Redmine\n        description: Integration with Redmine project management for resource planning.\n  - type: SpectralRules\n    url: rules/absence-io-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/absence-management.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/absence-io.yaml\n  - type: Vocabulary\n    url: vocabulary/absence-io-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/absence-io-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/absence-io/refs/heads/main/apis.yml
tags:
- Absences
- Employees
- Leave Management
- HR
url: https://raw.githubusercontent.com/api-evangelist/absence-io/refs/heads/main/apis.yml
use_cases:
- description: Integrate absence data with ERP systems to automatically reflect employee availability and costs.
  name: ERP Integration
- description: Sync employee records between Absence.io and HR information systems to maintain a single source of truth.
  name: HRIS Sync
- description: Use absence and allowance data to calculate accurate payroll deductions and entitlements.
  name: Payroll Processing
- description: Query team absence data to plan project staffing and identify scheduling conflicts.
  name: Capacity Planning
- description: Generate custom reports on absence patterns, allowance usage, and team availability.
  name: Absence Reporting
- description: Pull absence and allowance data into custom HR dashboards and analytics tools.
  name: Custom Dashboards
---
