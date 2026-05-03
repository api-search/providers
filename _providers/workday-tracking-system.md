---
api_count: 3
api_specs:
- filename: workday-tracking-system-time-tracking-openapi.yml
  format: yaml
  label: Workday Time Tracking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-time-tracking-openapi.yml
- filename: workday-tracking-system-absence-management-openapi.yml
  format: yaml
  label: Workday Absence Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-absence-management-openapi.yml
- filename: workday-tracking-system-scheduling-openapi.yml
  format: yaml
  label: Workday Scheduling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-scheduling-openapi.yml
apis:
- description: Manage employee time entries, time blocks, time clock events, work schedule assignments, and time requests within the Workday platform. Supports both individual and batch operations for enterprise wor
  name: Workday Time Tracking API
  slug: ''
- description: Track employee attendance, absences, leave requests, and time off balances in the Workday platform. Supports entering time off, requesting leave of absence, managing accrual balances, and processing r
  name: Workday Absence Management API
  slug: ''
- description: Create and manage employee work schedules, shifts, scheduling organizations, and labor demand within the Workday platform. Supports importing schedule data, managing shift assignments, and configuring
  name: Workday Scheduling API
  slug: ''
capabilities:
- description: Unified capability for managing the complete employee time lifecycle in Workday, combining Time Tracking and Absence Management APIs. Used by HR managers, payroll teams, and workforce administrators t
  name: Workday Workforce Time Management
  slug: workforce-time-management
common:
- title: ''
  type: Portal
  url: https://developer.workday.com
- title: ''
  type: GettingStarted
  url: https://developer.workday.com/getting-started
- title: ''
  type: Documentation
  url: https://docs.workday.com
- title: ''
  type: Authentication
  url: https://docs.workday.com/authentication/oauth2
- title: ''
  type: SignUp
  url: https://www.workday.com/en-us/forms/contact-sales.html
- title: ''
  type: Pricing
  url: https://www.workday.com/en-us/pricing.html
- title: ''
  type: RateLimits
  url: https://docs.workday.com/rate-limits
- title: ''
  type: StatusPage
  url: https://status.workday.com
- title: ''
  type: Support
  url: https://www.workday.com/en-us/company/latest/customer-support.html
- title: ''
  type: Community
  url: https://community.workday.com
- title: ''
  type: Blog
  url: https://blog.workday.com
- title: ''
  type: ReleaseNotes
  url: https://docs.workday.com/release-notes
- title: ''
  type: TermsOfService
  url: https://www.workday.com/en-us/terms-of-service.html
- title: ''
  type: PrivacyPolicy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/Workday
- title: ''
  type: JSON-LD
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-ld/workday-tracking-system-context.jsonld
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-leave-of-absence-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-time-block-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-timesheet-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-leave-of-absence-structure.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-time-block-structure.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-timesheet-structure.json
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/rules/workday-tracking-system-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/capabilities/workforce-time-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/capabilities/shared/time-tracking.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/capabilities/shared/absence-management.yaml
created: '2024-01-15'
description: APIs for managing employee time tracking, absence management, and workforce scheduling in the Workday platform. Covers time blocks, time clock events, timesheets, time off, leaves of absence, accruals, schedule shifts, scheduling organizations, labor demand, and worker scheduling preferences.
features:
- description: Capture, calculate, and report worker time blocks with batch import support for high-volume time entry workflows.
  name: Time Block Management
- description: Import time clock events from third-party clocks and devices into Workday for centralized time tracking.
  name: Time Clock Integration
- description: Retrieve, submit, approve, and report on timesheets covering configurable pay periods.
  name: Timesheet Lifecycle
- description: Enter time off entries, request leaves of absence, and process return-from-leave events through the Absence Management API.
  name: Time Off and Leave
- description: Inspect time off balances and apply accrual overrides to align worker plan balances with payroll requirements.
  name: Accrual Balances and Overrides
- description: Create, update, and import schedule shifts and assign them to workers within scheduling organizations.
  name: Schedule Shift Management
- description: Configure labor demand by scheduling organization to drive shift creation and workforce planning.
  name: Labor Demand Planning
- description: Capture worker availability and scheduling preferences to inform shift assignment decisions.
  name: Worker Scheduling Preferences
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Calculated time blocks and approved timesheets feed Workday Payroll for gross-to-net processing.
  name: Workday Payroll
- description: Worker, organization, and position data from Workday HCM are referenced across time, absence, and scheduling APIs.
  name: Workday HCM
- description: Third-party time clock vendors integrate with the Time Tracking API via the time clock events endpoints.
  name: Time Clock Hardware
- description: Scheduling and labor optimization partners exchange shifts, labor demand, and preferences with the Scheduling API.
  name: Workforce Management Partners
- description: OAuth 2.0 integration with enterprise identity providers authenticates API clients and workers.
  name: Identity Providers
jsonld:
- class_count: 1
  name: Workday Tracking System Context
  property_count: 36
  slug: workday-tracking-system-context
layout: provider
modified: '2026-05-03'
name: Workday Tracking System
rules:
- name: Workday Tracking System API Rules
  rule_count: 68
  severity_counts:
    error: 18
    hint: 0
    info: 11
    warn: 39
  slug: workday-tracking-system-spectral-rules
skills: []
slug: workday-tracking-system
solutions:
- description: Core HCM suite that includes Time Tracking, Absence Management, and Scheduling as integrated workforce capabilities.
  name: Workday Human Capital Management
- description: Native payroll solution that consumes time and absence data for accurate pay calculation.
  name: Workday Payroll
- description: Scheduling, labor optimization, and time tracking solution tailored to shift-based workforces.
  name: Workday Workforce Management
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-tracking-system\nname: Workday Tracking System\ndescription: >-\n  APIs for managing employee time tracking, absence management, and workforce\n  scheduling in the Workday platform. Covers time blocks, time clock events,\n  timesheets, time off, leaves of absence, accruals, schedule shifts, scheduling\n  organizations, labor demand, and worker scheduling preferences.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - name: Workday Time Tracking API\n    description: >-\n      Manage employee time entries, time blocks, time clock events, work\n      schedule assignments, and time requests within the Workday platform.\n      Supports both individual and batch operations for enterprise workforce\n      management.\n    image: https://www.workday.com/content/dam/web/images/icons/time-tracking.png\n\
  \    humanURL: https://www.workday.com/en-us/products/human-capital-management/time-tracking.html\n    baseURL: https://{tenant}.workday.com/api/time-tracking/v1\n    tags:\n      - Time Tracking\n      - Timesheets\n      - Time Blocks\n      - Time Clock\n      - Work Schedules\n      - Time Requests\n      - Hours\n      - Attendance\n    properties:\n      - type: Documentation\n        url: https://docs.workday.com/api/time-tracking\n      - type: APIReference\n        url: https://developer.workday.com/api-reference/time-tracking\n      - type: Authentication\n        url: https://docs.workday.com/authentication\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-time-tracking-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-shift-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-block-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-block-input-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-blocks-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-clock-event-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-clock-event-input-schema.json\n    \
  \  - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-clock-events-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-request-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-request-input-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-requests-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-timesheet-schema.json\n     \
  \ - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-timesheets-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-work-schedule-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-work-schedule-assignment-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-shift-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-block-structure.json\n    \
  \  - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-block-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-blocks-response-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-clock-event-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-clock-event-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-clock-events-response-structure.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-request-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-request-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-requests-response-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-timesheet-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-timesheets-response-structure.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-work-schedule-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-work-schedule-assignment-structure.json\n    contact:\n      - FN: Workday Developer Support\n        url: https://developer.workday.com\n  - name: Workday Absence Management API\n    description: >-\n      Track employee attendance, absences, leave requests, and time off\n      balances in the Workday platform. Supports entering time off, requesting\n      leave of absence, managing accrual balances, and processing\n      return-from-leave events.\n    image: https://www.workday.com/content/dam/web/images/icons/attendance.png\n    humanURL: https://www.workday.com/en-us/products/human-capital-management/absence-management.html\n\
  \    baseURL: https://{tenant}.workday.com/api/absence-management/v1\n    tags:\n      - Absence Management\n      - Time Off\n      - Leave of Absence\n      - Accruals\n      - Balances\n      - Attendance\n    properties:\n      - type: Documentation\n        url: https://docs.workday.com/api/absence-management\n      - type: APIReference\n        url: https://developer.workday.com/api-reference/absence-management\n      - type: Authentication\n        url: https://docs.workday.com/authentication\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-absence-management-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-accrual-override-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-accrual-override-input-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-accrual-overrides-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-leave-of-absence-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-leave-of-absence-input-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-leaves-of-absence-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-return-from-leave-input-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-balance-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-balances-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-entry-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-input-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-response-schema.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-accrual-override-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-accrual-override-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-accrual-overrides-response-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-leave-of-absence-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-leave-of-absence-input-structure.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-leaves-of-absence-response-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-return-from-leave-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-balance-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-balances-response-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-entry-structure.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-response-structure.json\n    contact:\n      - FN: Workday Developer Support\n        url: https://developer.workday.com\n  - name: Workday Scheduling API\n    description: >-\n      Create and manage employee work schedules, shifts, scheduling\n      organizations, and labor demand within the Workday platform. Supports\n      importing schedule data, managing shift assignments, and configuring\n      scheduling settings and worker scheduling preferences.\n    image: https://www.workday.com/content/dam/web/images/icons/scheduling.png\n    humanURL: https://www.workday.com/en-us/products/human-capital-management/scheduling.html\n\
  \    baseURL: https://{tenant}.workday.com/api/scheduling/v1\n    tags:\n      - Scheduling\n      - Schedules\n      - Shifts\n      - Scheduling Organizations\n      - Labor Demand\n      - Worker Preferences\n      - Workforce Management\n    properties:\n      - type: Documentation\n        url: https://docs.workday.com/api/scheduling\n      - type: APIReference\n        url: https://developer.workday.com/api-reference/scheduling\n      - type: Authentication\n        url: https://docs.workday.com/authentication\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-scheduling-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-labor-demand-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-labor-demand-input-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-labor-demand-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-schedule-shift-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-schedule-shift-input-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-schedule-shifts-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-scheduling-organization-schema.json\n \
  \     - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-scheduling-organization-input-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-scheduling-organizations-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-worker-scheduling-preferences-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-worker-scheduling-preferences-input-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-labor-demand-structure.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-labor-demand-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-labor-demand-response-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-schedule-shift-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-schedule-shift-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-schedule-shifts-response-structure.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-scheduling-organization-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-scheduling-organization-input-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-scheduling-organizations-response-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-worker-scheduling-preferences-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-worker-scheduling-preferences-input-structure.json\n\
  \    contact:\n      - FN: Workday Developer Support\n        url: https://developer.workday.com\ncommon:\n  - type: Portal\n    url: https://developer.workday.com\n  - type: GettingStarted\n    url: https://developer.workday.com/getting-started\n  - type: Documentation\n    url: https://docs.workday.com\n  - type: Authentication\n    url: https://docs.workday.com/authentication/oauth2\n  - type: SignUp\n    url: https://www.workday.com/en-us/forms/contact-sales.html\n  - type: Pricing\n    url: https://www.workday.com/en-us/pricing.html\n  - type: RateLimits\n    url: https://docs.workday.com/rate-limits\n  - type: StatusPage\n    url: https://status.workday.com\n  - type: Support\n    url: https://www.workday.com/en-us/company/latest/customer-support.html\n  - type: Community\n    url: https://community.workday.com\n  - type: Blog\n    url: https://blog.workday.com\n  - type: ReleaseNotes\n    url: https://docs.workday.com/release-notes\n  - type: TermsOfService\n    url: https://www.workday.com/en-us/terms-of-service.html\n\
  \  - type: PrivacyPolicy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: GitHubOrganization\n    url: https://github.com/Workday\n  - type: JSON-LD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-ld/workday-tracking-system-context.jsonld\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-leave-of-absence-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-time-block-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-timesheet-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-leave-of-absence-structure.json\n\
  \  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-time-block-structure.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-timesheet-structure.json\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/rules/workday-tracking-system-spectral-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/capabilities/workforce-time-management.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/capabilities/shared/time-tracking.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/capabilities/shared/absence-management.yaml\n\
  \  - type: Features\n    data:\n      - name: Time Block Management\n        description: >-\n          Capture, calculate, and report worker time blocks with batch\n          import support for high-volume time entry workflows.\n      - name: Time Clock Integration\n        description: >-\n          Import time clock events from third-party clocks and devices into\n          Workday for centralized time tracking.\n      - name: Timesheet Lifecycle\n        description: >-\n          Retrieve, submit, approve, and report on timesheets covering\n          configurable pay periods.\n      - name: Time Off and Leave\n        description: >-\n          Enter time off entries, request leaves of absence, and process\n          return-from-leave events through the Absence Management API.\n      - name: Accrual Balances and Overrides\n        description: >-\n          Inspect time off balances and apply accrual overrides to align\n          worker plan balances with payroll requirements.\n \
  \     - name: Schedule Shift Management\n        description: >-\n          Create, update, and import schedule shifts and assign them to\n          workers within scheduling organizations.\n      - name: Labor Demand Planning\n        description: >-\n          Configure labor demand by scheduling organization to drive\n          shift creation and workforce planning.\n      - name: Worker Scheduling Preferences\n        description: >-\n          Capture worker availability and scheduling preferences to\n          inform shift assignment decisions.\n  - type: UseCases\n    data:\n      - name: Payroll Time Capture\n        description: >-\n          Aggregate calculated time blocks and approved timesheets to feed\n          downstream payroll runs.\n      - name: Time Clock Device Integration\n        description: >-\n          Push punch-in and punch-out events from physical or mobile time\n          clocks into Workday in near real time.\n      - name: Absence and Leave Tracking\n\
  \        description: >-\n          Manage employee time off requests and leave of absence cases\n          across HR, payroll, and benefits.\n      - name: Workforce Scheduling\n        description: >-\n          Plan and publish weekly shift schedules across scheduling\n          organizations based on labor demand.\n      - name: Compliance Reporting\n        description: >-\n          Produce auditable records of worked hours, breaks, and leaves\n          for labor law and contractual compliance.\n      - name: Accrual Adjustment Workflows\n        description: >-\n          Apply targeted accrual overrides to correct worker balances\n          following payroll or eligibility changes.\n  - type: Integrations\n    data:\n      - name: Workday Payroll\n        description: >-\n          Calculated time blocks and approved timesheets feed Workday\n          Payroll for gross-to-net processing.\n      - name: Workday HCM\n        description: >-\n          Worker, organization, and position\
  \ data from Workday HCM are\n          referenced across time, absence, and scheduling APIs.\n      - name: Time Clock Hardware\n        description: >-\n          Third-party time clock vendors integrate with the Time Tracking\n          API via the time clock events endpoints.\n      - name: Workforce Management Partners\n        description: >-\n          Scheduling and labor optimization partners exchange shifts,\n          labor demand, and preferences with the Scheduling API.\n      - name: Identity Providers\n        description: >-\n          OAuth 2.0 integration with enterprise identity providers\n          authenticates API clients and workers.\n  - type: Solutions\n    data:\n      - name: Workday Human Capital Management\n        description: >-\n          Core HCM suite that includes Time Tracking, Absence Management,\n          and Scheduling as integrated workforce capabilities.\n      - name: Workday Payroll\n        description: >-\n          Native payroll solution that\
  \ consumes time and absence data for\n          accurate pay calculation.\n      - name: Workday Workforce Management\n        description: >-\n          Scheduling, labor optimization, and time tracking solution\n          tailored to shift-based workforces.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Absence Management\n  - Attendance\n  - Enterprise\n  - HCM\n  - Human Capital Management\n  - Payroll\n  - Scheduling\n  - Time Tracking\n  - Timesheets\n  - Workforce Management\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/apis.yml
tags:
- Absence Management
- Attendance
- Enterprise
- HCM
- Human Capital Management
- Payroll
- Scheduling
- Time Tracking
- Timesheets
- Workforce Management
url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/apis.yml
use_cases:
- description: Aggregate calculated time blocks and approved timesheets to feed downstream payroll runs.
  name: Payroll Time Capture
- description: Push punch-in and punch-out events from physical or mobile time clocks into Workday in near real time.
  name: Time Clock Device Integration
- description: Manage employee time off requests and leave of absence cases across HR, payroll, and benefits.
  name: Absence and Leave Tracking
- description: Plan and publish weekly shift schedules across scheduling organizations based on labor demand.
  name: Workforce Scheduling
- description: Produce auditable records of worked hours, breaks, and leaves for labor law and contractual compliance.
  name: Compliance Reporting
- description: Apply targeted accrual overrides to correct worker balances following payroll or eligibility changes.
  name: Accrual Adjustment Workflows
---
