---
api_count: 4
apis:
- description: RESTful APIs for core banking operations including account management, customer data, transactions, and payment processing.
  name: Temenos Transact Core Banking API
  slug: ''
- description: APIs for Temenos Transact microservices including callback registry, configuration management, user entitlements, and service orchestration for building event-driven and composable banking application
  name: Temenos Transact Microservices APIs
  slug: ''
- description: High-performance APIs built on the near real-time Analytics Data Store and Operational Data Store from Temenos Transact Data Hub, providing banking-specific analytical and operational data for reporti
  name: Temenos Transact Data Hub APIs
  slug: ''
- description: APIs built on the near real-time Operational Data Store from Temenos Transact Data Hub, presenting data in specific formats for operational and API use cases utilizing real-time data streams and ETL t
  name: Temenos Operational Data Store APIs
  slug: ''
capabilities:
- description: Unified digital banking capability combining account management, customer operations, payment processing, deposits, loans, and reference data for retail and corporate banking applications. Used by dig
  name: Temenos Digital Banking
  slug: digital-banking
common:
- title: ''
  type: Portal
  url: https://developer.temenos.com/
- title: ''
  type: GettingStarted
  url: https://developer.temenos.com/article/sandbox-quick-guide
- title: ''
  type: Documentation
  url: https://developer.temenos.com/guides
- title: ''
  type: Blog
  url: https://www.temenos.com/blog/the-modern-developer-portal/
- title: ''
  type: Community
  url: https://basecamp.temenos.com/s/
- title: ''
  type: Sign Up
  url: https://tcsp-signup.temenos.com/signup/communityregistration
- title: ''
  type: GitHubOrganization
  url: https://github.com/temenostech
- title: ''
  type: Website
  url: https://www.temenos.com/
- title: ''
  type: Support
  url: https://support.temenos.com
- title: ''
  type: TermsOfService
  url: https://www.temenos.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.temenos.com/privacy-policy/
- title: ''
  type: PostmanCollection
  url: https://www.postman.com/temenos-devex/temenos-essential-apis/documentation/sd6uv6m/temenos-essential-apis
created: '2024'
description: Core banking APIs from Temenos Transact, providing comprehensive banking functionality including accounts, transactions, payments, loans, and customer management.
features:
- description: Modular, component-based framework enabling reusable product components across retail, corporate, treasury, wealth, and Islamic banking.
  name: Arrangement Architecture
- description: Full support for multi-currency accounts, payments, and exchange rate management with ISO 4217 compliance.
  name: Multi-Currency Support
- description: Built-in customer verification, AML checks, and compliance tracking for regulatory requirements.
  name: KYC and AML Compliance
- description: Support for SEPA, SWIFT, ACH, RTGS, and domestic clearing payment types with real-time processing.
  name: Real-Time Payments
- description: Configurable product catalog with conditions, eligibility criteria, and arrangement details for banking products.
  name: Product Catalog
image: https://www.temenos.com/wp-content/uploads/2023/01/temenos-logo.svg
integrations:
- description: Integration with SWIFT, SEPA, ACH, and domestic clearing networks for cross-border and local payments.
  name: Payment Networks
- description: Integration with card issuance and processing networks for debit and credit card operations.
  name: Card Processing
- description: Integration with regulatory bodies for compliance reporting, AML screening, and KYC verification.
  name: Regulatory Reporting
jsonld:
- class_count: 31
  name: Temenos Transact Context
  property_count: 121
  slug: temenos-transact-context
- class_count: 0
  name: Temenos Transact Core Banking Context
  property_count: 0
  slug: temenos-transact-core-banking-context
layout: provider
modified: '2026-04-18'
name: Temenos Transact
rules:
- name: Temenos Transact API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: temenos-transact-spectral-rules
skills: []
slug: temenos-transact
solutions: []
source_yaml: "name: Temenos Transact\ndescription: >-\n  Core banking APIs from Temenos Transact, providing comprehensive banking functionality\n  including accounts, transactions, payments, loans, and customer management.\nimage: https://www.temenos.com/wp-content/uploads/2023/01/temenos-logo.svg\nurl: https://www.temenos.com/products/transact/\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\napis:\n  - name: Temenos Transact Core Banking API\n    description: >-\n      RESTful APIs for core banking operations including account management, customer\n      data, transactions, and payment processing.\n    image: https://www.temenos.com/wp-content/uploads/2023/01/temenos-logo.svg\n    humanURL: https://www.temenos.com/products/transact/\n    baseURL: https://api.temenos.com/transact/v1\n    tags:\n      - Accounts\n      - Banking\n      - Core Banking\n      - Customers\n      - Payments\n      - Transactions\n    properties:\n      - type: Documentation\n        url:\
  \ https://developer.temenos.com/transact/documentation\n      - type: OpenAPI\n        url: https://developer.temenos.com/transact/openapi.json\n      - type: Authentication\n        url: https://developer.temenos.com/transact/authentication\n      - type: Sandbox\n        url: https://sandbox.temenos.com/transact\n      - type: SDK\n        url: https://developer.temenos.com/transact/sdks\n      - type: TermsOfService\n        url: https://www.temenos.com/terms-of-service/\n      - type: PrivacyPolicy\n        url: https://www.temenos.com/privacy-policy/\n      - type: Support\n        url: https://support.temenos.com\n      - type: StatusPage\n        url: https://status.temenos.com\n      - type: ChangeLog\n        url: https://developer.temenos.com/transact/changelog\n      - type: OpenAPI\n        url: openapi/temenos-transact-core-banking-openapi.yml\n      - type: JSONSchema\n        url: json-schema/temenos-transaction-schema.json\n      - type: JSONLD\n        url: json-ld/temenos-transact-context.jsonld\n\
  \    contact:\n      - type: Support\n        url: https://support.temenos.com\n      - type: Email\n        email: api.support@temenos.com\n      - type: Sales\n        url: https://www.temenos.com/contact/\n  - name: Temenos Transact Microservices APIs\n    description: >-\n      APIs for Temenos Transact microservices including callback registry,\n      configuration management, user entitlements, and service orchestration\n      for building event-driven and composable banking applications.\n    image: https://www.temenos.com/wp-content/uploads/2023/01/temenos-logo.svg\n    humanURL: https://developer.temenos.com/transact-microservice-apis\n    baseURL: https://api.temenos.com/transact/v1\n    tags:\n      - Configuration\n      - Entitlements\n      - Microservices\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://developer.temenos.com/transact-microservice-apis\n  - name: Temenos Transact Data Hub APIs\n    description: >-\n      High-performance\
  \ APIs built on the near real-time Analytics Data Store and\n      Operational Data Store from Temenos Transact Data Hub, providing\n      banking-specific analytical and operational data for reporting and\n      integration use cases.\n    image: https://www.temenos.com/wp-content/uploads/2023/01/temenos-logo.svg\n    humanURL: https://developer.temenos.com/transact-data-hub\n    baseURL: https://api.temenos.com/transact/v1\n    tags:\n      - Analytics\n      - Data Hub\n      - Data Store\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developer.temenos.com/transact-data-hub\n  - name: Temenos Operational Data Store APIs\n    description: >-\n      APIs built on the near real-time Operational Data Store from Temenos\n      Transact Data Hub, presenting data in specific formats for operational\n      and API use cases utilizing real-time data streams and ETL\n      transformations.\n    image: https://www.temenos.com/wp-content/uploads/2023/01/temenos-logo.svg\n\
  \    humanURL: https://developer.temenos.com/operational-data-store\n    baseURL: https://api.temenos.com/transact/v1\n    tags:\n      - Data Streams\n      - ETL\n      - Operational Data\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://developer.temenos.com/operational-data-store\ncommon:\n  - type: Portal\n    url: https://developer.temenos.com/\n  - type: GettingStarted\n    url: https://developer.temenos.com/article/sandbox-quick-guide\n  - type: Documentation\n    url: https://developer.temenos.com/guides\n  - type: Blog\n    url: https://www.temenos.com/blog/the-modern-developer-portal/\n  - type: Community\n    url: https://basecamp.temenos.com/s/\n  - type: Sign Up\n    url: https://tcsp-signup.temenos.com/signup/communityregistration\n  - type: GitHubOrganization\n    url: https://github.com/temenostech\n  - type: Website\n    url: https://www.temenos.com/\n  - type: Support\n    url: https://support.temenos.com\n  - type: TermsOfService\n\
  \    url: https://www.temenos.com/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://www.temenos.com/privacy-policy/\n  - type: PostmanCollection\n    url: https://www.postman.com/temenos-devex/temenos-essential-apis/documentation/sd6uv6m/temenos-essential-apis\n  - type: Features\n    data:\n      - name: Arrangement Architecture\n        description: Modular, component-based framework enabling reusable product components across retail, corporate, treasury, wealth, and Islamic banking.\n      - name: Multi-Currency Support\n        description: Full support for multi-currency accounts, payments, and exchange rate management with ISO 4217 compliance.\n      - name: KYC and AML Compliance\n        description: Built-in customer verification, AML checks, and compliance tracking for regulatory requirements.\n      - name: Real-Time Payments\n        description: Support for SEPA, SWIFT, ACH, RTGS, and domestic clearing payment types with real-time processing.\n      - name: Product\
  \ Catalog\n        description: Configurable product catalog with conditions, eligibility criteria, and arrangement details for banking products.\n  - type: UseCases\n    data:\n      - name: Digital Banking\n        description: Build digital banking apps with account management, transaction history, and payment initiation APIs.\n      - name: Open Banking\n        description: Enable third-party access to banking data and payment services through standardized APIs.\n      - name: Loan Origination\n        description: Automate loan application, credit assessment, and disbursement workflows through API integration.\n      - name: Customer Onboarding\n        description: Streamline customer registration with KYC verification, account opening, and beneficiary setup.\n  - type: Integrations\n    data:\n      - name: Payment Networks\n        description: Integration with SWIFT, SEPA, ACH, and domestic clearing networks for cross-border and local payments.\n      - name: Card Processing\n\
  \        description: Integration with card issuance and processing networks for debit and credit card operations.\n      - name: Regulatory Reporting\n        description: Integration with regulatory bodies for compliance reporting, AML screening, and KYC verification.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Banking\n  - Core Banking\n  - Digital Banking\n  - Enterprise\n  - Financial Services\n  - Fintech\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/temenos-transact/refs/heads/main/apis.yml
tags:
- Banking
- Core Banking
- Digital Banking
- Enterprise
- Financial Services
- Fintech
url: https://www.temenos.com/products/transact/
use_cases:
- description: Build digital banking apps with account management, transaction history, and payment initiation APIs.
  name: Digital Banking
- description: Enable third-party access to banking data and payment services through standardized APIs.
  name: Open Banking
- description: Automate loan application, credit assessment, and disbursement workflows through API integration.
  name: Loan Origination
- description: Streamline customer registration with KYC verification, account opening, and beneficiary setup.
  name: Customer Onboarding
---
