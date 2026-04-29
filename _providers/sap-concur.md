---
api_count: 31
api_specs:
- filename: sap-concur-expense-openapi.yml
  format: yaml
  label: Concur Expense API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur/refs/heads/main/openapi/sap-concur-expense-openapi.yml
apis:
- description: Enables integration with Concur Expense for creating, retrieving, and managing expense reports, entries, and related data.
  name: Concur Expense API
  slug: ''
- description: Provides access to travel booking data, profiles, and itinerary information within Concur Travel.
  name: Concur Travel API
  slug: ''
- description: Allows integration with Concur Invoice for managing purchase requests, invoices, and payment requests.
  name: Concur Invoice API
  slug: ''
- description: Enables management of travel requests and approvals within the Concur system.
  name: Concur Request API
  slug: ''
- description: Manages user accounts and profiles, including creating, updating, and retrieving user information. Supports provisioning across Identity, Spend, and Travel services with bulk operations for managing m
  name: Concur User Provisioning API
  slug: ''
- description: Allows for the submission and management of digital receipts within Concur Expense.
  name: Concur Receipt API
  slug: ''
- description: Exposes budget and fiscal year data, enabling partners and clients to read and manage fiscal years, budget categories, budget items, budget tracking fields, and budget adjustments through API endpoint
  name: Concur Budget API
  slug: ''
- description: Provides an automated integration pathway for certified partner financial networks, issuing banks, and fin-tech partners to submit credit card account and transaction data to Concur Expense in near re
  name: Concur Cards API
  slug: ''
- description: Enables the creation of expenses with minimal information such as date, amount, and expense type, with or without a receipt image. Supports attaching receipt files including PNG, PDF, TIFF, and JPEG f
  name: Concur Quick Expense API
  slug: ''
- description: Allows users to create custom exchange rates for a company, supporting bulk uploads of exchange rate data for specified currency pairs and effective dates with a maximum of 100 rates per request.
  name: Concur Exchange Rate API
  slug: ''
- description: Allows an external system to interact with financial documents generated from SAP Concur for financial posting into an ERP, providing an automated solution to request approved expense reports, cash ad
  name: Concur Financial Integration API
  slug: ''
- description: Creates, updates, and reads user core identity profiles following the SCIM 2.0 standard. Enables looking up SAP Concur UUIDs for accessing other v4 APIs for individual users.
  name: Concur Identity API
  slug: ''
- description: Implements the Publish/Subscribe pattern using principles of Event Driven Architecture, notifying clients and partners when specific business events occur such as expense report status changes and tra
  name: Concur Event Subscription Service API
  slug: ''
- description: Allows clients to add interactions with outside systems to their users SAP Concur experience through application connectors, supporting attendee data fetch, list item fetch, event notifications, and e
  name: Concur Callouts API
  slug: ''
- description: Provides a method for custom hotel source suppliers to provide hotel inventory, rates, and booking related functionality to SAP Concur Online Booking Tool, supporting search, rate retrieval, reservati
  name: Concur Direct Connect Hotel Service API
  slug: ''
- description: Enables travel users to access ground transportation inventory from service providers, supporting search, reservation, cancellation, and update operations for ground transportation bookings.
  name: Concur Direct Connect Ground Transportation API
  slug: ''
- description: Facilitates ingestion and retrieval of receipt documents for use within Concur Expense, enabling users to create and retrieve simple receipts by uploading documents with associated metadata.
  name: Concur Spend Documents API
  slug: ''
- description: Provides an automated solution for retrieving, adding, updating, and deleting list items within SAP Concur, supporting hierarchical list structures with parent-child relationships across multiple leve
  name: Concur List Item API
  slug: ''
- description: Enables viewing configured lists within SAP Concur products and creating new lists, supporting shared lists across Expense, Invoice, and Request applications with managed list capabilities for partner
  name: Concur Lists API
  slug: ''
- description: Enables retrieval of travel profile information for specified users and lists of travel profile summaries, available to developers, travel suppliers, and travel management companies.
  name: Concur Travel Profile API
  slug: ''
- description: Allows extraction of travel allowance information from the SAP Concur platform, providing the ability to read travel allowance itinerary data, calculation results, and configuration settings.
  name: Concur Travel Allowance API
  slug: ''
- description: Enables users to create, view, and issue cash advances within Concur Expense. Supports single cash advance creation, retrieval, and issuance operations for both Professional and Standard editions. Req
  name: Concur Cash Advance API
  slug: ''
- description: Gives SAP Concur clients the ability to leverage external data to create and update approved purchase orders. Enables direct connections to manage purchase orders and resolve matching exceptions on in
  name: Concur Purchase Order API
  slug: ''
- description: 'Enables SAP Concur clients to leverage external data to create purchase requests for pre-authorization of purchase orders. Organizations can establish direct connections to automatically generate and '
  name: Concur Purchase Request API
  slug: ''
- description: Provides processes for managing vendor collections used in invoicing, including adding new vendors, updating, retrieving, and deleting information for existing vendors. Supports vendor banking informa
  name: Concur Vendor API
  slug: ''
- description: Enables retrieval and updating of invoices for tax calculation purposes, allowing external tax systems to fetch invoices requiring tax assessment and submit calculated tax amounts and rates back to Co
  name: Concur Sales Tax Validation API
  slug: ''
- description: Manages transmission of compliance documents between SAP Concur and validating vendors, enabling vendors to exchange compliance documents, validate them against relevant authoritative or regulatory so
  name: Concur Document Compliance Gateway API
  slug: ''
- description: Enables clients to manage receipt images attached to expense reports and images associated with invoices. Users can retrieve existing images by report ID, image ID, or invoice ID, and upload new image
  name: Concur Image API
  slug: ''
- description: 'Exposes receipt requests to inform E-Receipt partners which E-Receipts to send to SAP Concur and for which user. Partners receive paginated responses and can filter results using optional timestamps, '
  name: Concur Travel Receipts API
  slug: ''
- description: Retrieves details about locations used by Concur that are valid at a user's company. Supports filtering by name, city, country, and other geographic parameters, and returns location data including IAT
  name: Concur Locations API
  slug: ''
- description: Provides access to the configured attendee types within SAP Concur, allowing retrieval and management of attendee type resources used for categorizing attendees in expense reports.
  name: Concur Expense Attendee Types API
  slug: ''
capabilities:
- description: Unified expense management workflow combining report creation, expense tracking, approval workflows, and allocation management. Used by finance teams, approvers, and employees to manage the full expen
  name: SAP Concur Expense Management
  slug: expense-management
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.concur.com/
- title: ''
  type: Authentication
  url: https://developer.concur.com/api-reference/authentication/getting-started.html
- title: ''
  type: Authentication
  url: https://developer.concur.com/api-reference/authentication/company-auth.html
- title: ''
  type: Support
  url: https://developer.concur.com/support/
- title: ''
  type: TermsOfService
  url: https://www.concur.com/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.concur.com/privacy-policy
- title: ''
  type: StatusPage
  url: https://open.concur.com/
- title: ''
  type: Blog
  url: https://www.concur.com/newsroom
- title: ''
  type: SignUp
  url: https://developer.concur.com/register
- title: ''
  type: GitHubRepository
  url: https://github.com/SAP-docs/preview.developer.concur.com
- title: ''
  type: ReleaseNotes
  url: https://developer.concur.com/tools-support/release-notes/
- title: ''
  type: ChangeLog
  url: https://developer.concur.com/tools-support/release-notes/
- title: SAP Business Accelerator Hub
  type: Resources
  url: https://api.sap.com/products/SAPConcur/apis/REST
- title: ''
  type: Tutorials
  url: https://developers.sap.com/tutorials/data-to-value-conn-concur-part01..html
created: '2024'
description: SAP Concur is a leading provider of integrated travel, expense, and invoice management solutions. Their APIs enable developers to integrate Concur functionality into their applications, automate business processes, and access travel and expense data.
features:
- description: Secure token-based authentication supporting both company-level and user-level access tokens with automatic refresh.
  name: OAuth 2.0 Authentication
- description: Separate API endpoints for US, US2, EMEA, and China datacenters ensuring data residency compliance.
  name: Multi-Datacenter Support
- description: Publish/Subscribe event-driven architecture for real-time notifications on business events like report submissions.
  name: Event Subscription Service
- description: Standards-based user identity management following SCIM protocol for automated user lifecycle operations.
  name: SCIM 2.0 User Provisioning
- description: Integration framework allowing travel suppliers to provide inventory directly to the Concur booking tool.
  name: Direct Connect Framework
- description: Custom exchange rate management supporting bulk uploads for currency conversion across global operations.
  name: Multi-Currency Exchange Rates
image: https://www.concur.com/themes/custom/concur/logo.svg
integrations:
- description: Native integration with SAP S/4HANA and SAP ERP for financial posting, cost center sync, and master data management.
  name: SAP ERP
- description: Approve expense reports and travel requests directly from Microsoft Teams notifications.
  name: Microsoft Teams
- description: Automatic e-receipt submission for Uber business rides directly into Concur Expense.
  name: Uber for Business
- description: Sync customer and opportunity data to pre-populate expense reports and travel requests.
  name: Salesforce
- description: Automated financial posting of approved expense reports and invoices into Oracle NetSuite.
  name: Oracle NetSuite
jsonld:
- class_count: 0
  name: Sap Concur Context
  property_count: 15
  slug: sap-concur-context
- class_count: 0
  name: Sap Concur Expense Context
  property_count: 0
  slug: sap-concur-expense-context
layout: provider
modified: '2026-04-18'
name: SAP Concur
rules:
- name: SAP Concur API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: sap-concur-spectral-rules
skills: []
slug: sap-concur
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP Concur\ndescription: SAP Concur is a leading provider of integrated travel, expense, and invoice management solutions. Their APIs enable developers to integrate Concur functionality into their applications, automate business processes, and access travel and expense data.\nimage: https://www.concur.com/themes/custom/concur/logo.svg\nurl: https://www.concur.com\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntags:\n  - Business Travel\n  - Expense Management\n  - Financial Services\n  - Invoice Management\n  - Travel Management\napis:\n  - name: Concur Expense API\n    description: Enables integration with Concur Expense for creating, retrieving, and managing expense reports, entries, and related data.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/expense/\n    tags:\n      - Expenses\n      - Receipts\n      - Reports\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/\n      - type: OpenAPI\n        url: https://developer.concur.com/api-reference/expense/expense-report/expense-report.json\n      - type: OpenAPI\n        url: openapi/sap-concur-expense-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-concur-expense-report-schema.json\n      - type: JSONLD\n        url: json-ld/sap-concur-context.jsonld\n      - type: Authentication\n        url: https://developer.concur.com/api-reference/authentication/getting-started.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/v4.reports.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/v4.allocations.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/v4.workflows.html\n      - type: Documentation\n\
  \        url: https://developer.concur.com/api-reference/expense/expense-report/v4.comments.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/v4.expense-attendee-associations.html\n      - type: Resources\n        url: https://api.sap.com/package/ConcurExpense\n        title: SAP Business Accelerator Hub\n  - name: Concur Travel API\n    description: Provides access to travel booking data, profiles, and itinerary information within Concur Travel.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/travel/\n    tags:\n      - Bookings\n      - Itineraries\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/travel/\n      - type: OpenAPI\n        url: https://developer.concur.com/api-reference/travel/itinerary/itinerary.json\n      - type:\
  \ Authentication\n        url: https://developer.concur.com/api-reference/authentication/getting-started.html\n  - name: Concur Invoice API\n    description: Allows integration with Concur Invoice for managing purchase requests, invoices, and payment requests.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/invoice/\n    tags:\n      - Invoices\n      - Payments\n      - Purchase Requests\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/invoice/\n      - type: OpenAPI\n        url: https://developer.concur.com/api-reference/invoice/v3.invoice.json\n      - type: Authentication\n        url: https://developer.concur.com/api-reference/authentication/getting-started.html\n      - type: Resources\n        url: https://api.sap.com/package/ConcurInvoice\n        title: SAP Business Accelerator Hub\n  - name: Concur\
  \ Request API\n    description: Enables management of travel requests and approvals within the Concur system.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/request/\n    tags:\n      - Approvals\n      - Travel Requests\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/request/\n      - type: OpenAPI\n        url: https://developer.concur.com/api-reference/request/v4.request.json\n      - type: Authentication\n        url: https://developer.concur.com/api-reference/authentication/getting-started.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/request/v4.get-started.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/request/v4.endpoints.cashadvance-resources.html\n      - type: Resources\n        url: https://api.sap.com/package/ConcurRequest\n\
  \        title: SAP Business Accelerator Hub\n  - name: Concur User Provisioning API\n    description: Manages user accounts and profiles, including creating, updating, and retrieving user information. Supports provisioning across Identity, Spend, and Travel services with bulk operations for managing multiple user records.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/user/v1.0\n    humanURL: https://developer.concur.com/api-reference/user/\n    tags:\n      - Identity Management\n      - Provisioning\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/user/\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/user-provisioning/v4.user-provisioning.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/user-provisioning/spend/v4.spend-role-code-definition.html\n  - name: Concur Receipt\
  \ API\n    description: Allows for the submission and management of digital receipts within Concur Expense.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/receipts/\n    tags:\n      - Documents\n      - Images\n      - Receipts\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/receipts/\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/receipts/endpoints.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/receipts/sample-receipts.html\n  - name: Concur Budget API\n    description: Exposes budget and fiscal year data, enabling partners and clients to read and manage fiscal years, budget categories, budget items, budget tracking fields, and budget adjustments through API endpoints.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n\
  \    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/budget/getting-started.html\n    tags:\n      - Budgets\n      - Financial Planning\n      - Fiscal Years\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/budget/getting-started.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/budget/v4.fiscal-year.html\n  - name: Concur Cards API\n    description: Provides an automated integration pathway for certified partner financial networks, issuing banks, and fin-tech partners to submit credit card account and transaction data to Concur Expense in near real time.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/cards/v4.cards-get-started.html\n    tags:\n      - Credit Cards\n      - Financial Data\n      - Transactions\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/cards/v4.cards-get-started.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/cards/v4.cards-endpoints.schemas.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/cards/v4.cards-endpoints.account.html\n  - name: Concur Quick Expense API\n    description: Enables the creation of expenses with minimal information such as date, amount, and expense type, with or without a receipt image. Supports attaching receipt files including PNG, PDF, TIFF, and JPEG formats up to 50 MB.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/expense/quick-expense/v4.quick-expense.html\n    tags:\n      - Expenses\n      - Quick Entry\n      - Receipts\n    properties:\n      - type: Documentation\n     \
  \   url: https://developer.concur.com/api-reference/expense/quick-expense/v4.quick-expense.html\n  - name: Concur Exchange Rate API\n    description: Allows users to create custom exchange rates for a company, supporting bulk uploads of exchange rate data for specified currency pairs and effective dates with a maximum of 100 rates per request.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/expense/exchange-rate/v4.exchange-rate.html\n    tags:\n      - Currency\n      - Exchange Rates\n      - Financial Data\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/exchange-rate/v4.exchange-rate.html\n  - name: Concur Financial Integration API\n    description: Allows an external system to interact with financial documents generated from SAP Concur for financial posting into an ERP, providing an automated\
  \ solution to request approved expense reports, cash advances, and invoices for import into client internal systems.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/financial-integration/v4.financial-integration.html\n    tags:\n      - ERP\n      - Financial Integration\n      - Posting\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/financial-integration/v4.financial-integration.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/financial-integration/v4.financial-integration-use-cases-extract-information.html\n  - name: Concur Identity API\n    description: Creates, updates, and reads user core identity profiles following the SCIM 2.0 standard. Enables looking up SAP Concur UUIDs for accessing other v4 APIs for individual users.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n\
  \    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/profile/v4.identity.html\n    tags:\n      - Identity\n      - SCIM\n      - User Profiles\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/profile/v4.identity.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/profile/v1.getting-started.html\n  - name: Concur Event Subscription Service API\n    description: Implements the Publish/Subscribe pattern using principles of Event Driven Architecture, notifying clients and partners when specific business events occur such as expense report status changes and travel request updates.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/ess/v4.event-subscription.html\n    tags:\n      - Events\n      - Subscriptions\n \
  \     - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/ess/v4.event-subscription.html\n  - name: Concur Callouts API\n    description: Allows clients to add interactions with outside systems to their users SAP Concur experience through application connectors, supporting attendee data fetch, list item fetch, event notifications, and external URL launches.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v1.0\n    humanURL: https://developer.concur.com/api-reference/callouts/callouts-application-connectors.html\n    tags:\n      - Callouts\n      - Connectors\n      - Integrations\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/callouts/callouts-application-connectors.html\n  - name: Concur Direct Connect Hotel Service API\n    description: Provides a method for custom hotel source suppliers to provide hotel\
  \ inventory, rates, and booking related functionality to SAP Concur Online Booking Tool, supporting search, rate retrieval, reservation management, and cancellation handling.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/direct-connects/hotel-service-4/v4.getting-started.html\n    tags:\n      - Booking\n      - Direct Connect\n      - Hotels\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/direct-connects/hotel-service-4/v4.getting-started.html\n  - name: Concur Direct Connect Ground Transportation API\n    description: Enables travel users to access ground transportation inventory from service providers, supporting search, reservation, cancellation, and update operations for ground transportation bookings.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v1.0\n\
  \    humanURL: https://developer.concur.com/api-reference/direct-connects/ground-transportation.html\n    tags:\n      - Booking\n      - Direct Connect\n      - Ground Transportation\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/direct-connects/ground-transportation.html\n  - name: Concur Spend Documents API\n    description: Facilitates ingestion and retrieval of receipt documents for use within Concur Expense, enabling users to create and retrieve simple receipts by uploading documents with associated metadata.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/spend-documents/v4.spend-documents.html\n    tags:\n      - Documents\n      - Receipts\n      - Spend Management\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/spend-documents/v4.spend-documents.html\n\
  \      - type: Documentation\n        url: https://developer.concur.com/api-reference/spend-documents/get-receipt.html\n  - name: Concur List Item API\n    description: Provides an automated solution for retrieving, adding, updating, and deleting list items within SAP Concur, supporting hierarchical list structures with parent-child relationships across multiple levels.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/common/list-item/v4.list-item.html\n    tags:\n      - Configuration\n      - List Items\n      - Lists\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/common/list-item/v4.list-item.html\n  - name: Concur Lists API\n    description: Enables viewing configured lists within SAP Concur products and creating new lists, supporting shared lists across Expense, Invoice, and Request applications with\
  \ managed list capabilities for partner applications.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/common/lists/v4.list.html\n    tags:\n      - Configuration\n      - Lists\n      - Shared Resources\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/common/lists/v4.list.html\n  - name: Concur Travel Profile API\n    description: Enables retrieval of travel profile information for specified users and lists of travel profile summaries, available to developers, travel suppliers, and travel management companies.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v2.0\n    humanURL: https://developer.concur.com/api-reference/travel-profile/v2.profile-service.html\n    tags:\n      - Loyalty Programs\n      - Travel Profiles\n      - User Profiles\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/travel-profile/v2.profile-service.html\n  - name: Concur Travel Allowance API\n    description: Allows extraction of travel allowance information from the SAP Concur platform, providing the ability to read travel allowance itinerary data, calculation results, and configuration settings.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/travelallowance/v4.travelallowance-get-started.html\n    tags:\n      - Expenses\n      - Per Diem\n      - Travel Allowance\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/travelallowance/v4.travelallowance-get-started.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/travelallowance/v4.travel-allowance-days-endpoints.html\n\
  \  - name: Concur Cash Advance API\n    description: Enables users to create, view, and issue cash advances within Concur Expense. Supports single cash advance creation, retrieval, and issuance operations for both Professional and Standard editions. Requires the Identity v4 API to obtain user IDs.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/cash-advance/v4-1.cash-advance.html\n    tags:\n      - Cash Advances\n      - Expenses\n      - Reimbursements\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/cash-advance/v4-1.cash-advance.html\n  - name: Concur Purchase Order API\n    description: Gives SAP Concur clients the ability to leverage external data to create and update approved purchase orders. Enables direct connections to manage purchase orders and resolve matching exceptions on invoices through create,\
  \ update, and retrieve operations.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/invoice/v3.purchase-order.html\n    tags:\n      - Invoices\n      - Procurement\n      - Purchase Orders\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/invoice/v3.purchase-order.html\n  - name: Concur Purchase Request API\n    description: Enables SAP Concur clients to leverage external data to create purchase requests for pre-authorization of purchase orders. Organizations can establish direct connections to automatically generate and submit purchase requests into approval workflows, with approved requests resulting in purchase orders for vendor transmission.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/invoice/v4.purchase-request-get-started.html\n\
  \    tags:\n      - Approvals\n      - Procurement\n      - Purchase Requests\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/invoice/v4.purchase-request-get-started.html\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/invoice/v4.purchase-request-endpoints.html\n  - name: Concur Vendor API\n    description: Provides processes for managing vendor collections used in invoicing, including adding new vendors, updating, retrieving, and deleting information for existing vendors. Supports vendor banking information, grouping, and extensive search filtering with up to 20 custom fields.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/invoice/v3.vendor.html\n    tags:\n      - Invoices\n      - Supplier Management\n      - Vendors\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.concur.com/api-reference/invoice/v3.vendor.html\n  - name: Concur Sales Tax Validation API\n    description: Enables retrieval and updating of invoices for tax calculation purposes, allowing external tax systems to fetch invoices requiring tax assessment and submit calculated tax amounts and rates back to Concur. Handles comprehensive invoice data including vendor information, billing and shipping addresses, and line items.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/invoice/v3.sales-tax-validation.html\n    tags:\n      - Invoices\n      - Tax Compliance\n      - Tax Validation\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/invoice/v3.sales-tax-validation.html\n  - name: Concur Document Compliance Gateway API\n    description: Manages transmission of compliance documents\
  \ between SAP Concur and validating vendors, enabling vendors to exchange compliance documents, validate them against relevant authoritative or regulatory sources, and return the validation results. Streamlines compliance document validation and tax data extraction for expense creation.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v4.0\n    humanURL: https://developer.concur.com/api-reference/document-compliance-gateway/V4.document-compliance-gateway.html\n    tags:\n      - Compliance\n      - Document Validation\n      - Tax Documents\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/document-compliance-gateway/V4.document-compliance-gateway.html\n  - name: Concur Image API\n    description: Enables clients to manage receipt images attached to expense reports and images associated with invoices. Users can retrieve existing images by report ID, image ID, or invoice\
  \ ID, and upload new images in PDF, JPEG, JPG, and PNG formats up to 10 MB to users, expense entries, reports, or invoices.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/image/v1.0\n    humanURL: https://developer.concur.com/api-reference/image/v1.image.html\n    tags:\n      - Documents\n      - Images\n      - Receipts\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/image/v1.image.html\n  - name: Concur Travel Receipts API\n    description: Exposes receipt requests to inform E-Receipt partners which E-Receipts to send to SAP Concur and for which user. Partners receive paginated responses and can filter results using optional timestamps, with support for separate US and EMEA datacenter endpoints.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://us.api.concursolutions.com/travelreceipts/v1\n    humanURL: https://developer.concur.com/api-reference/travel-receipts/getting-started.html\n\
  \    tags:\n      - E-Receipts\n      - Travel\n      - Travel Receipts\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/travel-receipts/getting-started.html\n  - name: Concur Locations API\n    description: Retrieves details about locations used by Concur that are valid at a user's company. Supports filtering by name, city, country, and other geographic parameters, and returns location data including IATA codes, geographic coordinates, airport status, and booking tool availability.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/common/locations/v3.locations.html\n    tags:\n      - Common Resources\n      - Geography\n      - Locations\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/common/locations/v3.locations.html\n  - name: Concur Expense Attendee\
  \ Types API\n    description: Provides access to the configured attendee types within SAP Concur, allowing retrieval and management of attendee type resources used for categorizing attendees in expense reports.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    baseURL: https://www.concursolutions.com/api/v3.0\n    humanURL: https://developer.concur.com/api-reference/expense/attendee-types/v3.attendee-types.html\n    tags:\n      - Attendees\n      - Configuration\n      - Expenses\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/attendee-types/v3.attendee-types.html\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.concur.com/\n  - type: Authentication\n    url: https://developer.concur.com/api-reference/authentication/getting-started.html\n  - type: Authentication\n    url: https://developer.concur.com/api-reference/authentication/company-auth.html\n  - type: Support\n    url: https://developer.concur.com/support/\n\
  \  - type: TermsOfService\n    url: https://www.concur.com/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.concur.com/privacy-policy\n  - type: StatusPage\n    url: https://open.concur.com/\n  - type: Blog\n    url: https://www.concur.com/newsroom\n  - type: SignUp\n    url: https://developer.concur.com/register\n  - type: GitHubRepository\n    url: https://github.com/SAP-docs/preview.developer.concur.com\n  - type: ReleaseNotes\n    url: https://developer.concur.com/tools-support/release-notes/\n  - type: ChangeLog\n    url: https://developer.concur.com/tools-support/release-notes/\n  - type: Resources\n    url: https://api.sap.com/products/SAPConcur/apis/REST\n    title: SAP Business Accelerator Hub\n  - type: Tutorials\n    url: https://developers.sap.com/tutorials/data-to-value-conn-concur-part01..html\n  - type: Features\n    data:\n      - name: OAuth 2.0 Authentication\n        description: Secure token-based authentication supporting both company-level and user-level\
  \ access tokens with automatic refresh.\n      - name: Multi-Datacenter Support\n        description: Separate API endpoints for US, US2, EMEA, and China datacenters ensuring data residency compliance.\n      - name: Event Subscription Service\n        description: Publish/Subscribe event-driven architecture for real-time notifications on business events like report submissions.\n      - name: SCIM 2.0 User Provisioning\n        description: Standards-based user identity management following SCIM protocol for automated user lifecycle operations.\n      - name: Direct Connect Framework\n        description: Integration framework allowing travel suppliers to provide inventory directly to the Concur booking tool.\n      - name: Multi-Currency Exchange Rates\n        description: Custom exchange rate management supporting bulk uploads for currency conversion across global operations.\n  - type: UseCases\n    data:\n      - name: Expense Report Automation\n        description: Automate expense\
  \ report creation, submission, and approval workflows by integrating with ERP and financial systems.\n      - name: Travel Booking Integration\n        description: Connect travel management companies and suppliers to provide booking, itinerary, and receipt data within Concur Travel.\n      - name: Invoice Processing\n        description: Streamline accounts payable by automating invoice creation, purchase order matching, and vendor management.\n      - name: Financial Posting\n        description: Extract approved expense reports and invoices for automated posting into ERP systems like SAP, Oracle, and NetSuite.\n      - name: Receipt Digitization\n        description: Submit and manage digital receipts from e-receipt partners and mobile capture for paperless expense management.\n  - type: Integrations\n    data:\n      - name: SAP ERP\n        description: Native integration with SAP S/4HANA and SAP ERP for financial posting, cost center sync, and master data management.\n      - name:\
  \ Microsoft Teams\n        description: Approve expense reports and travel requests directly from Microsoft Teams notifications.\n      - name: Uber for Business\n        description: Automatic e-receipt submission for Uber business rides directly into Concur Expense.\n      - name: Salesforce\n        description: Sync customer and opportunity data to pre-populate expense reports and travel requests.\n      - name: Oracle NetSuite\n        description: Automated financial posting of approved expense reports and invoices into Oracle NetSuite.\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://developer.concur.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-concur/refs/heads/main/apis.yml
tags:
- Business Travel
- Expense Management
- Financial Services
- Invoice Management
- Travel Management
url: https://www.concur.com
use_cases:
- description: Automate expense report creation, submission, and approval workflows by integrating with ERP and financial systems.
  name: Expense Report Automation
- description: Connect travel management companies and suppliers to provide booking, itinerary, and receipt data within Concur Travel.
  name: Travel Booking Integration
- description: Streamline accounts payable by automating invoice creation, purchase order matching, and vendor management.
  name: Invoice Processing
- description: Extract approved expense reports and invoices for automated posting into ERP systems like SAP, Oracle, and NetSuite.
  name: Financial Posting
- description: Submit and manage digital receipts from e-receipt partners and mobile capture for paperless expense management.
  name: Receipt Digitization
---
