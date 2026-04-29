---
api_count: 8
apis:
- description: REST API for managing expense reports, entries, allocations, and attendees. Supports creating, updating, and submitting expense reports with receipt images, policy validation, and approval workflows.
  name: SAP Concur Expense API
  slug: expense-api
- description: REST API for managing travel itineraries, bookings, and travel profiles. Supports searching for travel options, creating bookings, and managing travel policies and preferences.
  name: SAP Concur Travel API
  slug: travel-api
- description: REST API for accounts payable invoice processing including purchase requests, vendor management, payment batches, and invoice approval workflows.
  name: SAP Concur Invoice API
  slug: invoice-api
- description: REST API for submitting and managing digital receipts from e-commerce providers, ground transportation, hotels, and other merchants directly to Concur expense.
  name: SAP Concur Receipts API
  slug: receipts-api
- description: REST API for managing pre-trip travel requests and approvals, enabling employees to submit travel requests for authorization before booking.
  name: SAP Concur Request API
  slug: request-api
- description: SCIM 2.0-compliant API for provisioning and managing Concur user accounts, roles, and profile information with support for bulk operations.
  name: SAP Concur User Provisioning API
  slug: user-provisioning-api
- description: Event subscription API enabling applications to receive real-time notifications when events occur in Concur such as expense report submissions, approvals, and status changes.
  name: SAP Concur Events API
  slug: events-api
- description: REST API for managing custom lists and list items used in expense forms, travel policies, and invoice configurations for dropdown and lookup fields.
  name: SAP Concur Lists API
  slug: lists-api
capabilities:
- description: Unified spend management workflow combining expense, travel, and invoice APIs for finance teams managing employee spend.
  name: SAP Concur Spend Management
  slug: spend-management
common:
- title: ''
  type: Portal
  url: https://developer.concur.com/
- title: ''
  type: Documentation
  url: https://developer.concur.com/api-reference/
- title: ''
  type: GettingStarted
  url: https://developer.concur.com/api-reference/getting-started.html
- title: ''
  type: Authentication
  url: https://developer.concur.com/api-reference/authentication/apidoc.html
- title: ''
  type: Blog
  url: https://www.concur.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/SAP/concur-platform
- title: ''
  type: Support
  url: https://developer.concur.com/tools-support/support.html
- title: ''
  type: TermsOfService
  url: https://www.concur.com/en-us/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.concur.com/en-us/privacy-policy
- title: ''
  type: Sandbox
  url: https://developer.concur.com/manage-apps/register.html
- title: ''
  type: ChangeLog
  url: https://developer.concur.com/tools-support/release-notes/
- title: ''
  type: Pricing
  url: https://www.concur.com/en-us/pricing
created: '2024-01-01'
description: SAP Concur provides a comprehensive suite of REST APIs for travel, expense, and invoice management. The Concur API platform enables integration with expense reporting, travel booking, invoice processing, receipt capture, and user management services used by enterprises worldwide for spend management automation.
features:
- description: Create, submit, and manage expense reports with policy validation and multi-level approval workflows.
  name: Expense Report Management
- description: Capture and process digital receipts from merchants for automatic expense matching.
  name: Receipt Digitization
- description: Search and book travel through API-connected travel management companies and booking tools.
  name: Travel Booking Integration
- description: Automate accounts payable workflows with purchase requests, vendor management, and payment processing.
  name: Invoice Processing
- description: Real-time event subscriptions for expense, travel, and invoice status changes.
  name: Event Notifications
- description: Standards-based user provisioning and management with SCIM 2.0 protocol support.
  name: SCIM User Provisioning
image: /assets/icons/concur.png
integrations:
- description: Financial posting integration for automated expense and invoice data transfer to SAP ERP.
  name: SAP S/4HANA
- description: HR integration for employee data synchronization and travel policy assignment.
  name: SAP SuccessFactors
- description: Automated ride receipt submission from Uber business accounts to Concur expense.
  name: Uber for Business
- description: Ground transportation receipt integration for business ride expense automation.
  name: Lyft
- description: Approval and notification integration for expense workflows within Teams.
  name: Microsoft Teams
jsonld:
- class_count: 2
  name: Concur Context
  property_count: 15
  slug: concur-context
layout: provider
modified: '2026-04-18'
name: SAP Concur
rules:
- name: SAP Concur API Rules
  rule_count: 11
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 4
  slug: concur-spectral-rules
skills: []
slug: concur
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: concur\nname: SAP Concur\ndescription: >-\n  SAP Concur provides a comprehensive suite of REST APIs for travel, expense, and\n  invoice management. The Concur API platform enables integration with expense\n  reporting, travel booking, invoice processing, receipt capture, and user management\n  services used by enterprises worldwide for spend management automation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/concur/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Expense Management\n  - Finance\n  - Invoice\n  - SAP\n  - Travel\napis:\n  - aid: concur:expense-api\n    name: SAP Concur Expense API\n    description: >-\n      REST API for managing expense reports, entries, allocations, and attendees.\n      Supports creating, updating, and submitting expense reports with receipt\n      images, policy\
  \ validation, and approval workflows.\n    humanURL: https://developer.concur.com/api-reference/expense/expense-report/v4.expenses.html\n    baseURL: https://us.api.concursolutions.com/expensereports/v4/\n    tags:\n      - Expense Reports\n      - Expense Tracking\n      - REST\n      - Spend Management\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/v4.expenses.html\n      - type: APIReference\n        url: https://developer.concur.com/api-reference/expense/expense-report/v4.expenses.html\n      - type: GettingStarted\n        url: https://developer.concur.com/api-reference/expense/expense-report/v4.expenses-get-started.html\n  - aid: concur:travel-api\n    name: SAP Concur Travel API\n    description: >-\n      REST API for managing travel itineraries, bookings, and travel profiles.\n      Supports searching for travel options, creating bookings, and managing\n      travel policies and preferences.\n    humanURL:\
  \ https://developer.concur.com/api-reference/travel/\n    baseURL: https://us.api.concursolutions.com/travel/\n    tags:\n      - Bookings\n      - Itineraries\n      - REST\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/travel/\n  - aid: concur:invoice-api\n    name: SAP Concur Invoice API\n    description: >-\n      REST API for accounts payable invoice processing including purchase requests,\n      vendor management, payment batches, and invoice approval workflows.\n    humanURL: https://developer.concur.com/api-reference/invoice/v3.invoice.html\n    baseURL: https://us.api.concursolutions.com/invoice/\n    tags:\n      - Accounts Payable\n      - Invoices\n      - Payments\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/invoice/v3.invoice.html\n  - aid: concur:receipts-api\n    name: SAP Concur Receipts API\n    description: >-\n      REST API\
  \ for submitting and managing digital receipts from e-commerce providers,\n      ground transportation, hotels, and other merchants directly to Concur expense.\n    humanURL: https://developer.concur.com/api-reference/receipts/\n    baseURL: https://us.api.concursolutions.com/receipts/v4/\n    tags:\n      - Digital Receipts\n      - E-Receipts\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/receipts/\n  - aid: concur:request-api\n    name: SAP Concur Request API\n    description: >-\n      REST API for managing pre-trip travel requests and approvals, enabling\n      employees to submit travel requests for authorization before booking.\n    humanURL: https://developer.concur.com/api-reference/request/v4.get-started.html\n    baseURL: https://us.api.concursolutions.com/travelrequest/v4/\n    tags:\n      - Approvals\n      - REST\n      - Travel Requests\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/request/v4.get-started.html\n\
  \  - aid: concur:user-provisioning-api\n    name: SAP Concur User Provisioning API\n    description: >-\n      SCIM 2.0-compliant API for provisioning and managing Concur user accounts,\n      roles, and profile information with support for bulk operations.\n    humanURL: https://developer.concur.com/api-reference/user-provisioning/v4.user-provisioning.html\n    baseURL: https://us.api.concursolutions.com/provisioning/v4/\n    tags:\n      - Provisioning\n      - REST\n      - SCIM\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/user-provisioning/v4.user-provisioning.html\n  - aid: concur:events-api\n    name: SAP Concur Events API\n    description: >-\n      Event subscription API enabling applications to receive real-time notifications\n      when events occur in Concur such as expense report submissions, approvals,\n      and status changes.\n    humanURL: https://developer.concur.com/api-reference/ess/v4.event-subscription.html\n\
  \    baseURL: https://us.api.concursolutions.com/events/v4/\n    tags:\n      - Events\n      - REST\n      - Subscriptions\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/ess/v4.event-subscription.html\n  - aid: concur:lists-api\n    name: SAP Concur Lists API\n    description: >-\n      REST API for managing custom lists and list items used in expense forms,\n      travel policies, and invoice configurations for dropdown and lookup fields.\n    humanURL: https://developer.concur.com/api-reference/common/lists/v4.list.html\n    baseURL: https://us.api.concursolutions.com/list/v4/\n    tags:\n      - Configuration\n      - Lists\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/common/lists/v4.list.html\ncommon:\n  - type: Portal\n    url: https://developer.concur.com/\n  - type: Documentation\n    url: https://developer.concur.com/api-reference/\n\
  \  - type: GettingStarted\n    url: https://developer.concur.com/api-reference/getting-started.html\n  - type: Authentication\n    url: https://developer.concur.com/api-reference/authentication/apidoc.html\n  - type: Blog\n    url: https://www.concur.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/SAP/concur-platform\n  - type: Support\n    url: https://developer.concur.com/tools-support/support.html\n  - type: TermsOfService\n    url: https://www.concur.com/en-us/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.concur.com/en-us/privacy-policy\n  - type: Sandbox\n    url: https://developer.concur.com/manage-apps/register.html\n  - type: ChangeLog\n    url: https://developer.concur.com/tools-support/release-notes/\n  - type: Pricing\n    url: https://www.concur.com/en-us/pricing\n  - type: Features\n    data:\n      - name: Expense Report Management\n        description: Create, submit, and manage expense reports with policy validation and multi-level approval\
  \ workflows.\n      - name: Receipt Digitization\n        description: Capture and process digital receipts from merchants for automatic expense matching.\n      - name: Travel Booking Integration\n        description: Search and book travel through API-connected travel management companies and booking tools.\n      - name: Invoice Processing\n        description: Automate accounts payable workflows with purchase requests, vendor management, and payment processing.\n      - name: Event Notifications\n        description: Real-time event subscriptions for expense, travel, and invoice status changes.\n      - name: SCIM User Provisioning\n        description: Standards-based user provisioning and management with SCIM 2.0 protocol support.\n  - type: UseCases\n    data:\n      - name: ERP Integration\n        description: Integrate Concur expense and invoice data with ERP systems for automated financial posting.\n      - name: Travel Management\n        description: Build travel booking integrations\
  \ connecting corporate travel policies with booking engines.\n      - name: Receipt Automation\n        description: Automatically capture and match digital receipts from e-commerce and travel merchants.\n      - name: Spend Analytics\n        description: Extract expense and travel data for spend analytics, compliance reporting, and budget tracking.\n      - name: Employee Onboarding\n        description: Automate Concur user provisioning as part of employee onboarding workflows.\n  - type: Integrations\n    data:\n      - name: SAP S/4HANA\n        description: Financial posting integration for automated expense and invoice data transfer to SAP ERP.\n      - name: SAP SuccessFactors\n        description: HR integration for employee data synchronization and travel policy assignment.\n      - name: Uber for Business\n        description: Automated ride receipt submission from Uber business accounts to Concur expense.\n      - name: Lyft\n        description: Ground transportation receipt\
  \ integration for business ride expense automation.\n      - name: Microsoft Teams\n        description: Approval and notification integration for expense workflows within Teams.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/concur/refs/heads/main/apis.yml
tags:
- Expense Management
- Finance
- Invoice
- SAP
- Travel
url: https://raw.githubusercontent.com/api-evangelist/concur/refs/heads/main/apis.yml
use_cases:
- description: Integrate Concur expense and invoice data with ERP systems for automated financial posting.
  name: ERP Integration
- description: Build travel booking integrations connecting corporate travel policies with booking engines.
  name: Travel Management
- description: Automatically capture and match digital receipts from e-commerce and travel merchants.
  name: Receipt Automation
- description: Extract expense and travel data for spend analytics, compliance reporting, and budget tracking.
  name: Spend Analytics
- description: Automate Concur user provisioning as part of employee onboarding workflows.
  name: Employee Onboarding
---
