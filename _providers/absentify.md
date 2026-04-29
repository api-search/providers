---
api_count: 1
apis:
- description: 'REST API for managing employee absences, leave requests, members, departments, leave types, public holidays, and workspace settings. Requires an API key (x-api-key header) available on the Plus plan. '
  name: Absentify API
  slug: absentify
capabilities:
- description: ''
  name: Absence Management Absentify
  slug: absence-management-absentify
common:
- title: ''
  type: Portal
  url: https://absentify.com/
- title: ''
  type: Documentation
  url: https://absentify.com/docs/en/
- title: ''
  type: Pricing
  url: https://absentify.com/pricing
- title: ''
  type: PrivacyPolicy
  url: https://absentify.com/privacy-policy
- title: ''
  type: TermsOfService
  url: https://absentify.com/terms-and-conditions
- title: ''
  type: Blog
  url: https://absentify.com/blog
- title: ''
  type: StatusPage
  url: https://status.absentify.com
- title: ''
  type: Security
  url: https://absentify.com/security
- title: MCP Server
  type: Tools
  url: https://absentify.com/docs/en/mcp-server
- title: ''
  type: SpectralRules
  url: rules/absentify-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/absence-management-absentify.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/absentify-vocabulary.yaml
created: '2025-02-17'
description: Absentify is an absence management platform integrated with Microsoft 365 and Microsoft Teams that helps businesses track and manage employee absences, leave requests, approvals, and team schedules. Built by BrainCore Solutions GmbH, it provides a REST API for integrating absence management into custom workflows, HR systems, and business automation tools.
features:
- description: Track and manage employee absences, time off, and leave requests across the organization.
  name: Absence Tracking
- description: Submit, approve, decline, and cancel leave requests with multi-level approval workflows.
  name: Leave Request Management
- description: Native integration with Microsoft 365 and Microsoft Teams for seamless absence management in existing workflows.
  name: Microsoft 365 Integration
- description: Organize employees into departments with custom leave type entitlements and approval chains.
  name: Department Management
- description: Define custom leave types with color coding, limits, approval requirements, and accrual policies.
  name: Leave Type Configuration
- description: Manage public holiday calendars per region and apply them to members and departments.
  name: Public Holiday Calendars
- description: Receive real-time webhook notifications for request creation and status changes.
  name: Webhook Support
- description: Configure workspace-wide settings, fiscal year, and default approval workflows.
  name: Workspace Management
- description: Query absences broken down by individual day for reporting and payroll integration.
  name: Absence Per Day Reporting
image: /assets/icons/absentify.png
integrations:
- description: Native Microsoft Teams app for submitting and approving absence requests without leaving Teams.
  name: Microsoft Teams
- description: Deep integration with Microsoft 365 calendar, Active Directory, and identity management.
  name: Microsoft 365
- description: Connect absentify to thousands of apps via Zapier automation workflows.
  name: Zapier
- description: Automate absence management workflows using Make's visual automation platform.
  name: Make (Integromat)
- description: Send real-time absence event notifications to any system via configurable webhooks.
  name: Custom Webhooks
jsonld:
- class_count: 9
  name: Absentify Context
  property_count: 36
  slug: absentify-context
layout: provider
modified: '2026-04-19'
name: Absentify
rules:
- name: Absentify API Rules
  rule_count: 15
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 9
  slug: absentify-spectral-rules
skills: []
slug: absentify
solutions: []
source_yaml: "aid: absentify\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/apis.yml\nname: Absentify\ndescription: >-\n  Absentify is an absence management platform integrated with Microsoft 365 and\n  Microsoft Teams that helps businesses track and manage employee absences, leave\n  requests, approvals, and team schedules. Built by BrainCore Solutions GmbH,\n  it provides a REST API for integrating absence management into custom workflows,\n  HR systems, and business automation tools.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Absence Management\n  - HR\n  - Leave Management\n  - Microsoft Teams\n  - Human Resources\ntype: Contract\naccess: 3rd-Party\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: absentify:absentify\n    name: Absentify API\n    description: >-\n      REST API for managing employee absences, leave requests, members, departments,\n  \
  \    leave types, public holidays, and workspace settings. Requires an API key\n      (x-api-key header) available on the Plus plan. Rate limit of 150 requests\n      per second per IP address.\n    humanURL: https://absentify.com/docs/en/api-reference/introduction\n    baseURL: https://api.absentify.com/api/v1\n    tags:\n      - Absence Management\n      - Leave Requests\n      - Members\n      - Departments\n      - Leave Types\n    properties:\n      - type: Documentation\n        url: https://absentify.com/docs/en/api-reference/introduction\n      - type: OpenAPI\n        url: openapi/absentify-openapi.yml\n      - type: JSONSchema\n        url: json-schema/absentify-member-schema.json\n        title: Member Schema\n      - type: JSONSchema\n        url: json-schema/absentify-department-schema.json\n        title: Department Schema\n      - type: JSONSchema\n        url: json-schema/absentify-leave-type-schema.json\n        title: Leave Type Schema\n      - type: JSONSchema\n    \
  \    url: json-schema/absentify-request-schema.json\n        title: Request Schema\n      - type: JSONSchema\n        url: json-schema/absentify-absence-schema.json\n        title: Absence Schema\n      - type: JSONSchema\n        url: json-schema/absentify-workspace-schema.json\n        title: Workspace Schema\n      - type: JSONSchema\n        url: json-schema/absentify-public-holiday-calendar-schema.json\n        title: Public Holiday Calendar Schema\n      - type: JSONStructure\n        url: json-structure/absentify-member-structure.json\n        title: Member Structure\n      - type: JSONStructure\n        url: json-structure/absentify-department-structure.json\n        title: Department Structure\n      - type: JSONStructure\n        url: json-structure/absentify-leave-type-structure.json\n        title: Leave Type Structure\n      - type: JSONStructure\n        url: json-structure/absentify-request-structure.json\n        title: Request Structure\n      - type: JSONStructure\n \
  \       url: json-structure/absentify-absence-structure.json\n        title: Absence Structure\n      - type: JSONStructure\n        url: json-structure/absentify-workspace-structure.json\n        title: Workspace Structure\n      - type: JSONStructure\n        url: json-structure/absentify-public-holiday-calendar-structure.json\n        title: Public Holiday Calendar Structure\n      - type: JSON-LD\n        url: json-ld/absentify-context.jsonld\n      - type: Example\n        url: examples/absentify-member-example.json\n        title: Member Example\n      - type: Example\n        url: examples/absentify-department-example.json\n        title: Department Example\n      - type: Example\n        url: examples/absentify-leave-type-example.json\n        title: Leave Type Example\n      - type: Example\n        url: examples/absentify-request-example.json\n        title: Request Example\n      - type: Example\n        url: examples/absentify-absence-example.json\n        title: Absence Example\n\
  \      - type: Example\n        url: examples/absentify-workspace-example.json\n        title: Workspace Example\ncommon:\n  - type: Portal\n    url: https://absentify.com/\n  - type: Documentation\n    url: https://absentify.com/docs/en/\n  - type: Pricing\n    url: https://absentify.com/pricing\n  - type: PrivacyPolicy\n    url: https://absentify.com/privacy-policy\n  - type: TermsOfService\n    url: https://absentify.com/terms-and-conditions\n  - type: Blog\n    url: https://absentify.com/blog\n  - type: StatusPage\n    url: https://status.absentify.com\n  - type: Security\n    url: https://absentify.com/security\n  - type: Tools\n    url: https://absentify.com/docs/en/mcp-server\n    title: MCP Server\n  - type: SpectralRules\n    url: rules/absentify-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/absence-management-absentify.yaml\n  - type: Vocabulary\n    url: vocabulary/absentify-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Absence Tracking\n\
  \        description: Track and manage employee absences, time off, and leave requests across the organization.\n      - name: Leave Request Management\n        description: Submit, approve, decline, and cancel leave requests with multi-level approval workflows.\n      - name: Microsoft 365 Integration\n        description: Native integration with Microsoft 365 and Microsoft Teams for seamless absence management in existing workflows.\n      - name: Department Management\n        description: Organize employees into departments with custom leave type entitlements and approval chains.\n      - name: Leave Type Configuration\n        description: Define custom leave types with color coding, limits, approval requirements, and accrual policies.\n      - name: Public Holiday Calendars\n        description: Manage public holiday calendars per region and apply them to members and departments.\n      - name: Webhook Support\n        description: Receive real-time webhook notifications for request\
  \ creation and status changes.\n      - name: Workspace Management\n        description: Configure workspace-wide settings, fiscal year, and default approval workflows.\n      - name: Absence Per Day Reporting\n        description: Query absences broken down by individual day for reporting and payroll integration.\n  - type: UseCases\n    data:\n      - name: HR System Integration\n        description: Integrate absence data into HRIS platforms like SAP, Workday, or BambooHR for unified people management.\n      - name: Payroll Processing\n        description: Export absence data to payroll systems to automatically calculate pay adjustments for time off.\n      - name: Team Scheduling\n        description: Sync absence data into scheduling tools to prevent understaffing and manage coverage.\n      - name: Compliance Reporting\n        description: Generate absence reports for regulatory compliance, labor law adherence, and audit purposes.\n      - name: Custom Approval Workflows\n    \
  \    description: Build custom absence request approval workflows integrated with business process automation tools.\n      - name: Absence Analytics\n        description: Analyze absence trends, patterns, and costs to improve workforce planning and reduce absenteeism.\n      - name: Microsoft Teams Automation\n        description: Automate absence-related notifications and approvals directly within Microsoft Teams channels.\n  - type: Integrations\n    data:\n      - name: Microsoft Teams\n        description: Native Microsoft Teams app for submitting and approving absence requests without leaving Teams.\n      - name: Microsoft 365\n        description: Deep integration with Microsoft 365 calendar, Active Directory, and identity management.\n      - name: Zapier\n        description: Connect absentify to thousands of apps via Zapier automation workflows.\n      - name: Make (Integromat)\n        description: Automate absence management workflows using Make's visual automation platform.\n\
  \      - name: Custom Webhooks\n        description: Send real-time absence event notifications to any system via configurable webhooks.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/apis.yml
tags:
- Absence Management
- HR
- Leave Management
- Microsoft Teams
- Human Resources
url: https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/apis.yml
use_cases:
- description: Integrate absence data into HRIS platforms like SAP, Workday, or BambooHR for unified people management.
  name: HR System Integration
- description: Export absence data to payroll systems to automatically calculate pay adjustments for time off.
  name: Payroll Processing
- description: Sync absence data into scheduling tools to prevent understaffing and manage coverage.
  name: Team Scheduling
- description: Generate absence reports for regulatory compliance, labor law adherence, and audit purposes.
  name: Compliance Reporting
- description: Build custom absence request approval workflows integrated with business process automation tools.
  name: Custom Approval Workflows
- description: Analyze absence trends, patterns, and costs to improve workforce planning and reduce absenteeism.
  name: Absence Analytics
- description: Automate absence-related notifications and approvals directly within Microsoft Teams channels.
  name: Microsoft Teams Automation
---
