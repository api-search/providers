---
api_count: 8
api_specs:
- filename: quickbooks-accounting.yml
  format: yaml
  label: QuickBooks Online Accounting API
  slug: quickbooks-accounting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/openapi/quickbooks-accounting.yml
apis:
- description: Intuit APIs provide developers with access to a wide range of services and functionalities to help them build innovative solutions for financial management, accounting, and tax-related needs. These AP
  name: Intuit APIs
  slug: intuit
- description: The QuickBooks Online Accounting API is a RESTful API that provides programmatic access to QuickBooks Online company data, including customers, invoices, payments, bills, vendors, accounts, and report
  name: QuickBooks Online Accounting API
  slug: quickbooks-accounting
- description: The QuickBooks Payments API enables developers to process credit card charges, bank account debits (ACH), and manage payment methods within the QuickBooks ecosystem. It supports tokenized card storage
  name: QuickBooks Payments API
  slug: quickbooks-payments
- description: The QuickBooks Payroll and Time API provides programmatic access to payroll and time-tracking data within QuickBooks Online. It supports use cases including time entry management, payroll compensation
  name: QuickBooks Payroll and Time API
  slug: quickbooks-payroll-time
- description: 'The QuickBooks Desktop API allows developers to integrate with QuickBooks Desktop applications using qbXML messages. It provides capabilities for adding, querying, modifying, and deleting data across '
  name: QuickBooks Desktop API
  slug: quickbooks-desktop
- description: The QuickBooks Projects API is a premium API that provides programmatic access to project data within QuickBooks Online Plus, Advanced, Accountant, and Intuit Enterprise Suite. It enables developers t
  name: QuickBooks Projects API
  slug: quickbooks-projects
- description: The QuickBooks Custom Fields API is a premium API that provides programmatic access to custom field definitions and values in QuickBooks Online and Intuit Enterprise Suite. It allows developers to cre
  name: QuickBooks Custom Fields API
  slug: quickbooks-custom-fields
- description: The QuickBooks Sales Tax API is a premium API that provides programmatic access to the automated sales tax calculation capabilities within QuickBooks Online. It enables developers to leverage QuickBoo
  name: QuickBooks Sales Tax API
  slug: quickbooks-sales-tax
asyncapis:
- description: QuickBooks Online Webhooks provide near real-time notifications when data changes in a QuickBooks Online company. When an entity is created, updated, merged, deleted, or voided, Intuit sends an HTTP P
  name: QuickBooks Online Webhooks
  slug: quickbooks-webhooks
capabilities:
- description: Unified workflow for small business accounting automation combining QuickBooks Online invoice, customer, item, and payment management. Used by accountants, bookkeepers, and business owners to automate
  name: Intuit Accounting and Payments
  slug: accounting-and-payments
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.intuit.com
- title: ''
  type: SignUp
  url: https://developer.intuit.com/app/developer/appcard/overview
- title: ''
  type: Blog
  url: https://developer.intuit.com/app/developer/blog
- title: ''
  type: Support
  url: https://help.developer.intuit.com
- title: ''
  type: StatusPage
  url: https://status.developer.intuit.com
- title: ''
  type: TermsOfService
  url: https://developer.intuit.com/app/developer/qbo/docs/learn/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.intuit.com/privacy/
- title: ''
  type: Authentication
  url: https://developer.intuit.com/app/developer/qbo/docs/develop/authentication-and-authorization/oauth-2.0
- title: ''
  type: Sandbox
  url: https://developer.intuit.com/app/developer/qbo/docs/develop/sandboxes/postman
- title: ''
  type: Console
  url: https://developer.intuit.com/app/developer/qbo/docs/get-started/get-started-with-the-api-explorer
- title: ''
  type: FAQ
  url: https://developer.intuit.com/app/developer/qbo/docs/get-started/partner-faq
- title: ''
  type: GitHubOrganization
  url: https://github.com/intuit
- title: ''
  type: GitHubOrganization
  url: https://github.com/intuitdeveloper
- title: PHP SDK
  type: SDK
  url: https://github.com/intuit/QuickBooks-V3-PHP-SDK
- title: .NET SDK
  type: SDK
  url: https://github.com/intuit/QuickBooks-V3-DotNET-SDK
- title: Java SDK
  type: SDK
  url: https://github.com/intuit/QuickBooks-V3-Java-SDK
- title: Ruby SDK
  type: SDK
  url: https://github.com/intuit/oauth-rubyclient
- title: Node.js SDK
  type: SDK
  url: https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples-collections/nodejs
- title: Python SDK
  type: SDK
  url: https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples-collections/python
- title: ''
  type: ChangeLog
  url: https://blogs.intuit.com/
- title: ''
  type: ReleaseNotes
  url: https://developer.intuit.com/app/developer/qbo/docs/release-notes/platform-release-notes
- title: ''
  type: ReleaseNotes
  url: https://developer.intuit.com/app/developer/qbo/docs/release-notes/general-release-notes
- title: ''
  type: Versioning
  url: https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api/minor-versions
- title: ''
  type: RateLimits
  url: https://help.developer.intuit.com/s/article/API-call-limits-and-throttling
- title: ''
  type: Security
  url: https://developer.intuit.com/app/developer/qbo/docs/go-live/publish-app/security-requirements
- title: ''
  type: Marketplace
  url: https://quickbooks.intuit.com/app/apps/home/en-global/
- title: ''
  type: X
  url: https://x.com/IntuitDev
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/intuit-developer
created: '2025-03-01'
description: Collection of APIs offered by Intuit for financial and business management services.
features:
- description: Secure API access using OAuth 2.0 authorization with OpenID Connect for user identity verification.
  name: OAuth 2.0 Authentication
- description: Real-time event notifications for changes to QuickBooks entities including invoices, payments, and customers.
  name: Webhooks
- description: Backward-compatible API versioning allowing access to newer fields and behaviors without breaking existing integrations.
  name: Minor Versioning
- description: Full-featured sandbox environment for testing and development with sample company data.
  name: Sandbox Environment
- description: Support for transactions in multiple currencies with automatic exchange rate management.
  name: Multi-Currency Support
- description: Extensible metadata system allowing up to 12 custom fields across transaction types.
  name: Custom Fields
image: https://developer.intuit.com/app/developer/common/imgs/IntuitDev_Logo.svg
integrations:
- description: Sync e-commerce orders, inventory, and payments between Shopify stores and QuickBooks for automated bookkeeping.
  name: Shopify
- description: Reconcile Stripe payment transactions with QuickBooks invoices and accounts receivable.
  name: Stripe
- description: Import Square POS transactions into QuickBooks for unified financial management.
  name: Square
- description: Connect CRM data with accounting to automate invoice creation from deals and track payment status.
  name: HubSpot
- description: Sync customer and opportunity data between Salesforce CRM and QuickBooks accounting.
  name: Salesforce
jsonld:
- class_count: 0
  name: Intuit Context
  property_count: 8
  slug: intuit-context
- class_count: 0
  name: Quickbooks Accounting Context
  property_count: 0
  slug: quickbooks-accounting-context
layout: provider
modified: '2026-04-18'
name: Intuit
rules:
- name: Intuit API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: intuit-spectral-rules
skills: []
slug: intuit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: intuit\nurl: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/apis.yml\napis:\n  - aid: intuit:intuit\n    name: Intuit APIs\n    tags:\n      - Accounting\n      - Financial\n      - Tax Preparation\n      - Taxes\n    humanURL: https://developer.intuit.com/app/developer/homepage\n    properties:\n      - url: https://developer.intuit.com/app/developer/homepage\n        type: Documentation\n    description: >-\n      Intuit APIs provide developers with access to a wide range of services and functionalities\n      to help them build innovative solutions for financial management, accounting,\n      and tax-related needs. These APIs allow developers to integrate with popular\n      Intuit products such as QuickBooks, TurboTax, and Mint, giving users the ability\n      to securely access and manage their financial data across multiple platforms.\n  - aid: intuit:quickbooks-accounting\n    name: QuickBooks Online Accounting API\n    tags:\n      - Accounting\n\
  \      - Bookkeeping\n      - Financial\n      - Invoicing\n      - Small Business\n    humanURL: https://developer.intuit.com/app/developer/qbo/docs/develop\n    properties:\n      - url: https://developer.intuit.com/app/developer/qbo/docs/develop\n        type: Documentation\n      - url: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account\n        type: APIReference\n      - url: https://developer.intuit.com/app/developer/qbo/docs/get-started\n        type: GettingStarted\n      - url: https://developer.intuit.com/app/developer/qbo/docs/get-started/get-started-with-the-api-explorer\n        type: Console\n      - url: https://developer.intuit.com/app/developer/qbo/docs/develop/authentication-and-authorization/oauth-2.0\n        type: Authentication\n      - url: https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api\n        type: Documentation\n      - url: https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api/minor-versions\n\
  \        type: Versioning\n      - url: https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples\n        type: SDK\n      - url: https://developer.intuit.com/app/developer/qbo/docs/release-notes/platform-release-notes\n        type: ReleaseNotes\n      - url: openapi/quickbooks-accounting.yml\n        type: OpenAPI\n      - url: asyncapi/quickbooks-webhooks.yml\n        type: AsyncAPI\n      - url: json-schema/intuit-invoice-schema.json\n        type: JSONSchema\n      - url: json-schema/intuit-customer-schema.json\n        type: JSONSchema\n      - url: json-ld/intuit-context.jsonld\n        type: JSONLD\n    description: The QuickBooks Online Accounting API is a RESTful API that provides programmatic access to QuickBooks Online company data, including customers, invoices, payments, bills, vendors, accounts, and reports. It enables developers to build integrations that automate accounting workflows, synchronize financial data, and extend QuickBooks Online functionality\
  \ for small and mid-sized businesses.\n  - aid: intuit:quickbooks-payments\n    name: QuickBooks Payments API\n    tags:\n      - Credit Cards\n      - eCommerce\n      - Financial\n      - Payments\n    humanURL: https://developer.intuit.com/app/developer/qbpayments/docs/learn/explore-the-quickbooks-payments-api\n    properties:\n      - url: https://developer.intuit.com/app/developer/qbpayments/docs/learn/explore-the-quickbooks-payments-api\n        type: Documentation\n      - url: https://developer.intuit.com/app/developer/qbpayments/docs/get-started\n        type: GettingStarted\n      - url: https://developer.intuit.com/app/developer/qbpayments/docs/develop\n        type: APIReference\n    description: The QuickBooks Payments API enables developers to process credit card charges, bank account debits (ACH), and manage payment methods within the QuickBooks ecosystem. It supports tokenized card storage, refunds, and the ability to link payments directly to QuickBooks Online invoices\
  \ for seamless reconciliation.\n  - aid: intuit:quickbooks-payroll-time\n    name: QuickBooks Payroll and Time API\n    tags:\n      - HR\n      - Payroll\n      - Small Business\n      - Time Tracking\n    humanURL: https://developer.intuit.com/app/developer/payroll-time/docs/get-started\n    properties:\n      - url: https://developer.intuit.com/app/developer/payroll-time/docs/get-started\n        type: GettingStarted\n      - url: https://developer.intuit.com/app/developer/payroll-time/docs/develop/develop-payroll\n        type: Documentation\n    description: The QuickBooks Payroll and Time API provides programmatic access to payroll and time-tracking data within QuickBooks Online. It supports use cases including time entry management, payroll compensation, and deductions, enabling developers to build integrations that streamline workforce and payroll operations for small businesses.\n  - aid: intuit:quickbooks-desktop\n    name: QuickBooks Desktop API\n    tags:\n      - Accounting\n\
  \      - Desktop\n      - Financial\n      - Small Business\n    humanURL: https://developer.intuit.com/app/developer/qbdesktop/docs/api-reference/qbdesktop\n    properties:\n      - url: https://developer.intuit.com/app/developer/qbdesktop/docs/api-reference/qbdesktop\n        type: APIReference\n      - url: https://developer.intuit.com/app/developer/qbdesktop/docs/api-reference\n        type: Documentation\n    description: The QuickBooks Desktop API allows developers to integrate with QuickBooks Desktop applications using qbXML messages. It provides capabilities for adding, querying, modifying, and deleting data across list objects, transaction objects, query objects, and report objects, enabling third-party applications to interact with on-premise QuickBooks installations.\n  - aid: intuit:quickbooks-projects\n    name: QuickBooks Projects API\n    tags:\n      - Accounting\n      - Financial\n      - Project Management\n      - Projects\n      - Small Business\n    humanURL: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account\n\
  \    properties:\n      - url: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account\n        type: APIReference\n      - url: https://developer.intuit.com/app/developer/qbo/docs/develop\n        type: Documentation\n    description: The QuickBooks Projects API is a premium API that provides programmatic access to project data within QuickBooks Online Plus, Advanced, Accountant, and Intuit Enterprise Suite. It enables developers to create projects, track profitability, and manage project-level financial data, allowing integrations that enhance project-based accounting and reporting workflows.\n  - aid: intuit:quickbooks-custom-fields\n    name: QuickBooks Custom Fields API\n    tags:\n      - Accounting\n      - Custom Fields\n      - Financial\n      - Metadata\n      - Small Business\n    humanURL: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account\n    properties:\n      - url: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/account\n\
  \        type: APIReference\n      - url: https://developer.intuit.com/app/developer/qbo/docs/develop\n        type: Documentation\n    description: The QuickBooks Custom Fields API is a premium API that provides programmatic access to custom field definitions and values in QuickBooks Online and Intuit Enterprise Suite. It allows developers to create and manage up to 12 custom fields that can be used across different transaction types, enabling flexible metadata extensions for invoices, estimates, sales receipts, and other entities.\n  - aid: intuit:quickbooks-sales-tax\n    name: QuickBooks Sales Tax API\n    tags:\n      - Accounting\n      - Financial\n      - Sales Tax\n      - Small Business\n      - Tax\n    humanURL: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/taxrate\n    properties:\n      - url: https://developer.intuit.com/app/developer/qbo/docs/api/accounting/all-entities/taxrate\n        type: APIReference\n      - url: https://developer.intuit.com/app/developer/qbo/docs/develop\n\
  \        type: Documentation\n    description: The QuickBooks Sales Tax API is a premium API that provides programmatic access to the automated sales tax calculation capabilities within QuickBooks Online. It enables developers to leverage QuickBooks automated sales tax engine to calculate the correct sales tax for invoices and other transactions, supporting tax compliance across different jurisdictions.\nname: Intuit\ntags:\n  - Accounting\n  - Custom Fields\n  - Financial\n  - Financial Services\n  - Invoicing\n  - Payments\n  - Payroll\n  - Project Management\n  - Sales Tax\n  - Small Business\n  - Tax\n  - Tax Preparation\n  - Taxes\n  - Time Tracking\ntype: Index\nimage: https://developer.intuit.com/app/developer/common/imgs/IntuitDev_Logo.svg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-18'\nposition: Consumer\ndescription: >-\n  Collection of APIs offered by Intuit for financial and business management services.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  \  - name: Intuit Developer\n    email: developer-support@intuit.com\n    url: https://help.developer.intuit.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://developer.intuit.com\n    type: DeveloperPortal\n  - url: https://developer.intuit.com/app/developer/appcard/overview\n    type: SignUp\n  - url: https://developer.intuit.com/app/developer/blog\n    type: Blog\n  - url: https://help.developer.intuit.com\n    type: Support\n  - url: https://status.developer.intuit.com\n    type: StatusPage\n  - url: https://developer.intuit.com/app/developer/qbo/docs/learn/terms-of-service\n    type: TermsOfService\n  - url: https://www.intuit.com/privacy/\n    type: PrivacyPolicy\n  - url: https://developer.intuit.com/app/developer/qbo/docs/develop/authentication-and-authorization/oauth-2.0\n    type: Authentication\n  - url: https://developer.intuit.com/app/developer/qbo/docs/develop/sandboxes/postman\n    type: Sandbox\n  - url: https://developer.intuit.com/app/developer/qbo/docs/get-started/get-started-with-the-api-explorer\n\
  \    type: Console\n  - url: https://developer.intuit.com/app/developer/qbo/docs/get-started/partner-faq\n    type: FAQ\n  - url: https://github.com/intuit\n    type: GitHubOrganization\n  - url: https://github.com/intuitdeveloper\n    type: GitHubOrganization\n  - url: https://github.com/intuit/QuickBooks-V3-PHP-SDK\n    type: SDK\n    title: PHP SDK\n  - url: https://github.com/intuit/QuickBooks-V3-DotNET-SDK\n    type: SDK\n    title: .NET SDK\n  - url: https://github.com/intuit/QuickBooks-V3-Java-SDK\n    type: SDK\n    title: Java SDK\n  - url: https://github.com/intuit/oauth-rubyclient\n    type: SDK\n    title: Ruby SDK\n  - url: https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples-collections/nodejs\n    type: SDK\n    title: Node.js SDK\n  - url: https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples-collections/python\n    type: SDK\n    title: Python SDK\n  - url: https://blogs.intuit.com/\n    type: ChangeLog\n  - url: https://developer.intuit.com/app/developer/qbo/docs/release-notes/platform-release-notes\n\
  \    type: ReleaseNotes\n  - url: https://developer.intuit.com/app/developer/qbo/docs/release-notes/general-release-notes\n    type: ReleaseNotes\n  - url: https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api/minor-versions\n    type: Versioning\n  - url: https://help.developer.intuit.com/s/article/API-call-limits-and-throttling\n    type: RateLimits\n  - url: https://developer.intuit.com/app/developer/qbo/docs/go-live/publish-app/security-requirements\n    type: Security\n  - url: https://quickbooks.intuit.com/app/apps/home/en-global/\n    type: Marketplace\n  - url: https://x.com/IntuitDev\n    type: X\n  - url: https://www.linkedin.com/company/intuit-developer\n    type: LinkedIn\n  - type: Features\n    data:\n      - name: OAuth 2.0 Authentication\n        description: Secure API access using OAuth 2.0 authorization with OpenID Connect for user identity verification.\n      - name: Webhooks\n        description: Real-time event notifications\
  \ for changes to QuickBooks entities including invoices, payments, and customers.\n      - name: Minor Versioning\n        description: Backward-compatible API versioning allowing access to newer fields and behaviors without breaking existing integrations.\n      - name: Sandbox Environment\n        description: Full-featured sandbox environment for testing and development with sample company data.\n      - name: Multi-Currency Support\n        description: Support for transactions in multiple currencies with automatic exchange rate management.\n      - name: Custom Fields\n        description: Extensible metadata system allowing up to 12 custom fields across transaction types.\n  - type: UseCases\n    data:\n      - name: Accounting Automation\n        description: Automate bookkeeping workflows by syncing invoices, payments, and expenses between business systems and QuickBooks.\n      - name: Payment Processing\n        description: Process credit card and ACH payments linked to QuickBooks\
  \ invoices for seamless financial reconciliation.\n      - name: Payroll Integration\n        description: Integrate payroll and time-tracking data to streamline employee compensation and workforce management.\n      - name: Tax Compliance\n        description: Automate sales tax calculations and ensure tax compliance across different jurisdictions.\n      - name: Financial Reporting\n        description: Build custom financial reports and dashboards by querying QuickBooks accounting data programmatically.\n  - type: Integrations\n    data:\n      - name: Shopify\n        description: Sync e-commerce orders, inventory, and payments between Shopify stores and QuickBooks for automated bookkeeping.\n      - name: Stripe\n        description: Reconcile Stripe payment transactions with QuickBooks invoices and accounts receivable.\n      - name: Square\n        description: Import Square POS transactions into QuickBooks for unified financial management.\n      - name: HubSpot\n        description:\
  \ Connect CRM data with accounting to automate invoice creation from deals and track payment status.\n      - name: Salesforce\n        description: Sync customer and opportunity data between Salesforce CRM and QuickBooks accounting.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/apis.yml
tags:
- Accounting
- Custom Fields
- Financial
- Financial Services
- Invoicing
- Payments
- Payroll
- Project Management
- Sales Tax
- Small Business
- Tax
- Tax Preparation
- Taxes
- Time Tracking
url: https://raw.githubusercontent.com/api-evangelist/intuit/refs/heads/main/apis.yml
use_cases:
- description: Automate bookkeeping workflows by syncing invoices, payments, and expenses between business systems and QuickBooks.
  name: Accounting Automation
- description: Process credit card and ACH payments linked to QuickBooks invoices for seamless financial reconciliation.
  name: Payment Processing
- description: Integrate payroll and time-tracking data to streamline employee compensation and workforce management.
  name: Payroll Integration
- description: Automate sales tax calculations and ensure tax compliance across different jurisdictions.
  name: Tax Compliance
- description: Build custom financial reports and dashboards by querying QuickBooks accounting data programmatically.
  name: Financial Reporting
---
