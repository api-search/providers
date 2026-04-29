---
api_count: 1
api_specs:
- filename: cflow-openapi.yml
  format: yaml
  label: Cflow Workflow API
  slug: cflow
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/openapi/cflow-openapi.yml
apis:
- description: The Cflow Workflow API provides REST endpoints for retrieving workflows, creating and managing requests, approving or rejecting requests at each stage, creating draft requests, and administering users
  name: Cflow Workflow API
  slug: cflow
common:
- title: ''
  type: Website
  url: https://www.cflowapps.com
- title: ''
  type: Documentation
  url: https://www.cflowapps.com/workflow/workflow-api/
- title: ''
  type: SignUp
  url: https://www.cflowapps.com/sign-up/
- title: ''
  type: Pricing
  url: https://www.cflowapps.com/pricing/
- title: ''
  type: Blog
  url: https://www.cflowapps.com/blog/
- title: ''
  type: Support
  url: https://help.cflowapps.com/
- title: ''
  type: TermsOfService
  url: https://www.cflowapps.com/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.cflowapps.com/privacy-policy/
created: '2025-01-08'
description: Cflow is a cloud-based workflow automation platform that helps organizations streamline and optimize business processes. It offers a drag-and-drop workflow builder, customizable forms, rule-based routing, approval flows, integrations with popular business applications, and real-time analytics. Cflow exposes a REST API allowing developers to list workflows, submit and manage requests, approve or reject tasks, and manage users and roles programmatically.
features:
- name: Drag-and-Drop Workflow Builder
- name: Custom Forms
- name: Conditional Rules
- name: Multi-Level Approvals
- name: Role-Based Access Control
- name: Real-Time Analytics
- name: Dashboards
- name: Email Notifications
- name: Mobile Access
- name: Audit Trails
- name: REST API
- name: Webhooks
- name: Integrations
- name: No-Code
- name: Low-Code
- name: Parallel Approvals
- name: Sequential Approvals
- name: Escalations
- name: Reminders
- name: Reports
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Zapier
- name: Microsoft Teams
- name: Slack
- name: Google Workspace
- name: Office 365
- name: Dropbox
- name: OneDrive
- name: SharePoint
- name: DocuSign
- name: Salesforce
- name: QuickBooks
- name: Webhooks
jsonld:
- class_count: 3
  name: Cflow Context
  property_count: 15
  slug: cflow-context
layout: provider
modified: '2026-04-23'
name: Cflow
skills: []
slug: cflow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cflow\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/apis.yml\nname: Cflow\nx-type: company\ntags:\n  - Automations\n  - Business Process Automation\n  - Integrations\n  - No-Code\n  - Platform\n  - Protocols\n  - Rules\n  - Workflows\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  Cflow is a cloud-based workflow automation platform that helps organizations\n  streamline and optimize business processes. It offers a drag-and-drop\n  workflow builder, customizable forms, rule-based routing, approval flows,\n  integrations with popular business applications, and real-time analytics.\n  Cflow exposes a REST API allowing developers to list workflows, submit and\n  manage requests, approve or reject tasks, and manage users and roles\n  programmatically.\napis:\n  - aid: cflow:cflow\n    name:\
  \ Cflow Workflow API\n    tags:\n      - Approvals\n      - Automation\n      - Integrations\n      - Protocols\n      - Requests\n      - Roles\n      - Rules\n      - Users\n      - Workflows\n    humanURL: https://www.cflowapps.com\n    baseURL: https://us.cflowapps.com\n    properties:\n      - url: https://www.cflowapps.com/workflow/workflow-api/\n        type: Documentation\n      - url: openapi/cflow-openapi.yml\n        type: OpenAPI\n      - url: json-schema/workflow.json\n        type: JSONSchema\n      - url: json-schema/stage.json\n        type: JSONSchema\n      - url: json-schema/request.json\n        type: JSONSchema\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-schema/role.json\n        type: JSONSchema\n      - url: json-ld/cflow-context.jsonld\n        type: JSONLD\n    description: >-\n      The Cflow Workflow API provides REST endpoints for retrieving workflows,\n      creating and managing requests, approving or rejecting requests\
  \ at each\n      stage, creating draft requests, and administering users and roles. All\n      business objects and integration objects are exposed as JSON resources\n      and authentication is handled via API key, user key, and username\n      headers.\ncommon:\n  - type: Website\n    url: https://www.cflowapps.com\n  - type: Documentation\n    url: https://www.cflowapps.com/workflow/workflow-api/\n  - type: SignUp\n    url: https://www.cflowapps.com/sign-up/\n  - type: Pricing\n    url: https://www.cflowapps.com/pricing/\n  - type: Blog\n    url: https://www.cflowapps.com/blog/\n  - type: Support\n    url: https://help.cflowapps.com/\n  - type: TermsOfService\n    url: https://www.cflowapps.com/terms-of-use/\n  - type: PrivacyPolicy\n    url: https://www.cflowapps.com/privacy-policy/\n  - name: Features\n    type: Features\n    data:\n      - name: Drag-and-Drop Workflow Builder\n      - name: Custom Forms\n      - name: Conditional Rules\n      - name: Multi-Level Approvals\n     \
  \ - name: Role-Based Access Control\n      - name: Real-Time Analytics\n      - name: Dashboards\n      - name: Email Notifications\n      - name: Mobile Access\n      - name: Audit Trails\n      - name: REST API\n      - name: Webhooks\n      - name: Integrations\n      - name: No-Code\n      - name: Low-Code\n      - name: Parallel Approvals\n      - name: Sequential Approvals\n      - name: Escalations\n      - name: Reminders\n      - name: Reports\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Purchase Request Approval\n      - name: Employee Onboarding\n      - name: Leave Requests\n      - name: Expense Approval\n      - name: Travel Requests\n      - name: Vendor Onboarding\n      - name: Invoice Approval\n      - name: Capital Expenditure Requests\n      - name: Document Approval\n      - name: Change Management\n      - name: Compliance Workflows\n      - name: Help Desk Ticketing\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Zapier\n\
  \      - name: Microsoft Teams\n      - name: Slack\n      - name: Google Workspace\n      - name: Office 365\n      - name: Dropbox\n      - name: OneDrive\n      - name: SharePoint\n      - name: DocuSign\n      - name: Salesforce\n      - name: QuickBooks\n      - name: Webhooks\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/apis.yml
tags:
- Automations
- Business Process Automation
- Integrations
- No-Code
- Platform
- Protocols
- Rules
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/apis.yml
use_cases:
- name: Purchase Request Approval
- name: Employee Onboarding
- name: Leave Requests
- name: Expense Approval
- name: Travel Requests
- name: Vendor Onboarding
- name: Invoice Approval
- name: Capital Expenditure Requests
- name: Document Approval
- name: Change Management
- name: Compliance Workflows
- name: Help Desk Ticketing
---
